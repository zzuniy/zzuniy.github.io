---
title: "Chirpy 마크다운 예시 포스트"
date: 2026-03-06
categories: [Tutorial, Markdown]
tags: [Chirpy, Markdown, TOC]
toc: true
comments: true
---

# Chirpy 마크다운 예시 포스트

안녕하세요! 이 글은 Chirpy 블로그에서 사용할 수 있는 **마크다운 기능**을 모두 담은 예시 포스트입니다.

## 텍스트 스타일

굵게, 기울임, 취소선 등:

- **굵게**
- *기울임*
- ~~취소선~~
- `인라인 코드`

## 제목과 목록

### 순서 없는 목록

- 항목 1
- 항목 2
  - 하위 항목
- 항목 3

### 순서 있는 목록

1. 첫 번째
2. 두 번째
   1. 서브
3. 세 번째

## 링크와 이미지

### 링크

[GitHub 바로가기](https://github.com)

### 이미지

![샘플 이미지](/assets/images/sample.jpg)

> 이미지는 `/assets/images/` 폴더에 넣는 것이 권장됩니다.

## 코드 블록

### 인라인 코드

``인라인 코드`` 예시

### 여러 줄 코드

```python
def hello():
    print("Hello, Chirpy!")
