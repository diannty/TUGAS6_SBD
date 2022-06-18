# TUGAS6 SISTEM BASIS DATA 

NAMA    = DIAN TRI HANDAYANI

NIM     = 312010041

KELAS   = TI 20 D1

1. Masuk ke database nama_nim

2. Lakukan proses backup dan recovery dengan sql dari database tugas sebelumnya!

-> Melakukan proses penguncian/lock table.
-> Melakukan proses backup table dengan perintah : SELECT * INTO OUTFILE
-> Jika proses backup berhasil maka akan muncul file backup pada direktori C:\xampp\mysql\data\nama database
-> Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;

3. Lakukan proses backup dan recovery dengan sqldump dari database tugas sebelumnya !
-> Jalankan shell atau commad-prompt dan ketikkan perintah berikut untuk memulai dump database
-> Data yang telah di-backup dapat di restrore kembali ke dalam database dengan perintah

4. Tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam!
