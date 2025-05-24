**Exp.No:3c
LIST - EVEN NUMBERS LIST**

**AIM** 

To write a Python function that creates a list of even numbers from 12 to n and prints the list and its sum.


**ALGORITHM**

1. Start the program.
2. Define a function named createlist that accepts a single parameter n.
3. Initialize an empty list l.
4. Iterate from 12 to n-1 using a for loop:
   For each number i in the range:
   Check if i is even using the condition i % 2 == 0.
   If the condition is true, append i to the list l.
5. After the loop ends, print the list using print("List =", l).
6. Calculate the sum of the list using sum(l) and print the result.
7. End the function.
8. Terminate the program.

**PROGRAM**

**212222040081 Kotha vamsi**

def createlist(n):
    l=[]
    for i in range(12,n):
        if i%2==0:
            l.append(i)
    print("List =",l)
    print("Sum of the list",sum(l))


**OUTPUT**

![image](https://github.com/user-attachments/assets/ed7c4457-ae3f-44e7-9595-582c59638b5a)



**RESULT**

Thus the program that creates a list of even numbers from 12 to n and prints the list and its sum has been implemented and executed successfully.
