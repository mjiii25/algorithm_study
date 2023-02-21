
![image](https://user-images.githubusercontent.com/80023660/203708906-ef2e47b2-607b-41b0-ad7f-8b7597b9089a.png)
# 




💻 **풀이로그**

|   날짜   |    문제     |     난이도    |
|:--------:|:-------------:|:-----------:|
| 22/11/23 | 나이출력 | 
| 22/11/23 | 양꼬치 | 
| 22/11/23 | 짝수의합 | 
| 22/11/23 | 피자나눠먹기(3) | 
| 22/11/24 | 배열뒤집기 | 
| 22/11/26 | 특정 문자 제거하기 | 
| 22/11/26 | 문자열 정렬하기(1) | 
| 22/11/30 | 가위 바위 보 | 
| 22/12/03 | 합성수 찾기 | 
| 22/12/03 | 369게임 | 
| 22/12/07 | 진료순서 정하기 | 
| 23/02/21 | 소인수분해 |
| 23/02/21 | 컨트롤 제트 | 



💡 **수학계산**
- 조합 (a 중 b를 고르는 경우의 수)
  - `import math; math.comb(a, b)`
- 팩토리얼
  - `from math import factorial; factorial(n)`
  
  
💡 **if문**
- 한 줄로 정리하기 : `int(s[i]) if s[i] != "Z" else -int(s[i-1])`



💡 **메소드**
- 특정 문자 변경하기
  - `문자열.replace(찾을문자,변경할문자)`
- 숫자형인지 확인하기(T/F)
  - `문자열.isdigit()`
- 사이사이 집어넣기
  - `'*'.join('my_string')` --> `m*y*_*s*t*r*i*n*g`
      - 빈 문자열 안에 넣는 방식으로도 가능!
          - `''.join(d[i] for i in rsp)`
          - `''.join(sorted(my_string.lower()))`
- 대소문자
  - `my_string.lower()`
  - `my_string.upper()`
  - `my_string.islower()`
  - `my_string.isupper()`
  - `my_string.swapcase()`
- 위치/인덱스
  - `my_string.index(찾을문자)`
      - my_string에서 찾을문자의 인덱스를 찾는 것
- 특정 원소 제거하기
  1. `my_string.pop('제거할 문자의 인덱스')`
      - 중복인 값에 대해서는 하나만 제거됨
      - 인덱스를 생략한 경우 가장 마지막 값이 제거됨
  2. `my_string.remove('제거할 문자`)
      - 중복인 값에 대해서는 가장 앞 값이 제거됨



💡 **리스트**
- 역순으로 출력하기
  - `num_lst[::-1]`
- 리스트 + 문자 합칠 경우
  - `my_list + [my_string]`


💡 **딕셔너리**
- value 기준으로 정렬하기
  - `dict(sorted(my_dict.items(), key = lambda x : x[1]))`


💡 **함수**
- lambda 사용하기
  - `map(lambda x : x ** 2, range(5))`
  - `sum(map(lambda x : str(my_string).count(str(x)), [3, 6, 9])`


💡 **집합 (set)**
- 중복값 제거 가능
- 순서 없음 -> 입력한 순서대로 결과값이 출력되는 것은 아님






