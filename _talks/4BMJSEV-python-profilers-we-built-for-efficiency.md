---
layout: talk
permalink: /talks/python-profilers-we-built-for-efficiency
recordingconsent: true
talkid: BMJSEV
title: Python Profilers we Built for Efficiency
track: deepdive
type: talk
endTime: "11:40"

speakers:
- biography: Jimmy Lai is a Software Engineer in Instagram Infrastructure. He developed
    in Python and shared his experiences in PyCon TW and APAC since 2012. His recent
    interests include Python efficiency profiling, optimization and asyncio. He also
    contributed a few asyncio bug fix and optimation to CPython. This year, he plans
    to share his efficiency experiences learned from large scale Python web application
    - Instagram.
  name: Jimmy Lai

abstract: | 
      As application becomes large scale, performance becomes a critical issue. We didn't find useful open source library fit our needs and ended up built our own profilers for efficiency opportunities including CPU, latency and cache. We'll share how we build them to optimize our Django web application.
---

We built one of the largest Python web application in the world and we care a lot about its efficiency. We started with cProfile to profile function call CPU cost and found it couldn't differentiate call-stacks sharing the same function calls. Asyncio makes the issue worse since gathered functions all have the event loop as caller. We decided to build our own function call profilers and it ended up as a long journey:

* CPU cost profiler: CPU instructions per function call with complete call stack.
* Latency profiler with asyncio support: collect timestamp/latency per function call and yield from await.
* Profiler identifies lru_cache opportunities: functions have high cost and high hit rate of parameters/returns.

We would like to share how we designed and implemented those profilers. After this talk, you'll have learned how to:

* Build profilers by registering a callback function for function calls.
* Handle call stacks correctly in asyncio world.
* Use different timers to collect different metrics and traversing through call-stack.
* Implement CPU profiler, latency profiler, and lru_cache opportunities profilers.
* Case studies on optimizing Python application from CPU, latency and cache aspects.
