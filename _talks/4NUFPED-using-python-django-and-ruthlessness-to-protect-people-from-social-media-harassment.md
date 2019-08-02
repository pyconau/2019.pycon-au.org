---
layout: talk
permalink: /talks/using-python-django-and-ruthlessness-to-protect-people-from-social-media-harassment
recordingconsent: true
talkid: NUFPED
title: Using Python, Django, and ruthlessness to protect people from social media
  harassment.
track: django
nicetrack: "DjangoCon AU"
type: talk

speakers:
- avatar: tom-eastman.jpg
  biography: 'Tom Eastman is a developer, systems engineer and occasional security
    consultant living in Wellington, New Zealand. Tom (still) writes words that control
    computers to tell other computers to build FAKE computers that run on DIFFERENT
    computers. [Website](https://tom.eastman.nz) [Twitter](https://twitter.com/tveastman)'
  name: Tom Eastman

abstract: | 
      In this talk, I present 'secateur', a tool for Twitter users to protect themselves from some forms of online harassment. I discuss using Python and Django to create tools that integrate with Twitter, use its APIs, and block lots of people (LOTS of people).
---

In some ways, Twitter seems like it was designed from the ground up to be the perfect tool for harassment. The social media phenomenon of 'dog-piling' can make life hell online. Twitter's own mechanisms that are supposed to protect users sometimes seem to be pretty inadequate to the task.

So I decided to make a few of my own.

I've built an open-source web app, 'secateur', that gives people a bit of power to protect themselves in a hostile online environment.

Along the way, I got to grapple with some interesting challenges:

- The technical aspects of scraping Twitter and using their APIs for blocking and muting lots of people (LOTS of people). Dealing with an occasionally surprising API with strict (and surprising) rate-limiting behaviours.

- How to build something beyond a Python script -- aiming to be a tool that other people can use to protect themselves, and that would be affordable to host.

- The threat landscape you need to consider when building a tool that's for people who are being attacked online.

- What's 'fair', and what's 'censorship', when it comes right down to it?
