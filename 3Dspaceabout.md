# Coordinate systems

Q. How do we define models position, rotation and scale in 3d space?
 USING Multiple Vectors

- Position the displacement from the origin of the world coordinate system
- Rotation is the degree rotation around each axis 
- Scale is the scale factor on each axis

A transform is a mathematical concept which packages position, rotation, and scale together.

# Understanding Materials:
Enhanced the look of my 'solar system' 3D project using materials.

# skybox:
It is a special material wrapped around the scene that represents vast beyond your world.
The vast beyond of the world that the player sees can be visually represented through a: Skybox Material

#Lights:
Goals of lighting: 
- Illumination - able to see the objects
- Modeling - reveal the structure of the objects
- Focus - create contrast, create light and dark areas to get the player's focus
- Visual Style - A texture is set as a property of a: Shader. The shader has properties for the available texture maps, such as Albedo, Normal, Bump, Emission, etc.

Types of light - 
- direct v/s indirect
- realtime v/s backed

#Game Engine Light:
- Lights have no geometry
- More lights, more processors, slow down games
- shadows negatively affect

#Adding Behaviors:
- using behaviours to get things rotating
- parent/child relationships
- understand the world - local coordinate systems
- When a script (aka, a behavior) is attached to a gameObject, it becomes a: COMPONENT

#World v/s Local Coordinate System:
- World coordinate system is centred at the origin of the world. For example - the earth rotates around the world origin coordinate.
- Local coordinate system where the origin is a defined location related to the game object, usually the center of the game object. For example - a planet spinning around its own axis.
- Parent-child relationships add yet a 3rd coordinate system; that is, the child may move relative to a parent's local coordinate system instead of a world coordinate system. Like the moon moves around the earth. Earth moves around the sun.

#Audio:
- **Audio Listener Component**: like a microphone in the game world.
   - Component takes audio from my environment
   - Have only 1 audio component active/turned on at a time within my unity scene
   - The audio listener component is what picks up sound in 3D space. There can be only one audio listener active at one time. Audio listeners can be on any GameObject but are typically on the main camera.
 
- **Audio Source Component**:
   - Component is attached to game objects within the scene
   - The audio listener picks up the sound emitted from all audio sources to create an overall sound mix the player hears.
   - Unity supports 3D position sounds

- Cameras:
   - In a game engine, the camera is really a projection of 3D geometry onto the 2D plane of the display.
   - 2 types of 3D Projections: perspective (view change with camera) and orthographic (remains static view)
   - ![Screenshot 2025-04-04 at 17 15 28](https://github.com/user-attachments/assets/fbc283ee-be2b-44ea-a5b3-accb5f0555c7)
 
- Prefabs:
   - Template of the Gameobject that you want to copy and use several times.
   - Objective: create 'comet' gameObject, turn the gameObject into prefab, spawn several comets into the scene based on this prefab.
   - Prefabs are imp concepts-
   - when you setup a game object with all of it's components and features, you can sconvert it a prefab (template), ready to use across scenes.
   - template gameobject
   - if you make changes to prefab - > all gameobjects under it will be chnages. you can revert the chnages as well. but you can also make chnages to 1 gameobject under prefab.
   - ![Screenshot 2025-04-04 at 18 20 31](https://github.com/user-attachments/assets/9ad192b8-900f-4dc8-af2f-951e7facc054)
   - ![Screenshot 2025-04-04 at 18 21 07](https://github.com/user-attachments/assets/ac56635f-2f87-4239-b234-4a136c5ea4b6)

 ##**Build & Test**
 - Mac
 - Windows
 - Web GL
 - Built solarsystem app for all 3 platforms
 - check and make the builds before every publishing

##**Solar System Project**
- made my own solar system unity project
- hands-on from scratch to build to modify and publishing

##**Publish Project**
- gather screenshots
- compress the builds for distribution
- publish the project
- using itch.io to host our game for this project
- location of the project:
- 



