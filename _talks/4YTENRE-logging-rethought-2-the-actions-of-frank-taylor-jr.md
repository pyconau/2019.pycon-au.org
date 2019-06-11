---
layout: talk
permalink: /talks/logging-rethought-2-the-actions-of-frank-taylor-jr
recordingconsent: true
talkid: YTENRE
title: 'Logging Rethought 2: The Actions of Frank Taylor Jr.'
track: general
type: talk

speakers:
- avatar: markus-holtermann.jpg
  biography: Markus Holtermann works as a back-end and infrastructure engineer at
    Crate.io. He has been a Django core contributor since early 2015. He is a member
    of the Django security and operations team as well as an organizer of DjangoCon
    conferences. Markus has been a project lead at the German ubuntuusers.de community
    support platform where he discovered Python and Django in 2010.
  name: Markus Holtermann

abstract: | 
      We build services, potentially used by thousands or even millions of people. And despite all the testing we do, some interactions with these services will not work out the way we hope. Wouldn’t it be great to reconstruct what let to a problem and analyze if the problem occurred at other times?
---

In this talk I want to look at structured logging. What are the benefits of it over plain text logging. How can it be used effectively?

Logging, by itself, can help to trace bugs. Structured logging adds additional, post-logging capabilities when used correctly. Because log events are structured data, they can be analyzed much more efficiently and effectively than plain text log messages. Furthermore, one can even build graphs and diagrams to nicely visualize what’s happening in a service.
