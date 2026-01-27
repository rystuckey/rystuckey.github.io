---
layout: essay
type: essay
title: "A New Type of Experience"
# All dates must be YYYY-MM-DD format!
date: 2026-01-26
published: true
labels:
---


*TypeScript - JavaScript with types (right?)*

I thought TypeScript would just be JavaScript with types added in, but I was completely wrong.  I thought all it would be is the same programming language just with different syntax.  I however learned how it differs from JavaScript in the way that it requires explicit declarations about what the data in the program is and how it is allowed to behave, all decided before runtime.  

JavaScript takes a variable declaration and sees the type of data it is given, and adapts to whatever the type is.  However this can lead to complications during runtime, where variables are treated as types they arent supposed to be.  


## TypeScript in Practice

My first experience with TypeScript was in ICS 314's WOD (Workout of the Day) assignments, which I found rather easy to complete.  There were some that were easy, but some that were harder which will require more practice to get used to.  This issue is however not a coding issue, because my experience actually programming with TypeScript was rather straightforward. 

A majority of the syntax in TypeScript is very Similar to JavaScript.  The main things I needed to learn was the style of type declarations, function syntax and return type declarations, and how to use various other functions. 

To learn the syntax, I've used AI tools such as ChatGPT during WODs to learn the specific syntax of TypeScript, so I don't have to spend hours memorizing specific functions or scrolling through documentation to find the exact syntax.  This likely saved me hours of time which optimized my workflow.


## TypeScript, Not JavaScript

In JavaScript, a variable can be updated to hold a new data type during runtime, but with explicit declarations in TypeScript, the compiler prevents you from writing code that would change the data type.

I found this out during the Wet Bulb WOD, when I tried take the estimated tw value and round it.  I tried tw = tw.toFixed(2); - but this lead to an error, even though this would work in JavaScript.

The reason why this happens is because toFixed() returns a string rather than a number, meaning I was trying to assign a string to a number variable, which obviously is a problem in TypeScript.  To fix this, I had to use parseFloat() with that as well to make sure that I was actually assigning a number to a number.

This is a clear example on how TypeScript works, catching type mistakes before the program runs.  Here it stopped me from changing the type of a variable, specifically in this instance where I tried to turn a string into a number.

## Looking Forward

I am very confident in my programming skills, which can translate well into using TypeScript, it just will take more exposure to ensure that my usage of it all is correct.  ChatGPT has helped me with learning how to use TypeScript specifically and is also automating tasks for me to improve my workflow.

I am sure that 314 is nowhere near an easy class, but fortunately learning TypeScript and the usage of it is fairly easy and fun, and this athletic software engineering approach is interesting.  It is going to be a new experience writing technical essays in this style, but I am hopeful that the skills I will gain from this class are going to be useful to me in my career.
