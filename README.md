# Git_Tutorial 
## 1. Title_Tutorial(Headers 헤더)
`깃(Git)`에서 `마크다운(Markdown)`을 어떻게 사용하는 지에 대한 나를 위한 정리이다.

본 Title에 대한 글씨 크기는 `#`을 통해 조정할 수 있다.

`#~######(6개)`까지 사용가능하며,

`#`이 많을 수록 크기가 작아진다.
```
# Title 부(parts)에 사용
## Title 장(chapters)에 사용
### Title 페이지 섹션에 사용
#### Title 하위 섹션에 사용
##### Title 하위 섹션 아래의 하위 섹션에 사용
###### Title 문단에 사용
```
* * * 
## 2. Subtitle_Tutorial(또는 인용문)
>## 인용
>>## 인용
>>>## 인용
`>`표시를 통해 타이틀 앞에 `굵은 선`을 추가할 수 있다.
```
> 인용
>> 인용
>>> 인용
```

## 3. Line_Tutorial
* * *
`* * *`을 삽입하며 `큰 줄`을 본문에 삽입할 수 있다.

* * *

## 4. Picture_Tutorial
`사진 첨부`에 관한 내용이다.

#### 1. issue에 첨부할 사진을 업로드 후 생성되는 `링크(Url,Web address)를 Git에 첨부`하거나.

#### 2. Copy link를 통해 얻은 Url을 `"![이미지설명](Url)"` 형식으로 직접 첨부한다.

#### 3. 이미지의 사이즈를 변경하기 위해서는 `<img width="OOOpx" height="OOOpx"></img>`와 같이 표현합니다.


>### 1번 방식
![image1](https://user-images.githubusercontent.com/50895677/140864400-beac9f5b-a92b-405d-8249-b519efdb9294.png)


>### 2번 방식
![image2](https://user-images.githubusercontent.com/50895677/140864460-44930060-6077-4d25-8d68-8c3e43394bf9.png)

* * *
## 5. MainText_Tutorial
본문 기술에 사용하는 `마크다운(Markdown)` 형식이다.

### 5-1. 코드설명
본문에 `코드 삽입`은 

#### 1. \`\`\`을 코드 위 아래로 감싸주면 된다.
#### 2. `공백 4칸`을 띄우고 첨부한다.
#### 3. `~~~`을 코드 위 아래로 감싸주면 된다.
```
    4 space
~~~
Code Block
~~~
```

### 5-2. 강조
* 기울여 쓰기(italic) : `*` 또는 `_`로 감싼 텍스트.
* 두껍게 쓰기(bold) : `**` 또는 `__`로 감싼 텍스트.
* 취소선 : `~~`로 감싼 텍스트.
* 이탤릭체와 두껍게를 같이 사용할 수 있다.

## 5. List_Tutorial

### 5-1. Unordered lists 순서가 없는 목록
`*`, `+`, `-` 를 이용해서 `순서가 없는 목록`을 만들 수 있다.
들여쓰기를 하면 모양이 바뀐다.

### 5-2. Ordered lists 순서가 있는 목록
`숫자를 기입`하면 `순서가 있는 목록`이 된다.
`들여쓰기`를 하면 모양이 바다.
```
Syntax 마크다운 사용법
* Item 1
* Item 2
  * Item 1
  * Item 2
    * Item 1
    * Item 2
 1. Item 1
 2. Item 2
 3. Item 3
   1. Item 1
   2. Item 2
   3. Item 3
     1. Item 1
     2. Item 2
     3. Item 3
 ```
* Item 1
* Item 2
  * Item 1
  * Item 2
    * Item 1
    * Item 2
 1. Item 1
 2. Item 2
 3. Item 3
    1. Item 1
    2. Item 2
    3. Item 3
        1. Item 1
        2. Item 2
        3. Item 3

[타이틀](#1.-title_tutorial(headers-헤더))
