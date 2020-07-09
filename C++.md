# *C++*

## **Common Styles and Examples**

Pascal Case       | Camel Case      | Snake Case         |   Lower Case    |  Caps Case 
:----------------:|:---------------:|:------------------:|:---------------:|:----------------:
LazyDogBrownFox   | lazyDogBrownFox | lazy_dog_brown_fox | lazydogbrownfox | LAZYDOGBROWNFOX

## **Naming Conventions**

### *File Names*
* Snake Case.
```C++
my_useful_class.c
my_useful_class.cpp
```

### *Class/Type Names*
* Pascal Case: The names of all types — classes, structs, type aliases, enums, and type template parameters — have the same naming convention. No underscores. 
```C++
class CirclePlotter : public PlotterClass{};
struct MyStruct{};
```

### *Funciton/Method Names*
* Pascal Case. The same naming rule applies to class- and namespace-scope constants that are exposed as part of an API and that are intended to look like functions
* Accessors and mutators (get and set functions) may be named like variables
```C++ 
int RandomFunctionGenerator();
void set_count(int count);
```

### *Variable Names*
* Lower Case or Snake Case for multiple words.
* Data members of classes (but not structs) additionally have trailing underscores
```C++
std::string table_name;
int count=0;
class TableInfo {
  ...
 private:
  std::string table_name_;  // OK - underscore at end.
  static Pool<TableInfo>* pool_; 
};
```

### *Namespace Names*
* Lower Case or Snake Case for multiple words.
```C++
example::example_scope::example_item temp_example;
```

### Macro Names
* All Caps Case with underscores separating words.
```C++
#define PI 3.14159265358979323;
```

## **Reference**
For more standards and links refer to [Coding Standards Lookup](README.md/#C++) page.

## **Guidelines**
To contribute refer to the [Contributing](guidelines/CONTRIBUTING.md) and [License](guidelines/LICENSE) pages.