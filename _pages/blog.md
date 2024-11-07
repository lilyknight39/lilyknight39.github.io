---
layout: posts
title: "Blog"
permalink: /blog/
---

这里是我分享的点滴，不一定包括旅行见闻、喜爱的电影、书籍和音乐推荐。

{% for post in paginator.posts %}
  ### [{{ post.title }}]({{ post.url | relative_url }})
  <small>发布于 {{ post.date | date: "%Y-%m-%d" }}</small>
  
  {{ post.excerpt }}
  <a href="{{ post.url | relative_url }}">阅读全文</a>
  
  ---
{% endfor %}
