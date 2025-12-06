---
layout: page
title: 사회
permalink: /categories/social-studies/
---

<div class="posts">
  {% for post in site.categories.social-studies %}
  <article class="post">
    <h1 class="post-title">
      <a href="{{ post.url | relative_url }}">
        {{ post.title }}
      </a>
    </h1>
    <time datetime="{{ post.date | date_to_xmlschema }}" class="post-date">{{ post.date | date: "%Y년 %m월 %d일" }}</time>
    {{ post.excerpt }}
  </article>
  {% endfor %}
</div>

{% if site.categories.social-studies.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
