##**Using C# within Unity**



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
