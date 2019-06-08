---
layout: talk
permalink: /talks/extending-micropython-using-c-for-good
recordingconsent: true
talkid: E7QJ8D
title: 'Extending MicroPython: Using C for good!'
track: deepdive
type: talk

speakers:
- biography: "Matt is a software engineer with twenty years professional experience.\
    \ This makes him feel old. \n\nHaving worked on a wide variety of projects from\
    \ tiny embedded applications to large web-based system means that he has tinkered\
    \ with most aspects of the software stack - and has enjoyed it all! Apart from\
    \ his technical pursuits he also loves rock climbing and, generally, being in\
    \ the outdoors.\n\nMatt helps run the [Melbourne MicroPython Meetup](http://melbournemicropythonmeetup.github.io/);\
    \ come along the next time you're in Melbourne!"
  name: Matt Trentini

abstract: | 
      MicroPython is a _fantastic_ environment for embedded development. But it _is_ an interpreted language; what happens when you hit performance limitations? Or want to use a new feature of your microcontroller? We'll look at how MicroPython can be _extended_ to add features and improve performance.
---

Embedded development using MicroPython is very productive and efficient. But understanding how the system works and how it can be _extended_ can open up many possibilities. You can reduce RAM usage, integrate 3rd party libraries, unlock features of your microcontroller and improve performance - sometimes _dramatically_!

Some techniques can be applied without looking _too_ deeply at the inner workings of MicroPython. We'll cover how to use _pre-compilation_ and _frozen modules_ which can reduce memory use. We'll touch on controlling the MicroPython code emitter using the mysterious @native and @viper decorators to improve performance. 
 
However, at some point you've got to roll up your sleeves and delve into C, the language that MicroPython is implemented in. For this talk, a working knowledge of C will be _very_ helpful as we will explore the MicroPython codebase to show how it's structured. The concept of a 'port' will be explained, and we'll look at how the various ports differ. It will become clear how MicroPython can be built to target various hardware.

Then we'll walk through the construction of a MicroPython module, written in C. 

Although developing in C can be challenging, there are benefits including improved performance and lower resource usage. It also allows the integration of existing C libraries. In particular, we'll explore how to create a module in C and learn how to cross the language boundaries so that, from MicroPython, your C module will feel _just like it was written in Python_.

The talk will focus on development on microcontrollers but MicroPython can also be used on desktop operating systems. We'll touch on how these techniques can be applied on these platforms. 

Knowing how the system works - and perhaps writing a _little bit_ of C - can help supercharge your MicroPython! The goal of this deep dive is to show you _how_.
