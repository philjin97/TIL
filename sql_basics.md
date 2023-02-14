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
<br/>

#### Filtering data
#### Distinct clause (조회 결과에서 중복된 결과를 제거)
#### SELECT DISTINCT lastName FROM employees ORDER BY lastName;
#### WHERE clause (조회 시 특정 검색 조건을 지정)
#### SELECT lastName, firstName, jobTitle FROM employees WHERE jobTitle != 'Sales Rep';
#### SELECT lastName, firstName, officeCode FROM employees WHERE officeCode BETWEEN 1 AND 4;
#### SELECT lastName, firstName, officeCode FROM employees WHERE officeCode IN (1, 3, 4);
#### SELECT lastName, firstName FROM employees WHERE lastName LIKE '%son';
#### SELECT lastName, firstName FROM employees WHERE firstName LIKE '___y';
<br/>

#### LIMIT clause (조회하는 레코드 수를 제한)
#### SELECT select_list FROM table_name LIMIT [offset,] row_count;
#### SELECT firstName, officeCode FROM employees ORDER BY officeCode DESC LIMIT 3, 5;
<br/>

#### GROUP BY clause (레코드를 그룹화하여 요약본 생성 with 집계 함수)
#### SELECT jobTitle, COUNT(*) FROM employees GROUP BY jobTitle;
#### SELECT country, AVG(creditLimit) AS avgOfCreditLimit FROM customers GROUP BY country ORDER BY avgOfCreditLimit DESC;
#### SELECT country, AVG(creditLimit) FROM customers GROUP BY country HAVING AVG(creditLimit) > 80000;



