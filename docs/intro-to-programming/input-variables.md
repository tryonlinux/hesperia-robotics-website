---
id: input-variables
title: Input & Variables 
sidebar_label: Input & Variables 
---

### Intro
Awesome! We can now output text to the user so they can see it on their screen, but if that is all we could do our programs would be quite boring and have very few use cases or expandability. What if someone wanted to provide our program some infomation for our program to use and store. How could we for example write a calculator program that took two numbers and added them together? How does that work? Well lets find out:

### Variables 
To deal with input form the user, we must first understand a part of a program called variables. Variables are an integral part of a program that are used to store and retrieve something we want to use later. You can think of variables as like sections in your brain that store data. For example we have a section of our brain that remembers our phone number. In programming we would consider that a variable and it would be stored in a section of our RAM/Memory on the computer, and to keep track of those sections we can provide them with a name. Variables are great for storing data from a user, values we want to use over and over again, and for keeping track of the status of a program. 

So how do we use variables in python? Simple! We give it a name and assign it a value using the equal sign.

```
variableName = "some value"

#or 

a = 55

#or 

phoneNumber = "555-555-5555" 
```

Variables in python are a bit different than most programming languages and do not need created with a thing called a type. However each variable has a type. These types say what kind of variable we created. This is helpful for the computer as it can define different sizes and sections of memory for this data. As you see above, if I have text I can define it with quotes to let Python know that I am storing a string of text instead of a number. Some of the types in Python are

* Integer  - Your run of the mill whole number 
* String - Text or a mix of text and numbers
* Float - A number with a decimal such as Money 
* Boolean - Either True or False value (0/1, on/off, etc)



### Input
Let's now discuss how we get input from a user into a variable. 

To get input from a user, Python has a special function we can call, similar to the print function that allows us to ask the user for data. It can be used like so:

```
#Call the input function with what you want to ask for
#Then store it to the name variable

name = input("Please enter your name:")

#lets now print it!

#As you can see below we can actually add our string "hey"
#with the value of the variable name to join them together. 

print("Hey " + name + "!") 


```

Give the above example a shot, remember type, don't copy and paste to gain that muscle memory! Feel free to change up variable names and ask for even more information like their age or eye colour. 

