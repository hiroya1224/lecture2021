# Project

## Garbage collection by the Salamander Robot

### Modification

#### World
- add garbages

#### Salamander
- add camera
  - enables object detection

    ![git](doc/salamander_camera.gif)

- add arms
  - grasp or sweep garbages

    ![git](doc/salamander_arm.gif)

#### State machine
  - Searching - Look and walk around in random directions for garbage
  - Approacning - When some garbages are detected, walk toward the nearest one.
  - Grabbing - Grab garbage by arms.
  - Returning - Carry garbage to the collection point.
  - Releasing - Release garbage.

  ![state machine](doc/StateMachine.png)

### Demo


https://user-images.githubusercontent.com/25011913/122124848-c90f2400-ce6a-11eb-82cd-68feb5a0631c.mp4

