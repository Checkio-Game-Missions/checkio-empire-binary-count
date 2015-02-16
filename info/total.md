For the Robots the decimal format is inconvenient. If they need to count to "1",
their computer brains want to count it in the binary representation of that number.
You can read more about binary [here](http://en.wikipedia.org/wiki/Binary_number).

Thus we are using integers to inform another towers about quantity of enemies.

You are given a number (a positive integer).
You should convert it to the binary format and count how many unities (1) are in the number spelling.
For example: 5 = 0b101 contains two unities, so the answer is 2.

**Input:** A number as a positive integer. 

**Output:** The quantity of unities in the binary form as an integer.


**Example:**

```python
count_units(4) == 1
count_units(15) == 4
count_units(1) == 1
count_units(1022) == 9
```
**How it is used:**

How to convert a number to the binary form. It can be useful for Computer Science purpЛадно

**Precondition:**
```python
0 < number <= 2 ** 32
```
