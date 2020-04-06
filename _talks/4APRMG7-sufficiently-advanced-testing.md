---
layout: talk
permalink: /talks/sufficiently-advanced-testing
recordingconsent: true
talkid: APRMG7
video_url: https://youtu.be/NT7Gg6MEbZk
title: Sufficiently Advanced Testing
track: deepdive
type: talk
endTime: "14:40"

speakers:
- biography: "Zac is a researcher at the Australian National University\u2019s 3A\
    \ Institute, which is building a new applied science to 'manage the machines'\
    \ - AI, cyber-physical systems, and other new technologies. \n\nHe started using\
    \ Python to analyse huge environmental datasets, and contributing to libraries\
    \ like Xarray to make such analysis easier for all scientists. Now, as a maintainer\
    \ of Hypothesis, Pytest, and Trio, Zac is still passionate about making it easy\
    \ to write software you can understand and rely on. When not at a computer he\
    \ can usually be found surrounded by books of all kinds, somewhere out of phone\
    \ range, or both."
  name: Zac Hatfield-Dodds
  avatar: zac-hatfield-dodds.png

abstract: | 
      Writing tests is great, and generating randomized tests even better... but we can push the techniques further still! What is a metamorphic relation good for?  How could (should?) you use a SAT solver for tests?  What about symbolic execution, guided fuzzing, delta debugging?  Come and find out!
---

*You care about writing correct code.  Of course bugs happen, but for this project you want as few as possible.*

*So you write unit test, integration tests, end-to-end tests.  You get enough sleep.  You review each other's code.  You've tried out static typing, linters, autoformatters, property-based testing - and kept everything that helped.  What more could you do?*

Let's do a deep dive into advanced techniques for computer-assisted testing - that is, systems which involve executing your code and checking what it does.  (Type systems, static analysis, and formal verification are all awesome, but out of scope for a testing talk.)

This talk is not a box of magic bullets; many techniques are still in academic papers rather than on PyPI.  Instead, learning about these techniques - what they do, how they're implemented, and most importantly why they work - might change the way you think about software engineering (perhaps even for the better).

Using Hypothesis as a pure-Python case study, we'll cover the shocking power of "dumb fuzzing", some of the many ways to make it smarter, and why they might (or might not) help.  You'll learn how to construct randomized tests that check much more than 'does it crash', and are implausibly likely to find bugs 'randomly'.  I'll unveil the algorithms that Hypothesis uses to find minimal examples - and why it *doesn't* use some others. 

And finally, we'll survey some of the exciting new techniques and applications of property-based testing in the Python ecosystem... including how you can join in!

[*You can read the edited-and-hyperlinked transcript of this talk on Zac's website.*](https://zhd.dev/sufficiently/)
