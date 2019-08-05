---
layout: talk
permalink: /talks/no-time-to-idle-about-profiling-import-time-in-python
recordingconsent: true
talkid: SEGQBU
video_url: https://youtu.be/dDSIzYVTC2I
title: 'No time to idle about: Profiling import time in Python'
track: general
type: talk

speakers:
- avatar: daniel-porteous.jpg
  biography: "Daniel is a Production Engineer at Facebook. He currently builds tooling\
    \ to support caching infrastructure and works on Facebook's internal IaaS efforts.\
    \ He also writes fun little open source programs, like online versions of board\
    \ games or scripts to find camping sites (anything to facilitate good time with\
    \ friends \U0001F920). He grew up in Townsville but moved to Melbourne for university,\
    \ and now lives in the US. He is passionate about learning new Python features\
    \ and teaching them to as many people as he can. He can't wait to live in an electric\
    \ van with solar panels one day."
  name: Daniel Porteous

abstract: | 
      Python 3.7 added the ability to print import times at startup. But what can we do with that data, and is it enough? In this talk we'll look at how to process import time data, structure it, visualise it, and make concrete choices to improve start up time. Python need not be slow to start!
---

As Python programs grow, import times can grow larger and larger. This is especially problematic for CLIs, every second counts when someone is waiting! As you approach massive scale, CLIs can have many dependencies — some of which might even be linked in from other languages — which can make start up time climb ever higher (even towards the half minute mark!). There are many strategies for making your program start up faster, but where do we look first? This is where profiling comes in.

The first step in tackling a problem is understanding it. Prior to Python 3.7, you had to roll your own solution to printing import times, such as overwriting import behaviour or wrapping imports in timers. But with 3.7 (using the appropriate runtime options) Python can print this information for you!

During this talk we'll briefly discuss how importing works, what a module actually is, and ways your program's import times can spiral out of control. We'll then move on to understanding the import time data given to us by Python 3.7, and look at ways to structure this data (e.g. a tree). Using this foundation we'll start to visualise the data, for example with flame graphs / icicle charts. These graphs will immediately demonstrate the power that visual aids bring to understanding data; you'll be able to see very quickly which imports are the biggest culprits to our startup time. Finally, we'll discuss what you can do with this knowledge.

We'll wrap up the talk with some caveats, such as how module import order can skew the data, and explore how to mitigate these problems. Time allowing, we'll also look at Python probes as a way to gather more information.

After this talk you should be inspired to use these standard import profiling tools to speed up your programs' startup times!
