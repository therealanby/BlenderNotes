**Camera**
- view/viewpoint/camera
- n for properties popup
- view/view lock/camera to view - turn that on to move the camera while you're in it's view
- view/camera/frame camera bounds
- focus lens
- opacity/passepartout

**UI Stuff**
- scene collection/(right-click) area/vertical split - sets up two viewports. one for working and one for camera view
- you can turn off UI stuff in view
- gizmo and ornaments can be turned off

**Custom HDRI**
- high dynamic range imaging 
- shading workspace
- node network
- world/view/frame all - access the background
- http://www.hdrlabs.com/sibl/archive.html for custom hdri
- to add one: add/texture/environment texture - upload a hdri to that node and connect it to background/color
- to frame the hdri/move it around: texture coordinate (generated) -> mapping (vector)
- mapping vector can connect to multiple nodes
- input/light path node - controls raytracing stuff
- shader/mix shader - connecting two hdr/background nodes
- 2x background + light path(is camera ray) -> mixshader -> world output
- creates blurry hdri and also clear reflection on object

**Color Grade**
- cinematic world
- compositing tab
- add/color/color balance
- good node for color grading 

**Importing**
- file/append for blender files
- file/import for other files (.fbx and .obj are most common)

**Outliner**
- located on the right
- shows a list view of all objects in the scene
- you can make collections (for organization and grouping purposes)
- you can view modifiers and material properties
- eye icon to hide things
- viewpoint visibility and render visibility (change render visibility in filter)
- good to name objects and group them into named collections
