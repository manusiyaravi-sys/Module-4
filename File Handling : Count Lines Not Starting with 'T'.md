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
def create_file(file_path, file_content): 
       with open(file_path,'w') as f:
           f.write(file_content)
def count_words_in_file(file_path):
       with open(file_path,'r') as f:
            file_content=f.read()
            w=file_content.split()
            return len(w)
```
## Output
<img width="1649" height="527" alt="m4-5" src="https://github.com/user-attachments/assets/db2be92e-aafc-462c-9592-187a997d34c9" />

## Result
sucessfully created
