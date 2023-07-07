Q.1. Create two int type variables, apply addition, subtraction, division and multiplications
and store the results in variables. Then print the data in the following format by calling the
variables:
First variable is __ & second variable is __.
Addition: __ + __ = __
Subtraction: __ - __ = __
Multiplication: __ * __ = __
Division: __ / __ = __


```python
num1=10
num2=5
Addition=num1+num2
print(Addition)
Subtraction=num1-num2
print(Subtraction)
Multiplication=num1*num2
print(Multiplication)
Division=num1/num2
print(Division)
def var_function():
    print("First variable is:",num1)
    print("Second variable is:",num2)
    print("Addition:num1+num2:",Addition)
    print("Suntraction:num1-num2:",Subtraction)
    print("Multiplication:num1*num2:",num1*num2)
    print("Division:num1/num2:",num1/num2)
var_function()
```

    15
    5
    50
    2.0
    First variable is: 10
    Second variable is: 5
    Addition:num1+num2: 15
    Suntraction:num1-num2: 5
    Multiplication:num1*num2: 50
    Division:num1/num2: 2.0
    

Q.2. What is the difference between the following operators:
(i) ‘/’ & ‘//’
(ii) ‘**’ & ‘^’
Ans:
Normal division (/) returns a fractional number, whereas floor division (//) truncates the decimal part and returns the quotient.
    
  ii.For numeric data types,double-asterisk(**)is defined as an Exponential Operator and when we use'^' we can swaptwo integers without using a temporary variable. 
 Q.3. List the logical operators.
Ans:Python has three logical operators:and,or,and not.

Q.4. Explain right shift operator and left shift operator with examples.
Ans:The left operand's value is moved toward right by the number of bits specified by the right operand and the left operand's value is moved toward left by the number of bits specified by the right operand.

```python
#Example
a=10
b=-10
print("a >>1=",a>>1)
print("b<<1=",b<<1)
```

    a >>1= 5
    b<<1= -20
    

Q.5. Create a list containing int type data of length 15. Then write a code to check if 10 is
present in the list or not.


```python
My_list=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]
i=10
if i in My_list:
    print("present")
else:
    print("not present")

```

    present
    


```python

```
