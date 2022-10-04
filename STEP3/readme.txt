MariaDB [xmodal]> describe annotation;
+---------------+-------------+------+-----+-------------------+-----------------------------+
| Field         | Type        | Null | Key | Default           | Extra                       |
+---------------+-------------+------+-----+-------------------+-----------------------------+
| annotation_id | int(11)     | NO   | MUL | NULL              | auto_increment              |
| name          | varchar(20) | YES  | MUL | NULL              |                             |
| number        | int(11)     | YES  |     | NULL              |                             |
| page_id       | int(11)     | YES  | MUL | NULL              |                             |
| user_id       | int(11)     | YES  | MUL | NULL              |                             |
| ene_id        | varchar(20) | YES  |     | NULL              |                             |
| candidate     | text        | YES  |     | NULL              |                             |
| level         | int(11)     | YES  |     | NULL              |                             |
| url           | varchar(50) | YES  |     | NULL              |                             |
| c_date        | datetime    | YES  |     | NULL              |                             |
| u_date        | timestamp   | NO   |     | CURRENT_TIMESTAMP | on update CURRENT_TIMESTAMP |
+---------------+-------------+------+-----+-------------------+-----------------------------+
11 rows in set (0.00 sec)

MariaDB [xmodal]> describe log;
+-----------+-------------+------+-----+-------------------+-----------------------------+
| Field     | Type        | Null | Key | Default           | Extra                       |
+-----------+-------------+------+-----+-------------------+-----------------------------+
| u_date    | timestamp   | NO   |     | CURRENT_TIMESTAMP | on update CURRENT_TIMESTAMP |
| event     | varchar(10) | YES  |     | NULL              |                             |
| name      | varchar(20) | YES  |     | NULL              |                             |
| number    | int(11)     | YES  |     | NULL              |                             |
| page_id   | int(11)     | YES  |     | NULL              |                             |
| user_id   | int(11)     | YES  |     | NULL              |                             |
| url       | varchar(50) | YES  |     | NULL              |                             |
| ene_id    | varchar(20) | YES  |     | NULL              |                             |
| candidate | text        | YES  |     | NULL              |                             |
| level     | int(11)     | YES  |     | NULL              |                             |
+-----------+-------------+------+-----+-------------------+-----------------------------+
10 rows in set (0.00 sec)
