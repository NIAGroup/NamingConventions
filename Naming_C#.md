# *Naming Conventions - C#*

Pascal Case       | Camel Case      | Snake Case         |   Lower Case    |  Caps Case 
:----------------:|:---------------:|:------------------:|:---------------:|:----------------:
LazyDogBrownFox   | lazyDogBrownFox | lazy_dog_brown_fox | lazydogbrownfox | LAZYDOGBROWNFOX

### *Files and Directories*
* Pascal Case.
```C#
MotorControl.cs
```

### *Classes*
* Pascal Case: Names of classes, enumerations, namespaces
* Interface names are recommended to start with "I".
```C#
public class MyClass {}
namespace MyNamespace {}
public enum MyEnum {}
public interface IMyInterface {}
```

### *Funcitons and Methods*
* Pascal Case.
```C# 
public int RandomFunctionGenerator();
```

### *Variables*
* Pascal Case: If field is a public field, static, or constant.
* Camel Case: If local variable or parameter.
* Camel case with a leading underscore: If private, protected, internal fields and properties. 
```C#
public class MyClass {
  public int MyPublicVariable = 0;
  public static bool IsConnectionOpen = false;
  private bool _myPrivateVariable = false;
  
  public int MyMethodNameHere(int valueReturned) {
    var myLocalVariable = "example";
    return valueReturned;
  }
}
```

## **Reference**
For more standards and links refer to [Coding Standards Lookup](README.md/#C&#35) page.

## **Guidelines**
To contribute refer to the [Contributing](guidelines/CONTRIBUTING.md) and [License](guidelines/LICENSE) pages.