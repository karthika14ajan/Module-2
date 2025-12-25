*Iterative Statements: Palindrome Number Checker*

_AIM:_
To write a Python program that checks whether a given number is a palindrome using loops.

_ALGORITHM:_

Get input from the user and assign it to a variable num.
Assign the value of num to a temporary variable temp.
Initialize a variable rev to 0 (used to store the reversed number).
Use a while loop to reverse the digits:
While temp > 0:
rev = (10 * rev) + temp % 10
temp = temp // 10
After the loop, compare rev with num:
If equal, print that the number is a palindrome.
Else, print that it is not a palindrome.

_PROGRAM:_

num=int(input())
rev=0
temp=num
while temp>0:
    rev=(10*rev)+temp%10
    temp//=10
if rev==num:
    print("The given number {} is a Palindrome".format(num))
else:
    print("The given number {} is not a palindrome".format(num))

_OUTPUT:_

<img width="968" height="186" alt="image" src="https://github.com/user-attachments/assets/e07d0067-42c8-4676-9521-e2a64af7e108" />

_RESULT:_
Thus , the program has been executed succesfully.

*Built-in Functions -Binary Conversion Using Built-in Functions in Python*

_AIM:_
To write a Python program to convert the number 16 into its binary representation using built-in Python functions.

_ALGORITHM:_

Assign the value 16 to a variable a.
Use the built-in bin() function to convert the number to binary.
Print the result.

_PROGRAM:_

a=16
binary_number= bin(x)
print(binary_number)

_OUTPUT:_

<img width="380" height="182" alt="image" src="https://github.com/user-attachments/assets/8cdff1d6-02ef-4f0b-8534-6f484a23fb6b" />


_RESULT:_
Thus , the program has been executed succesfully.

*Lambda Function in Python: Addition of Two Numbers*

_AIM:_
To write a Python program that defines a lambda function which takes two arguments a and b, and returns their sum.

_ALGORITHM:_

Get two integer inputs from the user.
Use a lambda function to define a function f that returns a + b.
Call the function with the user inputs and print the result.

_PROGRAM:_

a=int(input())
b=int(input())
f=lambda a,b:a+b
print(f(a,b))

_OUTPUT:_

<img width="455" height="288" alt="image" src="https://github.com/user-attachments/assets/1c81beb2-00b4-46b1-b298-c8b13ef46337" />

_RESULT:_
Thus , the program has been executed succesfully.

*Functions in Python: Modulo Calculator*

_AIM:_
To write a Python program that defines a function which accepts two values and returns their modulo using the % operator.

_ALGORITHM:_

Define a function called result that takes two arguments a and b.
Inside the function, compute the modulo using a % b.
Print the result of the modulo operation.
Get two integer inputs from the user.
Call the result function with the user-provided values.

_PROGRAM:_

def result(a,b):
    mod=a%b
    
    print(f"modulo is {mod}")

a = int(input())
b = int(input())

_OUTPUT:_

<img width="637" height="289" alt="image" src="https://github.com/user-attachments/assets/e85c54ec-6369-4c64-8914-526f54adfd79" />

_RESULT:_
Thus , the program has been executed succesfully.

*🔺 Looping(Patterns)-Pascal's Triangle Generator in Python*

_*This project demonstrates a simple Python program to generate Pascal’s Triangle, where the number of rows is provided by the user.*_

_AIM:_
To write a Python program that generates Pascal's Triangle using numbers. The number of rows is accepted from the user.

_ALGORITHM:_

Start the program.
Input the number of rows from the user.
Loop from 0 to the number of rows.
For each row:
Print appropriate spaces to shape the triangle.
Compute values using the formula:
[ C(n, k) = \frac{n!}{k!(n-k)!} ]
Print all rows of Pascal’s Triangle.
End the program.

_PROGRAM:_

n = int(input())
for i in range(1,n+1):
    c=1
    for j in range(1,i+1):
        print(c,end=' ')
        c = c*(i-j)//j
    print()

_OUTPUT:_

<img width="644" height="603" alt="image" src="https://github.com/user-attachments/assets/96648568-9ed5-492e-9313-713267894925" />

_RESULT:_
Thus , the program has been executed succesfully.
