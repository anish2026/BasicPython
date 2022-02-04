### Exercise 3

Modify the previous code (Exercise 2) so that you are able to find out the name of the player also who has scored the highest score.

```python
dict={}
for i in range(1,6):
    s=input()
    run=int(input())
    dict[s]=run
k=max(dict.values())
a=""
for s,run in dict.items():
    if run>k:
        k=run
        a=s
print("Max run: ",k)
print("Name: ",s)
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
Ponting
```

