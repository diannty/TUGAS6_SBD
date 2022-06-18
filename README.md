# TUGAS 6 SISTEM BASIS DATA 

# NAMA    = DIAN TRI HANDAYANI

# NIM     = 312010041

# KELAS   = TI 20 D1

---------------------------------------------------------''------------------------------------------------------------------------------------------------------------
![dumping bagian 2](https://user-images.githubusercontent.com/101880835/174418661-2c5804f8-f46c-44a4-bc48-f1b607b311ec.png)
![bagian 1](https://user-images.githubusercontent.com/101880835/174418663-f8797a0e-cecc-4379-872f-4c6a7e7cfa16.png)
![log in](https://user-images.githubusercontent.com/101880835/174418665-6023d653-4997-4802-920f-3f94006a8ebe.png)
![delete](https://user-images.githubusercontent.com/101880835/174418668-47df27e1-d6a6-4357-aad2-041a1c53964d.png)
![load berhasil](https://user-images.githubusercontent.com/101880835/174418672-a63f0a55-6490-400b-acc8-13b9b919c039.png)
![di folder](https://user-images.githubusercontent.com/101880835/174418677-b0a98acf-dc19-4bdd-bc8b-c2c43e1d64b9.png)
![backup](https://user-images.githubusercontent.com/101880835/174418686-cdc212c6-4bcc-461b-a5a8-0b55a8e64e58.png)
![masuk admin](https://user-images.githubusercontent.com/101880835/174418691-933288fa-ca58-4d13-aef1-a1a5efeffc78.png)


# 1. Masuk ke database nama_nim

![masuk admin](https://user-images.githubusercontent.com/101880835/174418691-933288fa-ca58-4d13-aef1-a1a5efeffc78.png)


2. Lakukan proses backup dan recovery dengan sql dari database tugas sebelumnya!

-> Melakukan proses penguncian/lock table.

-> Melakukan proses backup table dengan perintah : SELECT * INTO OUTFILE
-> Jika proses backup berhasil maka akan muncul file backup pada direktori C:\xampp\mysql\data\nama database
-> Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;

3. Lakukan proses backup dan recovery dengan sqldump dari database tugas sebelumnya !
-> Jalankan shell atau commad-prompt dan ketikkan perintah berikut untuk memulai dump database
-> Data yang telah di-backup dapat di restrore kembali ke dalam database dengan perintah

4. Tuliskan script cron job untuk melakukan backup otomatis setiap hari minggu jam 12 malam!
