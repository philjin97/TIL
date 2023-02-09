## SQL
#### 데이터베이스에 정보를 저장하고 처리하기 위한 프로그래밍 언어
#### SQL Syntax - SELECT column_name FROM table_name;
<br/>

## SQL Statements
#### Select Statements: SELECT column_name FROM table_name;
#### 유형 - DDL (데이터 정의), DQL (데이터 검색), DML (데이터 조작), DCL (데이터 제어)
<br/>

## 용어 정리
#### Query - 질의, 질문. 데이터베이스로부터 정보를 요청하는 것
#### SQL 표준 - 널리 사용되는 모든 RDBMS에서 SQL 표준을 지원. 
<br/>

## SQL - Single Table Queries 1
## DQL - 데이터 검색 (SELECT)
#### Querying data
#### SELECT select_list FROM table_name;
#### SELECT lastName, firstName FROM employees;
#### SELECT * FROM employees;
#### SELECT firstName AS '이름' FROM employees; (AS -> 필드에 새로운 별칭을 지정)
#### SELECT productCODE, quantityOrdered * priceEach AS '주문 총액' FROM orderdetails; (기본적인 사칙연산 사용 가능)
<br/>

#### Sorting data
#### SELECT firstName FROM employees ORDER BY firstName; 
#### SELECT firstName FROM employees ORDER BY firstName DESC;
#### SELECT firstName, firstName FROM employees ORDER BY firstName DESC, firstName
#### SELECT productCode, quantityOrdered * priceEach AS totalSales FROM orderdetails ORDER BY totalSales DESC;



