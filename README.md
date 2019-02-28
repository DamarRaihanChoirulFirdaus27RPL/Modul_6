# Modul_6
1.) cookie
Cookies disimpan di sisi klien
Cookies tidak aman bagi klien karena cookies dapat disisipi program yang tidak diketahi klien. Karena cookies tidak aman maka browser klien dapat di-set untuk menghapus cookies dan bahkan men-disable fungsi cookies. Menurut sumber lain cookies juga tidak aman bagi sisi server karena cookies dapat di-edit oleh klien.
Data yang disimpan ke dalam metode cookies dapat bertahan lebih lama dan dapat diatur waktu expired-nya. session
Disimpan disisi server
Lebih aman karena tidak ada file yang dimasukan ke sisi klien
Setelah web browser klien dimatikan maka data yang disimpan metode session akan hilang dan waktu expired juga tidak dapat diatur. 
2.)1. Pilih tools menu pada bagian atas browser mozilla, Click “Tools” -> “Options”
Pilih “Privacy” pada menu.
Pada bagian Firefox will pilih “Use custom settings for history”
Pilih “Show Cookies”
Pilih Cookies yang terdapat pada list yang muncul kemudian klik “Remove Cookies” untuk menghapus cookies pada list satu persatu namun untuk dapat menghapus semua cookies yang terdaftar anda dapat memilih “Remove All Cookies”
Pilih “OK atau Close” 
3.) session<php
session_name(“verify”); //menciptakan session bernama verify

session_start(); //memulai session

$username=”nama pengguna”;

$password=”kata sandi”;

$_SESSION[‘ses_username’]=$username; //mengisi session

$_SESSION[‘ses_password’]=$password;

Echo(“File Kedua”);

?> cookie

File Kedua”); ?>

Hasil

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/1.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/2.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/3.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/4.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/5.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/1.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/autentikasi%20cookie.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/autentikasi%20cookie%20(2).png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/autentikasi%20session.png)

![alt text](https://github.com/DamarRaihanChoirulFirdaus27RPL/Modul_6/blob/master/autentikasi%20session%202.png)

