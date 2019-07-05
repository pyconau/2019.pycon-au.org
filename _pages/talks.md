---
layout: page
title: Talks
permalink: /talks/
sponsors: true
---

{% for talk in site.talks -%}{% if talk.type == "talk" or talk.type == "keynote"%}{%if talk.hidefromlist != true-%}
* [{{ talk.title }}]({{talk.url}}) {% for speaker in talk.speakers %}{% if forloop.index0 > 0 %} and {% endif %}{{ speaker.name }}{% endfor %}{%endif%}{%endif%}
{% endfor %}

