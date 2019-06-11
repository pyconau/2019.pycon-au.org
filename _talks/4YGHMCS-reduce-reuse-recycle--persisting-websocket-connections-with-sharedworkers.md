---
layout: talk
permalink: /talks/reduce-reuse-recycle--persisting-websocket-connections-with-sharedworkers
recordingconsent: true
talkid: YGHMCS
title: Reduce, Reuse, Recycle - Persisting WebSocket connections with SharedWorkers
track: django
type: talk

speakers:
- avatar: aaron-bassett.jpg
  biography: 'Aaron Bassett has lived in Ireland, Scotland, and is currently wandering
    around Europe. He is a recovering senior software engineer turned [award-winning
    Developer Advocate](https://www.nexmo.com/blog/2018/11/28/all-your-devrel-award-belong-to-us-dr/)
    at [Nexmo](https://nexmo.com) where he leads their content creation.


    Aaron has been working online since 2005 and has always enjoyed sharing what he
    learned by organising and speaking at local meetups. He spoke at his first conference
    in 2013, and since then he''s spoken at conferences on a range of topics all over
    the world. He has a passion for mentoring and has been involved with [Social Innovation
    Camp UK](https://en.wikipedia.org/wiki/Social_Innovation_Camp), [Social Innovation
    Camp Kosovo](http://unicefstories.org/tag/social-innovation-camp-kosovo/), [Startup
    Weekend](https://startupweekend.org/), [Open Glasgow](http://futurecity.glasgow.gov.uk/hacking-the-future/),
    [DjangoGirls](https://djangogirls.org/) and [global diversity CFP day](https://www.globaldiversitycfpday.com/events/101).'
  name: Aaron Bassett

abstract: | 
      WebSockets have many advantages, reduced latency, lower bandwidth, and reduced costs. But when our browser starts duplicating WebSocket connections, we quickly begin to lose these advantages. In this talk, we'll see how we can share one WebSocket connection across all browser contexts.
---

When using WebSockets to communicate between your server and the client every new browser context; tab, window, iframe, and so on–is likely to create another WebSocket connection. All these open connections can quickly take a toll on your server resources, or if you're using a PaaS which charges for each connection, it could quickly add up to a big bill.

In this talk, we'll look at how you can use SharedWorkers to create a single persistent WebSocket which can be used by every browser context to communicate with your Django Channels WebSocket server
