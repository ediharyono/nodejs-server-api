Persiapan
Pastikan telah menginstall nodejs dan npm. Jika belum dapat didownload NodeJs dan NPM lalu di install sesuai dengan panduan di dokumentasinya.

Jika belum pernah menggunakan sequelize perlu maka perlu install Sequelize-cli secara global

npm i -g sequelize-cli
Lalu buat project nodejs dengan perintah

npm init
Install NPM modules
Selanjutnya menginstall npm modules yang kita butuhkan

npm install express express-session body-parser cookie-parser passport passport-local sequelize nodemon env2 --save
Setup ENV variabel
Buat file .env pada root project


Ada 5 variabel env yang kita buat

MYSQL_HOST diisi dengan host MySQL (jika menggunakan local silahkan isi localhost)
MYSQL_HOST diisi port MySQL (defaultnya 3306),
MYSQL_NAME diisi dengan nama database untuk project ini (jika belum membuat database silahkan buat terlebih dahulu)
MYSQL_USER diisi dengan username MySQL
MYSQL_PASS diisi dengan password MySQL (Jika tidak ada password bisa dikosongi saja)
Inisialisasi Sequelize
Kita perlu meng-init Sequelize untuk membuat config sequelize, dan membuat beberapa folder yang dibutuhkan oleh Sequelize.

sequelize init

https://medium.com/@nashirjamali/membuat-sistem-authentication-sederhana-menggunakan-node-js-dan-mysql-5e05cf5a3620 

