---
layout: default
title: 미술
permalink: /categories/art/
parent: 교과목
nav_order: 8
---

# 🎨 미술
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🖼️</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 미술 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/art.jpg 에 추가해주세요</p>
</div>

## 미술 과목 소개
{: .text-delta }

미술은 아름다움을 느끼고 표현하는 능력을 기르는 교과입니다. 1985년 국민학교 시절, 미술 시간에는 크레파스로 그림을 그리고, 색종이로 접기를 하며, 찰흙으로 만들기를 했습니다.

### 이 카테고리의 역할

- **시각 예술**: 그림, 사진, 디자인, 시각적 표현
- **창작과 디자인**: UI/UX 디자인, 그래픽 작업, 창의적 작업
- **미학과 감상**: 아름다움에 대한 탐구, 예술 작품 감상
- **표현과 소통**: 비주얼 스토리텔링, 시각적 커뮤니케이션

### 특징

당시 미술 교과서는 명화 감상과 함께 다양한 표현 기법을 소개했습니다. 16절 도화지에 크레파스로 "우리 가족"을 그리고, 물감으로 풍경화를 그렸습니다. 그림 잘 그리는 친구가 선생님께 칭찬받으면 부러워하던 시절, 미술 시간은 자유로운 상상의 시간이었습니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.art %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.art.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
