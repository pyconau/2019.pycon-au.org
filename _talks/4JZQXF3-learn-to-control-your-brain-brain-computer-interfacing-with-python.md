---
layout: talk
permalink: /talks/learn-to-control-your-brain-brain-computer-interfacing-with-python
recordingconsent: true
talkid: JZQXF3
video_url: https://youtu.be/d6YJpZBx4X8
title: 'Learn to control your brain: Brain Computer Interfacing with Python'
track: science
nicetrack: "Science and Data"
type: talk

speakers:
- biography: I am a neuroscientist currently working at the QIMR Berghofer Medical
    Research Institute in Brisbane, Australia. I have a fair fascination with Python
    which has recently been strengthened by having chosen to use it for my own research
    on Brain-Computer Interfacing and Neurofeedback Training.
  name: Johan van der Meer

abstract: | 
      Neurofeedback is a brain-computer interface where a person’s own brain waves are audio/visually presented back in real-time after they’ve been recorded and filtered within a few milliseconds. We present methods to allow people to see their own brainwaves with python.
---

Allowing people to see their own brainwaves enables brainwave training. People see their own brain rhythm and can try to exert control over it, for the purpose of getting a benefit out of this training. An example of an application is with athletes. When  it is desirable to have better fine motor control, the EEG is measured and the sensorimotor rhythm extracted from the brain. Then, the athlete will train this rhythm for several weeks for an hour a day and in the end, be able to perform better because of that training. Similar methods are also used to treat mental health disorders such as Attention Deficit Hyperactivity Disorder, with other rhythms being trained more specific for that disorder.

There are many types of software that Neurofeedback. However, most have stumbling blocks when you try to do something different or wish to scale your research. In particular, most of them require a licensing fee. Those that are not, are implemented in C++. Additionally, the real meat of the neurofeedback procedure: prepossessing, filtering and feature extraction of the EEG data, is usually hidden away. Introducing a new means of analysis is therefore more difficult than it needs to be either by the licensing or the need to compile a new module.

What we did is to take newer approaches in the python ecosystem and apply them for EEG Neurofeedback. Conda  and Jupyter Lab are used for Deployment and flexibility in user Interaction. Psychopy and Pyff are used for Neurfeedback Stimulus presentation. Wyrm and PyNFB are used for Real-Time Analysis. This allows to put new real-time analysis approaches of neurofeedback on the foreground so that they can be immediately changed. In addition, the software can be deployed on any OS without limitations.

In conclusion, in this talk we will showcase our python environments (nf-rtime and nf-stim) with several examples and show how we can take a look at our brains with python.
