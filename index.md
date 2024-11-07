---
layout: single
title: "欢迎来到我的妙妙屋"
---

![我的个人图片](/assets/images/btn_chara.png){: .profile-image }

## 欢迎来到我的妙妙屋

你好！我是鱼粉，这是一个分享我兴趣和生活点滴的小空间。在这里，你可能会找到关于我的爱好、社交活动和我的一些特别发现。

### 关于我

我是一位不擅长分享和记录生活的普通人，希望你在这里能找到一些有趣的内容，也欢迎与我交流。

### 快速导航
- [博客](blog/)
- [关于我](about/)
- [联系我](contact/)

### 最新博客文章

{% for post in site.posts limit: 3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
