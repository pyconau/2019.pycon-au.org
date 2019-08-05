---
layout: talk
permalink: /talks/making-acquaintances-with-exotic-encodings
recordingconsent: true
talkid: 3DWEQX
video_url: https://youtu.be/RiP6F3CL47s
title: Making Acquaintances with Exotic Encodings
track: general
type: talk

speakers:
- avatar: trapsilo-bumi.jpg
  biography: Bumi is a Software Developer for HENNGE, based in Tokyo, Japan. He's
    passionate for all kinds of tech, and always excited in challenges whether it
    be building software solutions or sharing it with others through talks. When he's
    not coding, he can be seen travelling, board gaming or playing (and conducting)
    [Angklung](https://en.wikipedia.org/wiki/Angklung).
  name: Trapsilo Bumi

abstract: | 
      Text encoding is a relatively straightforward feature of Python at first glance, but in the wild there are a lot of strange cases we can encounter. Together we will explore some occurences of out-of-ordinary encodings and how to handle them properly in Python.
---

Python 3 makes processing free-text easy as Unicode strings are made the default. Free-text can be anything from emails to website content, from essays to wiki pages and such. In an ideal world, Unicode is used everywhere, and we don't need to care about other encodings made before Unicode.

In this talk, I will show you that that ideal world sadly does not (yet) exist, and how people still use obsolete and exotic encodings, especially from the experience of my company in Japan. Maybe you have read blog posts about Unicode, maybe you have attended a talk explaining Unicode, but this talk will be different. We will *not* assume Unicode is ubiquitous.

First, I'll explain briefly what encoding is and how text is stored internally, including the difference between byte strings and Unicode strings. After that, I will give some examples showing that we cannot assume Unicode is used everywhere, along with some complications related to strange encodings. Finally I'll show you some options on how to recognize and handle non-Unicode text in Python, including those encodings that don't seem to be included in the standard library.

After this talk, the audience will be more prepared to tackle free-text processing in the real world.
