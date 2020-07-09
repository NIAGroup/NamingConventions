# *Python*

## **Common Styles and Examples**

Pascal Case       | Camel Case      | Snake Case         |   Lower Case    |  Caps Case 
:----------------:|:---------------:|:------------------:|:---------------:|:----------------:
LazyDogBrownFox   | lazyDogBrownFox | lazy_dog_brown_fox | lazydogbrownfox | LAZYDOGBROWNFOX

## **Naming Conventions**

### *Modue/File Names*
* Lower Case or Snake Case for improved readability.
```python
example.py
random_function_generator.py
```

### *Class Names*
* Pascal Case: 
```python
class CirclePlotter(object):
```

### *Function/Method Names*
* Lower Case or Snake Case for improved readability. Camel Case if that's already the prevailing style.
```python 
def example():
def random_function_generator():
def randomFunctionGenerator():
```

**Note:** Use one leading underscore for non-public methods: 
```python 
def _print_helper(self, user_id)
```

### *Variable Names*
* Lower Case or Snake Case for improved readability.
```python
status = "OK"
temp_func = random_funciton_generator()
```

**Note:** Use one leading underscore for non-public instance variables:
```python 
_user = _get_user_id()
```

### *Argument/Parameter Names*
* All Lower Case. 
```python
def example(guid=None):
```

**Note:** If name clashes with a reserved keyword, append a single trailing underscore: 
```python 
def example(class_):
```

### *Constants*
* All Caps Case with underscores separating words.
```python
MAX_OVERFLOW 
TOTAL
```

## **Additional Tools/Modules**
The module **pycodestyle** checks style compliance on existing projects.
```python
pip install pycodestyle
pycodestyle yourcode.py
```

The program **autopep8** can be used to automatically reformat code in the PEP 8 style 
```python
pip install autopep8 
autopep8   --in-place   yourcode.py
```

## **Reference**
For more standards and links refer to [Coding Standards Lookup](README.md/#Python) page.

## **Guidelines**
To contribute refer to the [Contributing](guidelines/CONTRIBUTING.md) and [License](guidelines/LICENSE) pages.
