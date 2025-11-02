# 🔤 To display the keys alphabetically using dictionary



## 🎯 Aim

To write a Python program to display all the keys of a dictionary in sorted order.

## 🧠 Algorithm

1.Start

2.Create a dictionary with key–value pairs.

Example: d = {1:'a', 2:'b', 3:'c', 4:'d', 5:'e', 6:'f'}

3.Use the sorted() function to get all keys in ascending order.

4.Use a for loop to iterate through the sorted keys.

5.Print each key using the print() statement.

6.Stop

## 🧪Program
```
d={1:'a',2:'b',3:'c',4:'d',5:'e',6:'f'}
print("Keys are")
for key in sorted(d):
    print(key,end=" ")
```

## Sample Output
<img width="472" height="197" alt="image" src="https://github.com/user-attachments/assets/1e4da0b4-eef2-4c1b-9756-8707f690b2e6" />

## Result
The program successfully displays all the keys of the dictionary in sorted order.

