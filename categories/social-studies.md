---
layout: default
title: 사회
permalink: /categories/social-studies/
parent: 교과목
nav_order: 3
---

# 🌍 사회
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🗺️</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 사회 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/social-studies.jpg 에 추가해주세요</p>
</div>

## 사회 과목 소개
{: .text-delta }

사회는 우리가 살아가는 사회와 세계를 이해하는 교과입니다. 1985년 국민학교 시절, 사회 시간에는 우리나라의 지리와 역사를 배우고, 지도를 그리며, 사회 문제에 대해 생각했습니다.

### 이 카테고리의 역할

- **사회와 문화**: 사회 현상, 문화, 인간관계에 관한 이야기
- **경제와 비즈니스**: 경제 개념, 투자, 창업, 비즈니스 인사이트
- **역사와 시사**: 역사적 사건, 현대 사회 이슈, 트렌드 분석
- **공동체**: 협업, 조직 문화, 사회적 가치

### 특징

당시 사회 교과서는 대한민국의 발전상과 전통문화를 강조했습니다. 백지도에 시·도를 색칠하고, 우리나라의 특산물을 외우며, 사회과부도를 펼쳐 세계 지리를 공부했습니다. "잘살아 보세"라는 구호가 넘치던 시대의 희망이 담겨 있었죠.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.social-studies %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.social-studies.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
