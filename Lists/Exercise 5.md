### List Comprehension 

Write a program to produce square of nos from 1 to 5 , store them in a list and print the list.

Do the code using:

1.Normal for loop

2.List Comprehension

```python
#using for loop
list=[]
temp=0
for i in range(1,6):
    temp=i*i
    list.append(temp)
print(list)
```
Output
```
[1, 4, 9, 16, 25]
```


```python
#using list comprehension
list=[x*x for x in range(1,6)]
print(list)
```
Output
```
[1, 4, 9, 16, 25]
```


