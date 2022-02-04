### Exercise 2

Write a program to create a dictionary called players and accept names of 5 players and their runs from the user. Now find out the highest score.

```python
dict={}
for i in range(1,6):
    s=input()
    run=int(input())
    dict[s]=run
print(max(dict.values()))
```
Input
```
Dhoni
249

Virat
190

Ponting
250

AB
134

Yuraj
234
```
Output
```
250
```

