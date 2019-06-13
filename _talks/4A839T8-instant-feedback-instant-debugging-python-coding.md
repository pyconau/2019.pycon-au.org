---
layout: talk
permalink: /talks/instant-feedback-instant-debugging-python-coding
recordingconsent: true
talkid: A839T8
title: Instant-feedback, instant-debugging Python coding
track: general
type: talk

speakers:
- biography: "Python coder, open sorcerer, Postgres fanboy, opinion haver, peanut\
    \ butter enthusiast. \n\nRobert yearns for more humanized software. He craves\
    \ radically different user interfaces, that remove the divide between users and\
    \ programmers.\n\nRobert makes software for the public good in Melbourne. \n\n\
    Some say his ideas cannot be truly explained, only experienced. But he'll try\
    \ to explain anyway, with slides."
  name: Robert Lechte

abstract: | 
      Building on Bret Victor's famous 'Inventing on Principle' presentation, we look at writing Python where the code is instantly run and every line visualized after every single keystroke. There's a future beyond the text-editor -> console-run loop and this is a taste of it.
---

Even with good tests, Python code can be a black box: Write a block of code, then test it to see if it spits out the right things. This process involves continuous context shifts: From the syntax, logic and internals of the code in the text editor, to the tests and output in the terminal window, and back again.

The inherent plainness of plain text imposes a high cognitive load, where the flow and structures of the program must be held in our heads, imposing a burden even for those of us who write such code professionally.

The work of Bret Victor and others has shown us that a better world is possible: A development interface where the state of the variables and data structures appears right alongside the code as we type.

It's a truly transformative way to write code. Feedback is instant, not delayed. No context switching is required as all relevant context is presented coherently together. Cognitive burden is lifted as the work of visualization is shifted from the fuzziness of our brains to the clarity of the computer screen.

Instead of tests being an additional piece of work bolted on separately, test cases emerge naturally from the process of writing and debugging.

By the end of this talk you'll:

- see Python code written with instant-feedback
- understand the transformative power of instant feedback and pervasive visualization
- see how we can use Python to construct such coding tools, with insights into Python debugger internals
- understand the practical obstacles to using such interfaces more universally to write "real world" code and how they might be overcome
