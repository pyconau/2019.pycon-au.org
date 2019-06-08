---
layout: talk
permalink: /talks/what-not-to-do-and-how-to-do-it
recordingconsent: true
talkid: ZQMLTH
title: What not to do, and how to do it
track: general
type: talk

speakers:
- biography: Jakub is a software engineer in the Confidential Computing team of Data61.
    He likes privacy-preserving technology, maths, and teaching computer science.
    His favourite data structure is disjoint sets, and his favourite desert is lemon
    meringue pie.
  name: Jakub Nabaglo

abstract: | 
      Python has powerful tools that let our programs inspect and modify themselves. These can be used for good or evil. We study a few of these tools, and some examples of how not to use them.
---

Python's advanced features let us do some truly terrible things. These tools permit us to modify code and state at runtime. Used well, they make many fantastic things possible. Used poorly, they can confuse anyone maintaining your code.

The most basic such tools are the locals and globals builtins, which let us view and modify local and global variables. We will see (1) how these work, (2) the circumstances in which they don't work, and (3) relate them to the __dict__ an object.

Stack inspection is a powerful feature that lets us track where we are in the execution of our program, and inspect the state of our current function and its callers. It can certainly be used for good: for example in the tracebacks that help you debug an exception. But can also be used for evil, as we will see in a war story.

At the most extreme, Python gives us the ability to modify bytecode. We will use the `goto-statement` decorator as a case study: it uses Python's parser to build an Abstract Syntax Tree, and then hijacks the function's bytecode to give it support for goto statements.

You should not use any of these tools, of course. But if you do, here's how to.
