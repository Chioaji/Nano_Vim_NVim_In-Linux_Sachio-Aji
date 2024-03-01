Penggunaan Nano,Vim,NVim pada os linux

A. Nano
   1. Nano" adalah salah satu editor teks sederhana yang sering digunakan pada sistem operasi Linux. Ini adalah pilihan yang populer bagi pengguna yang mencari editor yang mudah digunakan dan memiliki antarmuka yang intuitif.
   Untuk mengakses Nano kita perlu memasukkan command  nano "diisi dengan nama file  .dan beri format file  ." sebagai contoh
   
          Nano Mahasiswa.txt
      <img src="https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/ae2a6a05-7f59-4de0-8bd4-5ab1ce677475" width="500" height="100">

   2. Jika telah masuk ke file editor nya kita tinggal ketik kata kata yang ingin kita masukkan, untuk menyimpan dan keluar dari file editor kita perlu tekan `ctrl + x` dan `y` lalu enter
   
      <img src="https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/adfde5a2-8fd7-469c-be68-07a605c5688c" width="500" height="250">

   3. Untuk menampilkan text dari file tadi kita perlu memasukkan command `cat` dibarengi dengan nama file tadi sebagai contoh
       
          cat Mahasiswa.txt
        
      <img src="https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/ded56f57-a3d4-42f4-a563-69d4f158cea4" width="500" height="200">

B. Vim
   1. Vim adalah editor teks yang sangat kuat dan fleksibel yang sering digunakan di lingkungan Unix dan Linux. Vim, singkatan dari "Vi Improved," adalah pengembangan dari editor teks vi yang klasik, yang pertama kali muncul pada awal tahun 1970-an.
   keunggulan `Vim` dibandingkan dengan `Nano` adalah Vim unggul dari Nano dalam fleksibilitas, modal editing, pintasan keyboard, ekosistem plugin, dan portabilitas.Untuk mengakses Vim caranya sama seperti nano yaitu

          vim"Nama file.txt"

      ![1 vim](https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/d9500e0c-2b50-49e5-89b7-ef9192a3fa31)

   2. Jika kita ingin memasukkan teks caranya berbeda dari nano yaitu kita harus klik `i` agar masuk ke mode insert. jika sudah kita klik `escape` dan klik `:` dan ketik `wq` untuk menyimpan dan keluar dari vim
   
      <img src="https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/67e0552a-50de-4bcf-81ff-80d468358429" width="400" height="200">

   3. Untuk menampilkan isi file sama caranya dengan menggunakan `cat`
   
      <img src="https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/dfa5dbdb-3919-4214-88cd-abd4d85ca1a9" width="500" height="200">

 C. NVim
 
   1. NVim, atau NeoVim, adalah fork dari Vim yang bertujuan untuk memodernisasi dan memperbaiki beberapa aspek dari Vim yang sudah ada. Meskipun masih mempertahankan banyak fitur dan filosofi desain dari Vim, NVim memiliki beberapa perbedaan dan peningkatan yang signifikan. Untuk mengakses seperti biasa yaitu
             
          nvim "nama file.format"
  
      ![1 nvim](https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/57cebf0b-b62d-4e39-9425-7118b1f23ffe)
      
   2. Untuk cara memasukkan teks sama seperti vim yaitu  klik `i` agar masuk ke mode insert. jika sudah kita klik `escape` dan klik `:` dan ketik `wq` untuk menyimpan dan keluar dari vim
  
      ![2 nvim](https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/67933747-ae11-4f79-b542-45de860df99d) 

   3. Menampilkan isi file dengan `cat`
    
      ![3 nvim](https://github.com/Chioaji/Nano_Vim_NVim_In-Linux_Sachio-Aji/assets/126127582/67913e28-3818-4dd4-9bf0-7b0b877569da)

