# Lesson 1.0
## Your First Application is "Hello, World"
### **Objectives**
1. Students can display "Messages" on monitor.
2. Students can run Python program by theirselves.


### **Instruction**
1. Open your Editor
2. Create "New File" as **hello.py**
3. type below
```python
print("Hello, World")
```
4. Press F5, for run the program

OUTPUT
```python
Hello, World
```

# Congratulations!!


## Exercise 1a
1. Write a program to print out your name.
2. Write a program to print out your name and mobile number in multiple line.


# Lesson 1.1
## You will learn how to declare variables in Python.
### **Objectives**

1. Understanding in variable declaring.
2. Students can declare variable in Python
3. Students can print variable to disply.

### **Instruction**
```python
# Declare integer variable
apple = 5
```

```python
# Declare float variable (Decimal number)
money = 10.25
```

```python
# Declare string variable
book = "Python books"
```

```python
# Declare boolean variable (Logical)
like = True
# or
dislike = False
```
### Print Variable with print()
```python
print("How many apples?", apple)
# How many apples? 5
```

```python
print("How much money do you have?", money)
# How much money do you have? 10.25
```

```python
print("What is your favorite book?", book)
# What is yout favorite book? Python books
```

# Lesson 1.2
## You will learn how to make a decision.
### **Objectives**

1. Understanding in decision making
2. Students can use IF-ELSE syntax in Python
3. Students can apply IF-ELSE in the next lesson.

### Instruction

To change the following **"Flow Chart"** to a program you just need to undenstand the flow and write it down as a piece of code.

<img src="https://firebasestorage.googleapis.com/v0/b/adabrain-9229.appspot.com/o/PyNew-lessons%2Flesson-1%2FScreenshot%20from%202019-05-22%2014-28-47.png?alt=media&token=a8fad103-952b-4be9-8ba8-e8f9cef6f567">

```python
# Start program

# Declare variable
apple = 5

# Make a decision making
if apple < 10:
    print("Apples less than 10") # True
else:
    print("Apples more than 10") # False

# End program
```

### IF-ELSE IF-ELSE
In case, we need more than one condition. ElSE If is another syntax we should learn.

<img src="https://firebasestorage.googleapis.com/v0/b/adabrain-9229.appspot.com/o/PyNew-lessons%2Flesson-1%2FScreenshot%20from%202019-05-22%2015-04-45.png?alt=media&token=b62b9e68-0f51-4bf9-9761-104c4632dc8d">

```python
# Start program

# Declare variable
apple = 5

# Make a decision making
if apple < 10:
    print("Apples less than 10") # True
elif apple == 5:
    print("Apples equal to 5") # False from the first condition, but True in the second
else:
    print("Apples more than 10") # False

# End program
```

### Exercise 1b
1. Write a program to decide to go to school or stay at home.

<img src="https://firebasestorage.googleapis.com/v0/b/adabrain-9229.appspot.com/o/PyNew-lessons%2Flesson-1%2FScreenshot%20from%202019-05-22%2015-16-56.png?alt=media&token=a210ce6a-74a5-4ef7-b373-40ac7b24fc1c">

2. Write a program to convert Thai to Christian year.

    **Given,**
    2562 = 2019 + 543 <br>
    2561 = 2018 + 543

    > **FORMULA** <br>
    > Thai_year = Christian_year + 543

<hr>