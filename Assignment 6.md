Q.1. What are keywords in python? Using the keyword library, print all the python keywords.

Ans:Python has a set of keywords that are reserved words that can't be used as variable names ,function names ,or any other identifiers. 


```python
import keyword
print(keyword.kwlist)
```

    ['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
    
Q.2. What are the rules to create variables in python?

Ans:
     1.A variable name must start with a letter or the underscore character.
     2.A variable name cannot start with a number.
     3.A variable name can only contain alpha-numeric character and underscores
       (A-z,0-9,_)
     4.Variable names are case-sensitive(age,Age and AGE are three different variable)
Q.3. What are the standards and conventions followed for the nomenclature of variables in python to improve code readability and maintainability.

Ans:Constants enable you to use the same name to identify the same value throughout your code.If you need to update the constant's value,then you don't have to change every instance of the value.You just have to change the value in a single place:the constant definition.This improves your code's maintainability.
A descriptive name representing a given value throughout a program is always more readable and explicit than bare-bones value itself.
Q.4. What will happen if a keyword is used as a variable name?

Ans:It provide invalid syntax error because we can't use keyward as a variable name .This define the language's syntax and structure.
Q.5. For what purpose def keyword is used?

Ans:In python def keyword is used to define a function,it is placed before a function name that is provided by the user to create a user-defined function.
Q.6. What is the operation of this special character ‘\’?

Ans:In Python strings,the backslash "\" is a special character,also called the "escape" character.It is used in representing certain whitespace character.

Q.7. Give an example of the following conditions:
(i) Homogeneous list
(ii) Heterogeneous set
(iii) Homogeneous tuple

Ans:Homogeneous list store same type of data items in a list.
    Heterogeneous set store different type of data items in a set.
    Homogeneous tuple store same types of data items in a tuple.

```python
# Homogeneous list
l=[23,56,67]
print(l)
# Heterogeneous set
s={"john",56,7.9,True}
print(s)
#Homogeneous tuple
t=("john","rasmi","rekha")
print(t)
```

    [23, 56, 67]
    {56, True, 'john', 7.9}
    ('john', 'rasmi', 'rekha')
    
Q.8. Explain the mutable and immutable data types with proper explanation & examples.

Ans:An object is considered mutable if its state or value can be modified after it is created.
example:-lists,dictionaries,sets.
The immutable objects are objects whose value can not be changed after initialization.
example:-string,tuple,range etc.Q.
9. Write a code to create the given structure using only for loop.
*
***
*****
*******
*********

```python
n=5
for i in range(n):
    for j in range(n-i-1):
        print(' ',end=' ')
    for k in range (2*i+1):
        print('*',end=' ')
    print()    
```

            * 
          * * * 
        * * * * * 
      * * * * * * * 
    * * * * * * * * * 
    
Q.10. Write a code to create the given structure using while loop.
|||||||||
|||||||
|||||
|||
|

```python
rows=int(input("enter number of rows: "))
for i in range(rows,1,-1):
    for space  in range(0,rows-i):
        print(" ",end=" ")
    for j in range(i,2*i-1):
        print("|",end="")
    for j in range(1,i-1):
        print("|",end="")
    print()    
```

    enter number of rows: 6
    |||||||||
      |||||||
        |||||
          |||
            |
    


```python

```
