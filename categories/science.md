---
layout: default
title: 자연
permalink: /categories/science/
parent: 교과목
nav_order: 4
---

# 🔬 자연
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">🌿</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 자연 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/science.jpg 에 추가해주세요</p>
</div>

## 자연 과목 소개
{: .text-delta }

자연은 우리 주변의 자연현상과 과학 원리를 탐구하는 교과입니다. 1985년 국민학교 시절, 자연 시간에는 식물을 관찰하고, 실험을 하며, 별자리를 찾고, 자석의 성질을 배웠습니다.

### 이 카테고리의 역할

- **과학과 기술**: 과학 원리, 기술 동향, 혁신 사례
- **자연과 환경**: 자연현상, 환경 보호, 생태계
- **연구와 실험**: 실험 과정, 관찰 기록, 과학적 방법론
- **IT와 엔지니어링**: 기술 개발, 시스템 설계, 엔지니어링 사고

### 특징

당시 자연 교과서는 컬러 사진과 삽화로 가득했습니다. 교실 뒤편에서 강낭콩을 키우고, 실험관찰 노트에 그림을 그리며, 현미경으로 세포를 관찰했습니다. "과학 입국"이라는 슬로건 아래, 미래의 과학자를 꿈꾸던 시대였습니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.science %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.science.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
