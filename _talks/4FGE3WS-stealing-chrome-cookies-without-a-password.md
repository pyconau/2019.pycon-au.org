---
layout: talk
permalink: /talks/stealing-chrome-cookies-without-a-password
recordingconsent: true
talkid: FGE3WS
title: Stealing Chrome cookies without a password
track: security
type: talk

speakers:
- avatar: alex.jpg
  biography: "\"Alex\" (@mangopdf) does Red Teaming, recently completed Operation\
    \ ACTUAL CRIMES, and can't wait until they're inevitably struck down by their\
    \ own hubris. \n\nThey're known for hacking a friend (with consent!) in Operation\
    \ Luigi, being an organiser for [purplecon.nz](https://purplecon.nz) (a defensive,\
    \ inclusive, pastel-purple security conference) and for writing dumb blog posts\
    \ on [mango.pdf.zone](https://mango.pdf.zone). They're also known for exposing\
    \ a privacy flaw in Tinder, and showing it was possible to make graphs of when\
    \ your Facebook friends are awake.\n\nAt PyCon AU, they'll be wearing their Sunday\
    \ best _emotionally_, and hence or otherwise tryign their bset."
  name: '"Alex"'

abstract: | 
      A new technique to steal someone's Chrome cookies once you've compromised their machine. Cooler because it doesn't need root 😎. This talk is about how the technique was found, how it works, and what you can do with it.
---

buckle up kiddo we're gonna commit digital sin
If you steal someone’s Chrome cookies, you can log in to their accounts on every website they’re logged in to.

Normally you need the user’s password to do it, but I found a way to do it without the password. You just need to be able to execute code on their computer. It works by using Chrome’s Remote Debugging Protocol. To my knowledge this is the only way to extract a user's Chrome cookies without their password, and by far the easiest way.

It involves plugging together several extremely forbidden and undocumented Chrome features, as well as figuring out how to speak the websocket protocol stealthily on a victim's machine.

This talk is about how the technique was found, how it works, and what you can do with it.
