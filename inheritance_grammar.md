# Inheritance 
<br/>

#### What is inheritance? To set the relationship between a parent and a child.
#### *issubclass(class, classinfo)* -> If class is a subclass of classinfo, then True. 
#### *super()* -> When you want to use a parent class in a child class. ex) super().__init__(name, age, number, email)
#### Can use a method from another class. 
#### Redefine a method from an inherited class by rewriting the function. 
<br/>

# Advanced Grammar
<br/>

#### Conditional Expression -> <true인 경우 값> if <expression> else <false인 경우 값> ex) value = num if num >= 0 else -num
#### List Comprehension -> [<expression> for <변수> in <iterable> if <조건식>] ex) [number**3 for number in range(1,4)]
#### Dictionary Comprehension -> {key: value for <변수> in <iterable> if <조건식>} ex) {number: number**3 for number in range(1, 4)}
#### lambda [parameter]: 표현식 -> 굳이 다른 함수를 정의해서 사용 안해도 됨 (ex) map 함수)