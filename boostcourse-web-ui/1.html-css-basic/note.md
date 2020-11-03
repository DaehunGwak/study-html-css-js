# 1. HTML & CSS 기초 노트

- [1. HTML & CSS 기초 노트](#1-html--css-기초-노트)
  - [2. HTML 태그](#2-html-태그)
    - [5) 의미가 없는 컨테이너 요소](#5-의미가-없는-컨테이너-요소)
    - [7) 이미지 요소](#7-이미지-요소)
    - [References](#references)

## 2. HTML 태그

### 5) 의미가 없는 컨테이너 요소

- 별다른 의미없이 다른 목적으로 필요할 때 사용
  - `<div>`: block-level
    - block?
      - 한 공간 width를 다 차지
  - `<span>`: inline-level
    - inline?
      - 블록 요소안에 주로 많이들어가고
      - 컨텐츠 만큼만 차지
      - Ex. span, b, i, u, s
    - 이후 css에서 잘 알게 될 예정

### 7) 이미지 요소

- image태그의 alt 속성은 `접근성` 측면에서 매우중요
  - alt: 이미지 설명 영역
  - 시작 장애인 전용 스크립트 리더기는 alt영역을 읽어줌
  - width, height를 고정시켜주는게 성능적인 측면에서 더 좋음?
    - 미리 width, height 를 알고있으면 image를 받기 전 해당 영역을 미리 확보하여 다시 렌더링하는 비용을 줄일 수 있음

### References

- [img 태그에 width height 속성이 필요한 이유](http://blog.wystan.net/2007/08/01/img-tag-with-width-and-height)

