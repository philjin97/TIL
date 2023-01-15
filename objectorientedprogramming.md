# Procedural Programming vs. Object Oriented Programming
<br/>

#### Change of data and functions vs. Division based on abstract concepts
<br/>

## Example of PP
```
def area(x, y):
    return x * y

def circumference(x, y):
    return 2 * (x + y)

a = 10
b = 30
c = 300
d = 20

square1_area = area(a, b)
square1_circumference = area(a, b)
square2_area = area(c, d)
square2_circumference = area(c, d)
```
<br/>

## Example of OOP
``` 
class Rectangle:
    def __init__ (self, x, y): 
        self.x = x
        self.y = y

    def area(self):
        return self.x * self.y

    def circumference(self):
        return 2 * (self.x + self.y)

r1 = Rectangle(10, 30)
r1.area()
r1.circumference()

r2 = Rectangle(300, 20)
r2.area()
r2.circumference()
```
<br/>
