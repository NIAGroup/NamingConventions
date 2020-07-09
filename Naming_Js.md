# *Naming Conventions - JavaScript*

Pascal Case       | Camel Case      | Snake Case         |   Lower Case    |  Caps Case 
:----------------:|:---------------:|:------------------:|:---------------:|:----------------:
LazyDogBrownFox   | lazyDogBrownFox | lazy_dog_brown_fox | lazydogbrownfox | LAZYDOGBROWNFOX

### *Files and Directories*
* lower case with underscorees for readability.
```js
myscript.js
my_other_script.js
```

### *Variables, Parameters, and Functions*
* Camel case: Generally. 
  * Rarely you will find a leading underscore with variable/function name. It is intended to be used as private though not enforced in JavaScript.
* Upper case: If global variables or constants. May have underscores between words for readability. 
```js
class SoftwareDeveloper {
  constructor(firstName, lastName) {
    this.myFirstName = firstName;
    this.myLastName = lastName;
    this.name = _getName(firstName, lastName);
  }
 
  _getName(firstName, lastName) {
    return `${firstName} ${lastName}`;
  }
}
var dev = new SoftwareDeveloper("King", "Tchalla");
console.log(dev.name); //Good
console.log(dev._getName("King", "Tchalla")); // Bad

const THIS_IS_PI = 3.14;
function doSomething(arg){}
```

### *Classes*
* Pascal Case: Names of classes and enumerations
```js
class MyClass {}
namespace MyNamespace {}
public enum MyEnum {}
public interface IMyInterface {}
```

## **Reference**
For more standards and links refer to [Coding Standards Lookup](README.md/#JavaScript) page.

## **Guidelines**
To contribute refer to the [Contributing](guidelines/CONTRIBUTING.md) and [License](guidelines/LICENSE) pages.