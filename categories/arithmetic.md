---
layout: default
title: 산수
permalink: /categories/arithmetic/
parent: 교과목
nav_order: 2
---

# 🔢 산수
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">➗</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 산수 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/arithmetic.jpg 에 추가해주세요</p>
</div>

## 산수 과목 소개
{: .text-delta }

산수는 수와 연산, 도형, 측정 등을 배우는 교과입니다. 1985년 국민학교 시절, 산수 시간에는 곱셈구구를 외우고, 분수와 소수를 배우며, 도형의 넓이와 부피를 계산했습니다.

### 이 카테고리의 역할

- **수학과 논리**: 수학 개념, 알고리즘, 논리적 사고에 관한 글
- **프로그래밍**: 코딩, 알고리즘 구현, 문제 해결 방법
- **데이터 분석**: 통계, 데이터 시각화, 분석 기법
- **컴퓨팅 사고**: 계산적 사고, 문제 분해, 패턴 인식

### 특징

당시 산수 교과서는 알록달록한 그림과 함께 실생활 문제를 다뤘습니다. 주판으로 계산을 배우고, 모눈종이에 도형을 그리며, 문장제 문제를 풀던 기억이 납니다. "철수와 영희가 사과를 나누어 먹습니다"로 시작하는 문제들이 가득했죠.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.arithmetic %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.arithmetic.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
