1. Why are functions advantageous to have in your programs?

Ans:Function reduce the need for duplicate code .This makes programs shorter,
    easier to read ,and easier to update.

2. When does the code in a function run: when it's specified or when it's called?

Ans:The code in a function run  if we called the function not specified the function.

3. What statement creates a function?

Ans:At first we declare a def statement after that we create a function.

4. What is the difference between a function and a function call?

Ans:The main difference are when we create  a function we use def statement at first but in case of function call means we call function which alredy created .

5. How many global scopes are there in a Python program? How many local scopes?

Ans:There is one global and a local scope in a python program.


```python
# This is global
x=37
def myfunc():
    x=67    # This is local 
    print(x)
myfunc()
print(x)
```

    67
    37
    

 6. What happens to variables in a local scope when the function call returns?

Ans:When a function call returns ,the local scope is destroyed.

7. What is the concept of a return value? Is it possible to have a return value in an expression?

Ans:A return is a value that a function returns to the calling the function
    when it completes its task.Yes it is possible to have a return value in an 
    expression.

8. If a function does not have a return statement, what is the return value of a call to that function?

Ans:If a function does not specify a return statement,after calling that function it returns None.

9. How do you make a function variable refer to the global variable?

Ans:A global statement will force a variable in a function to refer to the global variable.

10. What is the data type of None?

Ans:Python uses the keyword None to define null objects and variables.

11. What does the sentence import areallyourpetsnamederic do?

Ans:That import statement imports a module named areallyourpetsnamederic.

12. If you had a bacon() feature in a spam module, what would you call it after importing spam?

Ans:This function can be called with spam.bacon().

13. What can you do to save a programme from crashing if it encounters an error?

Ans:Place the line of code that might cause an error in a try clause.

14. What is the purpose of the try clause? What is the purpose of the except clause?

Ans:The code that could potentially cause an error goes in the try clause.

   ->The code that executes if an error happens goes in the except clause.
