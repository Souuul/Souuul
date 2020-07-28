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


Idexing, Slicing
오늘은 `파이썬`의 `문자열` 의 Idexing 과 Slicing을 알아보겠습니다.

Indexing #문자열에 번호에 해당하는 문자를 추출하려면?? 
#indexing_python은 배열이 존재 X / 다른언어에서는 - index 사용가능

``` python
my_var = 'HELLO'
print(my_var[1])


```

H	E	L	L	O

0	1	2	3	4

-5	-4	-3	-2	-1


Slicing #문자열에 범위를 선정하여 추출하려면??
Slicing 잘라내는 것( 시작과 끝의 범위를 설정해야함)

``` python
my_var = 'HELLO'
print(my_var[0:3]) #HEL
print(my_var[0:]) #HELLO
print(my_var[0:-1]) #HELL
print(my_var[-2:]) #LO
print(my_var[:]) # HELLO

```




상기 예제를 확인해보면 파이썬에서는 문자와 문자열을 표현할때 `' '` 와 `" "` 을 구분하지않고 사용이 가능합니다.


오늘은 파이썬의 Indexing과 Slicing에 대하여 알아보았습니다.