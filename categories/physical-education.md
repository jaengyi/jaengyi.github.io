---
layout: default
title: 체육
permalink: /categories/physical-education/
parent: 교과목
nav_order: 6
---

# ⚽ 체육
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🏃</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 체육 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/physical-education.jpg 에 추가해주세요</p>
</div>

## 체육 과목 소개
{: .text-delta }

체육은 건강한 신체와 건전한 정신을 기르는 교과입니다. 1985년 국민학교 시절, 체육 시간에는 맨손체조, 달리기, 줄넘기, 피구, 축구 등 다양한 운동을 했습니다.

### 이 카테고리의 역할

- **건강과 운동**: 운동 방법, 건강 관리, 피트니스
- **도전과 성장**: 목표 달성, 끈기, 자기 극복 경험
- **활동과 취미**: 여행, 레저, 야외 활동, 취미 생활
- **에너지와 활력**: 일상의 활력, 에너지 관리, 라이프스타일

### 특징

당시 체육 시간은 운동장에서 보내는 가장 즐거운 시간이었습니다. 파란색 체육복을 입고 운동장에 모여 체조를 하고, 선생님의 호루라기 소리에 맞춰 달리기를 했습니다. 86아시안게임과 88올림픽을 앞두고 체육에 대한 관심이 높았던 시절입니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.physical-education %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.physical-education.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
