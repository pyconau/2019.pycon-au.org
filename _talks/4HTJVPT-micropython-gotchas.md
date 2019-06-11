---
layout: talk
permalink: /talks/micropython-gotchas
recordingconsent: true
talkid: HTJVPT
title: Micropython Gotchas
track: general
type: talk

speakers:
- biography: "Micha\u0142 is a software engineer who made friends with Python over\
    \ 10 years ago. He\u2019s also keen on embedded systems. He tries to combine those\
    \ two by spending time on MicroPython powered chips as well as SBCs like RaspberryPi.\
    \ Apart from that, he\u2019s a Linux and open source enthusiast and a very unprofessional\
    \ bass player. Likes talking to people."
  name: "Micha\u0142 Ga\u0142ka"

abstract: | 
      We all somehow get the feeling that MicroPython is not quite the Python we know. During the talk, I’ll show what the “not quite” actually means. I'll present a set of different issues I stumbled upon when working with different MicroPython powered boards ranging from memory constraints to API calls.
---

MicroPython gets more and more attention in the IoT world. There are new hardware platforms appearing for which MicroPython becomes a valid choice. Some time ago I came into possession of a thermal printer. After connecting it to the RaspberryPi I decided to give MicroPython a spin and that's how my journey has begun.

There are different issues that a Python programmer may face when switching to MicroPython such as:
- Memory constraints
- False friends - APIs that resemble ones from the "big" Python, but work slightly differently
- Differences between the MicroPython powered boards and their APIs

I'll present a couple of development boards that run MicroPython code and highlight the main differences between them.
Next, I'll show the examples of a real life code that may lead to unexpected behaviour and propose solutions to it.

The talk covers such topics as bytecode crosscompilation, communication with peripheral devices, time measurement and time operations.
