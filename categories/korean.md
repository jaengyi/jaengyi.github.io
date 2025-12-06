---
layout: default
title: 국어
permalink: /categories/korean/
parent: 교과목
nav_order: 1
---

# 📚 국어
{: .no_toc }

<div style="text-align: center; margin: 2em 0; padding: 2em; background-color: #f5f5f5; border-radius: 8px;">
  <div style="font-size: 4em; margin-bottom: 0.5em;">📖</div>
  <p style="color: #666; font-style: italic;">1985년 국민학교 5학년 국어 교과서</p>
  <p style="font-size: 0.9em; color: #999;">실제 교과서 표지 이미지는 images/textbooks/korean.jpg 에 추가해주세요</p>
</div>

## 국어 과목 소개
{: .text-delta }

국어는 우리말과 글을 바르게 이해하고 표현하는 능력을 기르는 교과입니다. 1985년 국민학교 시절, 국어 시간에는 동화와 시를 읽고, 받아쓰기를 하며, 일기와 편지글을 썼습니다.

### 이 카테고리의 역할

- **언어와 문학**: 한글 맞춤법, 문법, 시와 소설 등 문학 작품 이야기
- **글쓰기**: 블로그 글쓰기, 창작, 표현 기법에 관한 글
- **독서**: 책 리뷰, 독서 경험, 문학 작품 감상
- **의사소통**: 효과적인 소통 방법, 발표와 토론에 관한 이야기

### 특징

당시 국어 교과서는 동시, 동화, 전래동화 등 다양한 장르의 글을 통해 우리말의 아름다움을 배웠습니다. 분필 가루 날리는 교실에서 큰 소리로 교과서를 읽던 낭독 시간, 선생님께서 칠판에 쓰신 글씨를 공책에 옮겨 적던 시간들이 떠오릅니다.

---

## 목차
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## 글 목록

<ul>
  {% for post in site.categories.korean %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="fs-3 text-grey-dk-000"> - {{ post.date | date: "%Y년 %m월 %d일" }}</span>
  </li>
  {% endfor %}
</ul>

{% if site.categories.korean.size == 0 %}
<p>아직 작성된 글이 없습니다.</p>
{% endif %}
