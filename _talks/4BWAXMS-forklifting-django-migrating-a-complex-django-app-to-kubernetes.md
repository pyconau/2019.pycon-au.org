---
layout: talk
permalink: /talks/forklifting-django-migrating-a-complex-django-app-to-kubernetes
recordingconsent: true
talkid: BWAXMS
title: 'Forklifting Django: Migrating A Complex Django App To Kubernetes'
track: django
nicetrack: "DjangoCon AU"
type: talk

speakers:
- avatar: noah-kantrowitz.jpg
  biography: Noah Kantrowitz is a web developer turned infrastructure automation enthusiast,
    and all around engineering rabble-rouser. By day he runs an infrastructure team
    at Ridecell and by night he makes candy and stickers. He is an active member of
    the DevOps community, and enjoys merge commits, cat pictures, and beards.
  name: Noah Kantrowitz

abstract: | 
      Everyone is talking about Kubernetes, but migrating existing applications is often easier said than done. This talk will cover the tale of migrating our main Django application to Kubernetes, and all the problems and solutions we ran into along the way.
---

Kubernetes has rapidly become an omnipresent tool in the infrastructure world, running everything from the biggest monolith to the slightest microservices. But with power comes complexity, and Kubernetes has never been accused of being too simple or having too few moving pieces. Over about 9 months, we've moved Ridecell's primary Django application from AWS and Ansible to Kubernetes, encountering many pitfalls along the way. This talk will show the approaches we tried, the worst of the issues we encountered, and lay out a path for migrating other Python web applications more effectively!
