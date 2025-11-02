# File Handling in Python: To find longest word in the file

## 🎯 Aim
To write a Python program to create a text file and find the longest word present in that file.

## 🧠 Algorithm
1.Start the program.

2.Define a function create_file(file_path, content) that:

3.Opens a file in write mode.

4.Writes the given content to the file.

5.Closes the file automatically using the with statement.

6.Define another function find_longest_word(file_path) that:

* Opens the file in read mode.

* Initializes an empty string long to store the longest word.

* Reads the file line by line.

* Splits each line into words using split().

* Compares the length of each word with the current longest word.

* Updates long if a longer word is found.

* Returns the longest word.

7.Call both functions — first to create the file, then to find the longest word.

8.Stop the program.

## 🧾 Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to find the longest word in a file
def find_longest_word(file_path):
    with open(file_path,'r')as file:
        long=""
        for line in file:
            for words in line.split():
                if len(words)>len(long):
                    long=words
    return long

```

## Output
<img width="1054" height="332" alt="image" src="https://github.com/user-attachments/assets/78a240bd-7d35-4c2f-b87e-2d14a571152b" />


## Result
The program successfully creates a text file with user-provided content and displays the longest word in that file.
