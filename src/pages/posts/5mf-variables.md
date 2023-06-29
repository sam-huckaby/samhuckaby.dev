---
layout: ../../layouts/postLayout.astro
title: '5-Minute Fundamentals: Variables'
pubDate: 2023-06-28
description: 'A recap of a 5-Minute Fundamental overview of variables.'
author: 'Sam Huckaby'
youtube: 'https://youtu.be/lU1GhpG4uMw'
image:
    url: '/logo_pile.png' 
    alt: 'The Crash Course Pile.'
tags: ["computer science", "variables", "learning in public"]
---

# Understanding Variables in Programming: A Comprehensive Guide

Welcome to another educational installment from Five Minute Fundamentals. This time, we delve into the world of variables in programming. We will explore what variables are, why we use them, and how different programming languages handle them.

## Variables: Labelled Boxes for Data

![](https://cdn.videotap.com/RSZeY5n12bPorHY8M7aM-46.08.png)As an analogy, consider variables as labeled boxes placed on a table. The labels, assigned by you, allow you to decide and identify what's contained in each box. Imagine that you're preparing for a camping trip. You might have one box labeled 'food' containing edible provisions like protein bars, instant pasta, or water bottles. Another box might be labeled 'Protection', stocking items such as a tent, mosquito repellent, and even a rocket launcher for those potential bear encounters! Precisely like these labeled boxes, variables hold information necessary for the smooth execution of a program.

## The Genesis of Variables

![](https://cdn.videotap.com/lTs3cesKSIFMEBDUTv2T-77.3.png)When computer programming made its pioneering expedition into the mainstream, no concept of variables, as we comprehend them today, existed. To save data acquired from a process, you would need to place it directly into a register in the computer's memory and subsequently remember that memory address.

> "This is comparable to remembering your mom's phone number as a kid so you could call when not picked up from school."

However, memorizing such addresses, frequently appearing as complex hexadecimals, swiftly became a challenge when dealing with an abundance of them in your code.

That's when the concept of named variables entered the scene. This was introduced to high-level programming languages to enable programmers to affix a textual label or name to the memory address they were utilizing. Instead of trying to remember the hexadecimal address, you could simply refer to something more intuitive like 'MomsNumber'.

![](https://cdn.videotap.com/065BqhNZ76rXaAGJB4oY-160.55.png)## Importance of Variables in Computer Programming

In programming, variable storage is paramount as it helps perform fewer calculations by saving values for multiple uses, ultimately leading to more efficient code.

Another crucial aspect of variables is typing. The types of programming variables relate to the kind of values they store. However, it's important to mention that not all programming languages handle types in the same way.

## Static Typing vs Dynamic Typing

![](https://cdn.videotap.com/tKsAKORQBbKjDH6x3uLL-237.53.png)Programmers consider a language's variable typing as either static or dynamic. In a statically typed language, the types of variables are checked during compile time, which occurs before the code is run. This offers the advantage of not accidentally releasing code with faulty types.

On the contrary, a dynamic typing system decides the type of variable at runtime. While this can simplify calculations, it may also lead to confusing errors.

## Strongly Typed vs Weakly Typed Languages

Dynamic and static typing are often associated with another classification of programming languages, namely strongly typed and weakly typed. Most often, the term 'strongly typed' is associated with statically typed languages, because there is no real agreed upon definition otherwise.

For our purposes, the strength of a language's type system defines the number and variety of guarantees it provides about the type of variable. For instance, in JavaScript, you can add any type of data, yielding any result—almost no promises are made about variable types. In OCaml, you cannot even add two numerical values if one of them is a decimal.

![](https://cdn.videotap.com/aLi9SrJjAReCyniAamZZ-318.86.png)One more feature integral to a typing system is whether a language requires explicit typing. Some languages demand the declaration of a data type for a variable before assignment, while others are lenient and allow the declaration and assignment to occur simultaneously.

In essence, a language's type system is considered stronger based on the number of guarantees it provides about its variables. Check out the unbiased chart presented above for a comparison of common programming languages.

Variables and their types, as foundational elements in programming, are crucial when learning a new language. A subsequent video will discuss what types are available and their workings in more depth.

So, this brings us to the end of our overview of variables.

Do stay tuned for the next installment from Five Minute Fundamentals. Until then, keep coding!
