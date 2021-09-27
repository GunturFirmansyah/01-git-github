Langkah untuk membuat Repository
  1. Instalasi Git
      - Download Git terlebih dahulu di https://git-scm.com/downloads
      - Buka file Git dan lakukan instalasi
      - Pilih lokasi instalasi, Sudah tersedia lokasi default tapi bisa di ubah
      - Pilih komponen yang diperlukan
      - Klik Install
      - Untuk mengecek sudah terinstall atau belum buka Command Prompt, eksekusi "git --version"
      
  2. Cara membuat Repository
      - Buka link https://github.com/
      - Create account jika belum punya dan Sign in untuk yang sudah memiliki akun
      - Untuk mengecek Konfigurasi bisa menggunakan perintah "git config --list"
      - Setelah berhasil login Klik tanda "+" pada sisi kanan di sebelah profil
      - Pilih New Repository
      - Isi Nama dan Lisensi
      - Klik Creat Repository
      
  3. Clone Repository
      - Untuk proses clone gunakan perintah "git clone https://github.com/username/namarepository"
      - Apabila Repository yg di clone masih kosong maka akan ada pemberitahuan, tapi tidak masalah
      - Saat baru di clone branch utamanya adalah master dan untuk mengubah menjadi main gunakan perintah
        $cd namarepository
        $git branch -m main
      
      
