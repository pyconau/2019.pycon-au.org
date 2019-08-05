---
layout: talk
permalink: /talks/fantastic-blocks-and-where-to-hide-them
recordingconsent: true
talkid: GRZULZ
video_url: https://youtu.be/mBavPw0Kc0w
title: Fantastic Blocks And Where To Hide Them
track: general
type: talk

speakers:
- avatar: christopher-neugebauer.jpg
  biography: 'Christopher Neugebauer is an Australian developer, speaker, and serial
    community conference organiser. He serves as a director of the Python Software
    Foundation, and is co-organiser of the acclaimed North Bay Python conference,
    a boutique one-track conference run in a live music venue in Petaluma, California.


    By day, Christopher works as a Senior Software Engineer at AlphaSights, where
    he uses Kotlin to build communications tools that put clients around the world
    in touch with knowledge they need.'
  name: Christopher Neugebauer

abstract: | 
      Ruby has blocks. JavaScript has blocks. Swift has blocks. Python doesn’t have blocks.In this talk, we'll look at _why_ Python doesn't have blocks, and recent programming techniques that have developed in languages that _do_ have blocks. Then we'll look at what we – or Python – can do about it!
---

Ruby has blocks. JavaScript has blocks. Swift has blocks. Python doesn’t have blocks.

In Python, when you absolutely need an anonymous piece of code to pass to another function, you can either use a lambda (if the code you’re passing is a one-liner), or, perhaps, define a function locally (if it isn’t).

Whenever someone has proposed a means for multiline chunks of anonymous code, the Python Enhancement Process has found a better, more specialised solution: generator expressions allow complex processing of streamed data. Context managers elegantly solve the need for correct setup and teardown routines.

These use cases all had proposed solutions based on blocks, but with thought, we ended up with better syntax that led to more readable code.

Since Python last seriously considered blocks, functional programming – something Python helped pioneer amongst otherwise object-oriented languages – is experiencing a resurgence in other languages’ communities, and blocks are helping developers discover new approaches to error handling, safe handling of ambiguous data, and other techniques that Python doesn’t have obvious analogues for… or does it?

In this talk, we’re going to go back in time to 2005 and look at how Pythonistas thought that blocks would help us, why proposals for blocks didn’t succeed, and see how Python adapted to better serve their use cases. Armed with that knowledge, we’re going to look at a new generation of programming techniques, the problems they solve, and uncover how hard it can be to approach them with modern Python.

Is now the right time for Python to finally grow blocks, or are the solutions hiding in plain sight?
