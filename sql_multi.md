#### JOIN clause - 둘 이상의 테이블에서 데이터를 검색하는 방법
#### 종류 = INNER JOIN, OUTER JOIN (LEFT JOIN, RIGHT JOIN), CROSS JOIN
#### INNER JOIN clause - 두 테이블에서 값이 일치하는 레코드에 대해서만 결과를 반환
#### SELECT select_list FROM table1 INNER JOIN table2 ON table1.fk = table2.pk;
<br/>

#### LEFT JOIN clause - 오른쪽 테이블의 일치하는 레코드와 함께 왼쪽 테이블의 모든 레코드 반환
#### 왼쪽은 무조건 표시하고, 매치되는 레코드가 없으면 NULL을 표시
#### RIGHT JOIN clause - 왼쪽 테이블의 일치하는 레코드와 함께 오른쪽 테이블의 모든 레코드 반환
#### 오른쪽은 무조건 표시하고, 매치되는 레코드가 없으면 NULL을 표시