# Tugas_6_Sistem_Basis_Data

### Nama  : Monica Fabiola Pasaribu
### Kelas : TI.20.D1
### NIM   : 312010083

### LANGKAH-LANGKAH TUGAS 6 SISTEM BASIS DATA 

### 1. Masuk ke Database Nama_nim
![image](https://user-images.githubusercontent.com/101724604/172102124-18a32cfa-cd8a-4122-a38f-3ae0c41bede4.png)

### 2. Lakukan proses Backup Dengan SQL dari Database tugas sebelumnya
### 3. Jika proses berhasil maka akan muncul file backup pada Direktori
C:\Xampp\mysql\data\nama database
### 4. Recovery
Data yang telah di-Backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah :
LOAD DATA INFILE 'Nama_backup_file' INTO TABLE nama_table;
### 5. Lakukan proses Backup dan Recovery dengan Sqldump dari Database tugas sebelumnya!
### 6. Tuliskan Script Cron Job untuk melakukan Backup otomatis setiap hari minggu jam 12 malam!
Crontab-e
