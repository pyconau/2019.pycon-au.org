---
layout: talk
permalink: /talks/securing-your-aws-identity-management-pipeline-with-pytest
recordingconsent: true
talkid: CL7SMP
video_url: https://youtu.be/X2RM16AbbFM
title: Securing your AWS Identity Management pipeline with PyTest
track: security
nicetrack: "Security and Privacy"
type: talk

speakers:
- biography: Cloud Technical Lead at an Australian Retail company. A Canadian transplant
    of 6 years to the wonderful land of Sydney. I have a lifelong love for automation,
    woodworking and Python. I am a co-host of the local Sydney Python group. He/Him/They.
  name: Sean Johnson
  twitter: seansonbronson

abstract: | 
      Amazon's Identity and Access Management is a risky needle to thread when it comes to deploying into the cloud, especially when it comes to empowering your developers to make their own changes. In this talk I will be showing how to leverage PyTest to test your policies before they hit production.
---

PyTest is an amazing tool for any Pythonista. It protects our Fridays from bad code deployments and it fills our hearts with green PASSED statuses. But, did you know it can test much more than just Python files? 

In this talk I will be discussing how to leverage the collection capabilities of PyTest to bring easy and powerful testing capabilities to your Terraform and CloudFormation pipelines. I will be discussing the limits and capabilities of AWS' IAM policy management and how you can turn the traditionally grueling process of learning cloud security into a positive developer experience.
