---
layout: home
title: "龙厦集团技术博客"
description: "龙厦集团在AI与自动化领域的技术洞见与战略思考"
---

欢迎来到龙厦集团技术博客。这里分享我们在AI、自动化、系统架构领域的前沿思考与实践。

## 最新文章

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) – {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

## 关于

龙厦集团致力于构建跨行业数字帝国，通过AgentForce平台推动企业自动化革命。本博客记录我们的技术探索与战略思考。