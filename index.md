---
layout: home
title: Home
---
欢迎来到我的新博客。这是我从零开始，使用 Jekyll 重新构建的个人空间。

在这里，我将分享关于 Python、地球物理分析以及更多有趣的内容。

## 文章列表
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <span>({{ post.date | date: "%Y-%m-%d" }})</span>
    </li>
  {% endfor %}
</ul>
