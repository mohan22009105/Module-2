# Exp.No:2b  
## FUNCTIONS - sum of series

### AIM  
To write a Python program to find the sum of series: 1 + 1/2 + 1/3 + ….. + 1/N using function .Get the input for the value of n..



### ALGORITHM

1. Start the program.

2. Define a function sum_series(n) that:

   Initializes sum to 0.

   Uses a loop from 1 to n:

   Add 1/i to the sum at each step.

3. Prompt the user to input a value for n.

4. Call the function and store the result.

5. Print the sum rounded to two decimal places.

6. End the program.



### PROGRAM
```
#Reg.No: 212222220026
#Name: Mohan Kumar P

def series(n):
    sum1=0
    for i in range(1,n+1):
        sum1=sum1+(1/i)
    print("The sum of series is",round(sum1,2))

number=int(input())
series(number)


```
### OUTPUT

![Screenshot 2025-04-28 143836](https://github.com/user-attachments/assets/16156b04-c1b0-40d2-ae89-12c5225a75ad)

### RESULT
Thus, the program is verified and executed Successfully
