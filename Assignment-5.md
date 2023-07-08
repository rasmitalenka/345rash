1. What does an empty dictionary's code look like?

Ans:If we create an empty dictionary then assign the variable name it provide empty set of curly braces.


```python
d={}
d
type(d)
```




    dict



2. What is the value of a dictionary value with the key 'foo' and the value 42?


```python
{'foo':42}
```




    {'foo': 42}



3. What is the most significant distinction between a dictionary and a list?

Ans:In list items are set in ordered pair but in dictionary items are in unordered .

4. What happens if you try to access spam['foo'] if spam is{ 'bar': 100}?


```python
# This code provide error
spam={'bar':100}
spam['foo']
```


    ---------------------------------------------------------------------------

    KeyError                                  Traceback (most recent call last)

    Cell In[5], line 3
          1 # This code provide error
          2 spam={'bar':100}
    ----> 3 spam['foo']
    

    KeyError: 'foo'


5. If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys()?


Ans:There is no difference between them.


```python
spam={'cat':400}
'cat' in spam
```




    True




```python
'cat' in spam.keys()
```




    True



6. If a dictionary is stored in spam, what is the difference between the expressions cat in spam and cat in spam.values()?
Ans: The operator checks whether key value'cat' in spam but spam.values() check whether there is value 'cat' for one of the key in spam.


```python
spam={'cat':200}
'cat' in spam
```




    True




```python
'cat' in spam.values()
```




    False



7. What is a shortcut for the following code?
if 'color' not in spam:
spam['color'] ='black' 


```python
spam={'cat':200,'color':'black'}
spam
```




    {'cat': 200, 'color': 'black'}



8. How do you 'pretty print' dictionary values using which module and function?


```python
import json
# initializing dictionary
test_dict ={'gfg':{'rate':5,'remark':'good'},'cs':{'rate':3}}
#printing original dictionary
print("The original dictionary is:")
#Using json.dumps() to pretty print
pretty_dict=json.dumps(test_dict,indent=4)
print("The Pretty print dictionary is:\n",pretty_dict)
```

    The original dictionary is:
    The Pretty print dictionary is:
     {
        "gfg": {
            "rate": 5,
            "remark": "good"
        },
        "cs": {
            "rate": 3
        }
    }
    


```python

```
