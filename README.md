# kritaSpritesheetExporter

krita plugin using the Krita python script manager; **requires Krita 4.2.x** or later (currently using the 4.2.0 pre-alpha version, git 325cbf6)

**Exports to a spritesheet** from the animation timeline (using all visible layers) (the spritesheet's number of rows and columns are user-defined; default would be Best Fit (trying to form a square) (could be One Row instead, still to be decided))

- **EDIT:** I also wanted one to **import a spritesheet** to the animation timeline of a new layer, but there actually already are built-in tools:
simply (with your spritesheet open) go to Image > Image Split then (in a new file of the same dimensions as one frame), File > Import Animation Frames
- **EDIT2:** The Import Animation Frames option also renders useless the **merge spritesheets** feature, as you can just File > Import Animation Frames and then Tools > Scripts > Export As Spritesheet
