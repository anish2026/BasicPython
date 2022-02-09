### Exercise 3

Rewrite the previous code so that your code alos displays the items which are common in both the lists

```python
list1=[]
list2=[]

for i in range(5):
    a=int(input("Enter the element of list 1:"))
    list1.append(a)
    
for j in range(5):
    b=int(input("Enter the element of list 2:"))
    list2.append(b)

list3=[]
for x in list1:
    for y in list2:
        if x==y:
            list3.append(x)
if len(list3)==0:
    print("No common elements")
else:
    print(list3)
   ```
Output

```
Enter the element of list 1:10
Enter the element of list 1:20
Enter the element of list 1:30
Enter the element of list 1:40
Enter the element of list 1:50
Enter the element of list 2:60
Enter the element of list 2:70
Enter the element of list 2:20
Enter the element of list 2:30
Enter the element of list 2:10
[10, 20, 30]
```

