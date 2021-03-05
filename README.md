## Lists

A data structure that is a mutable(changable) ordered sequence of elements. Defined by having values between square brackets, [ ].

*Ex.*

```python

groceryList = ["chips","ice cream","chocolate","pizza","banana", "pineapple"] # List of strings
```
### Indexing List
Each item in an list corresponds to an index number, which uses an integer; starting with 0

`len(groceryList)` --> 6

### List Functions
1. LIST.append(ELEMENT)#Adds an item to the end of the list
`groceryList.append("milk")`
2. LIST.insert(INDEX, ELEMENT)#Adds an item to the index location
`groceryList.insert(3,"apples")`
3. LIST.remove(ELEMENT)#Searches the list and removes it
`groceryList.remove("banana")`
4. LIST.pop(INDEX)#Remove an item at the specified index
`groceryList.pop(4)`

To reference an item we use LIST[INDEX]

## Tuples

Another type of list that stores data/values inside but in parenthesis,( ).
Unlike lists, tuples __cannnot__ be changed(they are immutable).

`colors = ("Blue","Red","Yellow")`
`print(colors[2])` --> Yellow

## Dictionary

Another type of list that stores data/values inside curly brackets, { }. Similar to a list, it is mutuable, however, the index is key, which is linked to a data/value.

```python
students = {
  "visham" : "029138",
  "