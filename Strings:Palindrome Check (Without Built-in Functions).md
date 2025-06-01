# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
s = "google"
rev_s = s[::-1]
if s == rev_s:
    print(f'"{s}" is a palindrome.')
else:
    print(f'"{s}" is not a palindrome.')

```

## Output

![image](https://github.com/user-attachments/assets/bdd3e957-68fe-4fb4-b497-185fd9535d41)

## Result

Therefore,the given pyhton program is successfully verified
