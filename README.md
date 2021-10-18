# latihan-vcs
README.md
LatihanVcs1
Tutorial menggunnakan git
Apa itu Git?

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project. Developer software biasa menggunakan Git untuk distributed revision (VCS terdistribusi), hal ini bertujuan untuk menyimpan database tidak hanya ke satu tempat. Namun semua orang yang terlibat dalam penyusunan kode dapat menyimpan database ini.

Pada saat pertama kali menggunakan Git, perlu dilakukan konfigurasi Username dan Email. Jalankan perintah berikut
git config --global user.name "username"
git config --global user.email "email" Screenshot (17)
Jalankan perintah git init. untuk membuat repository local
git init Screenshot (18)
Untuk membuat file dapat menggunakan Text Editor, Lalu menyimpan filenya pada repository. Sebagai contoh disini saya akan membuat file README.md dengan perintah berikut
echo "# belajargit" >> README.md Screenshot (19)
Untuk menambahkan file yang sudah kita buat, gunakan perintah git add (Nama File) atau bisa menggunakan git add . (Jika file nya ada banyak)
git add README.md
git add . Screenshot (20)
Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah git commit -m "nama project" Dan yang ada di dalam tanda kutip " " itu adalah nama kommentar setiap kita mencommit project
git commit -m "menambahkan Project" Screenshot (21)
Untuk menyimpan setiap perubahan pada repository local, gunakan perintah git remote add origin (url)
git remote add origin https://github.com/ArjunSyah/LatihanVCS.git Screenshot (22)
Untuk mengirim perubahan pada repository local ke server, gunakan perintah git push, Perintah ini akan meminta Username dan Password pada akun github mu
git push -u origin master Screenshot (23)
Selesai
TRIMAKASIH
