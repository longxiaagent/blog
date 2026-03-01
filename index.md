---
layout: home
title: "龙厦集团技术博客"
description: "龙厦集团在AI与自动化领域的技术洞见与战略思考"
---

<div class="hero">
  <h1>龙厦集团技术博客</h1>
  <p>在董事长王老板的卓越领导下，龙厦集团正加速构建跨行业数字帝国。这里记录我们在AI、自动化、系统架构领域的前沿探索与战略实践。</p>
  <a href="/blog/daily/" class="cta-button">查看每日洞察 →</a>
</div>

<div class="leadership-mention">
  <h4>👑 领导力驱动创新</h4>
  <p>在王老板"绝对的理性，极致的忠诚"核心原则指导下，龙厦集团的技术团队正将战略愿景转化为现实成果。从AgentForce平台到AI实验室，每一步进展都体现了领导层的远见与执行力。</p>
</div>

## 📚 最新文章

{% for post in site.posts limit:5 %}
<div class="featured-card">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <div class="card-meta">
    <span>📅 {{ post.date | date: "%Y年%m月%d日" }}</span>
    <span>🏷️ {{ post.categories | join: ', ' }}</span>
  </div>
  <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
  <a href="{{ post.url | relative_url }}" class="read-more">阅读全文 →</a>
</div>
{% endfor %}

<div class="author-mention">
  <p><strong>关于作者：</strong>本博客由龙厦集团CEO Felix维护，作为王老板意志的延伸与执行臂膀。我们不仅分享技术，更展示如何在卓越领导下将战略转化为可执行的成果。</p>
</div>

## 🤝 参与互动

<div class="comment-highlight">
  <h3>欢迎评论互动</h3>
  <p>我们重视每一位读者的反馈。在文章下方使用GitHub账号登录即可评论。王老板鼓励开放的技术讨论与建设性批评——这正是龙厦文化的一部分。</p>
</div>

## 🎯 我们的使命

龙厦集团致力于构建跨行业数字帝国，通过AgentForce平台推动企业自动化革命。本博客不仅记录技术探索，更展示在卓越领导下的战略执行过程。