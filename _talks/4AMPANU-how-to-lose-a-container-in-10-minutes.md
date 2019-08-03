---
layout: talk
permalink: /talks/how-to-lose-a-container-in-10-minutes
recordingconsent: true
talkid: AMPANU
title: How to lose a container in 10 minutes
track: security
nicetrack: "Security and Privacy"
type: talk

speakers:
- avatar: sarah-young.jpg
  biography: Sarah is a cloud security architect working for Microsoft and based in
    Melbourne, Australia. She has a decade of experience in tech and is particularly
    interested in cloud security, container/orchestrator security and good ol' fashioned
    networking and infrastructure security (having previously worked as a network
    engineer). Sarah has spoken around the world at a variety of info sec conferences
    about a range of security and technical topics.
  name: Sarah Young

abstract: | 
      Moving to the cloud and deploying containers? In this talk I discuss both the mindset shift and tech challenges, with some common mistakes made in real-life deployments with some real life. We'll also be looking at my ongoing research about how easy it is to get a container or k8s cluster pwned.
---

Despite the fact that many organisations are already using/wanting to use containers and quite possibly moving to the cloud at the same time, I find that there is still an inherent lack of understanding from both devs and security teams as to how containerised applications should be designed and run. Many teams simply try to run a containerised application like it would be run on a virtual machine or in the traditional monolithic application stack, and to accompany that they use the traditional security toolset. This opens up the potential for security breaches and or simply an ineffective application that doesn't take advantage of the benefits containerised environments provide.
As I'm conscious this could be a bit of dry topic and I don't want it to sound like a lecture, my talk has many GIFs and memes and real life examples (they are redacted as I can't name where I saw some of these, unfortunately). More seriously though, it includes relevant stories and was developed with input from my real-life experiences and some stories from other engineers and security professionals. I've been spinning up different types of containers and leaving them open to the web to see what happens i.e. can I actually get myself pwned?
A brief summary of the talk structure:
Introduction to myself and the talk
Overview of cloud-native services and containers
Encryption and containers
Isolating containers
Structuring containerised applications
Orchestrator configuration
Using good container images
Running as root in the container
Secret/credentials storage
Deploying containers ephemerally
Shifting security to the left
Deploying a container-aware security toolset
What happened when I tried to get my containers pwned
Summary and close
