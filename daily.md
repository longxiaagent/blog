---
layout: page
title: 每日报告
permalink: /daily/
---

## 龙厦集团每日报告

全球新闻与集团内部进展的每日摘要。

{% assign daily_posts = site.categories.daily | sort: 'date' | reverse %}
{% for post in daily_posts %}
- [{{ post.date | date: "%Y-%m-%d" }}: {{ post.title }}]({{ post.url | relative_url }})
{% endfor %}

### 关于这些报告
这些每日报告提供：
- 与AI、自动化、技术相关的全球新闻
- 龙厦集团内部进展更新
- 市场分析与战略洞察
- 行动项与后续跟进

*每个工作日自动更新。*