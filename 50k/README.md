50k!
====

We made this to celebrate ⭐50k across our repos! It’s available as a
[Blender][blender] scene.

<img src="https://user-images.githubusercontent.com/25087/186230844-a6b865ff-2682-49e4-b960-6e5543a12a63.gif" width="350" alt="a little spinning star gem flanked by laurels">

The scene is comprised of two distinct parts: the little star gem in front of
some [metaballs][metaballs], and the golden two-dimensional elements like the
logo, laurels, and type.

The two-dimensional elements have their own lights to give them a nice sheen,
however these lights blow out the other items in the scene. We’d normally solve
this with light linking, which allows us to control which lights affect which
meshes, however Cycles [Cycles][cycles], Blender’s physical renderer doesn’t
support that so simply we work around it by rendering the 3D and 2D elements
separately and compositing them together post-render.

The bloom effects in the above GIF were done in After Effects, however you can
approximate something similar with a bloom effect on Blender camera.

[blender]: https://blender.org
[metaballs]: http://jamie-wong.com/2014/08/19/metaballs-and-marching-squares/
[cycles]: https://docs.blender.org/manual/en/latest/render/cycles/

***

Part of [Charm](https://charm.sh).

<a href="https://charm.sh/"><img alt="The Charm logo" src="https://stuff.charm.sh/charm-badge.jpg" width="400"></a>

Charm热爱开源 • Charm loves open source

