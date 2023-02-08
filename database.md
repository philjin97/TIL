## Why Database?
#### Data - 저장이나 처리에 효율적인 형태로 변환된 정보
#### 데이터 저장방식 (과거) - 파일, 스프레드 시트
#### 파일 - 쉽게 사용 가능 / But 구조적으로 관리 어려움
#### 스프레드 시트 - 구조적으로 관리 가능 /But 크기, 보안, 정확성
<br/>

## What is Database?
#### Organized collection of data (데이터를 저장하고 조작)
#### CRUD - Create, Read, Update, Delete
</br>

## Relational Database
#### 관계형 데이터베이스 - 데이터 간에 관계가 있는 데이터 항목들의 모음
#### 관계 - 여러 테이블 간의 (논리적) 연결
#### 이 관계로 인해 두 테이블을 사용하여 데이터를 다양한 형식으로 조회할 수 있음. 
<br/>

### 용어
#### 1. Table (relation) - 데이터를 기록하는 곳
#### 2. Field (column, attribute) - 각 필드에 고유한 데이터가 지정됨
#### 3. Record (row, tuple)
#### 4. Database (schema)
#### 5. Primary Key (기본 키) - 각 레코드의 고유한 값
#### 6. Foreign Key (외래 키) - 각 레코드에서 다른 테이블 간의 관계를 만드는 데 사용
<br/>

## RDBMS
#### DBMS - Database Management System
#### RDBMS - Relational Database Management System
#### 대표적인 RDBMS - MySQL, PostgreSQL, Oracle Database, etc.
#### Table은 데이터를 기록하는 최종 위치. 
#### 모든 Table에는 기본 키가는 속성이 있음, 외래 키를 사용하여 각 행에서 서로 다른 테이블 간의 관계를 만들 수 있음.
#### 데이터는 기본 키 또는 외래 키를 통해 결합 될 수 있는 여러 테이블에 결처 구조화 됨. 
#### 각 Table은 Database로 그룹핑됨
#### MySQL은 이러한 Database들을 그룹핑하여 관련된 작업을 수행하는 Database Server

