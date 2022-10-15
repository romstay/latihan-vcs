# latihan-vcs
# Tutorial Login Github, Membuat Repository Baru di Github, Instal Git, dan Cara Penggunaan Git 
## Cara Login dan Membuat Repository Baru 
### 1. Pertama ke browser 
- masukan link url https://github.com 
### 2. Setelah masuk saatnya membuat akun, jika belum memiliki akun silahkan daftar terlebih dahulu, jika sudah tinggal masuk aja ![Gambar1](ssgithub/ss1.png.png) 
### 3. Setelah berhasil login di github, saatnya anda membuat file repository baru, seperti gambar dibawah ini ![Gambar2](ssgithub/ss2.png.png) 
### 4. Isikan repository name, dan pilih repository untuk jadi file public atau private, saya buat public disini, setelah itu centang pilihan add a readme file, lalu klik create repository ![Gambar3](ssgithub/ss3.png.png) 
## Cara Install Git di Windows 
### 1. Unduh Git 
- Untuk menginstall git, anda perlu mengunduh file-nya terlebih dahulu di situs resminya. karena saya pakai git-scm, linknya adalah https://git-scm.com/ 
### 2. Install Git 
- Setelah selesai mengunduh file Git, silahkan install aplikasi nya, caranya seperti dibawah ini ![Gambar1](ssgit/ss1.png.png) 
- Lalu klik next terus seperti gambar dibawah, sampai ke menu install 
![Gambar2](ssgit/ss2.png.png) 
![Gambar3](ssgit/ss3.png.png) 
![Gambar4](ssgit/ss4.png.png) 
![Gambar5](ssgit/ss5.png.png) 
![Gambar6](ssgit/ss6.png.png) 
![Gambar7](ssgit/ss7.png.png) 
![Gambar8](ssgit/ss8.png.png) 
![Gambar9](ssgit/ss9.png.png) 
![Gambar10](ssgit/ss10.png.png) 
![Gambar11](ssgit/ss11.png.png) 
![Gambar12](ssgit/ss12.png.png)
![Gambar13](ssgit/ss13.png.png) 
![Gambar14](ssgit/ss14.png.png) 
![Gambar15](ssgit/ss15.png.png) 
![Gambar16](ssgit/ss16.png.png) 

- setelah finish git sudah dapat diguanakn 
## Cara Penggunaan Git 
### Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Dengan perintah berikut: 
- > git config --global user.name "username" 
- > git config --global user.email "email" 
![Gambar4](ssgithub/ss4.png.png) 
### Selanjunya kita siapkan directory dan folder, yang bertujuan untuk menyimpan repository yang akan kita clone dari git hub. Dengan perintah berikut: 
- > cd /"directory"/"nama folder"/ 
![Gambar5](ssgithub/ss5.png.png) 
### Nah setelah itu cara untuk mengaitkan/menambahkan repository, saya disini mengambil dari server dengan cara dan perintah berikkut: 
### - Pertama masuk terlebih dahulu ke git hub 
### - Kemudian salin link repositpry yang ingin anda kaitkan dengan komputer anda 
### - disini saya membuat repository dengan nama "Latihan-Vcs" kemudian saya salin urlnya 
![Gambar6](ssgithub/ss6.png.png) 
### Setelah itu kita masuk lagi ke git bash(yang ada dikomputer), dengan memasukan perintah: 
- > git clone "url repository yang ada di git hub" 
![Gambar7](ssgithub/ss7.png.png) 
### Maka otomatis kita sudah membuat repository dikomputer local kita 
### Kita akan mengecek apakah di repository sudah ada filenya, dengan memasukan perintah: 
- >ls ![Gambar9](ssgithub/ss9.png.png) 
### Nah disini saya sudah mempunyai file dengan nama README.md 
### Saya akan membuat project dengan file ini 
![Gambar10](ssgithub/ss10.png.png) 
### Nah setelah project kita sudah selesai, kita kembali lagi ke git bash 
### disini kita cek terlebih dahulu ada perubahan apa saja yang terjadi. Misalnya ada file baru kah, ada file yang diubah ataupun yang di hapuskah, dengan memasukan printah: 
- > git status ![Gambar14](ssgithub/ss14.png.png) 
### Nah disitu keterangannya bahwa file README.md masih berada distate modified atau di area working directory kita bisa lihat juga dengan warnanya yang berwarna merah ### Selanjutnya kita akan memindahkan atau menambahkan file yang saya buat ke staging area dengan perintah : 
- > git add "file yang ingin ditambhkan" 
![Gambar11](ssgithub/ss11.png.png) 
### Nah setelah itu kita akan menyimpan perubahan dari staging area ke Repository local kita, dengan mecommit file dan harus disertai dengan komentar, dengan menggunakan perintah : 
- > git commit -m "komentar apa saja" ![Gambar12](ssgithub/ss12.png.png) 
### Oke step by step sudah kita jalankan, kita lanjut ke step trakhir ### di step trakhir ini kita akan mengirim prubahan pada repository local ke server, dengan menggunakan printah: 
- > git push -u origin main ![Gambar13](ssgithub/ss13.png.png) 
# Selesai, Sekian dan Trimakasih