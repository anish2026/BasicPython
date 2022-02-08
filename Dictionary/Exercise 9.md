### Exercise 9

Write a program to produce a new dictionary from the given dictionary but with the value should be the string “EVEN” for even values and “ODD” for odd values.

```python

dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
dict={k:'even'if v%2==0 else 'odd' for k,v in dict1.items()}
print(dict)

```
Output
```
{'a': 'odd', 'b': 'even', 'c': 'odd', 'd': 'even', 'e': 'odd'}
```
