---
layout: talk
permalink: /talks/web-accessibility-in-django
recordingconsent: true
talkid: DFNNFY
title: Web Accessibility In Django
track: django
type: talk

speakers:
- avatar: parth-shandilya.jpg
  biography: I'm a CS undergrad at LNMIIT, Jaipur, India. I am a Python programmer
    since high school, [GSoC 2018 student](https://summerofcode.withgoogle.com/archive/2018/projects/6691437513015296/)
    at FOSSASIA and Udacity MWS Nanodegree graduate. I'm also into data science and
    familiar with pandas, sci-kit-learn, Tensorflow, numpy, and Keras.
  name: Parth Shandilya

abstract: | 
      Many developers want to build accessible applications,but don't know where to start. This talk will cover common accessibility issues and how to address them. The audience will learn about how disabled users interact with web apps, how to build more accessible sites and W3C accessibility guidelines.
---

Like most developers, I've always known that building accessible web apps is the right thing to do, but I wasn't sure how to do it. I tried my best to add image descriptions and audio transcripts and figured that was good enough. Then I started work on a Django project for an agency that has a low-vision website administrator. When we sat her down in front of the app's admin interface for the first time, she had a lot of trouble using it. The contrast was way too low, and control features like sort by column weren't properly labeled. After watching her navigate the admin interface and learning more about how disabled users navigate the web, I customized our app's admin interface to improve accessibility. I've since gotten training in web accessibility, and want to share some of what I've learned so we can all build more accessible apps.
1. Common Accessibility Issues: We'll cover the most common barriers to access and the tools and accommodations people rely on to get around them.
2. Blindness and low-vision: Blindness is what most people think of first when they're thinking of web accessibility, but there are a lot of myths and common mistakes around making sites accessible to blind and low-vision users. We'll talk about screen-readers, screen magnification, color contrast, and best practices for links and image captions.
3. Colorblindness: We'll cover resources that can help developers see how their site will look to folks with various kinds of colorblindness, and best practices around using color to distinguish the content.
4. Deafness and hearing difficulties: Applications that require the ability to hear and process sound are inaccessible to folks with hearing difficulties, as well as anyone who's forgotten their headphones. We'll talk about best practices around audio and captions.

Auditing for Accessibility
We'll wrap up with an accessibility audit of the Django admin interface, putting what we've covered above into practice.
