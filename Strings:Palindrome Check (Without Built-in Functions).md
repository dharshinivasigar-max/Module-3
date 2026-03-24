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
~~~
word = "google"
reversed_word = word[::-1]

if word == reversed_word:
    print(f'"{word}" is a palindrome.')
else:
    print(f'"{word}" is not a palindrome.')
~~~
## Output
"google" is not a palindrome.
## Result
The program identifies a palindrome by using the slicing technique [::-1] to create a reversed version of the original string. It then performs a direct comparison between the two. Since "google" reversed is "elgoog", the equality check fails, confirming it is not a palindrome.
