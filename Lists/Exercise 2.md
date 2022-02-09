### Exercise 2

Write a program to accept 2 lists from the user of 5 nos each . Assume each list will have unique nos Now find out how many items in these lists are common .

```python
list1=[]
list2=[]

for i in range(5):
    a=int(input("Enter the element of list 1:"))
    list1.append(a)
    
for j in range(5):
    b=int(input("Enter the element of list 2:"))
    list2.append(b)

count=0
for x in list1:
    for y in list2:
        if x==y:
            count+=1
if(count==0):
    print("No common elements")
else:
    print(count)
```
Output:
```
Enter the element of list 1:1
Enter the element of list 1:4
Enter the element of list 1:3
Enter the element of list 1:7
Enter the element of list 1:8
Enter the element of list 2:9
Enter the element of list 2:7
Enter the element of list 2:5
Enter the element of list 2:1
Enter the element of list 2:3
3
```
