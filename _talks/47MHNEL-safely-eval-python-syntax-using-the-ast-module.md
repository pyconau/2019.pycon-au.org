---
layout: talk
permalink: /talks/safely-eval-python-syntax-using-the-ast-module
recordingconsent: true
talkid: 7MHNEL
video_url: https://youtu.be/7e-2nUqnNqE
title: Safely eval Python syntax using the AST module
track: security
nicetrack: "Security and Privacy"
type: talk

speakers:
- avatar: tim-savage.jpg
  biography: 'I am currently the development lead for Westpac Databank.


    Got interested in Python around 2003-2004 by reading and absorbing the Python
    Cookbook, over the next 15 years Python has become my main language. Along the
    way, I have written Python applications for the likes of Fairfax Media, Woolworths,
    Westpac as well as several small startups. I contribute to many Python (and non-python)
    opensource projects including publishing several of my own modules, notably, Odin
    and PyApp.


    Outside of programming, am a multi-instrumentalist, play drums in multiple bands
    in and around Sydney, have an interest in electronics. Have my hands kept full
    with twin daughters!'
  name: Tim Savage

abstract: | 
      Allow your users to supply queries or define rules using Python syntax and safely eval them. Processing an AST into safely executable code.
---

Allowing users of your application the ability to provide rules or queries using Python syntax allows, gives control back to end users or allows for new solutions to be implemented without a new release. However, directly executing arbitrary Python syntax is a *major* security risk.

This talk dives into how to do this safely, along with the pitfalls/risks that must be avoided to ensure your application security.

Main points:
* Processing and parsing Python syntax using the `ast` module
* Interpreting the generated syntax tree
* Generating executable code that can be safely executed with `eval`
* Why this is necessary or why eval/compile are not safe
