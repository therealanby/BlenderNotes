**Shading Mode Layout**
- top to bottom, left to right
- files, texture, texture preview viewport, nodes, and workspace  

**Nodes**
- node base way to work with materials
- instead of stack view in the properties workspace, it's in a node view
- shows how different parts are networked together
- texture + shader = material
- texture is the 2D image
- shader is how the image will look (shiny, plastic-looking, transparent, ...)
- sample node connection: uvImage.jpg -> principled BSDF -> Material Output
- the 1st node is the image texture
- the 2nd node is the shader (BSDF stands for bidirectional scattering distribution function. It's a function that describes how light scatters)
- 3rd node I don't really know what it does exactly. I think it describes how everything is put together and shown?
- The node network describes the material (it can be considered the material itself)
- node connection types are specified by color I think

**Shading**
- metallic: how metal the object looks
- roughness: how clear the metal is
- emission: glowing effect I think
- image-texture/color space/non-color: for connecting to non-color slots

**Node Conncetions**
- input/UV map -> vector/mapping -> image.jpg -> principled BSDF -> Material output
- (UV of object is inputted) -> (scale of UV) -> (texture?) -> (shading) -> (output)
- 
