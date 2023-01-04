# **Input -> X -> Output**
<br/>

## Functions
<br/>
<br/>

#### Basic Functions
##### **print()**
```
print(*objects, sep=' ', end='\n')
```
##### **objects: 은 여러값을 무한하게 받을 수 있다*
##### *sep: 은 어떻게 분리할지*
##### *end: 는 다음 print 라인과 어떻게 이어질지*
<br/>

##### **map(function, iterable)**
```
list(map(str, numbers))
n, m = map(int, input().split())
```
##### map function은 map object라는 type으로 결과가 도출되기 때문에 list 형태로 바꾸어주어야 결과를 볼 수 있다. 
##### " "로 나누어진 입력된 값을 " "를 기준으로 두개로 나눈다음, 각 각 int function으로 type 을 string 에서 integer로 바꾸어준다음, n 과 m이라는 변수에 담는다. 
<br/>

##### **len(s)**
##### 객체의 길이 
<br/>

##### **sum(iterable, start=0)**
##### start와 iterable의 항목들을 왼쪽에서 오른쪽으로 합하고 합계를 돌려줌 
<br/>

##### **max(iterable)**
##### 큰것을 반환
<br/>

##### **min(iterable)**
##### 작은것을 반환
<br/>

##### **abs(x)**
##### 절댓값을 반환
<br/>

##### **divmod(a, b)**
##### 두 수를 받아 몫과 나머지를 반환 
<br/>

##### **pow(base, exp, mod=None)**
##### base의 exp 거듭제곱을 반환
<br/>

##### **round(number, ndigit=None)**
##### number를 소수접 다음에 ndigit 정밀도로 반올림한 값을 반환
<br/>