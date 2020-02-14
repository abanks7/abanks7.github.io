---
layout: essay
type: essay
title: No Empty Spaces
# All dates must be YYYY-MM-DD format!
date: 2020-02-13
labels:
  - Software Engineering
  - Javascript
---

## Standards. We need them.
Standards and consistency remind me of the military, where everything is uniform and everyone receives the same equipment. Why? Because when each cog in the machine is being held to a certain set of standards, the machine runs smoothly. At least that's how they would like it to be, but we all know in reality that isn't always the case. The point though is that by having established standards there is a baseline to work from in order to keep consistency and uniformity amongst the greater whole. Coding is no different. We've all seen poorly written code, in fact as learners we tend to produce **a lot** of it, but we have also seen *great* code - neat, readable, consistent - and it well, looks **good**.

![xkcd #1513](https://imgs.xkcd.com/comics/code_quality.png)

## JS means Jumbled Spaghetti
We mostly fly solo, trying to learn as much as we can and implement new techniques as we go and so it is easy to sometimes think that as long as it looks good to *us* we are good to go. It becomes evident very quickly when you start to think about how a large corporation or even just a large project is built, on why standards are needed. 10 developers? 100? Maybe even in the thousands. Every one chipping away at a piece of the puzzle, continuously merging their code into the bigger picture. If everyone did their own thing can you imagine how much a mess the codebase could be? To have to review the code (or worse, debug it) would be a nightmare. This is why large companies have either created their own or adopted popular coding styles, such as the AirBnB one we currently use for JS.

![xkcd #1695](https://imgs.xkcd.com/comics/code_quality_2.png)

## Why do we listen to these guys?
I like the AirBnB style guide. Not only does it produce good looking code, but the documentation is outstanding. Everything is laid out not just with good and bad examples, but with reasons **why**. It's clear that they have spent quite a bit of time and effort developing this, and by enforcing it internally it helps keep their codebase clear, readable, understandable, and developer friendly while minimizing ambiguity. It is easy to think that what *you* think looks best should be the style to follow, but this doesn't always mesh well with everyone else. But picking a style or standard and sticking to it? That creates known expectations, and that means consistency.

![xkcd #1833](https://imgs.xkcd.com/comics/code_quality_3.png)

## I hate it. I love it.
Using ESLint with the AirBnB style guide has be great I feel. Seeing a red squiggle doesnt worry me, it creates a tiny teaching moment each time, and I get to learn from it and practice not making the same mistake twice. Not only that, but it re-enforces better habits *with* reasons why. I thought using ++ was great, but now after being yelled at many times I firmly believe += 1 is the way to go. Easier to read, and even easier to modify if needed. I think that by learning some of these good habits now, I can continue to make my own code more readable and consistent with what developers in the real word are actually doing, and that will only help me be a better collaborater in the future.