## Set
#### 수학에서의 '집합'을 나타내는 데이터 구조.
#### 데이터의 중복이 없어야 할 때, 정수가 아닌 데이터의 삽입/삭제/탐색이 빈번히 필요할 때. 

'''
S = ['baekjoononlinejudge', 'startlink', 'codeplus', 'sundaycoding', 'codingsh']
words = ['baekjoon', 'codeplus', 'codeminus', 'startlink', 'starlink', 'sundaycoding', 'codingsh', 'codinghs', 'sondaycoding', 'startrink', 'icerink']
cnt = 0

for word in words:
    if word in S: 
        cnt += 1
print(cnt)
cnt = 0

S = set(S)
for word in words:
    if word in S: 
        cnt += 1
print(cnt)

print(len(set(S) & set(words)))
'''