# DataGrip
Learning Tool how to use SQL Database

DataGrip adalah lingkungan manajemen basis data untuk pengembang. Hal ini dirancang untuk **query, membuat, dan mengelola database**. Basis data dapat bekerja secara lokal, di server, atau di cloud. Mendukung **MySQL, PostgreSQL, Microsoft SQL Server, Oracle, dan banyak lagi**. Jika Anda memiliki driver JDBC, tambahkan ke DataGrip, sambungkan ke DBMS Anda, dan mulai bekerja.

Contoh: 
INSERT INTO table_name (column1, column2, column3)
VALUES (value1, value2, value3); 
```
Contoh Table:
create table Akun
(
      	ID integer
      		constraint Akun_pk
      			primary key autoincrement,
      	Email TEXT,
      	Password TEXT,
      	Username TEXT,
      	Nama text
)

Contoh Insert Table:
INSERT INTO Akun (Email, password, Username, Nama) VALUES ("dian@gmail.com", "secret", "dian", "Dian");

Contoh Delete Row:
DELETE FROM Akun WHERE ID = 1

Contoh Multi Insert:
INSERT INTO Akun (Email, password, Username, Nama) VALUES ("Selvi@DarkWeb.com", "secret", "Selvi", "Selvi"),
                                                          ("Doni@DarkWeb.com", "secret", "Doni", "Doni"),
                                                          ("Soni@DarkWeb.com", "secret", "Soni", "Soni"),
                                                          ("Alan@DarkWeb.com", "secret", "Alan", "Alan"),
                                                          ("Sonya@DarkWeb.com", "secret", "Sonya", "Sonya"),
                                                          ("Loyi@DarkWeb.com", "secret", "Loyi", "Loyi");
```
