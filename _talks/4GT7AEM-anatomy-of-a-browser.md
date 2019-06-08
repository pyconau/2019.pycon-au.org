---
layout: talk
permalink: /talks/anatomy-of-a-browser
recordingconsent: true
talkid: GT7AEM
title: Anatomy of a Browser
track: general
type: talk

speakers:
- biography: Erin is a Google Developer Expert and a Mozilla Tech Speaker, with over
    ten years experience in a variety of languages, from JavaScript to Model204 (no,
    nobody else has heard of it either). She is currently a senior web developer at
    Shine Solutions. She is an active member of the Melbourne developer community,
    and has spoken at conferences around the world. If you see her at a conference,
    she'll probably have knitting needles in hand.
  name: Erin Zimmer

abstract: | 
      Web browsers are a bit like digestive systems - we all have one, but we're not really sure how it works, and sometimes it makes funny smells. So let's have a look at what's going on under the hood when your browser turns a bunch of characters into a delightful picture of a cat.
---

This will be a deep-dive into the internals of a browser's HTML engine. We'll take a look at what an HTML engine actually is, and the different engines that exist out in the wild. Then, using the HTML and CSS specs as a guide, we'll see how the engine takes character streams of HTML and CSS and turns them into the DOM and CSSOM. From there, we'll see how the browser's rendering engine uses that information to create the images we see on screen.

At the end of this talk, we'll understand where rules like "put your script tags at the end of the body" come from and we’ll gain some insights into the historical circumstances that led to modern browsers being the way they are, and a better understanding of some of their quirks.
