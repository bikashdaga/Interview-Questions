# Python

* What is the value of `ans` in the following code? - **[1,1]** - [Blog](http://effbot.org/zone/default-values.htm)
``` python
>>> def function(data=[]):
...     data.append(1)
...     return data
...
>>> function()
[1]
>>> ans = function()
```
* What is break, continue and pass in Python? - [Reference](https://www.scaler.com/topics/python/break-pass-and-continue-statement-in-python/)

break, pass, and continue statements are provided in Python to handle instances where you need to escape a loop fully when an external condition is triggered or when you want to bypass a section of the loop and begin the next iteration. These statements can also help you gain better control of your loop.

**Example of break statement**
```python
nums = [7, 2, 3, 1, 5, 4, 6, 8, 9]
count = 0
while count < 7:
  print(nums[count])
  count += 1
  if nums[count] == 4:
    break
print("End")
```
**Output:**

```python
7
2
3
1
5
4
END
```
**Example of pass statement**

```python
if 1 + 2 == 3:
  print("Correct math")
  pass
  print("This will also be printed.")
```

**Output:**

```python
Correct math
This will also be printed.
```

**Example of continue statement**

```python
for letter in 'python':
  if letter == 'o':
    continue
  print(letter)
```

