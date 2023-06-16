1. Web Server

  Web Server adalah sebuah software yang memberikan layanan berupa data. Berfungsi untuk menerima permintaan HTTP atau HTTPS dari client atau di kenal dengan web browser
  
  Install Nginx
  
  ![nginx](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/f1a88067-a2e5-451a-9b88-01b0975c91c8)
  
sebelum menjalankan pm2 jalankan dulu npm install untuk mendapatkan modul nodejs npm run build untuk membundle aplikasi pastikan pm2 sudah terinstall dengan perintah npm install -g pm2

![npm](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/fbd0d27b-7e64-4f21-8f29-9f764d965777)


![BUILD](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/e370a7c6-a54f-4daf-a376-9db858938f34)

jalankan sudo snap install serve dan  npm install -g serve

![serve](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/35d422c5-0131-4c15-8f6f-898c45a6f258)

jalankan pm2 

![pm2serve](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/681a655c-7458-4a88-be30-a33f93dcdc8c)

![dumbflix](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/8d87ef4a-e2b4-4423-9281-86f7cee3938e)

tambahkan include "dimana file conf proxy"

![nginx](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/b2169507-663b-4e65-976e-0d0b2ffb719a)

conf proxy 

![11](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/643f8347-dd11-48b1-93c5-6fc18b8dd858)

kemudian restrat atau reload nginx cd /etc/nginx

masuk ke sudo nano /etc/hosts dan tambahkan ip dan domain yang kalian buat di proxy

kemudian masuk browser dan coba sear menggunakan link yang sudak dibuat dumbflix-andri.xyz

