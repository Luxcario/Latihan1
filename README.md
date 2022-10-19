# Assalamu'alaikum warohmatullohi wabarokatuhu 
hai nama saya Muhamad David ali
saya akan menjelaskan cara menggunakan git secara singkat.

# A.Penginstalan Git
Langkah pertama adalah penginstalan Git terlebih dahulu sebagai berikut:
	. Pertama pergi ke website www.git-scm.com
    
	. Pilih menu Download > lalu pilih device anda

	. Silakan download, tergantung dengan device anda apakah 32 bit atau 64 bit, disini saya memakai 64 bit
	
	. Jika sudah maka pergi ke file manager > download > file git yang sudah di download
	
	. Klik kanan > lalu run as administrator
	
	. Klik next sampai tahap penginstalan

  . setelah itu buka Git bash,ini adalah tampilan awalnya

# B.Membuat repository local
  Setelah membuka gitbash kita akan membuat repository local,caranya adalah sebagai berikut:
  . Sebelumnya pastikan file sudah berada di home atau dokumen lain,lalu buka direktory aktif di windows explorer
    disini saya menggunakan direktory c/user/..
    kita bisa berpindah directory dengan cara $ cd .. lalu cd d/nama_folder
    
  . Kita akan membuat repository dengan perintah $ mkdir nama_directory
          contoh : $ mkdir lab_komputer, $ mkdir tugas1
	  
  . Selanjutnya kita akan masuk kedalam directory menggunakan perintah $ cd nama_directory
  
  . Setelah itu kita akan membuat repository local dengan perintah $  git init
    
  . Sekarang kita akan membuat sebuah file (teks) dengan menggunakan perintah $ echo "# membuat teks" >> README.md
    
  . Sebelum kita menambahkan file kedalam repository,sebaiknya masukan perintah git config agar saat proses git commit tidak eror
  ($ git config --global user.name "nama.user"), 
  ($ git config --global user.email "email.user")
    
  . Setelah menambahkan git config untuk memasukan file kedalam repository kita gunakan perintah $ git add README.md
    
  . Untuk menyimpan perubahan kedalam database repository maka menggunakan perintah $ git commit -m "komentar"

# C.Membuat repository server
  Sekarang kita akan membuat repository server,langkahnya sebagai berikut
  . Masuk ke website git (www.github.com)
  . Lalu lakukan login / membuat akun terlebih dahulu
    
  . masukan email, password dan nama pengguna
   
  . setelah itu,ikuti perintah yang diarahkan oleh github.com
  
  . inilah tampilan awalnya,untuk membuat repository server klik icon "+" pojok kanan atas
    
  . masukan nama repository, klik create repository
    
# D.Mengirim perubahan
  Setelah kita membuat repository local dan repository server,kita akan mengirim file ke repository server caranya adalah sebagai berikut: 
  . kita akan menambahkan remote repository,fungsinya adalah menyimpan setiap perubahan pada repository local
    pada repository server ada link yang akan kita gunakan untuk menjalankan perintah $ git remote add origin [url]
    $ git remote add origin https://github.com/haritssalman/LatihanVCS.git
    
  . selanjutnya kita akan mengirim file ke repository server dengan perintah $ git push -u master
  
  . masukan nama user dan password
    
  . untuk memeriksa hasil,buka kembali website github > user > repository > klik repository
    
# CLONE REPOSITORY
  .Clone repository, pada dasarnya adalah meng-copy repository server dan secara otomatis membuat satu direktory sesuai dengan nama repositorynya (working directory).
Perintahnya adalah $ git clone [URL]

# Sekian bila kurang jelas mohon dimaafkan karena saya tidak kuat menahan ngantuk, saya menegrjakan ini ditengah malam meminjam komputer saudara saya, saya juga sudah tidak enak dengan beliau karna sudah larut, bila ingin lebih jelas liat di channel YouTube dosen saya pak Agung Nugroho 
sekian lagi maaf bila seadanya Terimakasih Wassalamu'alaikum warohmatullohi wabarokatuhu
