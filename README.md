# frontend

## 참고링크

https://www.w3schools.com/

https://codesandbox.io/

https://github.com/edu-ministori/frontend_08

https://www.dbcut.com/bbs/index.php

https://codesandbox.io/s/itac-08-0ye9v?file=/index.html

https://codesandbox.io/s/itac-08-0ye9v?file=/index.html

## HTML

### Introduction

https://www.w3schools.com/html/html_intro.asp

> 웹 페이지 구조 표시

> 웹 페이지 콘텐츠 표시
>
> - 텍스트 콘텐츠
> - 멀티미디어 콘텐츠 : 이미지, 비디오, 오디오

### HTML Element

https://www.w3schools.com/html/html_elements.asp

` (backtick)

```
<tagname>Contents</tagname>

* 시작태그만 있는 경우 : Empty Element
```

> 포함관계(nested)

```
<html>
  <body>
    <h1>Heading</h1>
  </body>
</html>
```

> html-body-h1 관계
>
> html : body와 관계 - 부모요소/ h1과 관계 - 조상요소
>
> body : h1과 관계 - 부모요소/ html과 관계 - 자식요소
>
> hl : body와 관계 - 자식요소/ html과 관계 - 자손요소

### HTML Attribute

https://www.w3schools.com/html/html_attributes.asp

### HTML Headings

https://www.w3schools.com/html/html_headings.asp

h1~h6 : 제목태그(h -> heading)

### HTML Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

### HTML Link

https://www.w3schools.com/html/html_links.asp

a : anchor

> URL(Uniform Resource Locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(Internet Protocol) : 숫자로 구성된 주소(192.168.0.1)
> - Domain Name : www.naver.com / DNS(Domain Name Server)
> - ex) blog.naver.com/blog/12345 => URL

### HTML File 경로

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 표시 기준의 변경 여부
- 절대 경로 방식
- ex) 대한민국 서울특별시 서초구 ~동 대호빌딩 803호
- 출발지 위치에 상관없이 항상 찾아갈 수 있도록 표시
- ex) 도메인 주소/상세경로 => https://www.naver.com/blog/image.jpg
-
- 상대 경로 방식
- ex) 강남역 11번 출구에서 3분 대호빌딩
- 출발지 위치를 기준으로 표시
- ex) 상세경로 => /blog/image.jpg || image.jpg

### HTML List

https://www.w3schools.com/html/html_lists.asp

> 중첩목록(Nested List)

### HTML Table

https://www.w3schools.com/html/html_tables.asp

Table Generator : https://www.tablesgenerator.com/html_tables

### HTML Images

https://www.w3schools.com/html/html_images.asp

alt : alternative

### HTML Video

https://www.w3schools.com/html/html5_video.asp

### HTML Youtube

https://www.w3schools.com/html/html_youtube.asp

### HTML Paragraph

https://www.w3schools.com/html/html_paragraphs.asp

### HTML Link

https://www.w3schools.com/html/html_links.asp

a : anchor

> URL(Uniform Resource Locator) : 파일식별자(위치표시), 가장 넓은 의미의 인터넷 주소
> 인터넷 주소
>
> - IP(Internet Protocol) : 숫자로 구성된 주소(192.168.0.1)
> - Domain Name : www.naver.com / DNS(Domain Name Server)
> - ex) blog.naver.com/blog/12345 => URL

### HTML File 경로

https://www.w3schools.com/html/html_filepaths.asp

절대 vs 상대

- 경로 위치 표시 방식
- 경로 위치 표시 방식
- 경로 표시 기준의 변경 여부
- 절대 경로 방식
- ex) 대한민국 서울특별시 서초구 ~동 대호빌딩 803호
- 출발지 위치에 상관없이 항상 찾아갈 수 있도록 표시
- ex) 도메인 주소/상세경로 => https://www.naver.com/blog/image.jpg
-

* 상대 경로 방식
* ex) 강남역 11번 출구에서 3분 대호빌딩
* 출발지 위치를 기준으로 표시
* ex) 상세경로 => /blog/image.jpg || image.jpg

### HTML List

> 중첩목록(Nested List)

### HTML Table

https://www.w3schools.com/html/html_tables.asp

Table Generator : https://www.tablesgenerator.com/html_tables

### HTML Images

https://www.w3schools.com/html/html_images.asp

alt : alternative

### HTML Video

https://www.w3schools.com/html/html5_video.asp

### HTML Youtube

https://www.w3schools.com/html/html_youtube.asp

### HTML Block & Inline

https://www.w3schools.com/html/html_blocks.asp

> 영역의 특성
>
> - 블럭요소 : 가로길이 - 부모요소에 채워짐 / 세로길이 - 자식요소에 맞춰짐
> - 인라인 요소 : 가로길이와 세로길이 모두 자식요소에 맞춰짐

> 포함관계
>
> - 블럭요소 : 다른 블럭요소, 인라인 요소, 콘텐츠 포함 가능
> - 인라인 요소: 다른 인라인 요소, 콘텐츠 포함 가능, 블럭 요소는 포함 불가능

> - 예외: a - 인라인 요소이지만 블럭 요소 포함 가능

### HTML Id & Class

https://www.w3schools.com/html/html_id.asp

https://www.w3schools.com/html/html_classes.asp

> id attribute
>
> - id로 붙여주는 이름은 한 HTML 문서 내에서 고유해야 함 (한번만 사용)
> - id는 한 대상의 HTML Element에 하나의 이름만 지정할 수 있음

> class attribute
>
> - class로 붙여주는 이름은 한 HTML 문서 내에서 여러번 중복 사용할 수 있음

### CSS 상속

> 부모요소에 적용된 CSS 속성이 자식요소에 적용되는것

### CSS Text

https://www.w3schools.com/css/css_text.asp

> - color
> - text-align
> - text-decoration
> - letter-spacing
> - line-height

### CSS Font

https://www.w3schools.com/css/css_font.asp

> Web Font

> 웹에서 사용하는 폰트는 브라우저에서 랜더링되기 때문에 기존에는 사용자 PC에 설치되어 있는 폰트를 사용
>
> 사용자 PC에 설치된 폰트를 찾지 않고 서버에 폰트를 저장해서 사용하는 방식 => 웹폰트 방식
>
> 웹폰트 서비스
>
> - 구글 폰트 (영문/한글) : https://fonts.google.com/
> - 눈누 폰트 (한글) : https://noonnu.cc/

> font-family
>
> - 항상 폰트 목록 끝에 기본 폰트 이름을 입력해야 함
> - 고딕 : sans-serif / 명조 : serif
>
> font-size
>
> font-style : italic
>
> font-weight
>
> - 100, 200, 300 ... : 숫자로 표시

### Box Model

https://www.w3schools.com/css/css_boxmodel.asp

> - content(width/height) : 콘텐츠의 너비 또는 높이
> - padding : 안쪽 여백
> - boarder : 테두리
> - margin : 바깥 여백

### Height/ Width

> - 블럭요소의 가로길이/세로길이 적용시
> - auto : 요소의 기본 특성을 따라 감 / default 값 : 적용하지 않은 상태와 같음
> - px : px 값으로 고정
> - % : 부모요소를 기준으로 특정 비율만큼 설정
> - 인라인 요소에 가로길이/세로길이는 적용되지 않음

### padding

> - padding-top / padding-right / padding-bottom / padding-left
> - padding : 10px 20px 30px 40px;
> - padding : 10px 20px 30px;
> - padding : 10px 20px;
> - padding : 10px;

### margin

> 마진 겹침 : 박스가 상하배치 되어있을 때 사이 마진이 한쪽만 적용되는 현상
>
> - 두 박스 모두 마진 적용 하지 않고 한쪽에만 마진을 적용

### Border

> border: 1px solid red;
>
> border-top / border-right / border-bottom / border-left

### Background

https://www.w3schools.com/css/css_background.asp

> background-color
>
> background-image:url()

### Color 표현방식

> RGB : Red Green Blue - 가산혼합
>
> - 스크린에서 color 표현
>
> CMYK : Cyan Magenta Yellow Black - 감산혼합
>
> - 프린터에서 color 표현

> color 코드 값
>
> - 10진수 표현 : rgb(255, 255, 255)
> - 16진수 표현 : #1a9cf0

### box-sizing

> box-sizing:border-box => width/height가 박스의 전체 길이가 됨
