#latihan 1
- Download git, buka website (git-scm.com)
- Jika sudah terinstall bisa dibuka di CMD kemudian klik (git --version)
- Lalu klik hub dan masukan config global repository $git config --global user.name "user_name", $git comfig --global user.email "user_name"
- lalu buka windows explorer dan buat folder baru "latihan 1"
- klik kana lalu pilih "git bash"g
- buat directory project dengan nama latihan 1
- $mkdir latihan 1
- $cd latihan 1
- selanjutnya masuk ke directory lalu ketik "cd"
- jalankan perintah "git init"
- semua perubahan pada working directory akan disimpan
- membuat file menggunakan text editor
- $echo "#latihan 1" >> readme.md
- lalu $git add readme.md
- menyimpan perubahan kedatabase
- $git commit -m"file pertama saya"
- membuat repository server di google chrome
- membuat akun git yang baru terlebih dahulu
- lalu tambahkan "$git remote add origin"
- mengirim perubahan $git push -u- origin
- lalu clone repository memakai perintah git clone