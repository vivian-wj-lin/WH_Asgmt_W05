# WH_Asgmt_W05
MySQL practice

The first screenshot below shows the complete command lines of the file data.sql, and serves as well as the source commands that the results of following screenshots are driven from:

Description: complete commands
![image](https://github.com/vivian-wj-lin/WH_Asgmt_W05/blob/main/commands.png)

Description: The database "website" and the table "member" were established.
![image](https://github.com/vivian-wj-lin/WH_Asgmt_W05/blob/main/reqt2.png)

Description:   
SELECT * FROM member;  
SELECT * FROM member ORDER BY time DESC  
SELECT ROW_NUMBER() OVER (ORDER BY time DESC) as rowId, id,name,username,password FROM member Limit 1,3;  
![image](https://github.com/vivian-wj-lin/WH_Asgmt_W05/blob/main/reqt3_pic2.png)

Description:  
SELECT * FROM member WHERE username="test";  
SELECT * FROM member WHERE username="test" and password='test';  
SELECT count( * ) as id from member;  
SELECT SUM(follower_count) FROM member;  
![image](https://github.com/vivian-wj-lin/WH_Asgmt_W05/blob/main/reqt3_pic3.png)

Description:   
SELECT AVG(follower_count) FROM member;  
UPDATE member SET name="test2" WHERE username="test";  
![image](https://github.com/vivian-wj-lin/WH_Asgmt_W05/blob/main/reqt3_pic4.png)
