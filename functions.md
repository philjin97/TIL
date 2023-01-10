## Functions (사용자 정의 함수)
<br/>

```
def phil():
```
##### Calling a function
<br/>

#### return vs. print (returning a value vs. printing out a value so it is visible)
#### parameter vs. argument (variable used to set the function vs. variable that is used in functions)
<br/>

```
def add(x, y=0, z=0)

add(1, z=3)

def add(*numbers)

def add(**numbers)
```
##### y = 0, z = 0 means when no value is put in, set default value of the variables to 0. 
##### add(x, z=3) means keep the y value as the default value which is 0, and make x = 1 and z = 3. 
##### *numbers mean many values can be put into numbers, and they are saved as tuples.
##### **numbers mean key-value needs to be put in as a set, and are saved as dictionaries. 
<br/>

## Scope of Functions
<br/>

#### Global Scope refers to a variable/function being able to be called from anywhere in the code.
#### Local Scope refers to a variable/function being called within a specific area in the code. 

