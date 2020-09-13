---
id: basic-math
title: Basic Math Using Code
sidebar_label: Basic Math
---

### Intro
Now that we are able to receive input from the user, lets build out a simple calculator program that adds together two numbers.


```
print("Welcome to the Addernator")
a = int(input("What is the first number you want to add: "))
b = int(input("What is the second number you want to add: "))

c = a + b

print("Your total is: " + str(c))

```

Whoa! What is up with these int() and str() functions? Well if you remember back to the last lesson 