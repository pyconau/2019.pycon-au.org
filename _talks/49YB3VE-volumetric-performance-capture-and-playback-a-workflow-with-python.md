---
layout: talk
permalink: /talks/volumetric-performance-capture-and-playback-a-workflow-with-python
recordingconsent: true
talkid: 9YB3VE
video_url: https://youtu.be/WVVk1Qctkx4
title: 'Volumetric Performance Capture and Playback: A Workflow with Python'
track: general
type: talk

speakers:
- biography: I am a software engineer with an interest in software as art, game development
    and python
  name: Luke Miller

abstract: | 
      Volumetric capture is a technique used to film in three dimensions for viewing in a virtual space.This talk will explore the different elements of a full volumetric capture stack, from coordinating usb cameras to playback in a 3D game engine and how python can be used to glue it all together.
---

Volumetric video uses a basic technique called photogrammetry to convert images into three-dimensional objects and then animate those 3D frames in sequence.  The technology has a lot of applications for filmmakers, sports broadcasters and game developers.

However even a short videogrammetry project requires a lot of data and computational power and so having a clean and flexible pipeline is important.
 
As part of a project for Creative Victoria's Creators Fund, we created a volumetric capture solution using off-the-shelf components and a workflow glued together by python.

This talk covers the basics of volumetric capture, from camera placement and coordination, image matching, point cloud construction, mesh reconstruction, texturing, storage and playback inside a 3D game engine using a stack managed in python.

I'll discuss the challenges we faced in developing the process, what went right, what went wrong and what can be improved. If you have an interest in game development, software in art, or 3D reconstruction you may enjoy this presentation.
