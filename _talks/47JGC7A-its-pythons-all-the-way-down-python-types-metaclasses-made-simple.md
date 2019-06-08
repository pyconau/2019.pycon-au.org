---
layout: talk
permalink: /talks/its-pythons-all-the-way-down-python-types-metaclasses-made-simple
recordingconsent: true
talkid: 7JGC7A
title: 'It''s Pythons All The Way Down: Python Types & Metaclasses Made Simple'
track: deepdive
type: talk

speakers:
- biography: My name is Mark Smith, although I'm often known as Judy2k online. I'm
    a Developer Advocate for Nexmo. I love writing stupid Python code in an attempt
    to really understand how Python works. When I'm not doing this, you'll find me
    crocheting, building custom keyboards, or designing models for 3D printing.
  name: Mark Smith

abstract: | 
      Don't be afraid of metaclasses! This talk will explain how, once you've grasped basic types, classes and inheritance, Python's advanced language features such as descriptors and metaclasses are just within your reach.
---

Python has a powerful type system, but this is not immediately obvious. At some point developers stumble across metaclasses, but their behaviour is mysterious and terrifying and so our natural reaction is to back away in fear!

One of the wonderful things about Python is that as you strip away layers of the language, more layers of _python_ are revealed. The aim of this talk is to explain how, once you've grasped basic types, classes and inheritance, Python's advanced language features such as descriptors and metaclasses are just within your reach.

This talk will begin with an explanation of the difference between core Python types and those defined in the language itself (rather than the C runtime). I'll then explain how types (and the `type` function) work, and how we can utilise `__new__` and `__init__` to affect instance construction. I'll cover how attributes (including methods) are looked up in both instances and classes, including inheritance, magic methods, and the descriptor protocol, and then we'll jump into where metaclasses fit into the inheritance hierarchy. It's not okay to describe them as the "type of a type" and leave it at that!

Once I've explained when metaclasses come into play, and what they do, I'll cover what they're used _for_ in existing popular libraries, and how many of the reasons for using metaclasses have been replaced with class decorators and some useful hooks provided in the Python data model.

The audience should enter the talk with a basic understanding of how classes and inheritance works. They should leave with a deep understanding of how the descriptor protocol affects attribute lookup, how metaclasses fit into the inheritance hierarchy, and what metaclasses can be used for. This should lead to a new generation of Python frameworks that are highly dependent on deep Python type magic.
