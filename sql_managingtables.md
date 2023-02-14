# DDL - 데이터의 기본 구조 및 형식 변경 
<br/>

## Create a table
#### CREATE TABLE examples (examId INT AUTO_INCREMENT, lastName VARCHAR(50) NOT NULL, firstName VARCHAR(50) NOT NULL, PRIMARY KEY(examId));
#### MySQL Constraints - Primary Key, Not Null
#### AUTO_INCREMENT attribute - 시작 값은 1, 자동으로 1씩 증가, Not Null 제약조건 내포
<br/>

## Delete a table
#### DROP TABLE statement (테이블 삭제) - DROP TABLE table_name;
<br/>

## Modifying table fields
#### ALTER TABLE statement (테이블 필드 조작)
#### ALTER TABLE table_name ADD new_column_name column_definition;
#### ALTER TABLE table_name MODIFY column_name column_definition;
#### ALTER TABLE table_name CHANGE COLUMN original_name new_name column_definition;
#### ALTER TABLE table_name DROP COLUMN column_name;
<br/>

# DML - 데이터 조작 
## Insert data into table
#### Insert statement - 테이블 레코드 삽입 
#### CREATE TABLE articles ( id INT AUTO_INCREMENT, title VARCHAR(100) NOT NULL, content VARCHAR(200) NOT NULL, createdAt DATE NOT NULL, PRIMARY KEY (id) );
#### INSERT INTO articles (title, content, createdAt) VALUES ('hello', 'world', '2000-01-01');
#### INSERT INTO articles (title, content, createdAt) VALUES ('mytitle', 'mycontent', CURDATE());
<br/>

## Update data in table
#### Update statement - 테이블 레코드 수정
#### UPDATE articles SET title = 'newTitle' WHERE id = 1;
#### UPDATE articles SET content = REPLACE(content, 'content', 'TEST')
<br/>

#### Delete statement - 테이블 레코드 삭제 
#### DELETE FROM articles WHERE id = 1;
