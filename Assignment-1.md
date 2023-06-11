1. In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators.

Ans:-  * :expression
       'hello':value
        -87.8:value
        -:expression 
         /:expression 
         + :expression
         6 :value
2. What is the difference between string and variable?

Ans:A variable is a kind of entity where  we able to store a data which process a runtime and variable holds strings types  data types.
    Strings together group of  character .
    eg:-g="rasmi"('g'is the variable and 'rasmi' is string types data types .

 3. Describe three different data types
 Ans: The three different types data types are :-
            1.Numerical data types
            2.sequential data types
            3.Dictionary data types

```python
#Example for numerical data types
e=65
#Example for sequential data types
string="rekha"
#Example for dictionary data types
d={'name':'john','age':'23','dept':'sales'}
print(e)
print(string)
print(d)
```

    65
    rekha
    {'name': 'john', 'age': '23', 'dept': 'sales'}
    
4. What is an expression made up of? What do all expressions do?

Ans:Expression made up of operators and operands .If any programming language its evaluated as perthe precedence of its  operators.

```python
print(45+67-90) # In this expression ,python interpreter evaluates it to 22
```

    22
    
5. This assignment statements, like spam = 10. What is the difference between an expression and a statement?

Ans:An expression evaluates to a single value but statement does't.An expressions are  part of statements.

6. After running the following code, what does the variable bacon contain?
bacon = 22
bacon + 1


```python
# Example
bacon=22
bacon+1
print(bacon)
```

    22
    
7. What should the values of the following two terms be?
'spam' + 'spamspam'
'spam' * 3

```python
print('spam' + 'spamspam')
print('spam'* 3)
```

    spamspamspam
    spamspamspam
    
8. Why is eggs a valid variable name while 100 is invalid?

Ans: The eggs are the character that's why this valid but 100 is a number,variable name can't begin with number.

```python
egg="spam"
100="spam"
```


      Cell In[11], line 2
        100="spam"
        ^
    SyntaxError: cannot assign to literal here. Maybe you meant '==' instead of '='?
    

9. What three functions can be used to get the integer, floating-point number,or string version of a value?

Ans:The int(),float(),and str()functions evaluate to the integer,floating-point number,and string versions of the value.

10. Why does this expression cause an error? How can you fix it?
'I have eaten ' + 99 + ' burritos.'

Ans:The expression causes an error because 99 is an integer number and string can be concatenated to other string with +operator.

    The correct way is 'I have eaten'+str(99)+'burritos'