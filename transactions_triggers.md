## Transactions
#### 여러 쿼리문을 묶어서 하나의 작업처럼 처리하는 방법
#### START TRANSACTION; INSERT INTO users (name) values ('james'), ('mary'); SELECT * FROM users; ROLLBACK; SELECT * FROM users;
#### START TRANSACTION; INSERT INTO users (name) VALUES ('james'), ('mary'); SELECT * FROM users; COMMIT; SELECT * FROM users;
#### 쪼개질 수 없는 업무처리의 단위 
#### 전체가 수행되거나 또는 전혀 수행되지 않아야 함 
<br/>

## Triggers
#### 특정 이벤트에 대한 응답으로 자동으로 실행되는 것 
#### DELIMITER // CREATE TRIGGER beforeArticleUpdate BEFORE UPDATE ON articles FOR EACH ROW BEGIN SET NEW.updatedAt = CURRENT_TIME(); END// DELIMITER ;
#### DELIMITER // CREATE TRIGGER recordLogs AFTER INSERT ON articles FOR EACH ROW BEGIN INSERT INTO articleLogs (description, createdAt) VALUES ('글이 작성 되었습니다.', CURRENT_TIME()); END // DELIMITER ;
#### 
