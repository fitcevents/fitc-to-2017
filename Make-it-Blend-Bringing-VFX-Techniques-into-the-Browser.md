# Make it Blend: Bringing VFX Techniques into the Browser
Presented by Jonathan Hooker

Started a company called Oblio. They focus primarily on campaigns for movies. Started in Flash. Now doing HTML, 3D (WebGL) and VR.

Looking at the VFX industry and what can be learned from them when doing WebGL work. Focusing on Compositing, FX Tricks and Tech.


## Fantastic Beasts
- series of 360 scenes around NYC with real-time animated characters inserted

Compositing: the steps

1. build a base layer 
  1. looking at matte painting, glass mattes, etc, but more modern technique is projection mapping (mapping a low res photo or photos onto simple geometry)
  2. for FB, took series of photos and had to infer room measurements for recreation of the 3D spaces
2. match the lighting
  1. look at traditional movie lighting, rim lights, key lights, gel lights - look at the angle of the lights - photos with multi-coloured lighting can be great for breaking down a setup as the colours and highlights make it easy to determine light positions and angles
  2. baked lighting techniques
    1. for web, consider pre-applying the lighting to the textures rather than do it real-time
    2. mat caps: can do single light source, spherical mapping, works for viewing within 180 degrees of rotation
    3. equirectangular - fully rendered lighting on complete texture for model
    4. three.js and such tend to want to do whole scene rendering, so if you want to do things like blur an object, you need to consider rendering multiple scenes and compositing them
    5. LUT - switching in a modified colour table on textures, in order to colour match something into a scene
    6. light rays in Fantastic Beasts, are actually rendered in as as static planes

FX Tricks 
Now You See Me 2 - 

- sliding panes of multiple images over each other
- projection mapping

Tech

- lots of opportunity to figure out details and pipelines using other 3D tools, ie. Houdini
- lets you stay mostly in creative tools and then provides a pipeline for the developers to re-create in three.js

Often uses an overall rendering effect on the final scene, lens flare, blending, something, that helps tie together all the elements.

Mostly uses three.js for projects. Did code his own 3D framework early on, which was a great way to learn and understand WebGL. For many projects, he will modify three.js heavily to achieve certain effects. ie. cracks on the walls in Insidious


Budgets:

- as a studio, hard to do any WebGL for under $100k
- even with freelancers, adds up kick


