# SDP Project

This will be the stage-two evaluation of the SDP on Open Source Tools. This document contains the details of the same. This project is group based, i.e. you will be working in groups. The project is designed in such a manner that, you will revise all the content that you've learnt during the 3 sessions and much more if you are willing to.

## The Basics

This will be a group based project. The project shall focus on key areas of the SDP sessions namely:

-   Python
-   HTML
-   Git

## The Projectwork

The project work has three parts to it. We will see them one by one now.

### Part 1

This part deals with Python programming language. So, what you need to do is pretty simple.

You will be given a program in C programming language, you will need to port that code into a valid Python 3 code.

For, example conside the following C code:

```C
#include <stdio.h>
#include <string.h>

int main()
{
   char source[1000], destination[1000];

   printf("Input a string\n");
   gets(source);

   strcpy(destination, source);

   printf("Source string:      \"%s\"\n", source);
   printf("Destination string: \"%s\"\n", destination);

   return 0;
}
```

If you haven't already guessed it, well..., I am just copying a string from one location to another.

Now the valid Python 3 code for the above C code would be:

```Python
import copy
a = input()
print("Source string: " + a)
b = copy.deepcopy()
print("Destination string: " + b)
```

And that's about it. A few things that you might find useful to remember is that, we aren't actually expecting that you convert every C instruction to a Python instruction. We just want a valid conversion that does the the same thing that previously the C code was doing.

### Part 2

The HTML part would be pretty straight foreword. This deals with presenting your answer. You need a render that looks something like this...

![HTML render](https://github.com/GLUG-REVA/SDP-Project/blob/master/images/Example.png)

Now this requires you to just Google for one tag in HTML that we haven't covered. We will be kind enough to provide you with a place where you can look for it.

[Click here](https://www.w3schools.com/html/default.asp) and you shall be directed to w3c website where you can find what you are looking for and much more.

### Part 3

The last and the simple part is to push your code to git. A caveat here is that you will need to push your HTML file that looks like something that we showed you above, to your git repository.

* * *

And that's it. You are done with your project.

## General rules

This section has a set of rules that you need to follow:

-   Each and every person in the group must have their own repository
-   You are to solve only those questions that the set alloted to you has
-   The answer to one question must be one commit, i.e. if there are three questions, your repository must have three commits
-   On the day of presentation you will be asked to explain what you have done. So, you might as well know what you are doing so that you won't have a problem later.
-   You can submit partial answers, although you will be scored accordingly

## Before the Project

We would just like to point out a few points before you start your project.

### Setting-up Git on your system

We recommend that you work on Linux operating system, if for some unfortunate reasons this is not feasible, you can complete your project using [Git for Windows](https://gitforwindows.org/).

For setting-up Git on Linux or macOS we recommend going through tutorials for respective operating systems.

Look [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) for instructions.

**_Note: Please, read the instructions carefully before you execute them._**

### Some useful links and pointers

We have listed some websites that you can visit if you get stuck anywhere:

-   [Git documentation](https://git-scm.com/book/en/v2)
-   [HTML reference](https://www.w3schools.com/tags/default.asp)
-   For python, you could just simply google your need and Google will point you in the right direction. [Python tutorials Point](https://www.tutorialspoint.com/python3/index.htm), [Stackoverflow](https://stackoverflow.com/) are some of the most trusted and used websites. If you are feeling adventurous you can seive through the [python3 documentation](https://docs.python.org/3/):stuck_out_tongue_closed_eyes::sunglasses:
-   Please make sure that you google for python 3 instead fo python 2 as there are significant syntax changes and the scripts might not always be cross-compatible
