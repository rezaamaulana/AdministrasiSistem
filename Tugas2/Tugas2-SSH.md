# **Administrasi Sistem**

### Tugas 2

## Kelompok

1. Reza Maulana / 2010131310012
2. Muhammad Gilang Ramadhan / 2010131310005

---
<br>

## 1. Client Server pada Linux Virtual Box dengan Windows

- langkah 1
![alt text](img/langkah1.png)

Pertama, masuk ke setting pilih Network, disana ada tulisan Attached to klik dan pilih "Host-only" Adapter dan Namenya Pilih "Virtual Host-only Ethernet Adapter" dan di Advanced disana ada Promiscuous Mode pilih "Allow All".

<br>

- langkah 2
![alt text](img/langkah2.png)

Setelah di setting kita masuk ke terminal debian dan masuk sebagai Super User atau **SU**

<br>

- langkah 3
![alt text](img/langkah3.png)

Setelah masuk menggunakan SU atau sebagai root, kemudian ketikan nano /etc/network/interfaces untuk mengkonfigurasi IP address server.

<br>

- langkah 4
![alt text](img/langkah4.png)

Disana tambahkan seperti digambar diatas, Kemudian save dengan cara menekan tombol keyboard “ctrl + x kemudian Y kemudian Enter.

<br>

- langkah 5
![alt text](img/langkah5.png)

Kemudian reboot service networking dengan cara mengetikan perintah terminal :
/etc/init.d/networking restart

<br>

- langkah 6.1
![alt text](img/langkah6.1.png)

Setelah di restart networknya kemudian kita akan mengkonfigurasi IP Address pada Windows (Client).
Buka Control Panel => Network and Internet => Network and Sharing Center => Change Adapter Setting. Kemudian pastikan adapter virtualbox host only dalam keadaan aktif (enable).

<br>

- langkah 6.2
![alt text](img/langkah6.2.png)

Pilih "Properties"

<br>

- langkah 6.3
![alt text](img/langkah6.3.png)

Pilih "Internet Protocol Version 4 (TCP/IPv4)"

<br>

- langkah 7
![alt text](img/langkah7.png)

Kemudian masukan IP yang satu subnet (satu network) dengan Ip Debian Server kita dan Klik Ok

<br>

- langkah 8
![alt text](img/langkah8.png)

Ketika sudah di setting, kita cek untuk clientnya menggunakan ping 192.168.10.2

<br>

- langkah 9
![alt text](img/langkah9.png)

Dan kita cek menggunakan cmd untuk cek servernya menggunakan ping 192.168.10.1