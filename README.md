# Materi
Repositori merupakan istilah yang digunakan untuk direktori proyek yang menggunakan Git
1. pada direktori proyek perlu dibuat dibuat direktori .git dengan menggunakan perintah git init "nama direktori" agar repository
2. Agar proyek dapat diupload ke dalam akun github maka perlu dibuat remote dengan menggunakan perintah git remote add "url HTTP atau SSH key"
3. File dimasukan kedalam direktori proyek file tersebut disebut Modified, karena file tersebut belum di add dan di commit
4. Agar file bisa disimpan, file tersebut harus di add menggunakan perintah git add "nama file". Kondisi file ini disebut kondisi staged
5. File yang sudah diubah menjadi kondisi staged dapat disimpan kedalam log menggunakan perintah git commit -m "nama log". Kondisi file ini disebut kondisi commited
6. Agar user dapat meliat data-data yang sudah disimpan digunakan perintah git log
7. file yang belum dimodifikasi namun belum diadd dapat dikembalikan kekeadaan semula menggunakan perintah git checkout "nama file"
8' file yang sudah diadd namun belum di commited bisa dikembalikan menggunakan perintah git reset "nama file" kemudian perintah git checkout "nama file"
9. file yang sudah diadd dan dicommited bisa dikembalikan menggunakan perintah git checkout "nomer commit".
10. file yang paling baru dan fix digunakan disimpan pada projekgithub menggunakan perintah git push "nama remote" "nama cabang"
11. file yang berada di github bisa diambil dengan perintah git fetch  "nama remote" "nama cabang" atau git pull "nama remote" "nama cabang"