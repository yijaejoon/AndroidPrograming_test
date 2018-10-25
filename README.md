# 마크다운 문법

## 1. 제목 Headers

'#'으로 시작하는 텍스트

'#'은 하나부터 여섯개까지 쓸 수 있고, '#'이 늘어날때마다 제목의 수준은 내려간다.
(보통 글씨 크기가 작아진다.)

또는 '-' , '=' 을 이용하여 h1, h2를 쓸 수 있다.

예시) 

# h1

## h2

### h3

#### h4

##### h5

###### h6

h1
===

h2
--

## 2. 인용 Blockquotes

'>'으로 시작하는 텍스트

예시)

> 인용문

>>인용문안의 인용문

## 3. 코드 블럭 Code Blocks

' ``` ' 혹은 ' ~~~ ' 코드 첫 줄과 마지막 줄에 Back quote (')또는 물결(~) 3개 삽입

예시)

```
이것은
코드 블럭
입니다
```


~~~
이것은
코드 블럭
입니다
~~~

~~~C
void f(){
  printf(%s, "이것은 c 코드 입니다.");
}
~~~

## 4. 인라인 코드 Inline Code Blocks

' `(Back quote) ' 로 감싸진 텍스트

예시)

`인라인 코드 블럭` 

## 5. 강조 Emphasis

기울여 쓰기(italic) : ' * ' 또는 ' _ '로 감싼 텍스트
굴게쓰기(bold) : ' ** ' 또는 ' __ '로 감싼 텍스트

예시)

*기울여쓰기(italic)*

_기울여쓰기(italic)_

**굵게쓰기(bold)**

__굵게쓰기(bold)__

## 6. 수평선 Horizontal Rules

'-' 또는 '*' 또는 '_'을 3개 이상 작성
(단, '-'을 사용 할 경우 header로 인식할 수 있으니 이 전 라인은 비워 두어야 한다.)

예시)

---

***

___

