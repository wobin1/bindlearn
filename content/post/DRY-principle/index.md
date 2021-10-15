---
title: "The DRY Principle"
date: 2021-09-21T11:24:58+01:00
categories:
- Programming Basics
- 
tags:
- programming basics
keywords: 
- DRY principle
- What is dry principle
- dry principle for beginners
- programming for beginners
- programming Basics

thumbnailImage: https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=872&q=80
coverImage: https://images.unsplash.com/photo-1498050108023-c5249f4df085?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=872&q=80
metaAlignment: center
---

There is every possibility you won't be the only person who will maintain the code you are writing now or will write in the future. We might change Jobs or retire, sickness and death are what can happen to anyone at any time. These possibilities warrant developers to write code in a way it can easily be understood and managed even in their absence, one way to achieve this is to make sure you don't repeat a piece of information or a piece of code twice in your program.

### What Is DRY Principle
DRY is an acronym representing *Don't Repeat Yourself*, This principle was stated by  Andy Hunt and Dave Thomas in a book they wrote titled **Pragmatic Programmer**. This principle states that *"Every piece of knowledge must have a single, unambiguous, authoritative representation within a system".*

This simply means every code and logic with the possibility of being repeated within the program should be written in a way it can be referenced anywhere in the program.

### Violation Of DRY Principle
The violation of DRY is a concept known as WET(Wasting everyone's time or We Enjoy Typing). WET is the act of writing the same code or logic over and over again making a codebase very bulky and difficult to maintain, and if by any means the logic changes then the changes will have to be made in all the places the code was written, thereby wasting everyone's time and making the program vulnerable to bugs.

### How To Avoid violating The Dry Principle
Violating the DRY principle can be avoided by;
- making sure code is always broken into small reusable units in such a way it can be referenced or called anywhere within a program.
- making sure every method or function written performs only one functionality.

### Conclusion
Writing clean code that can easily be understood by every developer should be one of the goals of every developer whenever he or she is faced with a project. 

Feel free to ask any question or leave a comment in the comment section below I'll be glad to respond.
