## Normalization (정규화)
#### RDB 설계 단계에서 중복을 최소화하여 데이터를 구조화하는 과정
#### 제 1 정규화 - 데이터베이스의 각 필드에는 하나의 값만 저장해야 함. 반복되는 부분을 찾아 테이블을 분할하고 기본키가 될 필드를 작성.
#### 제 2 정규화 - 키 값을 이용해 데이터를 특정 지을 수 있는 것 (함수 종속성)을 찾아 테이블을 분할.
#### 제 3 정규화 - 기본 키 이외의 부분에서 중복이 없는 지를 조사하여 테이블을 분할. 
<br/>

## Data Modeling 
#### 데이터베이스 시스템을 시각적으로 표현하는 프로세스 
#### ER (Entity-Relationship) Diagram - 다이어그램을 사용하여 데이터베이스의 Entity 간 관계를 나타내는 방법 
#### ER Diagram 구성요소 - Entity, Attribute, Relation
#### Relationship 표현 방법 - Cardinality & Optionality 
#### Cardinality (기수) 
#### Optionality (선택 가능성)
#### 회원과 글의 관계는 1:N이며, 글은 필수적으로 회원과 연결되어야 하지만 회원은 선택적으로 글과 연결될 수 있는 관계 
