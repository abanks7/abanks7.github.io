---
layout: essay
type: essay
title: I R Smrt
# All dates must be YYYY-MM-DD format!
date: 2020-01-30
labels:
  - Software Engineering
  - StackOverflow
---

## Please edit your post.

Smart questions get smart answers, and dumb questions get... dumb answers. The internet is not in its infancy, it is home to *billions* of webpages and users with a total amount of data so large the number isn't even comprehendible. Throughout the giant tangled web (pun intended) of the internet there exits almost anything you can think of, and with that comes a wealth of knowledge. The internet is home to so much valuable information and a plethora of resources that allow one to expand their depth on any subject they choose too. When it comes to programming, the holy grail of information is StackOverflow. With over 19 *million* questions, and an even larger amount of answers, what you are looking for is probably there. 

Navigating the deep waters of StackOverflow isn't necessarily easy, and sometimes searching for the correct answer you need can be a skill in its own. Expert level StackOverflow searching is actually the real reason software developers get paid so much. Ok, its not, but it emphasizes just how valuable of a resource it is. For every good, well thought out, informative question there is at least a handful of terrible ones. Being able to ask smart questions that enable smart answers allows a novice programmer (or any level) to gain a better understanding of the solution they are looking for, and in turn expand their knowledge and skills rather than just be spoon fed an answer.

To demonstrate how a smart question can foster smart answers that not only solve a problem, but serve to enhance the understanding of those involved in the discussion and anyone in the future who might come across it, I searched StackOverlow for a question on a topic I know nothing about.

>#### [Does the C++ standard allow for an uninitialized bool to crash a program?](https://stackoverflow.com/questions/54120862/does-the-c-standard-allow-for-an-uninitialized-bool-to-crash-a-program)
>
>I know that an *"undefined behaviour"* in C++ can pretty much allow the compiler to do anything it wants. However, I had a crash that surprised me, as I assumed that the code was safe enough.
>
>In this case, the real problem happened only on a specific platform using a specific compiler, and only if optimization was enabled.
>
>I tried several things in order to reproduce the problem and simplify it to the maximum. Here's an extract of a function called `Serialize`, that would take a bool parameter, and copy the string `true` or `false` to an existing destination buffer.
>
>Would this function be in a code review, there would be no way to tell that it, in fact, could crash if the bool parameter was an uninitialized value?

I'm not familiar with C++, but the author that posed the question has given information in a clear and concise way which allows me to begin to understand what is going on. They mention specific platform and specific compiler using certain arguments, they emphasize what they have done to reproduce the problem, and have not only given code snippets that are well commented but also included a link to an online compiler that reproduces the problem at hand. They have shown their understanding of the language and their pursuit of finding the answer on their own before asking for help from others. At the end of their post, they sum up the main question into a single sentence that gives others a starting point to provide solutions.

The answers are thorough, and it's clear that this topic has sparked a solid conversation full of useful information with every answer having multiple comments contributing to the discussion. While this is a solid example of a well thought out question sparking intelligent conversion in the comments, there are many examples of bad questions with negative votes and sometimes harsh comments.

#### [Arrays algorithms](https://stackoverflow.com/questions/59996519/arrays-algorithms)
<blockquote>
<br><br>
<p>I've tried solving algorithm problem for several hours without any success, so i ended up here.
<br><br>
We are given two initiger arrays t1[N] and t2[N]. We are connecting  elements from t1 and t2 in pairs (one element from each array) so that,  sum of elements chosen from t1 was equal to sum of elements from t2.  Please write a function that given t1,t2 will return maximal number of  pairs or 0 if such a pair doesn't exist.
<br><br>
I simply can't find any better way than brute-force check of all posible sub-arrays. Thanks for help!</p>
<footer>—jason</footer>
</blockquote>

It's almost too easy to see the mistakes made here. The author of this question has stated right in the beginning that they have "given up" along with a poorly worded and confusing attempt at explaining the problem they are having. They have not given any indication they have looked at other resources, and have not provided any code snippets showing their attempt at the problem. At the end they do mention that they have tried one approach, but offer no insight as to any other possible solutions to the problem. Other users of StackOverflow are quick to point this out in the comments:

> You should attempt to write some code and if you are having troubles, post that code with your questions. *Please write a function...* won't get you much here.

> Please edit your post with your attempt at resolving the requirements.

> What's wrong with the brute-force technique?

There is not much to be learned from reading the questions and answers, other than the insight that this must not be the way to get help on StackOverflow. Had the user spent just a small amount of their time searching for answers, figuring out a direction, and showing at least some attempt at a solution, it is likely that the community would have been more receptive in helping this budding programmer out. The internet is full of smart and willing to help programmers that **want** to help other grow their skillsets, but one must put in effort to get it in return. "You get out what you put in."
