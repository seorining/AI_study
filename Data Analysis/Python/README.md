# 알아두면 좋은 파이썬 문법

## 목차
1. [몫과 나머지를 함께 구하기](#1.-몫과-나머지를-함께-구하기)
2. [조건식에서 False로 취급하는 것들](#2.-조건식에서-False로-취급하는-것들)
3. 실수 오차(rounding error)
4. 단락 평가 (short-circuit evalution)
5. escape sequence
6. slice 객체 사용하기
7. 딕셔너리
8. 리스트 응용
9. 문자열 응용
10. 간단한 세트 문법
11. 일급 객체 & 클로저
12. 데코레이터 (staticmethod, classmethod, abstractmethod...)


## 1. 몫과 나머지를 함께 구하기

- 몫과 나머지를 함께 구하려면 divmod를 사용
```
>>> divmode(5, 2)
(2, 1)
```

- 2진수, 8진수, 16진수 나타내기
```
>>>0b110
6

>>> 0o10
8

>>> 0xF
15
```


## 2. 조건식에서 False로 취급하는 것들
```
None
False
0, 0.0, 0j
'', "", [], (), {}, set()
```