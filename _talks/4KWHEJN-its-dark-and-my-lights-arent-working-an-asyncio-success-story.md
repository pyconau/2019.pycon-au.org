---
layout: talk
permalink: /talks/its-dark-and-my-lights-arent-working-an-asyncio-success-story
recordingconsent: true
talkid: KWHEJN
title: It's dark and my lights aren't working (an asyncio success story)
track: general
type: talk

speakers:
- avatar: jim-mussared.jpg
  biography: Jim works full time on MicroPython related projects and loves all things
    embedded and electronics. He has previously worked in education, teaching Python
    & MicroPython to school students (at Grok Learning) and before that in Site Reliability
    Engineering (at Google). He particularly loves teaching, and has been a lecturer
    and tutor at the National Computer Science School, teaching electronics and robotics
    to high school students for the past 7 years.
  name: Jim Mussared

abstract: |
      I have invested huge amounts of time in achieving a simple goal -- making the lighting in my home "smart". It's not ground breaking, nor is it practical or cost effective, but it sure was educational, uses a bunch of Python, and the result makes me (and my family) happy.
---

Scenario: You have a houseful of "smart" light bulbs, based on ZigBee. The vendor software and hardware is pretty much completely broken. You have one seemingly simple goal in mind: if you turn the lights on in the middle of the night, they should be dim. It'd be nice to have a single button by the front door that turns off the entire house. Oh, and find a way to make up for the terrible placement of light switches in this house. _And most of all, not require unlocking my phone and using some app to control the lights!! Seriously who wants to use their phone to turn on their lights?_

Join me on my adventure, starting with lights that don't work, a soldering iron, a Wikipedia page about ZigBee, and an unhealthy misunderstanding of the sunk cost fallacy. **And Python!**

Over time, I acquired software defined radios, ZigBee transceivers, extremely worrying firmware updates, a mitre saw, hundreds of RGB leds, a baby, more 8051 assembly than anticipated, some familiarity with asyncio, more ZigBee devices, and finally... success.

This was my first time using asyncio, and it really worked well for this project. I hope you can walk away from this talk with an appreciation of how asyncio is life-changing and how home automation can actually be a great thing. And you might even see a light bulb running async Python code.
