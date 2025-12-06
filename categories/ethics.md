---
layout: default
title: 도덕
permalink: /categories/ethics/
parent: 교과목
nav_order: 5
---

# 💡 도덕
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🌟</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 도덕 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/ethics.jpg 에 추가해주세요</p>
</div>

## 도덕 과목 소개
{: .text-delta }

도덕은 올바른 가치관과 인성을 기르는 교과입니다. 1985년 국민학교 시절, 도덕 시간에는 효도, 예절, 정직, 협동과 같은 덕목을 배우고, 바른 생활 태도를 익혔습니다.

### 이 카테고리의 역할

- **철학과 사고**: 철학적 질문, 사유의 깊이, 세계관
- **윤리와 가치**: 윤리적 딜레마, 도덕적 판단, 가치 탐구
- **삶의 지혜**: 인생 경험, 교훈, 성찰
- **인간관계**: 공감, 이해, 배려, 소통의 지혜

### 특징

당시 도덕 교과서는 위인전과 교훈적인 이야기로 가득했습니다. 이순신 장군, 세종대왕, 유관순 열사의 이야기를 읽으며 애국심을 배우고, "정직은 최선의 방책"과 같은 격언을 외웠습니다. 국기에 대한 맹세로 시작하던 아침 조회가 떠오릅니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.ethics %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.ethics.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
