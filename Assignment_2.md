1.What are the two values of the Boolean data type? How do you write them?

Ans:The two data types are true and false.The value '1' represents a true condition and '0' represents a false condition.

```python
#Return True as x is equal to y
x=5
y=5
print(bool(x==y))
#Return False as x is not equal to y
x=5
y=6
print(bool(x==y))

```

    True
    False
    
2. What are the three different types of Boolean operators?

Ans: The three different types of bolean operators are and,or and not.

3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ).

Ans:The and operators compares two expression then returns a true value if both expression are true.

   Truth Table of AND operator
   A B Output
   0 0 0
   0 1 0
   1 0 0
   1 1 1
   
   The or operators compares two expression then returns a true value if either 
   expression and both expression are true.
   
   Truth Table of OR operator
   A B Output
   0 0 0
   0 1 1
   1 0 1
   1 1 1
   
   The not operators switches true to false and false to true.
   
   Truth Table of NOT operator
   A  Output
   0   1
   1   0
4. What are the values of the following expressions?
(5 > 4) and (3 == 5)
not (5 > 4)
(5 > 4) or (3 == 5)
not ((5 > 4) or (3 == 5))
(True and True) and (True == False)
(not False) or (not True)



```python
print((5>4) and (3==5))
print(not (5>4))
print((5>4) or (3==5))
print(not ((5>4) or (3==5)))
print((True and True) and (True==False))
print((not False) or (not True))
```

    False
    False
    True
    False
    False
    True
    
5. What are the six comparison operators?

Ans:The six comparison operators are ==,!=,<,>,<=,and >=.

6. How do you tell the difference between the equal to and assignment operators?Describe a condition and when you would use one.

Ans:In python programming,'=' is an assignment operator used to assigning the value to a variable ,while '==' is an equal to operator that used for comparing
two values then evaluates to a Boolean.

```python
# Assignment operator
a=7
print(a)
#Equal to operator
if (a==7):
    print("True")
else:
    print("False")
    
```

    7
    True
    
7. Identify the three blocks in this code:
spam = 0
if spam == 10:
print('eggs')
if spam > 5:
print('bacon')
else:
print('ham')
print('spam')
print('spam')


```python
spam = 0
if spam == 10:
    print('eggs')
    if spam > 5:
        print('bacon')
else:
    print('ham')
    print('spam')
    print('spam')
```

    ham
    spam
    spam
    
8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam.

```python
spam=int(input())
if spam==1:
    print("Hello")
elif spam==2:    
        print("Howdy")
else:
    print("Greetings")
```

    2
    Howdy
    
9.If your programme is stuck in an endless loop, what keys you’ll press?
Ans:ctrl+c

10. How can you tell the difference between break and continue?

Ans:In break statement ,the control exits from the loop and used to stop the execution of the loop at a specific condition.But in case of continue the control remains within the loop and used to skip a particular iteration of the loop.

```python
# Using break 
l=[1,2,3,4,5]
for i in l:
    if i==3:
        break
    print(i) 
    
#Using continue
for i in l:
    if i==3:
        continue
    print(i)
```

    1
    2
    1
    2
    4
    5
    
11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)?

Ans:1. The user call range(10)with one argument, in case the user only decide where the  series are stop the range 0 to 9(but not include10) and its automatically start at 0 . 

2. The user call range(0,10)with two arguments,the user decide where the series start and also stop i,e start at 0 and stop at 10 not including 10.

3. In case range(0,10,1),the user decide where the series are start and stop and also big difference between one number and the next.

12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop.    

```python
for i in range(1,11): # Using for loop
    print(i,end=" ")
print()    

#  Using while loop
i=1
while i<=10:
    print(i,end=" ")
    i+=1
```

    1 2 3 4 5 6 7 8 9 10 
    1 2 3 4 5 6 7 8 9 10 
13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?

Ans:spam.bacon()