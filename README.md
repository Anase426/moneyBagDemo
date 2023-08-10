# moneyBagDemo

## 建表语句
CREATE TABLE IF NOT EXISTS moneybag(
	user_id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
	moneybag_num INT NOT NULL
);

INSERT INTO moneybag(user_id, moneybag_num)
	VALUES(1001, 100);


CREATE TABLE IF NOT EXISTS moneybag_bill(
	user_id INT NOT NULL,
	bill_num INT NOT NULL
);

INSERT INTO moneybag_bill(user_id, bill_num)
	VALUES(1001, 100);

 ## postman截图
 ![image](https://github.com/Anase426/moneyBagDemo/assets/69397210/d00d3d76-da27-4830-a4b0-58c061149f3a)
![image](https://github.com/Anase426/moneyBagDemo/assets/69397210/fe71e9c2-4aa9-4c38-931d-431594cabb19)
![image](https://github.com/Anase426/moneyBagDemo/assets/69397210/b7a6f714-5280-4fae-8c89-1692829252be)
![image](https://github.com/Anase426/moneyBagDemo/assets/69397210/82c226f4-60b1-4ed0-9ac7-a1645456de7a)
