# CSS

- CSS: Cascading Style Sheets
- CSS는 HTML의 각 요소의 style을 정의하여 Screen 등에 어떻게 렌더링하면 되는지 브라우저에 설명하기 위한 언어

```css
p {
  color: orange;
  font-size: 10px;
}
```

## 1. Selector, 선택자

- 스타일을 적용하고자 하는 HTML 요소를 선택할 수 있게 함
- 위의 `p` 영역이 선택자 영역

## 2. Property, 속성

- 요소 선택 후 {} 내 Property 지정으로 다양한 스타일 정의 가능
- 표준 스펙으로 지정되어 있는 것만 가능
- 위의 `color` `font-size` 영역이 속성 영역

## 3. Value, 속성값

- "키워드", "크기 단위", "색상 표현 단위" 등, 특정 단위로 지정되는 속성값

## 4. html css 연동

> 예제 참고

## 5. Reset CSS 사용하기

- 모든 웹 브라우저엔 디폴트 스타일이 존재
- 하지만 브라우저마다 상이
- Reset CSS 는 기본적인 HTML 요소의 CSS를 초기화 하는데 사용

### 자주 사용되는 Reset CSS

- [Eric Meyer's reset](http://meyerweb.com/eric/tools/css/reset/)
- [normalize.css](https://necolas.github.io/normalize.css/)
