## Latar Belakang

Dalam era digital saat ini, pengelolaan basis data menjadi aspek krusial dalam berbagai sistem informasi. Database digunakan untuk menyimpan, mengelola, dan mengolah data dengan efisien agar dapat diakses dengan cepat dan akurat. Terdapat dua jenis utama basis data yang digunakan dalam sistem manajemen data, yaitu database relational (SQL) dan database unrelational (NoSQL).

Permasalahan utama yang sering muncul dalam implementasi database adalah pemilihan jenis database yang sesuai dengan kebutuhan sistem serta konfigurasi yang optimal agar kinerja basis data tetap stabil. Penggunaan database yang tidak sesuai dapat menyebabkan lambatnya pengolahan data, ketidakkonsistenan, dan bahkan kehilangan data.

## Permasalahan

Dalam materi ini, beberapa permasalahan yang diangkat adalah: Pemilihan antara database relational dan unrelational dalam sistem manajemen basis data. Proses instalasi dan konfigurasi MySQL agar dapat digunakan secara optimal. Perubahan konfigurasi variabel penting dalam MySQL, seperti port dan buffer pool size, untuk meningkatkan performa database. Pengelolaan keamanan database melalui perubahan password root. Pembuatan database yang sesuai dengan standar tertentu untuk kebutuhan akademik.

## Solusi

Untuk mengatasi permasalahan tersebut, solusi yang dilakukan adalah: Menentukan kriteria penggunaan database relational dan unrelational sesuai dengan kebutuhan sistem. Melakukan instalasi MySQL dari awal hingga akhir dengan dokumentasi langkah-langkah secara rinci. Mengubah konfigurasi default MySQL, seperti port dan ukuran buffer pool, untuk meningkatkan performa sistem. Mengamankan akses ke database dengan mengganti password root secara berkala. Membuat database dengan format tertentu guna memastikan standar pengelolaan data yang baik.

## Pembahasan

database relational cocok digunakan untuk aplikasi yang membutuhkan integritas data tinggi, seperti sistem perbankan dan inventaris. Sementara itu, database unrelational lebih fleksibel dalam menangani data tidak terstruktur dan sangat cocok untuk big data dan media sosial.

Instalasi MySQL dilakukan dengan mengikuti langkah-langkah sistematis, dimulai dari pengunduhan, konfigurasi server, hingga verifikasi koneksi. Selain itu, perubahan konfigurasi pada MySQL dilakukan untuk meningkatkan kinerja dan keamanan sistem, seperti mengubah port default dan buffer pool size. Perubahan password root juga menjadi langkah penting dalam mengamankan akses ke database

## Kesimpulan

Dari hasil percobaan dan konfigurasi yang dilakukan, dapat disimpulkan bahwa pemilihan jenis database yang tepat sangat berpengaruh terhadap performa dan keamanan sistem. Database relational lebih cocok untuk sistem yang membutuhkan integritas data tinggi, sementara database unrelational lebih baik dalam menangani data dalam skala besar dengan fleksibilitas tinggi.

Instalasi dan konfigurasi MySQL yang benar dapat meningkatkan efisiensi pengelolaan data serta memastikan sistem berjalan dengan optimal. Selain itu, perubahan konfigurasi dan pengamanan database merupakan langkah penting dalam menjaga stabilitas dan keandalan sistem basis data yang digunakan.

##Skenario

Lakukan instalasi database mysql dari awal sampai akhir: a. Buka browser dan kunjungi situs resmi MySQL b. Unduh MySQL Installer c. Pilih versi installer d. Mulai instalasi e. Konfigurasi instalasi f. Konfigurasi MySQL Server g. Instalasi

# Untuk menginstal MySQL di Windows Server, Anda dapat:
1.Memilih tipe setup yang ingin digunakan

2.Memilih software yang dibutuhkan untuk membuat website

3.Mengunduh semua komponen sesuai dengan setup type yang dipilih

4.Menunggu sampai semua komponen ter-install dan muncul tanda check

5.Memilih port yang ingin digunakan

6.Memilih metode yang direkomendasikan dalam Authentication Method

7.Memasukkan password untuk akun database MySQL

8.Mengatur semua bagian sesuai dengan keinginan dan kebutuhan

## Bukti Dukung Gambar

## port dari default 3307 menjadi 3309.

![426904564-0b412a0a-278d-42d8-a5a1-d3bb308ba57b](https://github.com/user-attachments/assets/947e05a3-40e2-4f67-8eb1-5970c0d1461b)


## innodb_buffer_pool_size dr default 16M (menjadi 25% dari RAM ) 22

![image](https://github.com/user-attachments/assets/75da5480-b05b-4b38-bf0f-f710707a74ed)


Buat database dengan nama: kelompok_AB_nama_mhs

![image](https://github.com/user-attachments/assets/653386e0-fd82-41be-8805-bdca20c7fa66)

## REVERENSI

https://dev.mysql.com/doc/

Panduan Praktikum Sistem Manajemen Basis Data
https://drive.google.com/file/d/1BV8gJeSMBDQH_n0ph0PDrX9uQLI5A-LY/view?usp=drive_link
