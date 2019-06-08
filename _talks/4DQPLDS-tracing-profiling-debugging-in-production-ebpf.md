---
layout: talk
permalink: /talks/tracing-profiling-debugging-in-production-ebpf
recordingconsent: true
talkid: DQPLDS
title: Tracing, Profiling & Debugging in Production (eBPF)
track: general
type: talk

speakers:
- biography: Trent Lloyd (@lathiat) works in Canonical's Sustaining Engineering team
    providing Ubuntu & OpenStack support (where Python is the primary language). Previously
    having spent nearly a decade on the MySQL Support Team he is no stranger to being
    thrust into other team's production problems.
  name: Trent Lloyd

abstract: | 
      Trace, Profile & Debug applications in production without restarting or loading a framework.We will look at a number of modern techniques including eBPF and ptrace to attach to running production applications with no preparation and minimal performance impact.
---

It can be difficult to Trace, Profile or Debug applications in production due to both the performance overhead or required preparation (needing to have already configured a framework).

There are now a number of modern techniques including eBPF-based tools that allow us to trace applications at runtime and ptrace-based tools such as pyflame that allow us to profile applications without pre-loading any code and with minimal performance overhead. These tools can be particularly helpful in production environments.

We will look at how to use a number of tools including pyflame, py-spy and eBPF based tool pythoncalls and how these might be used to solve production problems including
 - Profiling code to understand a specific performance problem that suddenly appears in production
 - Understanding where a production process is stuck and stops responding
 - Debugging an application that is behaving inappropriately

After this talk you should be empowered with an understanding of how these tools can help you in a future production scenario.
