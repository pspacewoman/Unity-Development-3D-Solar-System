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

#Lights:
Goals of lighting: 
- Illumination - able to see the objects
- Modeling - reveal the structure of the objects
- Focus - create contrast, create light and dark areas to get the player's focus
- Visual Style -

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

#World v/s Local Coordinate System:
- World coordinate system is centred at the origin of the world. For example - the earth rotates around the world origin coordinate.
- Local coordinate system where the origin is a defined location related to the game object, usually the center of the game object. For example - a planet spinning around its own axis.
- Parent-child relationships add yet a 3rd coordinate system; that is, the child may move relative to a parent's local coordinate system instead of a world coordinate system. Like the moon moves around the earth. Earth moves around the sun.

#Audio:
- **Audio Listener Component**:
   - Component takes audio from my environment
   - Have only 1 audio component active/turned on at a time within my unity scene
 
- **Audio Source Component**:
   - Component is attached to game objects within the scene
   - The audio listener picks up the sound emitted from all audio sources to create an overall sound mix the player hears.
   - Unity supports 3D position sounds
