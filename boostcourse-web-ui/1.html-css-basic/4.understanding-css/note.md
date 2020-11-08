# 3. CSS 이해하기

## 1) CSS 소개

- CSS: Cascading Style Sheets
- HTML 을 꾸며주는 언어

## 2) CSS 문법과 적용

### CSS 구성

```css
h1 {
  color: yellow;
  font-size: 2em;
}
```

- 선택자(selector): `h1`
  - 어느 요소를 꾸밀건지
- 속성(property): `color`, `font-size`
- 값(value): `yellow`, `2em`
- 선언(declaration): `property: value;`
- 선언부(declaration block): `{}`
- 규칙(rule set): 이런 선언부 집합

### 주석

```css
/* 내용 */
/*
  내용
  여러줄
*/
```

### CSS 적용방식

- inline
  - `<div style="...">내용</div>`
- internal
  - `<style>...</style>`
- external
  - 외부 파일로
  - `<link rel="stylesheet" href="css/style.css">`
- @import
  - `@import url("./normalize.css");`
  - import를 사용했을 때, css를 병렬적으로 다운로드하지 못하기 때문에 로드시간이 늘어날 수 있다.
  - 따라서 css 파일간 디펜던시는 없어야함
  - ref: [TOAST UI blog: 성능 최적화](https://ui.toast.com/fe-guide/ko_PERFORMANCE#%EB%B8%94%EB%A1%9D-%EB%A6%AC%EC%86%8C%EC%8A%A4css-%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%B5%9C%EC%A0%81%ED%99%94)