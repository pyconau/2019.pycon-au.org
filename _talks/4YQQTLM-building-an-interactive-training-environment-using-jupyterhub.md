---
layout: talk
permalink: /talks/building-an-interactive-training-environment-using-jupyterhub
recordingconsent: true
talkid: YQQTLM
title: Building an interactive training environment using JupyterHub
track: general
type: talk

speakers:
- biography: Graham is the author of mod_wsgi, the Apache module for hosting of Python
    web applications using the WSGI interface, and the author of wrapt, a decorator
    and monkey patching library for Python. He also has a keen interest in docker,
    Kubernetes, and Platform as a Service (PaaS) technologies. He is currently a developer
    advocate for OpenShift at Red Hat.
  name: Graham Dumpleton

abstract: | 
      JupyterHub is used to run and manage Jupyter notebook instances for multiple users at the same time. Did you know though that you can use JupyterHub to spawn applications other than Jupyter notebooks? Come see how JupyterHub was used to create a multi user interactive training environment.
---

In this talk you will learn what JupyterHub is and how it works. You will be stepped through how JupyterHub was used to implement a multi user workshop environment running in Kubernetes. Instead of creating Jupyter notebooks, JupyterHub was used to create user environments in Kubernetes which gave the user access to an interactive Linux shell environment in their web browser, along with workshop course notes and presenter slides, in the same integrated dashboard view. Because the user environment provided all the tools required for the workshop, users were immediately good to go, with no need to install anything locally on their own computer.
