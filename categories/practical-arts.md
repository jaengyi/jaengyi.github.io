---
layout: default
title: 실과
permalink: /categories/practical-arts/
parent: 교과목
nav_order: 9
---

# 🔧 실과
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🛠️</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 실과 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/practical-arts.jpg 에 추가해주세요</p>
</div>

## 실과 과목 소개
{: .text-delta }

실과는 실생활에 필요한 기술과 지식을 배우는 교과입니다. 1985년 국민학교 시절, 실과 시간에는 바느질, 요리, 목공, 재배 등 생활에 유용한 기술들을 배웠습니다.

### 이 카테고리의 역할

- **실용 기술**: 생활 기술, 도구 사용법, 문제 해결 방법
- **만들기와 DIY**: 제작 과정, 수공예, 창작물 만들기
- **생활과 관리**: 일상 관리, 정리 정돈, 효율적인 생활
- **응용과 실천**: 배운 것을 실제로 적용하고 실천하기

### 특징

당시 실과 교과서는 남학생과 여학생의 내용이 달랐습니다. 여학생은 바느질과 요리를, 남학생은 목공과 재배를 주로 배웠죠. 단추 달기, 손바느질, 간단한 요리 만들기 등 어른이 되어서도 유용한 기술들을 배웠습니다. 작은 화분에 채소를 키우고, 나무판으로 연필꽂이를 만들던 기억이 납니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.practical-arts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.practical-arts.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
