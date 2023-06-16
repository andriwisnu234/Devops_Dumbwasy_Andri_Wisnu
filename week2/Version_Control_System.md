
1. Version Control System

Version Contro berfungsi untuk mentracking setiap perubahan yang dilakukan secara terus-menerus digunakan untuk menejemen perubahan 

saya akan mencoba membuat sebuah repository dengan nama Exampel yang mana didalam repository ini berisi 3 file dan untuk aktifitasnya saya lakukan/kerjakan melalu terminal
  
  a. Buat repository 
  
  ![examplerepository](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/a27469b4-0cb5-4ee4-ae36-70761b8fc339)

git config --global user.name "your.github-user.name"

git config --global user.email "your.github-user.email"

perintah diatas digunakan untuk menetapkan user name dan email akun github kalian ke terminal pastikan username dan email sesuai dengan akun github

![git username](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/49cf73c3-3ec8-4669-b697-fa97874bc6d0)

untuk mengintegrasikan antara repository local anda dengan platform github diutuhkan SSH Keygen

 gunakan perintah ssh-keygen untuk mendapatkannya
 
 ![ssh](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/ccb99842-7c06-44b7-979e-12ac02c46ec9)

Masukan perintah cat .ssh/id_rsa.pub untuk mendapatkan key nya kemudian copy key dan paste di akun github untuk masuk ke setting di github bisa melalu https://github.com/settings/keys. pilih new ssh kemudian paste key yang dicopy ke bagian kolom key dan add sshkey

![key](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/4367b7dc-1b70-4034-8d17-c92dac435133)

![keygit](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/57a7c9f7-f054-4956-a114-88924a4bbc70)

 . Repository
 
 adalah tempat untuk menampung setiap perubahan pada git, untuk membuat repository pertama buat directory masuk kedalam direktory tersebut kemudian jalankan perintah git init

![init](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/1222f28d-1dc0-407c-8cf6-608c6396bed4)

 kemudian buat 3 contoh file
 
 ![file](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/b9ced3ac-d6a3-4777-a129-9de93c842ce5)

lakukan perintah git status untuk melihat status git kalian dan git add untuk melakukan stage pada file 

![gitsataus](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/8f02c379-1a13-4dae-a766-96522ac283dd)

setalah melakukan stage langakah sealanjutnya adalah commit, untuk menjalankan commit lakukan perintah git commit -m "pesan commit yang ingin kalian buat"

![commit](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/03b7d9a2-24a0-4374-9895-a001fc76df8e)

kemudian buat satu repository pada akun github kalian dibagian quick setp pilih ssh dan copy link ini yang akan kita gunakan untuk remot di terminal lakukan perintah git remote add tambah link pository github kalian dan terakhir proses uploading menggunakan perintah git push

![gitpush](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/5fecef6a-ccb1-4984-b6d7-7c11a5797bbb)

kemudian reload web browser

![gitpushdown](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/1bfb1f7b-71f3-4e26-9aae-3288a8e978ba)

  Branch merupakan perintah yang dibuat untuk membuat versi dari sebuah repository. Seperti kita melakukan clone terhadap sebuah folder dimana folder lainnya dapat diubah atau dihapus lebih leluasa.

![git branc](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/6539f1e3-f17c-4639-bb4f-553d1911d201)

git branch -a untul melihat branch yang ada

git checkout (name branch) untuk berpindah branch sesuai nama branch

git branch -m (name branch) untuk membuat branch baru dan langsung berpindah pada branch tersebut

![git branc -a](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/43a301a9-1aac-4398-8b74-376fcab3fb76)

contoh 3 commen git

git log menampilkan hasil perubahan yang telah di commit

![gitlog](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/815621b9-9ba9-4909-ba74-b6246b7da470)

git show

![gitshow](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/e169894c-5199-4752-9ec7-775615d82cc2)

git marge Perintah merge digunakan untuk menggabungkan sebuah branch ke branch aktif





