# Python

## Tips:
- type(<input>) : show the datatype of a <input>
```
type(10) // int
type('hello') // str
```
- uc

## 00-Variable
To store a variable in computer memory

```python
price = 10
print(price) // 10
price = 20 // update
print(price) // 20

price = 10 // integer
rating = 4.9 // float
name = "samit" // string
title = 'Mr' // string
is_published = False // boolean

```
## 01-Getting Inputs
Receive an input from user
```python
name = input('What is your Name? ')
print('Hi ' + name)

```

## 02-TypeConversation

```python
int() // covert to integer
float() // convert to float
bool() // convert to bool

type() // will let you know the data types
type(10)
type('Samit')
```
## 03-Strings
string can be defaine in `''` or `""`

```python

course = "python's cource for Begineer"
course = 'python cource for "Begineer"'

//multi line
message='''
  Hello World!
  This is python learning basic Notes
  Br,
  Samit
'''

course = 'Python for begineer'
course[0] // 0th position of a string
course[-2] // last character from the string
course[0:3] // pyt
course[1:] // ython for begineer

//Formatted String
firstName = 'John'
lastName = 'Smith'
message = firstName+'['+lastName+'] is a legend'

msg=f'{firstName} [{lastName}] is a coder' //formatted string

//string supported methods
course = 'Python for Begineers'
len(course) // 20
course.upper() // convert this string to upper case
course.lower()
course.find('p') // will return first Index of the first occurance of the character
course.replace('p','j')
check = 'Python' in course

```
## 04-Arithmatic-Operator
```python
value = 10 +4
value = 10-4
value = 10 // 3
value = 10 % 3
value = 10 ** 3

x = 10
x += 3 // is similar to x = x + 3

//math function - to work with numbers
round(2.9)
abs(-2.9)
```

## 05-if-Statement
```python
is_hot = True
is_cold= True
if is_hot:
   print("It's a hot day")
   print("Drink plenty of Water")
elif is_cold:
   print("It's a cold")
   print("Wear Warm cloth")
else:
   print("It's a lovely day")
print("Enjoy your day")
```

## uc
```python

```
