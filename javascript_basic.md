## Basic syntax of Javascript
<br/>

### 변수 
#### let - 재할당 가능, 재선언 불가능 
#### const - 재할당 불가능, 재선언 불가능
#### block scope - if, for, 함수 등의 중괄호 {} 내부. 블록 스코프를 가지는 변수는 블록 바깥에서 접근 불가능 
<br/>

### 데이터 타입 
#### 원시 자료형 (Primitive) - Number, String, Boolean, undefined, null
#### 참조 자료형 (Reference) - Objects
#### Template Literal - (like f-string in python)
#### null / undefined (null은 원시 자료형이지만 object로 출력됨. 버그.)
<br/>

### 연산자 
#### Increment (++), Decrement (--), +=, -=
#### Compare (>, <) -> returns a boolean
#### == -> returns a boolean (type can be different)
#### === -> returns a boolean (even the type has to be the same)
#### and (&&), or (||), not (!)
<br/>

### 조건문 
#### if {} else if {} else {}
### 반복문
#### while, for, for ... in, for ... of
#### for (let i = 0; i < 6; i++>)
#### for (const key in fruits)
#### for (const number of numbers) 
#### => 차이는 for...in 은 "속성 이름"을 통해 반복. for...of 은 "속성 값"을 통해 반복. 