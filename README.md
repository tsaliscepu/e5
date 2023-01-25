# Versi baru dalam pengembangan......Repositori ini tidak akan dipertahankan jika telah selesai。
# Prosedur Perpanjangan E5
Proyek ini merupakan kode sumber (back-end) dari URL ini https://e5.qyi.io/
(Front-end) https://github.com/luoye663/e5-html
#### Tutorial
https://qyi.io/archives/687.html

#### Rencana:
- [ ] Data dasar disimpan menggunakan h2 ringan
- [x] Log yang tersimpan menggunakan TDengine/influxdb
- [ ] Menghilangkan dependensi mysql
- 
### 2021-08-19
1、Membatalkan pengosongan otomatis pada redis  
2、Menaruh log panggilan pada influx，untuk mengurangi beban pada mysql
### 2021-07-28
Menghilangkan dependensi rabbitMQ，Implementasi lebih sederhana menggunakan thread pool(Mengurangi Waktu eksekusi)

### 2020-12-20
Framework front-end diubah menjadi Angular, yang mendukung banyak aplikasi sekaligus, dan setiap akun mendukung hingga 5 aplikasi.。
## Penjelasan
Proyek ini merupakan awal saya untuk berlatih，hot chicken code，telah berjalan sejak Maret 2020 hingga kini。  
Jika anda ingin membangunnya sendiri lakukan riset sendiri，tidak dukukang teknis(malas)，Ingat untuk mengubah berkas konfigurasi 
src/main/resources/application-online.properties 
```
user.admin.githubId  - memiliki github id  
Pengaturan basis data  
Pengaturn redis  
Pengaturan Rabbit  
github.client_id  
github.client_secret  
(Keduanya terdapat pada https://github.com/settings/developers cukup ajukan sebuah apps。)
```
## Tindakan Pencegahan


## Gunakan teknologi framework
### spring boot  

### Redis
1 library digunakan secara default，anda dapat mengubahnya pada berkas konfigurasi  

### Mysql
impor sendiri berkas sql  
Tidak ada fungsi tulis hapus log, diikuti dengan penambahan。  
Terdapat alasan mengapa log disimpan di MongoDB，jadi？
### Mybatis Plus

### Spring Security
Dikarenakan hanya ada sedikit pengaturan izin，hal itu tidak ditulis di dalam mysql。
### log4j2
Pencatatan Framework

## Terimakasih

> [IntelliJ IDEA](https://www.jetbrains.com/zh-cn/idea/buy/#personal?billing=yearly) merupakan sebuah IDE yang memaksimalkan produktifitas pengembang di setiap waktu，untuk platrofm JVM。

Terimakasih kepada [JetBrains](https://www.jetbrains.com/?from=) Gratis untuk proyek sumber terbuka [IntelliJ IDEA](https://www.jetbrains.com/idea/?from=) Menunggu otorisasi IDE 
[<img src=".github/jetbrains-variant-3.png" width="200"/>](https://www.jetbrains.com/)
