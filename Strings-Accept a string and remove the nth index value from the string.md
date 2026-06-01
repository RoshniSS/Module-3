# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
def remove(s):
    n = int(input())
    a = ""
    
    for i in range(len(s)):
        if i != n:
            a += s[i]
            
    return a

s = input()
print(remove(s))

## Output
<img width="1449" height="431" alt="Screenshot 2026-06-01 113751" src="https://github.com/user-attachments/assets/f4ec4daa-9425-42af-89b7-7bd7fcbe54af" />

## Result
Thus, the Python program was executed successfully and the desired output was obtained.
