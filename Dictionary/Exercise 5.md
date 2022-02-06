### Exercise 5

 Write a program to produce a new dictionary from the given dictionary with the keys of each key getting doubled

 dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
 
 ```python
 dict1 = {'a': 1, 'b': 2, 'c': 3, 'd': 4, 'e': 5}
new_dict = {2*k:v for k,v in dict1.items()}
print(new_dict)
```
Output
```
{'aa': 1, 'bb': 2, 'cc': 3, 'dd': 4, 'ee': 5}
```
