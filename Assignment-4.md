1. What exactly is []?

Ans:Lists in python can be created by just placing the sequence inside the squre brackets[].
2. In a list of values stored in a variable called spam, how would you assign the value 'hello' as the third value? (Assume [2, 4, 6, 8, 10] are in spam.)

```python
spam=[2,4,6,8,10]
spam.insert(2,'hello')
print(spam)
```

    [2, 4, 'hello', 6, 8, 10]
    
Let's pretend the spam includes the list ['a', 'b', 'c', 'd'] for the next three queries.
3. What is the value of spam[int(int('3' * 2) / 11)]?

```python
spam=['a','b','c','d']
spam[int(int('3'*2)/11)]
```




    'd'


4. What is the value of spam[-1]?

```python
spam[-1]
``
  'd'


5. What is the value of spam[:2]?

```python
spam[:2]
```




    ['a', 'b']


Let's pretend bacon has the list [3.14, 'cat,' 11, 'cat,' True] for the next three questions.
6. What is the value of bacon.index('cat')?

```python
bacon=[3.14,'cat',11,'cat',True]
bacon.index('cat')
```




    1


7. How does bacon.append(99) change the look of the list value in bacon?
Ans:If we use append() then add the items in last of our list.

```python
bacon=[3.14,'cat',11,'cat',True]
bacon.append(99)
print(bacon)
```

    [3.14, 'cat', 11, 'cat', True, 99]
    
8. How does bacon.remove('cat') change the look of the list in bacon?
Ans: If we use remove ()then it check the element after that remove the first matching element from the list.

```python
bacon=[3.14,'cat',11,'cat',True]
bacon.remove('cat')
print(bacon)
```

    [3.14, 11, 'cat', True]
    
9. What are the list concatenation and list replication operators?

Ans:As with strings,we can use the operators + and * to concatenate and replicate lists.
->When + appears between two lists,the expression will be evaluate as a new list that contains the elements from both lists.
->When * appears between a list and an integer,the expression will be evaluated as a new list that consists of several copies of the original list concatenated together.

```python
#Example 
l1=[1,2,3]
l2=[3,4,5]
print(l1+l2)
print(l2*3)
```

    [1, 2, 3, 3, 4, 5]
    [3, 4, 5, 3, 4, 5, 3, 4, 5]
    
10. What is difference between the list methods append() and insert()?

Ans:There is a simple difference between append and insert in python list,append method can be use for adding new element in the list only but by using insert we can add as well as can modify already occupied position.
11. What are the two methods for removing items from a list?

Ans:The remove() method removes the first matching element from the list.The pop() method removes an element at a given index,and will also return the removed item.
12. Describe how list values and string values are identical.

Ans:The similarity between Lists and Strings in python is that both are sequences.
13. What's the difference between tuples and lists?

Ans:Lists are denoted by the squre brackets and this is mutable.Tuples are denoted as parenthesis and this is immutable.
14. How do you type a tuple value that only contains the integer 42?

Ans:In this case we create a tuple then store a single integer value after that we use comma.

```python
t=(42,)
print(t)
print(type(t))
```

    (42,)
    <class 'tuple'>
    
15. How do you get a list value's tuple form? How do you get a tuple value's list form?

Ans:If we want to convert a python list to a tuple,you can use the tuple() function to pass the full list as an argument,and it will return the tuple as an output similarly case of tuple values list form.

```python
#Example 
l=[23,45,"rekh"]
print(l)
l=tuple(l)
l

```

    [23, 45, 'rekh']
    




    (23, 45, 'rekh')




```python
#Example
t=(67,89,"rekha")
print(t)
t=list(t)
t
```

    (67, 89, 'rekha')
    




    [67, 89, 'rekha']


16. Variables that "contain" list values are not necessarily lists themselves. Instead, what do they contain?

Ans:They contain references to list values.
17. How do you distinguish between copy.copy() and copy.deepcopy()?

Ans:The copy()return a shallow copy of the list,and deepcopy() returns adeep copy of the list.