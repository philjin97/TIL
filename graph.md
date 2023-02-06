## Graph
#### Vertex (정점): nodes
#### Edge (간선): 관계(연결)하는 선 
#### Path (경로): 시작 node 부터 도착 node까지 거치는 정점을 나열한 것
#### Adjacency (인접): 두개의 정점이 하나의 간선으로 직접 연결된 상태
<br/>

## 그래프의 종류 
#### 1. Undirected Graph (무방향 그래프) 
#### 간선의 방향이 없음. 
#### 간선을 통해 양방향의 정점 이동 가능 
#### Degree (차수) - 하나의 정점에 연결된 간선의 개수 
#### 모든 정점의 차수의 합 = 간선 수 x 2
<br/>

#### 2. Directed Graph (유방향 그래프)
#### 간선의 방향이 있음. 
#### 간선의 방향이 가리키는 정점으로 이동 가능 
#### Degree (차수) - 진입 차수(In-degree)와 진출 차수(Out-degree)로 나누어짐. 
<br/>

## 그래프의 표현 
#### 1. 인접 행렬 
#### n = 7 (정점 개수), m = 7 (간선 개수)
#### graph = [[0] * n for _ in range(n)]
#### for _ in range(m):
####    v1, v2 = map(int, input().split())
####    graph[v1][v2] = 1
####    graph[v2][v1] = 1
<br/>

#### 2. 인접 리스트 - 리스트를 통해 각 정점에 대한 인접 정점들을 순차적으로 표현 
#### n = 7 (정점 개수), m = 7 (간선 개수)
#### graph = [[] for _ in range(n)]
#### for _ in range(m):
####    v1, v2 = map(int, input().split())
####    graph[v1].append(v2)
####    graph[v2].append(v1)
<br/>

## 인접 행렬 vs 인접 리스트 
#### 인접행렬 = 직관적, 만들기 편함. 하지만 공간 낭비. 
#### 인접 리스트 = 연결된 정점만 저장, 효율적. 
