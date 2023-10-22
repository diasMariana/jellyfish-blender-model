# jellyfish-blender-model

A jellysih model designed in Blender using geometry nodes, in an under-water scene. 

![jellyfish-animation](visuals/anim_light.gif)

## About
The jellyfish is fully desgined using geometry nodes. A few useful details:
- The length and position of the tentacles can be manipulated using a external object, you can set it in the ```Tentacles controller``` parameter which is exposed in the modifiers tab;
- The speed of the jellyfish's oscillation can also be controlled through the parameters that are exposed in the modifiers tab: ```Head oscillation speed```, ```Internal tentacles oscillation speed```, and ```External tentacles oscillation speed```. 

I took inspiration from several great tutorials:

- Jellyfish design:
    - [Blender jellysih by CGMatter](https://www.youtube.com/watch?v=zdivNPbugzY)
    - [Blender Tutorial - Creating Procedural Jellyfish by Nino](https://youtu.be/2m-QQDC6wzE?si=INKS3d2i5KyucKQl)
    - [Blender Geometry Nodes 025 by Albin MERLE](https://youtu.be/G-7q4aDKWac?si=MK0e89r0sjj3Wa8o)

- Underwater scene:
    - [Blender Underwater Scene Extended Tutorial by Resgoliste](https://youtu.be/0OI8TFmjQvM?si=RH1fa2CVykL1ItK3)
    - [Discovering Fake Caustics in Blender by Polyfjord](https://youtu.be/X9YmJ0zGWHw?si=wl7KWtm88NFpGLOx)

The HDRI was sourced from [PolyHaven](https://polyhaven.com/a/kloofendal_48d_partly_cloudy_puresky).


## Requirements
The scene was designed using Blender 3.6.4 LTS, but it should work fine in any version that supports geometry nodes. 