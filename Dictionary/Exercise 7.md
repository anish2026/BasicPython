### Exercise 7

Write a program to produce a new dictionary from the given dictionary but with the values that are greater than 2

dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}

```python
dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
dict={ k:2*v for k,v in dict1.items() if v>2 }
print(dict)
```
Output
```
{'c': 6, 'd': 8, 'e': 10}
