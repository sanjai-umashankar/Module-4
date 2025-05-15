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
my_dict = {'banana': 3, 'apple': 5, 'cherry': 2, 'date': 4}

# Sort by keys
sorted_by_keys = dict(sorted(my_dict.items()))

# Sort by values
sorted_by_values = dict(sorted(my_dict.items(), key=lambda item: item[1]))

# Display results
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)
print("Sorted by Values:", sorted_by_values)

```

## Sample Output
![image](https://github.com/user-attachments/assets/811eeacf-3d5d-433f-bf1a-5e6007c701fb)

## Result
Thus the program has been successfully executed
