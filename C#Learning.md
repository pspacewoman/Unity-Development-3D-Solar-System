**Using C# within Unity**
1. Unity is an event-driven environment.
2. So, add functions to classes to respond to events that occur in the software/applications/games. 
Ex. Start () and Update()
In software (or apps, games) there are other main events as well, like-

![Screenshot 2025-04-07 at 15 32 23](https://github.com/user-attachments/assets/06586e15-7742-4013-84c2-e1a52eb01514)

3. We can create Custome Events as well and respond to them accordingly.
4. In scripts, we can modify gameObjects like, When a script is attached to a gameObject, we can reference the gameObject in the script

this.gameObject = gameObject

5. Now, the COMPONENTS can be set on Unity and as well as can be handled via code.

a. EX- for making changes in transform components. and transform function also has built-in translate function
   gameObject.transform.position.x +=1;
   gameObject.transform.translate (1,0,0)

b. gameObject.GetComponen<TYPE>();
EX- rb = gameObject.GetComponen<Rigidbody>();
    rb.useGravity = true;
    
![Screenshot 2025-04-07 at 15 56 00](https://github.com/user-attachments/assets/6f79d558-e84b-4360-a971-fecae8f39a3f)

c. Another way to reference a component is to set up a public variable in your Class. This will make the variable appear in the Unity Editor Inspector. ex- public Text scoreDisplay;

d. Common COMPONENT TYPES (games)

![Screenshot 2025-04-07 at 15 59 33](https://github.com/user-attachments/assets/6bc2bac7-5bc5-433c-8654-3542d9c7ef9d)

e. Spawning GameObjects

To spawn or instantiate gameObjects into the game scene. Example, to spawn enemies create projectiles that the player fires. Once you attach the script to a gameObject, you can then set the prefab variable in the Unity Editor to be the prefab that you want to spawn. 

Script that instantiates a prefab-

![Screenshot 2025-04-07 at 16 05 18](https://github.com/user-attachments/assets/1277a16f-3d55-4593-b89a-e55899ae1769)

http://docs.unity3d.com/
https://learn.microsoft.com/en-us/dotnet/csharp/

[Unity Programming Quick Reference.pdf](https://github.com/user-attachments/files/19633597/Unity.Programming.Quick.Reference.pdf)

___________________________________________________________________

**Anatomy of a C# Script**
- Script created becomes game assets (under projects in UNITY)
- Edit scripts on Visual Studio

- ![Screenshot 2025-04-07 at 02 48 49](https://github.com/user-attachments/assets/9c586329-b4cc-4c1f-ac58-f728e881975e)

- Scripts, when attached to GameObjects, become components of the GameObjects and appear in the inspector

![Screenshot 2025-04-07 at 02 51 36](https://github.com/user-attachments/assets/d3b8ac7f-78ea-4233-b8e0-b804f833f51a)

## Programming in C# 
General
- INTELLISENSE - VS has this feature, which provides you with just-in-time documentation as I program.
- debug classes:
    - Debug.Log
    - Debug.LogWarning
    - Debug.LogError
- C# is case-sensitive
- Semicolon ends a statement
- We can write multiple statements or a line or span multiple lines
- Add comments for readability using
  - // OR
  - /* & */

**Variables in C#**
- For variable names, I follow lower camel casing (lower first word)
- If multiple words, Captital the subsequent names
- Primitive Data Type (means hold single values): int, float, bool, string
- Compound Data Type (Arrays and Lists)
- UNITY Data Types: Vector2, Vector3, GameObject, Any component type
- Access Modifiers: public, private
- Syntax:
AccessModifiers DataType VariableName
public int playerHeallth

**Execution Order of C# Code**
- Branching and Looping
- Branching: allows to change of execution order based on some condition ex. User Input, Changes in environment (Time)
      - Conditionals operators
      - If Statements
      - Logical Operators && ||
      - Switch Statement
- Looping: loops are portions of code that repeat until a condition is met
      - while loop
      - for loops
      - foreach loops

**Functions & Classes**
- Functions can perform specific tasks
- Syntax:
  AccessModifier ReturnType FunctionName Arguments
  public void DoAction ()
- Class is a container for a related group of variables, properties, methods and functions.
- Syntax:
   AccessModifier ClassKeyword ClassName BaseClass
   public class Player :MonoBehavior

  ![Screenshot 2025-04-07 at 15 21 01](https://github.com/user-attachments/assets/ba818bda-6eef-4949-9d2d-7d80caa46c76)

