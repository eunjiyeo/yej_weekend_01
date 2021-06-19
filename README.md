# HTML, CSS, JS 기초 

## HTML

> HTML : Hyper Text Markup Language - 마크업(표시) 언어
> 
> 웹페이지의 구조를 표시
>
> 웹페이지의 콘텐츠를 표시

### HTML Elements

> Element : 요소 - 의미적
> 
> Tag : 태그 - 기술적

> 문법(Syntax)
> 
> <>로 감싸줌
> 
> 소문자 사용
> 
> 시작태그와 종료태그로 구성
```
<tagname>contents</tagname>
```
>
> 예외) 시작태그만 존재하는 경우 : 빈 요소(Empty Element)
> 
> 포함관계(Nested)
```
<body>
  <div>
    김매미 안녕
  </div>
</body>
```

### HTML Attribute

> HTML 속성
> HTML 요소의 부가정보
> 속성이름 = "속성값"


```
<a href="http://www.naver.com">네이</a>
```

### 제목태그


> heading -> h
> h1 ~ h6 "h1이 가장 큰 제목"

### 

```
<!DOCTYPE html> -1
<html> - 2 
  <head> - 3
    <meta charset="utf-8"> -4 
    <title>My test page</title> - 5 
  </head>
  <body> - 6
    <p>This is my page</p>
  </body>
</html>
```

1. 웹 문서의 버전 : HTML5
2. html 문서의 가장 바깥쪽 요소
3. 설명하는 정보가담기는 영역요소
4. 웹문서의 정보 표현
5. 웹문서의 제목을 표시하는 요소(탭)
6. 웹문서의 콘텐츠 요소들이 담기는 영역요소

### 단락 태그

> 단락을 표시
> 단락과 단락 사이를 구분하는 수평선

```
<hr> - Horizontal Rule
```

> 단락을 구분하지 않고 줄 바꿈
```
<br> - Break
```

### 목록태그
> 순서없는 목록ul(unordered list)
> 순서있는목록 ol (ordered list)
> 목록 항목 li(List Item)

```
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>

<ol>
  <li>HTML</li>
  <li>CSS</li>
</ol>
```
> 포함관계(nested)로 구성된 목록 - 코딩할 때 밖에서 안쪽 방향 순서로

- HTML
  - HTML4
  - HTML5
- CSS
  - CSS2
  - CSS3
```
<ul>
 <li>
  HTML
  <ul>
    <li>HTML4</li>
    <li>HTML5</li>
  </ul>
 </li>
 <li>
  CSS
    <li>CSS2</li>
    <li>CSS3</li>
 </li>
</ul>
```


> 설명목록 (description List)-<dl>

```
<dl>
  <dt>HTML</dt> (dt : Description Title)
  <dd>표준 마크업 언어</dd> (dd : Description Data)
</dl>
```
  
> 하이퍼링크 a(anchor)
>
> attribute(속성) : href(Hypertext Reference) : 연결되는 웹 문서의 URL
```
<a href = "http://www.naver.com">네이버로 이동</
```
  
>북마크 기능
>
>외부 페이지 연결이 아닌 같은 페이지에서 특정 위치로 이동할 수 있게 해주는 기능
>
>도착 지점에 id attribute를 사용하여 이름을 지정
```
  <a href="#t1"></a>
```
  <h2 id="t1">제목</h2>
  
### Table Element

> 기본 사용 태그 : table, thead, tbody, tr, th, td
> 열 제목 : thead(table head), th(table heading)
> 표 내용 : tbody(table body), td(table data)
> 행 : tr(table row)
  
### Image element
> Tag : img
> Attribute : src(image 위치, 파일명), alt(대체텍스트)
` : backtick
'''
<img src = "image.jpg" alt = "대체텍스트">
'''

>
>
>
>
>

