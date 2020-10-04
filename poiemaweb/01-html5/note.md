# HTML5 파트 요약

## 1.2 HTML5 Introduction & Syntax

### 1. HTML5

- HTML (Hypertext Markup Language) : 웹페이지를 기술하기 위한 마크업 언어
- 웹 페이지의 내용(content)과 구조(structure)를 담당
- HTML 태그를 통해 정보를 구조화
- `.html` 확장자를 가짐

### 2. Hello HTML5

```html
<!DOCTYPE html> <!--해당 문서는 html5 입니다 를 알림-->
<html> <!--HTML Document 시작-->
  <head> <!--해당 문서 설정 요소-->
    <meta charset="utf-8">
    <title>Hello World</title>
  </head>
  <body> <!--웹브라우저에 노출(출력)되는 모든 요소-->
    <h1>Hello World</h1>
    <p>안녕하세요! HTML5</p>
  </body>
</html>
```

### 3. HTML5 기본 문법

#### 3.1. 요소 (Element)

- HTML document = set of Elements
- 대소문자 구별은 하지 않으나 소문자 권장
- 구조: start tag + content + end tag

```html
<!--예시-->
<p>Hello</p>
```

content 를 가질 수 없는 빈 태그들 도 있음

```html
<meta charset="utf-8">
```

#### 3.2. 속성 (Attribute)

- 요소의 성질, 특징을 정의하는 명세
- 아래의 `src` `width` `height` 에 해당

```html
<img src="html.jpg" width="104" height="142">
```

- 모든 태그에 적용할 수 있는 Global Attribute가 있음
  - 자주 사용되는 글로벌 속성: id, class, hidden, lang, style, tabindex, title

#### 3.3 주속 (Comments)

```html
<!--주석은 화면에 표시되지 않는다.-->
```

## 1.3 Semantic Web

> 시맨틱 요소와 검색 엔진

### 시맨틱 웹 (Semanctic Web)

- 각 검색엔진은 HTML 문서 수집을 위한 `크롤링`작업을 함
- 이때, 검색 사용자가 이용할만한 검색 키워드에 대응하여 해당 문서를 `인덱싱` 함
- 인덱스를 생설할 때 사용되는 정보는 HTML 코드
- 이때, 주로 `시맨틱 요소(Semantic element)`를 해석함

```html
<!--기능은 하지만 의도 불명확-->
<font size="6"><b>Hello</b></font>

<!--Semantic Element-->
<!--header 1 이라는 의미가 명확해 짐-->
<h1>Hello</h1>
```

- 위와 같은 h1 태그는 `개발자가 의도한 요소의 의미를 명확히 드러내고, 가독성과 유지보수성을 높임`
  
#### 시맨틱 태그란

브라우저, 검색엔진, 개발자 모두에게 콘텐츠의 의미를 명확히 설명하는 역할

#### 시맨틱 웹이란

웹에 존재하는 수많은 웹페이지들에게 Metadata를 부여하여, 기존의 잡다한 데이터 집합이었던 웹페이지를 '의미'와 '관련성'을 가지는 거대한 데이터베이스로 구축하고자 하는 발상

#### HTML Element 구분

- non-semantic tag
  - div, span 등 content에 대한 설명 X
- semantic tag
  - form, table, img 등 content에 대한 설명을 함

> [본 강의 페이지](https://poiemaweb.com/html5-semantic-web)에서 HTML5에 추가된 시맨틱 태그를 확인하시길 바람

## 1.4 HTML5 Tag - Basic

