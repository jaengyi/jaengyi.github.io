---
layout: default
title: 음악
permalink: /categories/music/
parent: 교과목
nav_order: 7
---

# 음악
{: .no_toc }

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.music %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.music.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
