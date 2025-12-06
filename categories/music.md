---
layout: default
title: 음악
permalink: /categories/music/
parent: 교과목
nav_order: 7
---

# 🎵 음악
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🎼</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 음악 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/music.jpg 에 추가해주세요</p>
</div>

## 음악 과목 소개
{: .text-delta }

음악은 아름다운 소리와 리듬을 통해 감성을 키우는 교과입니다. 1985년 국민학교 시절, 음악 시간에는 동요를 부르고, 리코더를 불며, 악보를 읽는 법을 배웠습니다.

### 이 카테고리의 역할

- **음악과 소리**: 음악 감상, 악기 연주, 음악 이론
- **창작과 표현**: 창작 활동, 예술적 표현, 감성 개발
- **청각 예술**: 소리 디자인, 오디오 기술, 음향 효과
- **감성과 치유**: 음악 치료, 힐링, 감정 표현

### 특징

당시 음악 교과서에는 "학교종", "고향의 봄", "우리의 소원은 통일" 같은 노래들이 가득했습니다. 피아노 반주에 맞춰 노래를 부르고, 리코더로 "작은 별"을 연습하며, 캐스터네츠와 트라이앵글로 리듬을 맞췄습니다. 음악실에서 들려오던 따뜻한 선율이 그립습니다.

---

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
