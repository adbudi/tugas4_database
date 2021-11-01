# tugas4_database

### 1. Buatlah database permainan
- create databases permainan

### 2. Buatlah table sepakbola
- use permainan
- create table sepakbola

### 3. Buatlah struktur table sepakbola sebagai berikut:
![gambar](https://user-images.githubusercontent.com/84311409/139655377-20b3dcf1-c8b3-4aeb-9f69-1674ccbfeacc.png)

<br>
### 
     create table sepakbola
    -> (id_pemain INT(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
    -> nama_pemain VARCHAR(100),
    -> usia_pemain INT(2),
    -> posisi_pemain VARCHAR(50));

### 4. Ubah nama tabel menjadi sepakbola_indonesia
- rename table sepakbola to sepakbola_indonesia

### 5. Hapus table sepakbola_indonesia dan database permainan
- drop if exists from  sepakbola_indonesia, permainan;
