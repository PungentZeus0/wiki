 Note: A SceneGraph is currently used in the C\# SuperTux editor, but
> not in the game itself. At this point the effort to switch the game
> over to a SceneGraph doesn't seem worth it, as the `DrawingRequest`s
> that are used in the game already offer enough flexibility and
> speed.

A scenegraph is a graph of nodes which change the OpenGL state (color,
texture, drawing mode, ...) or draw some OpenGL primitives
(rectangles, triangles, ...).

Let's look at a simple example, to get an impression on why a scene
graph is useful. Say we have a node CUBE that can draw a cube. Drawing
in OpenGL can be done in several different modes: You can change the
textures, color, drawing mode and many other things. To keep the code
flexible the CUBE node will simply draw the cube, but not care about
the OpenGL environment at all. We will introduce some nodes that are
only there to change the environment for example a node COLOR which
will change the drawing color. A red and a blue cube could be
constructed like this:

                 ROOT
           /              \
          /                \
        COLOR (red)    COLOR (blue)
          |                 |
         CUBE             CUBE

The Draw() function of the rootnode would simply call the draw
functions of it's child nodes. So the Draw() functions of the 2 COLOR
nodes would be called. The COLOR nodes, would change the OpenGL
drawing color, then call the Draw() function of all child nodes and
change the color back to what it was before after that. In effect a
red and a blue cube would be drawn.

Commonly used node types are: State changing nodes like DrawingColor,
Transformations (rotate,zoom,translate), blend mode, active texture.
Or nodes that help organisation like simply nodes that do nothing and
contain a list of child nodes, nodes that sort their child nodes in
some form.

Links
-----

- [Wikiepdia about SceneGraphs](https://en.wikipedia.org/wiki/Scene_graph)
