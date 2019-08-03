---
layout: talk
permalink: /talks/forecasting-australias-2019-election-with-pymc3
recordingconsent: true
talkid: MKRZ9F
title: Forecasting Australia's 2019 Election with PyMC3
track: science
nicetrack: "Science and Data"
type: talk

speakers:
- biography: "I am a data scientist who is passionate about using information for\
    \ good. \n\nI've created [Buckley's & None](https://www.buckleysandnone.com \"\
    Buckley's & None\") a site that forecasts Australia's election. \n\nI have a diverse\
    \ set of experiences including a PhD in neuroscience and monitoring and evaluations\
    \ work with an international NGO in Mumbai, India. \n\nI'm excited about increasing\
    \ data literacy and making programming accessible to all audiences."
  name: Martin Burgess
  avatar: martin-burgess.png

abstract: | 
      Can we predict the result of an Australian election before it occurs? How certain of the outcome can we be? My talk will use the 2019 Australian federal election as a case study to provide an entry-level introduction to the benefits of probabilistic forecasting and PyMC3.
---

I've used the PyMC3 package to create a model of the 2019 Australian federal election. This forecast is published live at [Buckley's & None](https://www.buckleysandnone.com). My talk will use this model as a case study to introduce the PyMC3 package and probabilistic forecasting. Probabilistic forecasting assigns a *probability* to each of the different outcomes. This contrasts with other methods that only predict the most-likely outcome. Because of this, probabilistic forecasting can provide a clear idea of the uncertainty associated with a forecast's predictions.

This talk is aimed at anyone interested in estimating uncertainty, probabilistic forecasting, using Bayesian statistics, or using data to predict political outcomes. If you've heard of these terms but aren't sure what they mean, this will be an entry-level talk to get you started.

I'll have three short sections:

1. A quick background to thinking probabilistically and using Bayesian statistics.
2. I'll walk through how a comprehensive model can be specified in PyMC3 in a straightforward and concise way. 
3. A review of how the model performed.

It's my aim that after this talk you'll understand some of the benefits of using probabilistic/Bayesian methods. You'll also have a clear idea of how to implement models in PyMC3 so you can start to build your own.
