# #3 Statements

---

## If Statement

```Python
score = 59
if score >= 60:
    print('Pass!')
```


```Python
if score >= 60:
    print('Pass!')
else:
    print('OOPS! You failed.')
```


```Python
if score >= 60:
    print('Pass!')
else if gender == 'girl':
    print('OK! Let\'s try something to fix it!')
else:
    print('OOPS! You failed.')
```


Comarision Operators

![Comarision Operators](http://aaronr.github.io/scienceday2015/images/math.jpg)


### Practice

Create a program for ranking:

- Over 90: print A
- Over 80: print B
- Over 70: print C
- Over 60: print D
- Others: F

---

## For Statement

- Iterating elements
- Do something for each element


```Python
# Measure some strings:
words = ['cat', 'window', 'howdoyouturnthison']
for w in words:
    print(w, len(w))
```

```Bash
cat 3
window 6
howdoyouturnthison 18
```


The range() Function

```Python
lst = range(4) # [0, 1, 2, 3]

for i in lst:
    print(i)
```

```Bash
0
1
2
3
```


### Practice

Create a program for printing follow lines:

```Bash
 1 2 3 4 5 6 7 8 9
 2 4 6 8 10 12 14 16 18
 3 6 9 12 15 18 21 24 27
 4 8 12 16 20 24 28 32 36
 5 10 15 20 25 30 35 40 45
 6 12 18 24 30 36 42 48 54
 7 14 21 28 35 42 49 56 63
 8 16 24 32 40 48 56 64 72
 9 18 27 36 45 54 63 72 81
```
