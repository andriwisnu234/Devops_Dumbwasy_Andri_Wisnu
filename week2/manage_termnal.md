
1. Text Manipulation

  Manipulasi text tanpa menggunakan text editor, seperti manipulasi file menggunakan terminal tanpa text editor
  
  contoh beberapa perintah 
  
  1.1 cat
  
      a. cat (file) melihat isi konten
      
      b. cat > nama membuat file baru dan membuat kontennya
      
      c. cat file1 file2 > file3 menggabungkan isi dari dua file ke file baru
      
![cat](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/d0eeb2a1-683c-4cf0-a346-25a477884e99)

  1.2 sed
      
      a. sed -i 's/Hello/Holla/g' file3 perintah ini akan merubah kata hallo menjadi holla pada file3
     
     ![sed](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/39f0e217-0da1-4feb-bc36-ae9a9471edf9)

  1.3 grep
      
     digunakan untuk mencari text  
     
     a. grep haii file1 untuk mencari kata haii pada file3
     
     b. grep -c haii cantik file1 untuk menghitung jumlah kata
     
     c. grep haii * untuk mencari semua file yang berisi kata haii
     
   ![grep](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/e1199b62-8bc0-4f66-bad1-eb5ce0e29300)

  1.4 sort

      digunakan untuk mengutkan data
      
      a. sort file4 pengurutan data a-z 1-9
      
      b. sort -r file4 pengurutan data z-a 9-1
            
![sort](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/b32af43d-1add-4e67-ae61-8fb0117f7bc4)

  1.5 echo
  
      a. echo "hallo semua!" untuk mencetak string
      b. 
      b. echo "hallo semua!" >> file4
      
      c. echo "hallo kawan semua kita sambut hari baru" > file4 replace semua dan data dan menggantinya
      
      ![echo](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/0d310356-431d-407c-a9ce-fdeb3ebc3b08)

2. htop

    htop merupakan perintah untuk memonitoring sistem, kita dapat melihat penggunaan memory, cpu, swap. Berikut adalah contoh penggunaan
 
 ![htop](https://github.com/andriwisnu234/Devops_Dumbwasy_Andri_Wisnu/assets/135598387/6a4995ab-30a4-4b9b-801c-d43ea58f9d10)
 
 f1 help untuk mengetahui informasi htop
 
 f2 setup untuk mengatur informasi yang ingin ditampilkan
 
 f3 search mencari proses, user, command
 
 f4 filter memfilter proses, user, command
 
 f5 tree menampilkan cabang commend
 
 f6 sort by pengurutan berdasarkan karakteristik
 
 f7 nice - 
 
 f8 nice +
 
 f9 kill 
 
 f10 quit

    CPU adalah berapa jumlah core yang kita miliki.
    Mem adalah total penggunaan memory.
    Swp adalah Memory cadangan.
    Tasks adalah aplikasi yang sedang berjalan di server.
    Load average adalah rata-rata aplikasi yang berjalan.
    Uptime adalah berapa lama server kita hidup.
    PID adalah nomor proses id setiap proses yang berjalan di linux.
    VIRT adalah memory yang terpakai.
    Command adalah perintah apa yang sedang di jalankan.
    
    
