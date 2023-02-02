#### 리스트 - Stack, Queue, Heap
#### 해시 - set, dictionary

## 이차원 리스트 
#### 리스트를 원소로 가지는 리스트
#### 이차원 리스트는 행렬이다. 
##### Youtube: *3blue1brown linear algebra*
#### matrix = [list(map(int, input().split())) for _ in range(3)]
#### =>
#### for _ in range(n):
####    line = list(map(int, input().split()))
####    matrix.append(line)
<br/>

'''
import sys
sys.stdin = open("input.txt")
'''
#### 파일 입력으로 받기 
<br/>

'''
from collections import dequeue

a = [1, 2, 3, 4, 5]
d = dequeue(a)
d.rotate(2)
print(d)
'''
<br/>

'''
matrix = [
    [1, 2, 3, 4],
    [5, 6, 7, 8],
    [9, 0, 1, 2]
]

for i in range(3):
    for j in range(4):
        print(matrix[i][j], end=' ')
    print()
'''
#### 행: len(matrix), 열: len(matrix[0])
<br/>

'''
count = 0
for i in range(N):
    for j in range(M):
        count += matrix[i][j]
'''
#### or 
'''
count = 0
for elem in matrix:
    count += sum(elem)
print(count)
'''
#### or 
'''
print(sum(map(sum, matrix)))
'''
<br/>

#### 전치/ Transpose
#### *transposed_matrix[i][j] = matrix[j][i]*
<br/>

'''

grid = [
    [0,0],
    [0,1],
    [1,0],
    [0,0],
    [0,1]
]

m = 5
n = 2

for x in range(n):
    for y in reversed(range(m)):
        if grid[y][x] == 1:
            while True:
                if grid[y+1][x] == 1:
                    break
                grid[y][x] = 0
                grid[y+1][x] = 1

                move_dis += 1

                y += 1 

def pprint(arr):
    for a in arr:
        print(*a)

pprint(grid)
print(move_dis)
'''
                


