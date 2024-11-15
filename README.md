Print Half Diamond Star Pattern
In this Python Program, we will be discussing about how to write a program to print Half Diamond Star Pattern. In this pattern, there are n rows with i numbers of time of iterations through all the rows and i+1 numbers of column are present for printing upper stars. Run another loop with i numbers of time of iterations through all the rows and num-1 numbers of column are present for printing lower stars. So, User have to enter a single value, that will be determine as a number of rows of the pattern. With the help of “Two Different Different Nested For Loop” , we will print the Half Diamond Star Pattern.

Python Program for Printing Half Diamond Star Pattern
Working:
Step 1. Start

Step 2. Take number of rows as input from the user and stored it into num.

Step 3. Run a loop ‘i’ number of times to iterate through all the rows which is Starting from i=0 to num.

Step 4. Run a nested loop inside the main loop for printing stars which is starting from j=0 to i+1.

Step 5. Move to the next line by printing a new line using print() function.

Step 6. Run another outer loop ‘i’ number of times to iterate through all the rows which is Starting from i=1 to num.

Step 7. Run a nested loop inside the main loop for printing stars which is starting from j=0 to num-1.

Step 8. Move to the next line by printing a new line using print() function.

Stop 9. Stop

Python Program:
num = int(input("Enter the Number: "))

for i in range(0, num):
    for j in range(0, i+1):
        print("*", end="")
    print()

for i in range(1, num):
    for j in range(0, num-i):
        print("*", end="")
    print()
