# Module-3
# 🧹 Strings-Remove Nth Index Character from a String
## Name: SANJEV R M
## Reg No: 212223040186
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
~~~
n=int(input())
def remove(a):
    for i in range(0,len(a)):
        if(i!=n):
            print(a[i],end='')
~~~

## Output
![image](https://github.com/user-attachments/assets/2994d62f-80a3-45e7-bf3e-b98c17a2547a)

## Result
Thus the python program is executed successfully
