# # Stack-Stack Reversal Program 🔁

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```
stack = []
n = int(input("Enter number of elements to push: "))

for i in range(n):
    val = int(input(f"Enter element {i+1}: "))
    stack.append(val)

reverse = []
while stack:
    reverse.append(stack.pop())

print("Reversed stack elements:", reverse)
```
## 🧪 Sample Input and Output
<img width="1449" height="808" alt="image" src="https://github.com/user-attachments/assets/5509554a-33be-457b-b132-fdac779b914e" />

## Result
Therefore the given Python Program has been executed successfully and the output has been verified.



