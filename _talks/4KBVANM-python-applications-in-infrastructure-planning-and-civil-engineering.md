---
layout: talk
permalink: /talks/python-applications-in-infrastructure-planning-and-civil-engineering
recordingconsent: true
talkid: KBVANM
title: Python Applications in Infrastructure Planning and Civil Engineering
track: general
type: talk

speakers:
- biography: 'Ben is a graduate engineer in the Data Analytics and Automation team
    in WSP here in Sydney.

    He first started his adventures in Python less than a year ago and has since been
    helping engineers automate the boring things.'
  name: Ben Chu

abstract: | 
      Engineers tasked with planning new infrastructure constantly face the problem of having to look through too much information. This talk is about how we wanted to be lazy and wrote a bot to do it for us instead.
---

There is an abundance of data available to the modern engineer tasked with planning new infrastructure. However, this data is not always in a readily accessible format or may be scattered across various locations. Furthermore, the volume of data is often too large to be processed manually in a timely manner. When planning major infrastructure, it is critical to understand potential impacts from third party developments that may impact upon the planned works. In New South Wales this information is in the public domain but scattered across various local and state government websites which must be manually searched (often by junior staff) to detect third party developments that present a risk to the alignment. This talk describes how this process was automated for a railway project in Sydney. Web scraping bots were written to mine pertinent development application information from government websites, which were then automatically risk-rated using natural language processing and machine learning methods. In order to mine the information effectively and geocode the data, several publicly available spatial datasets were integrated, including lot and administrative boundary information from the Digital Cadastral Database (DCDB) combined with the Geocoded-National Address File (G-NAF). Many machine learning techniques were tested and ultimately a boosted tree algorithm (XGBoost) was used to build a model that allocated a preliminary risk rating to development applications. The automated system drastically reduced the time taken to search through development applications. The speed allowed for high-risk developments to be identified as they were submitted for planning approvals and new assessments could be made rapidly upon changes to the alignment. The use of the human mind was then targeted towards verification.
