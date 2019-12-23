# Materi

### 1. Membuat Repositori
Repositori merupakan istilah yang digunakan untuk direktori proyek yang menggunakan Git pada direktori, dengan menggunakan perintah "git init <nama direktori>" agar repository

### 2. Menambahkan Remote
Agar proyek dapat diupload ke dalam akun github maka perlu dibuat remote dengan menggunakan perintah git remote add "url HTTP atau SSH key"

### 3. Kondisi File
untracked files : File dimasukan kedalam direktori proyek file secara manual

Modified : File yang sudah diedit namun belum diadd atau commit disebut kondisi

staged : file yang sudah di add

Commited : File yang sudah diubah menjadi kondisi staged dapat disimpan kedalam log 

### 4. Git Add
Dengan menggunakan perintah ini, maka artinya sama aja kita menyuruh agar di git untuk melakukan penambahan (add) pada semua file dalam folder "git add <nama file>"

### 4. Git Commit
Dengan menggunakan perintah "git commit -m <nama log>" perubahan file akan disimpan kedalam log

### 5. Git Log
perintah "git log" user dapat melihat log-log perubahan yang sudah diCommit

### 6. Membatalkan perubahan
git checkout <nama file> : untuk membatalkan perubahan pada file yang sudah dimodifikasi namun belum diadd

git reset <nama file> : untuk membatalkan perubahan pada file yang sudah diadd namun belum di commit

Git Revert -n <nomor commit> : mengembalikan semua file ke suatu commit

### 7. Git Stash
perintah "git stash" digunakan untuk menyimpan file yang sudah dimodifikasi ditempat penyimpanan sementara

### 8. Git Push
perintah "git push <nama remote> <nama cabang>" digunakan untuk menyimpan file yang paling baru dan fix digunakan disimpan pada projek github


### 9. Git Fetch
Perintah "git fetch <nama remote> <nama cabang>" digunakan untuk mengambil file yang berada di github

### 10. Git Pull
Perintah "git pull <nama remote> <nama cabang>" digunakan untuk mengambil file yang berada di github dan menggabungkan file tersebut dengan file didirektori lokal
