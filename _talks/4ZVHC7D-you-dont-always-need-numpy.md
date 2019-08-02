---
layout: talk
permalink: /talks/you-dont-always-need-numpy
recordingconsent: true
talkid: ZVHC7D
title: You don't always need NumPy
track: science
nicetrack: "Science and Data"
type: talk

speakers:
- biography: 'I''m a software developer at QUT''s Digital Observatory. I work with
    Python at the intersection of the web, data and analytics. I started a PhD: I
    might even finish it one day.'
  name: Sam Hames

abstract: | 
      The numerical Python ecosystem and communities are mature and powerful, but sometimes we can be too quick to reach for the numerical hammer when simpler options exist. This talk will outline some areas where the numerical stack may not be the best starting point, and survey some alternatives.
---

The numerical Python ecosystem, centered around NumPy as a base library, is a powerful and mature ecosystem that is driven by a strong community. Sometimes this power comes at a cost though, and without meaning to we can make our day to day problems more complex by reaching for the wrong tool. This can happen when we reach for a familiar tool from our domain, and we just haven't come across other options before. 

This talk will start by situating numerical Python in the broader Python ecosystem including a discussion of cases where you definitely want to be 'numerical' from the beginning. We'll also take a look at some examples of friction points that can make numerical Python more costly than beneficial. Finally, we will survey some other parts of the Python ecosystem that might replace or complement your use of NumPy. In particular we will go through some hidden (and not so hidden!) gems in the standard library and some great little task specific libraries from outside the standard library.

Ultimately, the aim of this presentation is not to talk you out of NumPy, but to help you assess what tools you need for your project by raising awareness of other useful parts of the Python ecosystem.
