마크다운 사용법(문법)
=====================

헤더 Headers
------------

-	큰제목: 문서제목

	```
	This is an H1
	==============
	```

	This is an H1
	=============

-	작은제목: 문서 부제목

	```
	This is an H2
	-------------
	```

	This is an H2
	-------------

-	글머리: 1~6까지만 지원

	```
	# This is a H1
	## This is a H2
	### This is a H3
	#### This is a H4
	##### This is a H5
	###### This is a H6
	```

	This is a H1
	============

	This is a H2
	------------

	### This is a H3

	#### This is a H4

	##### This is a H5

	###### This is a H6

BlockQuote
----------

이메일에서 사용하는 `>` 블럭인용문자를 이용한다.

```
> This is a blockqute.
```

> This is a BlockQute.
>
> > This is a blockqute.
> >
> > > This is a blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.

> This is a H3
>
> -	List `code`

##목록* 순서있는 목록(번호)

```
1. 첫번째
2. 두번째
3. 세번째
```

1.	첫번째
2.	두번째
3.	세번째

현재까지는 어떤 번호를 입력해도 순서는 내림차순으로 정의된다.

-	순서없는 목록(글머리 번호)

```
* 빨강
  * 녹색
    * 파랑

+ 빨강
  + 녹색
    + 파랑

- 빨강
  - 녹색
    - 파랑
```

-	빨강

	-	녹색

		-	파랑

-	빨강

	-	녹색
		-	파랑

-	빨강

	-	녹색
		-	파랑

코드 `<pre><code></code></pre>`
-------------------------------

4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지 변환이 계속된다.

```
This is a normal paragraph:

  This is a code block.
end codeblock.
```

실제로 적용해보면, This is a normal paragraph:

수평선 `<hr/>`
--------------

아래 줄은 모두 수평선을 만든다. 마크다운 문서를 미리보기로 출력할 때 페이지 나누기 용도로 많이 사용한다.

```
* * *
***
*****
- - -
--------------------------------------
```

링크
----

-	참조링크  

```
[link keyword][id]


Link: [Google](googlelink)

```

Link: [Google](https://google.com)

-	자동연결

```
  <http://example.com/>
  <address@example.com>
```

http://example.com/address@example.com

강조
----

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~
```

*single asterisks* *single underscores* **double asterisks** **double underscores** ++underline++ ~~cancelline~~

이미지
------

```
  ![Alt text](/path/to/img.jpg)
  ![Alt text](/path/to/img.jpg "Optional title")
```

![Alt text](/path/to/crystal.png)  
![Alt text](/path/to/crystal.png)
