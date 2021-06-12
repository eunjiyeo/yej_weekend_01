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
<a href="http://www.naver.com">href</a>
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
> 
