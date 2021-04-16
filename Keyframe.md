1. select camera object
2. set up location
3. at the frame you want, right click the location of camera in right workspace and select insert keyframe
4. move to a different frame and insert a new keyframe for a new camera position
5. this should make a simple camera movement animation. moving from the position at frame 1 to the position at frame x(the other frame which has a position set up)

- select keyframes in timeline and set interpolation to linear for constant camera movement instead of slow, then fast
- outliner/render: turn on screen space reflections (sword not reflecting the ground?) and motion blur (camera motion blur)
- outliner/output properties: set render save location(// for current project directory) and render file format(FFmpeg for animation)
  - in encoding, click h264 MP4 in presets. also can set the quality here
- look into OpenEXR (image sequence)

**To finish, click Render animation**
