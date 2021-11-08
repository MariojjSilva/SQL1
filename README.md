# SQL1

mysql> SHOW TABLES;
+-------------------------+
| Tables_in_wild_db_quest |
+-------------------------+
| school                  |
| wizard                  |
+-------------------------+
2 rows in set (0,00 sec)

mysql> DESCRIBE wizard;
+-------------+--------------+------+-----+---------+----------------+
| Field       | Type         | Null | Key | Default | Extra          |
+-------------+--------------+------+-----+---------+----------------+
| id          | int          | NO   | PRI | NULL    | auto_increment |
| firstname   | varchar(100) | NO   |     | NULL    |                |
| lastname    | varchar(100) | NO   |     | NULL    |                |
| birthday    | date         | NO   |     | NULL    |                |
| birth_place | varchar(255) | YES  |     | NULL    |                |
| biography   | text         | YES  |     | NULL    |                |
| is_muggle   | tinyint(1)   | NO   |     | NULL    |                |
+-------------+--------------+------+-----+---------+----------------+
7 rows in set (0,00 sec)

mysql> DESCRIBE school;
+----------+--------------+------+-----+---------+----------------+
| Field    | Type         | Null | Key | Default | Extra          |
+----------+--------------+------+-----+---------+----------------+
| id       | int          | NO   | PRI | NULL    | auto_increment |
| name     | varchar(100) | NO   |     | NULL    |                |
| capacity | int          | YES  |     | NULL    |                |
| country  | varchar(255) | YES  |     | NULL    |                |
+----------+--------------+------+-----+---------+----------------+
4 rows in set (0,00 sec)

mysql> 
