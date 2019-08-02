---
layout: talk
permalink: /talks/not-a-long-time-ago-in-a-galaxy-not-very-far-away-an-astronomer-and-a-computer-scientist-walk-into-a-bar
recordingconsent: true
talkid: MBT77Q
title: Not a long time ago, in a galaxy not very far away, an astronomer and a computer
  scientist walk into a bar...
track: science
nicetrack: "Science and Data"
type: talk

speakers:
- biography: George is an astrocoder who likes to play the ukulele in his (nonexistent)
    free time.
  name: Georgios Bekiaris

abstract: | 
      Python is one of the most popular programming languages in astronomy. In this talk, I will tell a story about how Python helped me to develop a software tool for galaxy modelling, and tackle the scientific and technical challenges that arise in the Big Data era of astronomy.
---

We are on the verge of revolutionizing our understanding of galaxies in the nearby universe. The vast amount of spatially-resolved spectroscopic data produced by new-generation instruments and telescopes as part of large-scale survey projects, such as SAMI, Hector, and WALLABY, will reveal the internal structure and kinematics of many thousands of galaxies. This unprecedented amount of information will enable scientists to conduct large-scale statistical multi-wavelength studies for first time, and shed light into several aspects of galaxy structure, formation, and evolution. 

To tackle the technical and science analysis requirements of this ever growing amount of data I developed an extensible high-performance software for modelling the kinematics and photometry of galaxies. The generality of the software enables it to tackle a wide range of science cases, from the modelling of simple rotating disks, to the simultaneous fitting of multi-wavelength observations with peculiar morphological and kinematic signatures. Its flexible architecture allows it to support a great range of galaxy models and optimisation techniques, while it can also run on a variety of computational hardware including multi-core CPUs and GPUs. 

In this talk I am going to give an overview of the upcoming major release of the software and comment on its significance in the era of the large-scale 3D spectroscopic galaxy surveys. I will discuss why and how the software evolved from a pure C++ code to a Python project. I will comment on the design decisions I had to make, and I will provide a review of the most essential libraries used by the software. Throughout the talk, I will discuss the technical challenges I faced during the development of the software from an astronomer's as well as a computer scientist's perspective.
