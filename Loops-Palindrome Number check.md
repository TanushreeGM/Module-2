## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
<img width="413" height="234" alt="image" src="https://github.com/user-attachments/assets/6048b8a1-478a-40ca-ba0f-ae52c50a4d03" />

## Output
<img width="248" height="140" alt="image" src="https://github.com/user-attachments/assets/47375482-6a0a-4288-8fb3-8c4303c433f5" />

## Result
Thus, the program has been successfully executed.
