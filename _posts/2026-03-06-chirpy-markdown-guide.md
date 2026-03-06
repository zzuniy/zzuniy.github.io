---
title: "Jekyll Git Blog 마크다운 기능 총정리 - Chirpy 테마"
date: 2026-03-06
categories: [Tutorial, blog]
tags: [chirpy, markdown, blog, gitblog, jekyll]
toc: true
comments: true
image: /assets/images/sample.jpg
---

안녕하세요! 오늘은 **Chirpy 블로그에서 쓸 수 있는 마크다운 기능**을 하나씩 정리하면서 예시와 함께 보여드리려고 합니다.  

저처럼 처음 Chirpy를 접하는 분들도 쉽게 따라 할 수 있도록, **텍스트 스타일, 목록, 링크, 이미지, 코드 블록**까지 모두 담았습니다.

---

## 텍스트 스타일

Chirpy에서 지원하는 기본 텍스트 스타일을 살펴볼게요.

- **굵게** → `**굵게**`
- *기울임* → `*기울임*`
- ~~취소선~~ → `~~취소선~~`
- `인라인 코드` → `` `인라인 코드` ``

> Tip: 블로그 글에서 중요한 키워드를 강조할 때 굵게/기울임을 적절히 섞으면 가독성이 좋아집니다.

---

## 제목과 목록

### 순서 없는 목록

- 항목 1
- 항목 2
  - 하위 항목
- 항목 3

### 순서 있는 목록

1. 첫 번째
2. 두 번째
   1. 서브 항목
3. 세 번째

---

## 링크와 이미지

Chirpy에서는 링크와 이미지를 쉽게 삽입할 수 있습니다.

### 링크

[GitHub 바로가기](https://github.com)  
> 예시 코드: `[GitHub 바로가기](https://profile.com)`

### 이미지

![샘플 이미지](/assets/images/sample.jpg)  
> 이미지는 `/assets/images/` 폴더 안에 넣는 것을 권장합니다.  
> 예시 코드: `![샘플 이미지](/assets/images/sample.jpg)`

---

## 코드 블록

### 인라인 코드

텍스트 중간에 짧은 코드를 삽입할 때:

`print("Hello, Chirpy!")`  
> 예시 코드: `` `print("Hello, Chirpy!")` ``

---
Jekyll의 chirpy 테마  마크다운 작성법을 소개해 드렸습니다. 
도움이  되셨길 바라며, 다음글로 찾아뵙겠습니다! 