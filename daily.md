---
layout: page
title: Daily Reports
permalink: /daily/
---

## LongXia Group Daily Reports

Daily summaries of global news and internal progress at LongXia Group.

{% assign daily_posts = site.categories.daily | sort: 'date' | reverse %}
{% for post in daily_posts %}
- [{{ post.date | date: "%Y-%m-%d" }}: {{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

### About These Reports
These daily reports provide:
- Global news relevant to AI, automation, and technology
- LongXia Group internal progress updates
- Market analysis and strategic insights
- Action items and follow-ups

*Updated automatically each business day.*