**Overview**
- complemenatary colors(color wheel opposites)
- negative and positive space(glowing/not glowing??)
- 20% of canvas to stand out and 80% to be a contrast
- negative space/depth
- atmosphere can give a good sense of depth
- foreground is contrasted and clear while background is washed out (scene looks bigger, depth)

**Background/Space**
- shading tab
- world nodes is where to add the atmosphere
- volume metrics in the world output is the thing to use
- add/shader/emission - adds atmosphere/depth(adjust strength)
- compositing tab: add/color/gamma - adjusts grey values (bright and dark value crunching) (helps scene not feel so washed out)

**Lighting**
- use a light object, set it at a reasonable power (5000 for this case) and move it to a good angle
- use objects to block the light from the view of the object you want to light to set up "rays" (it's easier to do if you orient your view so that the light lines with the object)

**Volumetrics**
- shading tab
- world nodes
- add/shader/volume scatter
- connect to volume output
- creates light shafts (idk...)
- volumetric lighting
- combine both volume scatter and emission, use add/shader/add shader

**Improvement stuff**
- f12 fast render
- render tab (right area) set % to 50% for faster rendering
- DOF (depth of field)
  - camera tab, check depth of field, select object, set f-stop
 - better contrast
  - shading tab and mess with emission and gamma in compositing
  - change bloom to inc/decr glow
  - 
