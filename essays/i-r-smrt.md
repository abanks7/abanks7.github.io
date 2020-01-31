---
layout: essay
type: essay
title: I R Smrt
# All dates must be YYYY-MM-DD format!
date: 2020-01-30
labels:
  - Software Engineering
  - Personal Growth
---

## I believe we can reach the morning light.

Smart questions get smart answers, and dumb questions get... dumb answers. The internet is not in its infancay, it is home to *billions* of webpages and users with a total amount of data so large the number isnt even comprehendable. Throught the giant tangled web (pun intended) of the internet there exits almost anything you can think of, and with that comes a wealth of knowledge. The internet is home to so much valuable information and a plethora of resources that allow one to expand their depth on any subject they choose too. When it comes to programming, the holy grail of information is StackOverflow. With over 19 *million* questions, and an even larger amount of answers, what you are looking for is probably there. 

Navigating the deep waters of StackOverflow isnt necessarily easy, and sometimes searching for the correct answer you need can be a skill in its own. Expert level StackOverflow searching is actually the real reason software developers get paid so much. Ok, its not, but it emphasizes just how valuable of a resource it is. For every good, well thought out, informative question there is at least a handful of terrible ones. Being able to ask smart questions that enable smart answers allows a novice programmer (or any level) to gain a better understanding of the solution they are looking for, and in turn expand their knowledge and skills rather than just be spoon fed an answer.

To demonstrate how a smart question can foster smart answers that not only solve a problem, but serve to enhance the understanding of those involved in the discussion and anyone in the future who might come across it, I searched StackOverlow for a question on a topic I know nothing about.

### [Does the C++ standard allow for an uninitialized bool to crash a program?](https://stackoverflow.com/questions/54120862/does-the-c-standard-allow-for-an-uninitialized-bool-to-crash-a-program)

>I know that an "undefined behaviour" in C++ can pretty much allow the compiler to do anything it wants. However, I had a crash that surprised me, as I assumed that the code was safe enough.

In this case, the real problem happened only on a specific platform using a specific compiler, and only if optimization was enabled.

I tried several things in order to reproduce the problem and simplify it to the maximum. Here's an extract of a function called Serialize, that would take a bool parameter, and copy the string true or false to an existing destination buffer.

Would this function be in a code review, there would be no way to tell that it, in fact, could crash if the bool parameter was an uninitialized value?
