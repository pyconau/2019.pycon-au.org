---
layout: talk
permalink: /talks/tunnel-snakes-rule-bringing-the-many-worlds-of-python-together-to-monitor-melbournes-biggest-infrastructure-project
recordingconsent: true
talkid: 3ZZPQV
title: Tunnel Snakes Rule! Bringing the many worlds of Python together to monitor
  Melbourne's biggest infrastructure project.
track: general
type: talk

speakers:
- biography: Evan is a senior developer and solutions architect at WSP Digital. He's
    been a professional software engineer for over 11 years, predominantly working
    in web, IoT, and curly integration problems. He likes board games and listening
    to four hour Studio Ghibli cafe jazz remixes on YouTube.
  name: Evan Brumley

abstract: | 
      Python is being used to provide real-time environmental monitoring on the Melbourne Metro Tunnel project. Come along to see how open source Python tools from the web, IoT, cloud infrastructure and scientific domains are being used together to monitor environmental telemetry on a city-wide scale.
---

The  Melbourne Metro Tunnel is an $11 billion project, building twin nine-kilometre rail tunnels directly underneath the city's central business district, along with five new underground stations along the route.

Construction of the new tunnel is being performed across seven major construction sites in Melbourne's CBD, all of which are placed in highly sensitive locations. Accordingly, the project has extremely strict environmental performance requirements. These include the straightforward (don't be noisy around this apartment block), the complex (don't vibrate this electron microscope at these very particular frequencies), and the potentially life-critical (don't throw this radiotherapy machine out of alignment).

In 2018 a small engineering team was put together to build a real-time environmental monitoring platform. The platform needed to:

- Retrieve telemetry data from any environmental sensor being used on the project
- Securely store that data in a fully auditable format
- Track performance against 20+ separate environmental requirements
- Send out alerts to stakeholders and site managers if a requirement was breached
- Provide formal workflows and issue tracking for breaches

The platform was built from scratch, with a total development time of less than one year. In this talk, Evan Brumley, the project's lead developer, will walk through the design of the system and show how Python's broad ecosystem of scientific, web, IoT and cloud infrastructure tools made such an ambitious project possible.
