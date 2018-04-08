# #2 Basic

---

## Operator

```Python
print(1 + 1)

print("Hello" + "World")
```


![operator](https://d1e4pidl3fu268.cloudfront.net/f20083ef-a2fb-4673-ac88-13d58ba68133/Arithmeticoperators.png)

---

## Variables

```Python
i = 1 # Assignment
i * 10 # Use vairable
j = i * 20 # Assign to another variable

name = pcwu
message = 'Hello ' + name + '!' # Hello pcwu!
```

---

## Data Structure

```Python
# Number
>>> 1 + 2
3

# String
>>> '1' + '2'
'12'

# List
>>> [1] + [2]
[1, 2]
```

---

## Number

```Python
>>> 2 + 2
4
>>> 50 - 5*6
20
>>> (50 - 5*6) / 4
5.0
>>> 8 / 5  # division always returns a floating point number
1.6
>>> 17 / 3  # classic division returns a float
5.666666666666667
>>>
>>> 17 // 3  # floor division discards the fractional part
5
>>> 17 % 3  # the % operator returns the remainder of the division
2
```

---

## String

```Python
>>> 'spam eggs'  # single quotes
'spam eggs'
>>> 'doesn\'t'  # use \' to escape the single quote...
"doesn't"
>>> "doesn't"  # ...or use double quotes instead
"doesn't"
>>> '"Yes," he said.'
'"Yes," he said.'
>>> "\"Yes,\" he said."
'"Yes," he said.'
>>> '"Isn\'t," she said.'
'"Isn\'t," she said.'
```

---

## List

- A list of element
- Any kind of variable could be a element in list
  - `[1, 3, 5, 7, 9]`
  - `['apple', [1,2,3], 123]`
- 0-index



```Python
>>> squares = [1, 4, 9, 16, 25, 36]

>>> squares[0]  # indexing returns the item
1
>>> squares[-1]
36

>>> squares[1:]  # slicing returns a new list
[4, 9, 16, 25, 36]
>>> squares[:-1]
[1, 4, 9, 16, 25]
>>> squares[2:4]
[9, 16]
>>> squares[2:-2]
[9, 16]
```


String is a List

```Python
>>> s = 'Python'

>>> s[0]
P
>>> s[0:2]
Pyt
```


How it works?

```
 +---+---+---+---+---+---+
 | P | y | t | h | o | n |
 +---+---+---+---+---+---+
 0   1   2   3   4   5   6
-6  -5  -4  -3  -2  -1
```

---

## Other Data Structures

- Dictionaries
- Sets
