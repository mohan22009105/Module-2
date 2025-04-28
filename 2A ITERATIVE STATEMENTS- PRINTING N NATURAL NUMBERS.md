# Exp. No: 2a  
## ITERATIVE STATEMENTS –  print the sum of N even numbers

###  Aim
To Write a Python program to print the sum of N even numbers.

---

###  Algorithm

1. Start the program.

2. Prompt the user to input a number n.

3. Initialize a variable sum to 0.

4. Use a loop from 1 to n:

   In each iteration, check if the number is even (number % 2 == 0).

   If even, add it to the sum.

5. Display the total sum of even numbers.

6. End the program.

---

### 🧾 Program

```python
#Reg.NO 212222220026
#Name Mohan Kumar P

n=int(input())
sum=0
for i in range(1,n+1):
    if i%2==0:
        sum=sum+i
print("Sum of Even numbers is:",sum)

```
### OUTPUT
![Screenshot 2025-04-28 143252](https://github.com/user-attachments/assets/f2296035-2ae4-4da1-a129-b77d90ff2441)

### RESULT

The program was successfully executed.

