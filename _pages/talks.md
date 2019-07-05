---
layout: page
title: Talks
permalink: /talks/
sponsors: true
---
{% assign sortedtalks = site.talks | reverse %}
{% for talk in sortedtalks -%}{% if talk.type == "talk" or talk.type == "keynote"%}{%-if talk.hidefromlist != true-%}
<li><a href="{{talk.url}}">{{ talk.title }}</a> {% for speaker in talk.speakers %}{% if forloop.index0 > 0 %} and {% endif %}{{ speaker.name }}{% endfor %}{%endif%}{%endif%}
{% endfor %}

