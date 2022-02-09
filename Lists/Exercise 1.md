### Exercise 1

Write a program to accept 5 unique integers from the user. Make sure if the integer being entered is already present in the list your code displays the message “Item already present” and ask the user to reenter the integer. 

```python

list=[]
print("Enter 5 elements:")
a=int(input("Enter the element:"))
list.append(a)
while(len(list)<5):
    
            b=int(input("Enter the next element:"))

            if b in list:
                print("Item already present")
            else:
                list.append(b)
print(list)
```
Output
```
Enter 5 elements:
Enter the element:12
Enter the next element:2
Enter the next element:2
Item already present
Enter the next element:3
Enter the next element:2
Item already present
Enter the next element:4
Enter the next element:2
Item already present
Enter the next element:5
[12, 2, 3, 4, 5]
```
