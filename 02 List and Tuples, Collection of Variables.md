# List and Tuples in Python

### Advanced Data Types

- ***list***
- ***tuple***
- ***dict***
- ***set***
- ***frozenset***
- ***bytes***
- ***bytearray***
- ***memoryview***

### List
A **Read** and **Write** collection of variables that may be used to sort certain data.

**Syntax**:  
identifier = [value, value1, value2]

```py
courses = ["BSIT", "BSCS", "BSCpE"]
```

### Reading WHOLE List
You can read a list by printing the whole list.

**Syntax**:  
print(list)

```py
courses = ["BSIT", "BSCS", "BSCpE"]

print(courses)
```
#
    ['BSIT', 'BSCS', 'BSCpE']


### Reading lists ITEMS
You can read a list by printing one of the items inside it by using an index.

**Syntax**:  
print(list[index])

### Index
The number of where an item is on a collection.

|  |  |  |  |
| ----------- | ----------- | ----------- | ----------- |
| ***+ index :*** | 0 | 1 | 2
| ***courses =*** | ***["BSIT ,"*** | ***"BSCS ,"*** | ***"BSCpE"]*** |
| ***- index :*** | -3 | -2 | -1

```py
# + INDEX    0       1        2
courses = ["BSIT", "BSCS", "BSCpE"]
# - INDEX   -3      -2       -1

print(courses[2])
print(courses[0])
print(courses[-1])
print(courses[-2])
```
#
    BSCpE
    BSIT
    BSCpE
    BSCS

### Reading Lists RANGE
You can read a list's range of items by specifying a range of index.

**Syntax**:  
print(list[ startIndex : endIndex ])  
print(list[: endIndex])  
print(list[startIndex: ])

***NOTED: endindex item is excluded***

```py
courses = ["BSIT", "BSCS", "BSCpE", "BS(Physics)", "BSME"]

print(list[2 : ])
print(list[ : 3])
print(list[1 : 4])
```
#
    ['BSCpE', 'BS(Physics)', 'BSME']
    ['BSIT', 'BSCS', 'BSCpE']
    ['BSCS', 'BSCpE', 'BS(Physics)']

### Assigning List ITEMS
You can assign a list item by using an INDEX and an Assignment Operator '='.

**Syntax**:  
list[index] = value  

```py
courses = ["BSIT", "BSCS", "BSCpE", "BS(Physics)", "BSME"]

courses[0] = "BSCE"

print(courses)
```
#

    ['BSCE', 'BSCS', 'BSCpE', 'BS(Physics)', 'BSME']


### List LENGTH
You can check the number of items in a list by using the ***len()*** function.

**Syntax**:  
len(list)

```py
courses = ["BSIT", "BSCS", "BSCpE", "BS(Physics)", "BSME"]

print(len(courses))
```
#
    5

### List COUNT
You can count how many times an item occurs in a list by using the ***count()*** function.

**Syntax**:  
list.count(value)

```py
courses = ["BSIT", "BSCS", "BSCpE", "BSIT", "BSCS", "BSIT"]

print(courses.count("BSIT"))
```
#
    3


### List ADD ITEMS by APPEND
***append()*** adds an item at the **END OF THE LIST.**

**Syntax**:  
list.append(value)

```py
courses = ["BSIT", "BSCS", "BSCpE"]

courses.append("BS(Physics)")

print(courses)
```
#
    ['BSCE', 'BSCS', 'BSCpE', 'BS(Physics)']

### List ADD ITEMS by INSERT
***insert()*** adds an item at the **SPECIFIED INDEX**

**Syntax**:  
list.insert(index, value)

```py
courses = ["BSIT", "BSCS", "BSCpE"]

courses.insert(1, "BS(Physics)")

print(courses)
```
#
    ['BSCE', 'BS(Physics)', 'BSCS', 'BSCpE']

### List DELETING ITEMS by REMOVE
***remove()*** deletes an item **based** on their **value**.

**Syntax**:  
list.remove(value)

```py
courses = ["BSIT", "BSCS", "BSCpE"]

courses.remove("BSIT")

print(courses)
```
#
    ['BSCS', 'BSCpE']

### List DELETING ITEMS by POP
***pop()*** deletes an item **based** on their **index** but if **index** is not specified it deletes the last item.

**Syntax**:  
list.pop()  
list.pop(index)

```py
courses = ["BSIT", "BSCS", "BSCpE"]

courses.pop()

print(courses)
```
#
    ['BSIT', 'BSCS']