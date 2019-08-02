---
layout: talk
permalink: /talks/how-i-migrated-a-huge-oss-project-to-use-pytest
recordingconsent: true
talkid: NBECJ9
title: How I auto-refactored a huge OSS project to use pytest
track: general
type: talk

speakers:
- avatar: craig-de-stigter.jpg
  biography: 'I''ve been a platform engineer for [Koordinates](https://koordinates.com/)
    for ages. I''m a Christian, a husband and father of two small people.


    Back when I used to have spare time, I spent most of it snowboarding, drinking
    craft beer and doing open source programming. I do a bit of brewing now and then.


    I like Python. I like upgrading stuff and refactoring code. Sometimes I think
    I''d be a good janitor, or possibly a demolition person.'
  name: Craig de Stigter

abstract: | 
      Over a couple of months in 2018 I developed a script for refactoring GDAL's ancient and arcane test suite to use Pytest. The final pull request was over 118,000 lines. This talk covers how I did it and what I learned.
---

At Koordinates we've been using [Pytest](https://docs.pytest.org/en/latest/) for all our testing. It's so much better than the other options that I cringe whenever I have to test a project that uses the stdlib.

We also make heavy use of [GDAL](https://www.gdal.org/), a broad and ancient data-munging library and tool. Unfortunately the test suite was 20 years old and homegrown. The test runner *predates* the unittest tools in the standard library, and sprouts weird quirky behaviour all over the place.

At Pycon AU 2018 I happened across John Reese's excellent talk on [Refactoring Using the Standard Library](https://2018.pycon-au.org/talks/45063-refactoring-code-with-the-standard-library/) and realised I could use [Bowler](https://pybowler.io/) to do an automated rewrite of the GDAL test suite, and hopefully convert it to use Pytest.

This talk describes my experience, including:
 * when to use automated refactoring tools
 * the basics of automated refactoring
 * how to avoid git conflicts when working on a huge pull request on a very active project
 * how to actually get your [>100,000 line pull request](https://github.com/osgeo/gdal) merged upstream (!)
