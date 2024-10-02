# Python - Classes and Objects

![alt text](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/247/oop-meme.jpg)

In this project, I began practicing object-oriented programming using classes and objects in Python. I learned about attributes, methods, and properties as well as data abstraction, data encapsulation, and information hiding.

## Tests :heavy_check_mark:


* **2. Size validation**
  * [2-square.py](./2-square.py): Python class `Square` that defines a square. Builds on [1-square.py](./1-square.py) with:
    * Instantiation with optional `size`: `def __init__(self, size=0):`
  * If a provided `size` attribute is not an integer, a `TypeError` exception is raised with the message `must be an integer`.
  * If a provided `size` attribute is less than `0`, a `ValueError` exception is raised with the message `size must be >= 0`.

* **3. Area of a square**
  * [3-square.py](./3-square.py): Python class `Square` that defines a square. Builds on [2-square.py](./2-square.py) with:
    * Public instance attribute `def area(self):` that returns the current square area.

* **4. Access and update private attribute**
  * [4-square.py](./4-square.py): Python class `Square` that defines a square. Builds on [3-square.py](./3-square.py) with:
    * Property `def size(self):` to retrieve the private instance  attribute `self`.
    * Property setter `def size(self, value):` to set `self`.

