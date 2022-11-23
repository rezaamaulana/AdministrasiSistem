# Tugas Kelompok FTP
**Nama Anggota Kelompok:**

1. Muhammad Gilang Ramadhan (2010131310005)
2. Reza Maulana (2010131310012)

---

## Langkah - Langkah Penginstalan dan Konfigurasi FTP 

- Langkah 1
![alt text](img/FTP1.png)
pertama kita harus Masuk Debian Linux pada VirtualBox, masuk terminal, kemudian masuk sebagai user administrator(SuperUser). Sekarang untuk penginstalan dengan mengetikkan "apt-get install proftpd"

<br>

- Langkah 2 <br>
![alt text](img/FTP2.png)
Jika sudah terinstall proftpd pada server, Kita membutuhkan aplikasi bernama filezilla untuk melakukukan pengujian ftp pada windows sebagai client. Berikut link download filezilla: <br>
https://filezilla-project.org/download.php.<br>
Jika sudah download, instal filezilla seperti aplikasi pada umumnya kemudian jalankan. Selanjutnya Isi kolom Host dengan ip address server linux, Username dan password linux anda, 
port isi saja 21 lalu klik Quickconnect

<br>

- langkah 3<br>
![alt text](img/FTP3.png)
Jika sudah download, instal filezilla seperti aplikasi pada umumnya kemudian jalankan. Selanjutnya Isi kolom Host dengan ip address server linux (Untuk mencek ip address server linux tuliskan command "ip a" pada terminal).

<br>

- Langkah 4<br>
![alt text](img/FTP4.png)
Isi juga username dan password linux anda, 
port isi saja 21 lalu klik Quickconnect

<br>

- langkah 5<br>
![alt text](img/FTP5.png)
Jika sudah terhubung, Kita akan uji coba mengirim file dari server linux ke computer client. Saya akan mengirim file (text.txt) dari server linux ke computer client.<br>
    1. Pilih file text.txt
    2. drag file dari sebelah kanan ke kiri.

- langkah 6<br>
![alt text](img/FTP6.png)
Jika file sudah berhasil terkirim akan ada notifikasi bahwa transfer berhasil.