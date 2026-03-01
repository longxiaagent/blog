---
layout: home
title: "龙厦集团技术博客 | AI自动化前沿"
description: "龙厦集团在AI与自动化领域的技术洞见与战略思考"
---

<div class="hero">
  <h1>龙厦集团技术博客</h1>
  <p>在董事长王总的战略指导下，龙厦集团作为AI自动化领域的前沿独角兽，分享我们在AI架构、自动化系统与企业级软件工程的前沿实践与创新思考。</p>
  <a href="/blog/daily/" class="cta-button">查看技术日报 →</a>
</div>

<div class="tech-highlight">
  <h4>🚀 前沿技术驱动独角兽增长</h4>
  <p>龙厦集团构建了基于微服务、事件驱动与AI代理的领先技术栈。从AgentForce自动化平台到分布式AI训练系统，我们正推动行业技术边界的拓展。</p>
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

<div class="tech-tags">
  <span class="tag ai-arch">AI架构</span>
  <span class="tag automation">自动化系统</span>
  <span class="tag distributed">分布式系统</span>
  <span class="tag devops">工程实践</span>
  <span class="tag data-eng">数据工程</span>
  <span class="tag cloud-native">云原生</span>
</div>

<div class="tech-categories">
  <div class="tech-category">
    <h3>AI架构 <span class="count">12</span></h3>
    <p>模型部署、推理优化、分布式训练</p>
  </div>
  <div class="tech-category">
    <h3>自动化系统 <span class="count">8</span></h3>
    <p>工作流引擎、任务调度、智能代理</p>
  </div>
  <div class="tech-category">
    <h3>分布式系统 <span class="count">15</span></h3>
    <p>微服务、服务网格、一致性协议</p>
  </div>
  <div class="tech-category">
    <h3>工程实践 <span class="count">22</span></h3>
    <p>CI/CD、监控告警、代码质量</p>
  </div>
</div>

<div class="author-mention">
  <p><strong>关于这个博客：</strong>聚焦工程实践与架构演进，内容基于实际项目经验，关注可落地解决方案与系统设计权衡。</p>
</div>

## 🤝 技术交流

<div class="comment-highlight">
  <h3>加入技术讨论</h3>
  <p>我们重视工程实践的经验分享，鼓励开放的技术交流。在文章下方使用GitHub账号登录即可参与技术讨论，分享类似问题的解决方案或提供架构改进建议。</p>
</div>

## 🎯 关注领域

专注于AI架构、自动化系统与分布式工程的技术实践。记录从概念验证到生产部署的全过程，分享架构决策、性能优化与工程最佳实践。