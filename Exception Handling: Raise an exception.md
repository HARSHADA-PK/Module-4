# Exception Handling in Python: Raise an exception

## 🎯 Aim
To write a Python program that takes the user's age as input and calculates the year of birth, handling invalid input using exception handling.

## 🧠 Algorithm
1.Start the program.

2.Read the user's age using input() and convert it to an integer.

3.Print the entered age.

4.Use a try block to handle errors:

5.If the age is less than 0, display a message "Input Correct age."

6.Otherwise, calculate the year of birth using year = 2022 - age.

7.Print the calculated year of birth.

8.Use the except block to catch and print any errors.

9.Stop the program.

## 🧾 Program
```
age=int(input())
print("Age is:")
print(age)
try:
    if(age<0):
        print("Input Correct age.")
    else:
        year=2022-age
        print("Year of Birth is:")
        print(year)
except:
    print(e)
```

## Output
<img width="870" height="355" alt="image" src="https://github.com/user-attachments/assets/c1e40985-6862-4c26-a08c-73b70d72db10" />

## Result
The program successfully displays the user's age and calculates their year of birth if the input is valid.
If the input age is negative, it prompts the user to enter the correct age.
