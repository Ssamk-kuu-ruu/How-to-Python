# Variables, DataType, and Input in Python

### Python
- **Easiest Language** to **understand.**
- **Identation** is **VERY IMPORTANT**
- **Brief** syntaxes.
- **No semicolon** needed.

---

### Variables
Variables are used to store up data for later use.

---

### Basic Data Types
- ***string***: identifier = "HelloWorld"
- ***int***: identifier = 25
- ***float***: identifier: 8.62
- ***bool***: identifier: True

---

### Identifiers
The name of the variable which the user decides to choose.

**Syntax** : ***(identifier = value)*** 

``` py
firstName = "Kkuru"  
lastName = "Lee"
number = 25
money = 750.50
isTall = True
```

---

### Advanced Data Types
(will be tackle in the next lessons.)

- ***list***
- ***tuple***
- ***dict***
- ***set***
- ***frozenset***
- ***bytes***
- ***bytearray***
- ***memoryview***

---

### ***print()***
used to display something  in the console.

**Syntax** : print(variable)

```py
firstName = "Kkuru"  
lastName = "Lee"
number = 25
money = 750.50
isTall = True

print(firstName)
print(lastName)
```
#
    Kkuru
    Lee

#

### ***input()***
used to make the user input something in the console.

**Syntax** :  
variable = input()  
variable = input("Enter Something")

```py
firstName = input("Enter your first name: ")

print("Hi, " + firstName)
```
#

### Casting Variables
A technique used to convert a datatype to another datatype.

**Syntax** :  
- Convert **numbers** to **string**: ***str(number)***
- Convert **string** to **numbers** : ***int(string)*** or ***float(string)***

```py
firstName = "Kkuru"
number = 25

print(firstName + str(number))
```
#
    Kkuru25

```py
money = 75000.62
number = "252"

print(money + int(number))
```
#
    75252.62

#

### Arithmetic Operations
used to perform mathematical operations inside our programming language.

| Symbol | Operation | Result | Usage |
| ----------- | ----------- | ----------- | ----------- |
| + | Addition | Sum | x + y
| - | Subtraction| Difference| x - y |
| * | Multiplication | Product | x * y
| / | Division | Quotient | x / y
| % | Modulus | Remainder | x % y
| // | Floor Division | Quotient (Rounded Off) | x // y
| ** | Exponent | Power | x ** y
