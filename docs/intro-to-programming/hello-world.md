---
id: hello-world
title: Hello World
sidebar_label: Hello World
---

### Hello World

Hello world is the first program that most people start with when learning to program, this tutorial will be no different. We will be using the programming language called Python (Version 3.X) for most of this course. We will learn Python as we go, but to basically sum it up, it is special text (code) that the computer is able to translate into to doing something. The reason we choose Python is due to how close it is to English, it's power, and it's global use around the world. (i.e. can land you a job in the future!)


The basic structure of a hello world program is this:

* Program Source File
* A few lines of code to build the most basic empty project that can output text to the screen 
* A line of code that outputs the text "Hello World" or whatever you want to say!


So without further delay lets get into it:

1. Open a text editor or your IDE 
2. Type in (do not copy and paste, muscle memory is important when coding) the code below 
3. Save the file in the folder hello-world and with the file name helloWorld.py. 
4. Click the run button in your IDE or open a command window to the same directory as your helloWorld.py file and run the command ``` python3 helloWorld.py ```

```
#!/usr/local/bin/python3 
print("Hello, World!")
```

Now that is cool and all, but what in the world is all this stuff.

* ```#!/usr/local/bin/python3 ``` <-- this is a special line of code when running on Linux and Mac to tell the command line it is a Python Program and what to launch it with, in this case Python3. I recommend including this in your programs for cross platform support
*  ```print("Hello, World!") ``` <-- this is where the magic happens. What happens is we call this thing called a function, it is named "print" and we pass it in the value we want to print. In this case Hello World (with quotes, so the program knows it is text/string)

#### Functions 
So we mentioned functions briefly above, but what truly are they? 

Functions are shortcuts to a block of code that someone or ourselves wrote in another spot in our file or even another file. They allow us to re-suse our code that we/others have written instead of rewriting the same code over and over again making our program huge and messy. For example the developers of the Python programming language knew people would want to output text to their users frequently, so they created a function called print that takes in a thing called a parameter (explained below), and prints it to the user's screen using multiple lines of code that are within the print function call saving us the need to write them or type them every time we want to print text to the screen. 

#### Parameters

So what is a parameter? 

A parameter is the stuff you want to pass to your or someone else's function so that it uses your input/data instead of just whatever it wants. You can have as many parameters as you want when you write a function. However you are limited when calling it to how many parameters the person who created the function choose to allow or use. The "Hello World" part of our program between the ( and ) is the parameter that print accepts and uses when printing text to the user. These parameters can be all sorts of things like text, numbers, objects, etc. We will cover this in the next section when discussing a thing called "Variables"