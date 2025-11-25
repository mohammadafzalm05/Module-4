# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def create_file(file_path,file_content):
    with open(file_path,'w')as file:
        file.write(file_content)
def count_words_in_file(file_path):
    with open(file_path,'r')as file:
         content=file.read()
         words=content.split()
         return len(words)
```

## Output
![image](https://github.com/user-attachments/assets/6ad88cd2-e8cf-46d7-a6fb-38f02403077e)


## Result
Thus,the program  that counts the number of words in a text file has been executed successfully.
