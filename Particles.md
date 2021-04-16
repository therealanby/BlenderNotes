1. Select an object
2. Open particles tab in the outliner
3. add new particle setting
- when you press play on timeline, the object will emit particles
- lots of particle settings

**settings**
- number: number of particles emitted
- frame start: which frame to start on
- lifetime: particles will stay on screen for x frames
- field weights
- gravity: particles will fall or float upwards
- velocity
- normal: particle direction based off faces(normals)
- randomize: random direction
- render
- render as: select what to render as 
- render as object: particles will become a chosen object

**other stuff**
- select cube, go to shader tab, remove principled bsdf and add shader/transparent bsdf (make the object see-through) 
- select cube, go to materials tab in outliner, set blend mode to alpha blend and shadow mode to none
