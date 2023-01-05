## Modules (Internal Libraries / Packages)
##### *modules are a block of code saved in a .py file to serve a purpose*
<br/>

#### to import an internal library 
```
import random
```

#### **random**
<br/>

##### *random.choice(seq)*
##### gives back a random choice from the objects in the sequence. 
<br/>

##### *random.sample(population, k)*
##### from the sequence *population*, choose *k* number of choices. 
<br/>

##### *random.shuffle(students)*
##### students 안에 있는 것들을 섞어줌 - *list*
<br/>

#### **datetime**
<br/>

##### *import datetime*
##### *print(datetime.datetime.now())* -> 현 날짜/시간을 보여줌.
##### *print(datetime.date(2023, 1, 5))* -> 2023.1.5 를 지정해서 보여줌. 
<br/>

#### **os**
##### os 라이브러리로 컴퓨터도 조작할 수 있음. 
<br/>
<br/>

## Error 종류
<br/>

##### **Syntax Error** 문법에러
<br/>

##### **Exception** ZeroDivisionError, NameError, 등
<br/>

##### **Type Error** 타입 불일치, arguments 부족
<br/>

##### **Value Error** 타입은 올바르나 값이 적절하지 않거나 없는 경우
<br/>

##### **Index Error** list index out of range.
<br/>

##### **Key Error** 존재하지 않는 key.
<br/>

##### **ModuleNotFoundError** 존재하지 않는 모듈 import하는 경우.
<br/>

##### **Import Error** 모듈은 있으나 존재하지않는 클래스/함수를 가져오는 경우.
<br/>

##### **Indentation Error** Indentation이 적절하지 않는 경우. 
<br/>

##### **KeyboardInterrupt** 임의로 프로그램을 종료하였을때. 
<br/>

## 예외 처리 
##### *try/ except 구문. try에서 시도하고 에러가 나면, except 구문을 실행한다.*
##### *raise <표현식> (메세지)* 또는 *assert <표현식>, <메시지>* 로 error을 강제로 발생. <표현식>에서 예외 type 지정. 

