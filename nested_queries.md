## Subquery 
#### "A query inside a query" 단일 쿼리문에 여러 테이블의 데이터를 결합하는 방법
#### SELECT MIN(age) FROM table1; DELETE FROM table1 WHERE age = **위에서 찾은 최소값**;
#### =>
#### DELETE FROM table1 WHERE age = **( SELECT MIN(age) FROM table1)**;
<br/>

#### SELECT lastName, firstName, FROM employees WHERE officeCode IN 미국에 있는 사무실 코드 목록;
#### SELECT lastName, firstName FROM employees WHERE officeCode IN (SELECT officeCode FROM offices WHERE country = 'USA'); 
<br/>

## EXISTS operator
#### 쿼리 문에서 반환된 레코드의 존재 여부를 확인
<br/>

## Conditional Statements
#### CASE statement - SQL문에서 조건문을 구성
#### SELECT contactFirstName, creditLimit, CASE WHEN creditLimit > 100000 THEN 'VIP' WHEN creditLimit > 70000 THEN 'Platinum' ELSE 'Bronze' END AS grade FROM customers;
