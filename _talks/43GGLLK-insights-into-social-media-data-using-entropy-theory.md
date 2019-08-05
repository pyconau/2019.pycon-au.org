---
layout: talk
permalink: /talks/insights-into-social-media-data-using-entropy-theory
recordingconsent: true
talkid: 3GGLLK
video_url: https://youtu.be/lW5ZJcrjYLw
title: Insights into Social Media Data using Entropy Theory
track: general
type: talk

speakers:
- avatar: mars-geldard.jpg
  biography: 'Mars is a Honours-year Computing student from the University of Tasmania.
    Entering the world of technology relatively late as a mature-aged student, she
    has found her place in the world: an industry where she can apply her lifelong
    love of mathematics and optimisation.


    When she is not busy being the most annoyingly eager student ever--or mouthing
    off about why everyone should love data science as much as she does--she compulsively
    volunteers at industry events, tutors in AI, hikes around in the wilderness, dabbles
    in research, builds [Game of Thrones in Minecraft](http://www.westeroscraft.com/),
    and makes Swift Playgrounds for everything. She also serves on the Executive Committee
    for her state''s branch of the [Australian Computer Society](https://www.acs.org.au)
    (ACS), where she aids in efforts to improve tech education and community engagement
    for young Tasmanians, as well as the national Executive Council of the [AUC](https://auc.edu.au),
    where she helps run the [/dev/world](http://www.devworld.com.au) conference and
    initiatives to support the Australian Apple development community. In the time
    she has left she is [writing a book](https://www.amazon.com/dp/1492044814/ref=cm_sw_em_r_mt_dp_U_QSvPCbATKE7J3)
    for O''Reilly Media.'
  name: Mars Geldard

abstract: | 
      Entropy theory is usually thought of as something that applies to matter and energy, but it turns out that we can apply the same techniques of analysis to social media sites. Join me as we study the thermodynamic behaviour of users on Twitter, and learn how to analyse it better.
---

Statistical mechanics, built upon the concept of entropy from classical thermodynamics, is used to reveal properties of physical systems and describe them in great detail based on properties such as thermodynamic states (entropy and enthalpy) and constants (heat capacitance). This method of gaining insight into macroscopic behaviour of a system by treating it as a set of microscopic interactions is particularly effective when a large number of entities are concerned--such as particles in a gas or ions in a plasma cloud.

An exploratory study is being conducted into whether these methods can be used to describe the macroscopic behaviour of a social media platform by prescribing analogous measures of density, temperature, and particle velocity to traits such as the number of tweets on a topic, their engagement metrics, and the growth of interest over time.

Findings could indicate suitability of the method to answer key questions often asked of social media data:
* Does the total amount of potential "energy" (user engagement) of a platform fluctuate over time? If so, how?
* Can we estimate how much of it is currently being channeled?
* Can we estimate the relative potential energy of different topic areas (politics, celebrity gossip, sports, etc.)?
* **And most importantly:** if we can analyse and understand these factors, could this provide tangible benefit to users, such as points in time where certain topic areas have optimal engagement potential?

Researchers posit this data mapped as entropy-over-time will be a more effective analogy for the lifetime of a trend that the oft-applied technology adoption curve or other metrics. Using only [Twarc](https://github.com/DocNow/twarc) and a bunch of good old-fashioned scripting, we present and evaluate initial findings from an investigation into historical datasets from Twitter, and discuss what this means for treating social media platforms as closed, intra-connected systems for analysis.
