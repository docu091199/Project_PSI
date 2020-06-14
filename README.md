Petunjuk Instalasi dan Penggunaan

Note : Pada contoh Instalasi berikut menggunakan Xampp dan SQLYog/phpmyadmin.

I. Petunjuk Instalasi 
1. Instalasi Software
    Unduh Aplikasi VSCode di browser : https://code.visualstudio.com/download
    Unduh Aplikasi SQLYog : https://sqlyog.id.jaleco.com/
    Unduh MySQL : https://mysql-com.id.softonic.com/
    Unduh XAMPP : https://www.apachefriends.org/download.html
    Unduh Composer : https://getcomposer.org/download/

2. Unduh Framework 
    Unduh Laravel (laravel terinstal di proyek )
    Buka terminal pada repository dan masukkan 
    composer global require "laravel/installer=~1.1"

II. Petunjuk Penggunaan 
1. Extract Folder project.zip 
2. Buka XAMPP lalu jalankan Apache dan MySql
3. Buka SQLYog dan eksekusi query yang terdapat pada db_pupuk_bersubsidi.sql
4. Tambahkan user database baru dengan 
    - username = "root"
    - password = " "
5. Pada folder project yang sudah terinstall buka command prompt (cmd) ketikkan command 
    - composer update .Pastikan composer sudah terinstall.
    - setelah proses selesai ketikkan php artisan serve 
5. Kemudian buka localhost/login untuk masuk ke halaman login
6. Masuk ke sistem dengan user yang berbeda 
    - Dinas pertanian
        email : disper@gmail.com
        password : rahasia 
    - Kelompok Tani
        email : tanijaya@gmail.com
        password : rahasia
    - PPL
        email : bowok@gmail.com
        password : rahasia 
    - Pengecer 
        email : majatani@gmail.com
        password : rahasisa
    Email user yang lainnya dapat dilihat di database pada tabel users dengan password = rahasia
