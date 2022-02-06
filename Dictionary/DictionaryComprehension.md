## Dictionary Comprehension

### *syntax*: dict_variable = { key:value for (key,value) in iterable}

1.Iterable can be any object on which iteration is possible

2.(key,value) is the tuple which will receive these key-value pairs one at a time

3.key:value  is the expression or key-value pair which will be assigned to new dictionary

```python


dict={1:'A',2:'B',3:'C',4:'D',5:'E'}

new_dict={k:v for k,v in dict.items()}

print(new_dict)

```
Output

```
{1: 'A', 2: 'B', 3: 'C', 4: 'D', 5: 'E'}
```

