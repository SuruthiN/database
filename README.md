# database
USE mysql_demo_tnj

CREATE TABLE tb_sruthi_nagarajan(

employee_id INT ,
first_name  VARCHAR(100),
last_name VARCHAR(100),
age INT,
is_employed INT,
email VARCHAR(200),
city VARCHAR(200),
state VARCHAR(200),
country VARCHAR(200),
pincode INT
);
INSERT INTO tb_sruthi_nagarajan VALUES ('1','jeno','ziyavul imran','23','1','jenovaimran@gmIL.com','thanjavur','tamilnadu','india','613005');
INSERT INTO tb_sruthi_nagarajan VALUES ('2','nisha','venkat','23','0','nishavenkat@gmail.com','thanjavur','tamilnadu','india','613005');
INSERT INTO tb_sruthi_nagarajan VALUES ('3','sruthi','nagarajan','23','1','shruthikanagarajan42@gmail.com','thanjavur','tamilnadu',' india','613005');
INSERT INTO tb_sruthi_nagarajan VALUES ('4','sahana','anbu','22','0','sahana@gmail.com','orathanad','tamilnadu','india','613004');
INSERT INTO tb_sruthi_nagarajan VALUES ('5','sadhana','raj','20','0','sadhanaraj@gmail.com','thanjavur','tamilnadu','india','613003');

SELECT * FROM tb_sruthi_nagarajan WHERE First_name LIKE '%je';
SELECT * FROM tb_sruthi_nagarajan WHERE Last_name LIKE '%zi';

SELECT * FROM tb_sruthi_nagarajan WHERE country IN ('orathanad');
SELECT * FROM tb_sruthi_nagarajan WHERE pincode NOT IN ('613003');



![Screenshot (13)](https://user-images.githubusercontent.com/116864585/205286745-2521870f-7cd3-4c57-9c6f-37607e115890.png)

