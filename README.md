# Tugas_6_Sistem_Basis_Data

### Nama  : Monica Fabiola Pasaribu
### Kelas : TI.20.D1
### NIM   : 312010083

### LANGKAH-LANGKAH TUGAS 6 SISTEM BASIS DATA 

### 1. Masuk ke Database Nama_nim
![image](https://user-images.githubusercontent.com/101724604/172102124-18a32cfa-cd8a-4122-a38f-3ae0c41bede4.png)

### 2. Lakukan proses Backup Dengan SQL dari Database tugas sebelumnya
![image](https://user-images.githubusercontent.com/101724604/175054079-fc528f9b-8364-40d9-b3e1-9fcd13c6307d.png)

![image](https://user-images.githubusercontent.com/101724604/175053994-a8c1551b-2fe2-4d5b-a80d-6d502f0091a0.png)

### 3. Jika proses berhasil maka akan muncul file backup pada Direktori
C:\Xampp\mysql\data\nama database
![image](https://user-images.githubusercontent.com/101724604/175054980-0c8fab7f-2d46-4b6d-9efc-6a504b5b1a0a.png)

### 4. Recovery
Data yang telah di-Backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah :
LOAD DATA INFILE 'Nama_backup_file' INTO TABLE nama_table;
![image](https://user-images.githubusercontent.com/101724604/175055665-b2ea0492-a615-4eb6-9bf0-58ed45022d58.png)

### 5. Lakukan proses Backup dan Recovery dengan Sqldump dari Database tugas sebelumnya!
![image](https://user-images.githubusercontent.com/101724604/175056731-304405df-9a7f-4952-9d98-742930323a03.png)

### 6. Tuliskan Script Cron Job untuk melakukan Backup otomatis setiap hari minggu jam 12 malam!
- Crontab-e

00**7myqldump -u root -p klinik_312010083 > BackupTugas6.sql
