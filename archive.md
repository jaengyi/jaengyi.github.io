---
layout: default
title: 전체목록
nav_order: 2
---

## 날짜별 전체 글 목록

{% assign postsByYearMonth = site.posts | group_by_exp: "post", "post.date | date: '%Y년 %m월'" %}
{% for yearMonth in postsByYearMonth %}
  <h3>{{ yearMonth.name }}</h3>
  <ul>
    {% for post in yearMonth.items %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span class="post-date">{{ post.date | date: "%Y년 %m월 %d일" }}</span>
        {% if post.categories %}
          <span class="post-category">[{{ post.categories | join: ", " }}]</span>
        {% endif %}
      </li>
    {% endfor %}
  </ul>
{% endfor %}

{% if site.posts.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
