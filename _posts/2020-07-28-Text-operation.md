---
title:  "Python_Text operation (str Data Type)"
header:
  teaser: "/assets/image/Text Operation.png"
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
  - operation
---



문자열의 연산 (문자열, str)
오늘은 `파이썬`의 `문자열` 연산에 대하여 알아보겠습니다. 
일상생활에서 말을 할때 대부분 단일언어로 대화를 하지않습니다. 문자를 조합하거나 합성해서 문장을 만들어 대화를 합니다.
파이썬의 문자열도 마찬가지로 합치거나 원하는 문자열을 추가를 할 수가 있습니다. 자세한 내용은 하기 예제를 통하여 알아보겠습니다.

``` python
first = 'haha'
second = 'hoho'

print(first + second) #hahahoho
print(first + str(10)) # error 자동으로 숫자를 문자로 변경 X ( Java 에서는 가능 합니다 !)
print(first*3) #hahahahahaha

```
상기의 예제는 문자열을 더하거나 곱하여서 새로운 문자열을 생성하는 것을 보았습니다. 

앞으로 프로젝트를 진행하면서 받는 데이터들이 완벽한 문자열 혹은 문자로 받아진다면 저러한 연산은 필요없겠지만 저희가 앞으로 받은 데이터는 예상할 수 없는 데이터이기 때문에 항상 가공을 해야합니다. 문자열의 연산은 앞으로의 프로젝트에서 데이터를 처리하기위한 '첫걸음' 정도로 생각하면 되겠습니다.


오늘은 파이썬의 문자열 연산에 대하여 알아보았습니다.