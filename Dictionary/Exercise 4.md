### Exercise 4

Write a program to produce a new dictionary from the given dictionary with the values of each key getting doubled

dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}

```python

dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
new_dict={k:2*v for k,v in dict1.items()}
print(new_dict)
```
Output:
```
{'a': 2, 'b': 4, 'c': 6, 'd': 8, 'e': 10}
```
