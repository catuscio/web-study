# HTML
> __Hyper Text Markup Language__\
> 웹사이트 표시를 위해 개발된 마크업 언어
하이퍼링크(참조)를 통해 한 문서에서 다른 문서로 즉시 접근이 가능한, 태그들로 구성된 언어

## HTML5의 개선점
- div 남용 -> headr, nav, article, section, aside, footer 등 블럭 요소(cimentic tags) 추가
- 멀티미디어 요소:
  - ActiveX 플러그인 피요 X
  - audio, video, cavas
- 불필요한 태그 제거(dir 등)

## HTML의 구성요소
- HTML 문서는 elements들로 구성됨.
  - element는 태그 한쌍으로 이루어짐 -> 시작태그와 종료태그 사이에는 컨텐츠가 들어감(<p></p>)
  - tag에는 속성이 첨가될 수 있음
  ```html
  <태그 속성1="값1">컨텐츠, 보이는 내용</태그>
  ```

## HTML의 구조
### head
- 웹사이트에 대한 설명이 첨부된 메타데이터
```HTML
<!DDOCTYPE html>
<html lang="en">    <!--최상위 root 요소 html-->
  <head>
      <!--웹문서의 메타데이터 + UI 상으로 보여지지 않는 정보들-->
      <!--SEO(타이틀, 설명, 저자), CSS 스타일/JS링크 -->
    <meta charset="UTF-8" />
      <!--UTF-8 인코딩 문자열 세트-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
      <!--IE9 주소바에 호환성 버튼 안 보이게 하는 코드 / Edge 렌더링 엔진 사용-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <!--사용자의 디바이스(viewport) 크기에 맞게 컨텐츠 표기-->
    <title>Document</title>  <!--웹사이트 제목-->
  </head>
  <body></body>
</html>
```

### body
- 웹사이트의 내용
![image](https://github.com/catuscio/web-study/assets/77739745/74cbcacd-6748-4429-8880-268ae43e0d56)
> 시멘틱 태그들을 이용한 구조적인 구획 구분 필요

## HTML Tags
### element
h1 ~ h6 태그, address, blockquote, __p__, pre, table, ol, ul, a, abbr, audio, b, span, cite, code, data, i, mark 등
### container
__div__, section, articel, header, footer, aside, nav, main 등
---
### block level
h1~h6, address, blockquote, p, pre, table, ol, ul
### inline level
a, abbr, audio, b, span, cite, code, data, i, mark






