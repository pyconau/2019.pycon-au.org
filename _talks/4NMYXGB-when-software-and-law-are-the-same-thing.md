---
layout: talk
permalink: /talks/when-software-and-law-are-the-same-thing
recordingconsent: true
talkid: NMYXGB
title: When software and law are the same thing
track: general
type: talk

speakers:
- avatar: brenda-wallace.jpg
  biography: '"The person I''d most want on my team if I were fighting against a killer-robot
    apocalypse."'
  name: Brenda Wallace

abstract: | 
      In Aotearoa New Zealand the government ran an experiment to encode law openly as python, publish versioned in git, licenced as open source, and available on a hosted as an API.
---

I'm the tech lead of a bunch of techies paid by the NZ government to try new things. 

We saw our fellow coders left to write software that implements rules that originated in legislation, regulation, policy and other rule sets. (very) Often those rules are complex, complicated, and written in language that hasn't benefited from the zen of python. 

We know we can have one coder reading the rules coming to different conclusions and implementation results than another coder.
When those rules are something that affects everyone such as how much income tax to pay or how many days of sick leave you get from your employer, we end up in a situation where how much you get depends on what software you or your employer install.

But the law isn't meant to vary like that. It should be clear, implementable, and open for all to see.  Not ambiguous, not differing in each implementation, and not applied to your life closed and uninspectable.

So we started a Legislation as Code project.  Give it input variables, and it will run the rules and calculate a result for you.
