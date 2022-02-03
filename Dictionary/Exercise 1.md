### Problem 1

Write a program to create a dictionary called accounts containing account id and balance of account holders . 

Initialize it with the following data:

101 : 50000

102 : 45000

103 : 55000

Now ask the user to input an account id and amount . If the account id is present in the dictionary then update the balance by adding the amount given otherwise add a new entry of account id and balance in the dictionary. Finally 
print all the accounts details.

```python
accounts={101: 50000,
          102: 45000,
          103: 55000}
id=int(input())
amount=int(input())
if id in accounts:
    accounts[id]+=amount
else:
    dict={id:amount}
    accounts.update(dict)
print(accounts)
```
Input

```
104
25000
```
Output
```
{101: 50000, 102: 45000, 103: 55000, 104: 25000}
```
Input
```
102
80000
```
Output
```
{101: 50000, 102: 125000, 103: 55000}
```


