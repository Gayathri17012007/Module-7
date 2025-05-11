# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:
~~~c
def sum_of_digits(n):
    if n == 0:
        return 0
    else:
        return n % 10 + sum_of_digits(n // 10)
number = int(input("Enter a number: "))
print(f"Sum of digits of {number} is:", sum_of_digits(abs(number)))
~~~
## OUTPUT
![Screenshot 2025-05-11 134851](https://github.com/user-attachments/assets/eb8259e4-5973-4162-a4d7-5efdd711a3bd)


## RESULT
Thus the program has been executed successfully.
