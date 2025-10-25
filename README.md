Berikut langkah-demi-langkah untuk membuat repository Dan mengaktifkan GitHub page


---

1. Membuat Repository

1. Masuk ke akun GitHub mu.


2. Klik tombol “New” atau ikon “+” lalu pilih New repository. 


3. Isi kolom:

Repository name: misalnya portfolio atau bisa juga username.github.io jika ingin membuat website user-site. 

Deskripsi (opsional) yang mendeskripsikan proyekmu.

Visibility: pilih Public agar bisa dilihat oleh siapa saja.



4. Klik Create repository.


5. Setelah dibuat, upload file-file kamu: index.html, style.css, folder img/, dan lainnya. Bisa melalui fitur “Upload files” di GitHub atau lewat Git di command line.




---

2. Mengisi & Push File ke Repository

Jika menggunakan Git di komputer:

git init
git add .
git commit -m "Initial commit: portfolio website"
git remote add origin https://github.com/username/repositoryname.git
git push -u origin main

Pastikan branch default adalah main (atau master tergantung pengaturan). 


---

3. Mengaktifkan GitHub Pages

1. Pada halaman repository di GitHub, masuk ke tab Settings. 


2. Di sisi kiri menu, cari bagian Pages (ada di bawah “Code and automation” atau “Pages”). 


3. Di bagian Source (“Build and deployment”):

Pilih branch yang ingin digunakan (misalnya main).

Pilih folder sebagai sumber situs: “/ (root)” jika file HTML berada di root repository. 



4. Klik Save (atau “Save” / “Publish”).


5. Tunggu beberapa menit, kemudian GitHub akan menampilkan URL situsmu: misalnya https://username.github.io/repositoryname/. 




---

4. Cek & Troubleshoot

Pastikan ada file index.html di root folder repository — ini file yang akan dibuka saat URL dibuka. 

Jika muncul error 404 atau halaman belum muncul, tunggu beberapa menit dan refresh. Kadang perlu push komit baru agar build berjalan. 

Pastikan nama repository sesuai aturan jika ingin user-site: yakni username.github.io. 



---

Jika kamu setuju, saya dapat menuliskan panduan khusus untuk portfolio desain grafis kamu — lengkap dengan screenshot tiap langkah dan template teks yang bisa diikuti. Mau saya siapkan?
