---
title:  "Python_Idexing, Slicing (str Data Type)"
header:
  teaser: "https://miro.medium.com/max/2646/1*GokwxHxq5I-Myy3_ummrtw.png"
categories: 
  - Jekyll
  - Minimal mistake
  - Python
tags:
  - Text sequence
  - Data Type
  - 문자열
  - 데이터타입
  - str
  - Idexing
  - Slicing
---



오늘은 `파이썬`의 `문자열` 의 Idexing 과 Slicing을 알아보겠습니다.

Indexing #문자열에 번호에 해당하는 문자를 추출하려면?? 
python은 배열이 존재 하지 않아요! 하지만 다른언어에서는 - index 사용가능합니다.
그렇다면 파이썬의 문자열에서 번호 혹은 순서에 맞는 문자를 추출하기 위해서는 어떻게 해야할까요 ?

하기 그림은 문자열에 해당되는 번호를 명시한 그림입니다. 

<figure>
	<img src="/assets/image/index_table.png">
</figure>

그렇다면 그림에 해당하는 번호를 파이썬 코드로 구현해볼까요?

``` python
my_var = 'HELLO'
print(my_var[1])  #E
```

Slicing #문자열에 범위를 선정하여 추출하려면??
Slicing은 말 그대로 잘라내다입니다. Indexing과의 차이점은 번호가 아닌 범위로 문자열을 추출이 가능합니다.
하기 예제를 확인하면서 익혀보도록 하겠습니다.

``` python
my_var = 'HELLO'
print(my_var[0:3]) #HEL
print(my_var[0:]) #HELLO
print(my_var[0:-1]) #HELL
print(my_var[-2:]) #LO
print(my_var[:]) # HELLO

```

오늘은 파이썬의 Indexing과 Slicing에 대하여 알아보았습니다.