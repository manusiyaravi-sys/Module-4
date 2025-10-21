# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {3: 'c', 6: 'f', 1: 'a', 4: 'd', 2: 'b', 5: 'e'}
key=sorted(d.keys())
print('Keys are')
for i in key:
    print(i,end=" ")
```
## Sample Output
<img width="528" height="398" alt="m4-3" src="https://github.com/user-attachments/assets/2c43b02a-2c5b-46ec-b304-17a096c6e256" />

## Result
successsfully created
