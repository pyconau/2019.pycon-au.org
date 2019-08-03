---
layout: talk
permalink: /talks/best-practices-for-cryptography-in-python
recordingconsent: true
talkid: AHCQT7
title: Best Practices for Cryptography In Python
track: security
nicetrack: "Security and Privacy"
type: talk

speakers:
- biography: Paul audits codebases that have significant cryptographic implementations
    to find both code-level vulnerabilities and architectural issues. He draws upon
    those engagements to write educational blog posts, tools and libraries for cryptographers.
    A founding member of the Python Cryptographic Authority, Paul has played a large
    part in the development of three major cryptographic libraries in Python since
    2013. When he's not banging his head against a keyboard he enjoys baking and kiteboarding.
  name: Paul Kehrer

abstract: | 
      Part of what makes Python great also brings challenges for cryptographic operations that need rigorous control of memory and CPU instructions. In this talk we'll discuss situations where Python is a poor fit as well as ones where it shines and learn how to work around some of the issues.
---

Languages can't always be great at everything. Part of what makes Python great also brings challenges for disciplines that need rigorous control of the way your processor executes instructions and the way memory is handled. We'll walk through situations where Python is a wonderful fit and also ones where it is a terrible fit for cryptographic operations. When it's good, we'll carefully examine why that is the case. When it's not, we'll discuss the workarounds and mitigations that can allow its use in most cases. 

This talk is targeted at any developer who has wondered whether how to best do sensitive cryptography related things (like encrypting a file, deriving a key, creating secrets, and much, much more) in Python.

While beneficial, this talk assumes no background knowledge about cryptography or the implementation details of a Python interpreter and provides a brief introduction to cryptographic concerns to provide grounding for users without cryptographic/C experience.

Attendees will gain knowledge about the limitations and strengths of Python when writing security sensitive software. They will be able to use this insight to better inform their threat modeling when designing/refactoring software they write.
