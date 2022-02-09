### Exercise 4

Write a program to accept an alphanumeric string from the user. Now extract only digits from the given input and add it to the list . Finally print the list. Make sure your list contains numeric representation of digits

```python

s=input()
list1=[]
for ch in s:
    if ch in "1234567890":
        list1.append(ch)       
print(list1)

```
Input
```
I am An18H , my reg no. is 19BAI10192
```
Output
```
['1', '8', '1', '9', '1', '0', '1', '9', '2']
```
