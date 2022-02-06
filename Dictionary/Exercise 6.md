### Exwrcise 6

Write a program to accept a string from the user and print the frequency count of it’s letters ,
i.e. how many times each letter is occuring in the string.

```python
s=input()
dict ={ch:s.count(ch) for ch in s}
for k,v in dict.items():
    print(k,v)
```

Input
```
anishanandsrivastava
```
Output
```
a 6
n 3
i 2
s 3
h 1
d 1
r 1
v 2
t 1
```
