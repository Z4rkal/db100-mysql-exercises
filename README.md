This project was part of a coding assignment for [@SanDiegoCodeSchool](https://github.com/SanDiegoCodeSchool).
`exercises.sql` contains several MySQL exercises that were to be completed for the sake of learning how to query a MySQL database.

You can download this project to your machine with `git clone git@github.com:Z4rkal/db100-mysql-exercises.git`.
From there you can use Node Package Manager to download the dependencies with `npm install`.

To run the tests you'll need to have MySQL 8 server installed, and you will need to change your `my.cnf` file (which will be in varying places depending on how you installed MySQL) to have the following lines:

`[mysqld]`
`bind-address = 127.0.0.1`
`default-authentication-plugin=mysql_native_password`

Once all of that is set up and you've launched (or relaunched if you had it running before editing the config file) your MySQL server, you can run the tests with `npm test`.