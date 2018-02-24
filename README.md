# SDP Project

This will be the stage-two evaluation of the SDP on Open Source Tools. This document contains the details fo the same. This project is group based, i.e. you will be working in groups. The project is designed in such a manner that, you will revise all the content that you've learnt during the 3 sessions and much more if you are willing to.

## The Basics

This will be a group based project. The project shall focus on key areas of the SDP sessions namely:

-   Python
-   HTML
-   git

You will receive bonus points if you complete tasks labelled as bonus, which usually include doing something that hasn't be done in the SDP session. In such cases, references will be provided to help you with the task. For those whose eyes just popped out, completeing these bonus tasks are completely optional.

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

Now the valid Python 3 code for this would be:

```Python
import copy
a = input()
print("Source string: " + a)
b = copy.deepcopy()
print("Destination string: " + b)
```

And that's about it. A few things that you might find useful is that, we aren't actually expecting that you convert every C instruction to a Python instruction. We just want a valid conversion that does the the same thing that previously the C code was doing.

### Part 2

The HTML part would be pretty straight foreword. This deals with presnting you answer. We need a render that looks something like this...

![HTML render](https://github.com/GLUG-REVA/SDP-Project/blob/master/images/Example.png)

Now this required you to just Google for one tag in HTML that we haven't covered. Anyway we will be kind enough to provide you with a place where you can look for it.

[Click here](https://www.w3schools.com/html/default.asp) and you shall be directed to w3c website where you can find what you are looking for and much more.

### Part 3

Again, another simple part is to push your code to git. A small caveat here is that you will need to push your HTML file that looks like something that we showed above to your git repository.

* * *

And that's it. You are done with your project.

## General rules

This section has a set of rules that you need to follow:

-   Each and every person in the group must have their own repository.
-   The answer to one question must be one commit, i.e. if there are three questions, your repository must have three commits
-   On the day of presentation you will might be asked to explain what you have done. So, you might as well know what you are doing so that you won't have a problem later.
