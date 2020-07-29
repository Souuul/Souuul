---
title:  "Python_Numeric Data Type"
header:
  teaser: "/assets/image/Numeric.png"
categories: 
  - Jekyll
  - Minimal mistake
  - Python
tags:
  - Numeric
  - Data Type
  - 숫자형
  - 데이터타입
---
Numeric Data Type (숫자형)
오늘은 `파이썬`의 `숫자형` 데이터 타입에 대하여 알아보겠습니다. 
데이터 숫자는 크게 3가지로 나눌 수가 있습니다!
1. int(정수)
2. float(실수)
3. complex(복소수)

하기 예제를 보면서 파이썬의 특징을 알아보겠습니다.
``` python
a = 100 # 정수
b = 3.14159265358979 # 실수
c = 1+ 2j # 복소수
d = 0o34 # 8 진수
e = 0xAB # 16 진수
```
파이썬이 아닌 다른 프로그램언어를 배우신 분이라면 변수선언을 할때 var같은 선언을 하지않고 간편하게 변수를 선언을 할 수 있습니다. 

Type # 데이터 타입에 대하여 알기를 원한다면??
``` python
print (type(a)) # class int
print (type(b)) # class float
print (type(c)) # class complex
print (type(d)) # class int
print (type(e)) # class int
```

Python의 연산의 특징에 대하여 알아보아요!
``` python
my_result = 3 / 4 # 0이 아니라 0.75  프로그래밍에서는 버림으로 표시
print(my_result) # 0.75


my_result = 10 % 3 #나머지 연산자
print(my_result) # 1

my_result = 10 // 3 #몫 연산자
print(my_result) # 3
```

오늘은 파이썬의 숫자형 데이터 타입에 대하여 알아보았습니다.