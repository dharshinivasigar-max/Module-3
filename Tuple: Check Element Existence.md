# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
~~~
x = ('a', 'n', 3, 8, 'z')

check1 = 'n' in x
check2 = 8 in x

print("Does 'n' exist in the tuple?", check1)
print("Does 8 exist in the tuple?", check2)
~~~
## Output
Does 'n' exist in the tuple? True
Does 8 exist in the tuple? True
## Result
The program demonstrates the use of the in operator in Python, which is used to verify the membership of an element within a sequence. By applying this operator to the tuple x, the program returns a Boolean value (True or False) depending on whether the specified character or integer is present in the collection.
