# Python - if/else, loops, functions

In this project, I began utilizing conditionals and loops in Python by using `if`, `if ... else`, `break`, `continue`, `pass`, and `range` statements with `while` and `for` loops. I practiced writing my own Python functions while learning about scope of variables, tracebacks, and arithmetic operators.

## You have to execute `TASK 2 to TASK 6 and TASK 14` using the command `chmod u+x filename` to enable the last checker 7 to check.

## Function Prototypes :floppy_disk:

Prototypes for functions written in this project:

| File                       | Prototype                                               |
| -------------------------- | ------------------------------------------------------- |
| `7-islower.py`             | `def islower(c):`                                       |
| `8-uppercase.py`           | `def uppercase(str):`                                   |
| `9-print_last_digit.py`    | `def print_last_digit(number):`                         |
| `10-add.py`                | `def add(a, b):`                                        |
| `11-pow.py`                | `def pow(a, b):`                                        |
| `12-fizzbuzz.py`           | `def fizzbuzz():`                                       |
| `13-insert_number.c`       | `listint_t *insert_node(listint_t **head, int number);` |
| `101-remove_char_at.py`    | `def remove_char_at(str, n):`                           |
| `102-magic_calculation.py` | `def magic_calculation(a, b, c):`                       |

## Tasks :page_with_curl:

* **0. Positive anything is better than negative nothing** `mandatory`
  * [0-positive_or_negative.py](./0-positive_or_negative.py): Python program that assigns a random signed number to the variable `number` each time it is executed and prints whether `number` is positive or negative.
  * Prints the number followed by:
    * If the number is greater than 0: `is positive`
    * If the number is 0: `is zero`
    * If the number is less than 0: `is negative`
    * Followed by a new line.
  * Completion of [this source code](https://github.com/holbertonschool/0x01.py/blob/master/0-positive_or_negative_py).

* **1. The last digit** `mandatory`
  * [1-last_digit.py](./1-last_digit.py): Python program that assigns a random signed number to the variable `number` each time it is executed and prints its last digit.
  * Prints the string `Last digit of [number] is [last_digit]` followed by:
    * If the number is greater than 5: `and is greater than 5`
    * If the number is 0: `and is 0`
    * If the number is less than 6 and not 0: `and is less than 6 and not 0`
    * Followed by a new line.
  * Completion of [this source code](https://github.com/holbertonschool/0x01.py/blob/master/1-last_digit_py).

* **2. I sometimes suffer from insomnia. And when I can't fall asleep, I play what I call the alphabet game** `mandatory`
  * [2-print_alphabet.py](./2-print_alphabet.py): Python program that prints the alphabet in lowercase, not followed by a new line.
  * Using only one `print` and one loop.
  * Storing characters in variables or importing modules not allowed.

* **3. When I was having that alphabet soup, I never thought that it would pay off** `mandatory`
  * [3-print_alphabt.py](./3-print_alphabt.py): Python program that prints the alphabet in lowercase, followed by a new line.
  * Using only one `print` and one loop.
  * Without storing characters in variables or importing modules.
  * Prints every letter except for `q` and `e`.

  bytecode provided by Holberton School.
