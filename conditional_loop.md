## 1. Typecasting 
<br/>

#### A. **Implicit Typecasting:**
##### no need to type. Computer automatically changes the type. *float + int -> result in float.*
<br/>

#### B. **Explicit Typecasting:** 
##### need to explicitly change the type of the object. *string + int -> error.*
<br/>

## 2. String Formatting 
#### **String Interpolation**
```
print(f'Hello, {name}')
```
##### An f string is used to replace the {variable} with the object of the variable. 
<br/>

## Control Statement
<br/>

#### **Conditional Statement**
```
if <expression>:
    #run a code
elif <expression>:
    #run a code
else:
    #run a code
```
#### *Nested Conditional*
```
if <expression>:
    if <expression>:
        #run a code
    else:
        #run a code
else:
    #run a code
```
##### if, else statements can exist within each other. 
<br/>

#### **Range**
```
range(4) -> (0,4)
list(range(4)) -> [0, 1, 2, 3]
list(range(4, 0, -1)) -> [4, 3, 2, 1]
```
##### range is used to produce numbers. range(start, stop, step). 
<br/>

## Loop Statements 
<br/>

#### **for statements**
```
for <variable> in <iterable>:
    #run a code
```
##### 반복가능한 객체를 모두 순회하면 종료. 
##### break: 반복을 종료. continue: 다음으로 넘어감. 
<br/>

#### **while statements**
```
targetnumber = input("")
n = 1
result = 0

while n <= targetnumber:
    result += n 
    n += 1
print(result)
```
##### 종료조건에 해당하는 코드를 통해 종료시켜야함. 

