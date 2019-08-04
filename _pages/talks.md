---
layout: page
title: Talks
permalink: /talks/
sponsors: true
---
{% assign nud = 0 %}
{% assign sortedtalks = site.talks | reverse %}
{% for talk in sortedtalks -%}{% if talk.type == "talk" or talk.type == "keynote"%}{%-if talk.hidefromlist != true-%}
{% assign nud = nud | plus: 1 %}<li>{{nud}}<a href="{{talk.url}}">{{ talk.title }}</a> {% for speaker in talk.speakers %}{% if forloop.index0 > 0 %} and {% endif %}{{ speaker.name }}{% endfor %}{%endif%}{%endif%}
{% endfor %}

