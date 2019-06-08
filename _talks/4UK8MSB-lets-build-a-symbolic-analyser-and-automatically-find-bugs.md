---
layout: talk
permalink: /talks/lets-build-a-symbolic-analyser-and-automatically-find-bugs
recordingconsent: true
talkid: UK8MSB
title: Let's Build a Symbolic Analyser And Automatically Find Bugs
track: general
type: talk

speakers:
- avatar: jon-manning.jpg
  biography: Jon Manning is the co-founder of [Secret Lab](http://secretlab.com.au),
    an independent game development studio. He's written a whole bunch of books for
    [O'Reilly Media](http://oreilly.com) about iOS development and game development,
    and has a doctorate about jerks on the internet. He's currently working on Button
    Squid, a top-down puzzler, and on the [BAFTA](https://www.youtube.com/watch?v=X3OHIo_5Qx8)-
    and [IGF Seumas McNally Grand Prize](https://www.rockpapershotgun.com/2018/03/22/night-in-the-woods-wins-igf-grand-prize/)-winning
    adventure game [Night in the Woods](http://nightinthewoods.com), which includes
    his interactive dialogue system [Yarn Spinner](http://github.com/thesecretlab/YarnSpinner).
  name: Jon Manning

abstract: | 
      Learn the theory and practice of symbolic analysis, a method of fake-running your code that lets you discover bugs and verify functionality without actually executing code, using Z3 and Python!
---

Traditionally, bugs are usually discovered by running your program, and noting where it behaves incorrectly. However, there are other tools for discovering problems that don't require you to run the code under test. These tools perform _static analysis_, which involves an analysis of the source code itself, and not an observation of its executed behaviour. The tools that you need to build this in Python are very easy to come by!

There are several methods of performing static analysis. One of them, _symbolic execution_, "runs" a piece of your code, and develops symbolic variables that represent the possible values and inputs that the code is working with. This means that the test doesn't necessarily rely on any pre-existing state, or any knowledge of the kind of input that the program will run.

In this talk, we'll discuss how you can build your own symbolic execution system in Python, using the Z3 solver to perform the heavy mathematical lifting. Along the way, you'll learn the benefits and drawbacks of this approach, how you can use it in your own projects, and also some formal logic, too!
