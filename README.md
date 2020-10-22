# LatihanVCS1

nama:faizal dwianto

kelas:TI.20.A1

nim:312010467

### LANGKAH AWAL MENGGUNAKAN GIT

* ### CARA MENDOWNLOAD GIT
   - Hal pertama yang perlu kita lakukan jika ingin menggunakan aplikasi git tentu saja yaitu mendownloadnnya. Bagaimana caranya? Pertama kalian bukalah situs resmi dari git itu sendiri yaitu *git-scm.com*.
  
   - Setelah kalian mendapat tampilan seperti dibawah ini kalian bisa langsung saja mendownloadnya dengan cara memilih terlebih dahulu yang sesuai dengan komputer atau laptop kalian apakah itu 32bit atau 64bit. Setelahnya kalian bisa langsung menekannya dan akan terdownload otomatis.

![1](https://user-images.githubusercontent.com/72906579/96366907-cee62580-1174-11eb-9649-79f84b038f5b.png)

   - Setelah installasi terbuka, kalian bisa langsung membuka software *gitbash* pada menu windows kalian dan melakukan pengecekan versi dari git kalian dengan mengetikan syntax: *git --version*
  
   - jika sudah mendapat tampilan seperti gambar dibawah ini, itu mengartikan bahwa git kalian telah berhasil terinstall.
  
![Screenshot (51)](https://user-images.githubusercontent.com/72909858/96850641-4243ac00-1481-11eb-8ced-851e56f8067d.png)

   - Selanjutnya yang perlu kita lakukan adalah mengkonfigurasikan username & email kita pada git dengan mengetikan syntax: *'git config --global user.name "Nama Anda"'  'git config --global user.email "Email Anda"'*. Seperti pada gambar dibawah.
  
![Screenshot (52)](https://user-images.githubusercontent.com/72909858/96850644-4374d900-1481-11eb-8c7b-401d8a0f656c.png)

   - Jika sudah, lakukanlah pengecekan untuk mengetahui apakah kita sudah terdaftar atau belum dengan mengetikan syntax: *'git config --global user.name'  'git config --global user.email'*. Seperti pada gambar dibawah.
  
![Screenshot (53)](https://user-images.githubusercontent.com/72909858/96850649-440d6f80-1481-11eb-86fe-cfb2ed49dae7.png)

### LANGKAH AWAL MENGGUNAKAN GITHUB

* ### LOGIN AKUN GITHUB
  - Bukalah Github pada situs resminya yaitu *github.com*. Setelah itu pilih menu Sign Up yang terletak pada pojok kanan atas jika memang belum mempunyai akun.
  
![Screenshot (19)](https://user-images.githubusercontent.com/72906579/96261495-b9dd8b00-0fea-11eb-965a-9b26f0ba76e0.png)


  - Kemudian, isilah data & email kalian dengan benar.
  
![Screenshot (20)](https://user-images.githubusercontent.com/72906579/96261506-bcd87b80-0fea-11eb-8b18-8940821bddc1.png)


  - Setelah itu lakukanlah verifikasi gambar, dan tekan pada bagian *'create account'*.
  
![Screenshot (22)](https://user-images.githubusercontent.com/72906579/96261510-be09a880-0fea-11eb-939f-d0f73589e1b1.png)


  - Silahkan mengecek email yang sama dengan yang digunakan pada saat mendaftar tadi untuk melakukan verifikasi.

![Inked4_LI](https://user-images.githubusercontent.com/72906579/96267990-adf5c700-0ff2-11eb-82bb-3cb06cdee4cb.jpg)


  - Setelah terdapat notif dari Github pada email kalian, segera lakukanlah verifikasi sebelum terjadi error (kadaluarsa).
  
![Inked5_LI](https://user-images.githubusercontent.com/72906579/96268077-d087e000-0ff2-11eb-9c15-0d040e9ef587.jpg)


# SELANJUTNYA ADALAH LANGKAH MEMBUAT REPOSITORY..


### CARA MEMBUAT REPOSITORY PADA GITHUB

  - Bukalah profile kalian, kemudia pilih dibagian *start a project*, atau bisa juga dengan menekan lambang (+) pada bagian pojok kanan atas.
  - Setelahnya kamu dapat pergi pada tulisan *'New Repository'*
  
![Screenshot (47)](https://user-images.githubusercontent.com/72909858/96850614-36f08080-1481-11eb-971d-86f3efdc1368.png)

  - Tulislah judul yang kalian inginkan. Kalian'pun juga bisa mengatur Repository yang akan kalian buat menjadi Privasi ataupun Publik.

  - Pilih kolom yang bertuliskan 'README file' pada pilihan yang diberikan.

 - Setelah itu arahkan kursor pada bagian *'Create Repository'*

![Screenshot (54)](https://user-images.githubusercontent.com/72909858/96850653-453e9c80-1481-11eb-8cb8-7cfe593cc805.png)


 - Setelah mendapat tampilan seperti gambar dibawah, berarti Repository kalian sudah berhasil dibuat. dan kalian juga bisa tekan pada tulisan 'README' yang berwarna biru untuk membukanya.

 - Jika ingin menulis sesuatu atau mengedit sebuah teks yang sudah ada sebelumnya pada lembar kerja, kalian bisa menekan gambar pensil seperti pada gambar dibawah ini.

![Screenshot (14)](https://user-images.githubusercontent.com/72906579/96259174-6f0e4400-0fe7-11eb-817d-f89aee7f3614.png)


 - Tekan pada kolom 'Commit Changes' jika kalian ingin menyimpan hasil kerja kalian ataupun setelah kalian melakukan perubahan pada lembar kerja kalian.
 
 ![Screenshot (22)](https://user-images.githubusercontent.com/72906579/96267209-bdc0db80-0ff1-11eb-9a6c-32da7d9cbb17.png)

# SETELAH PEMBUATAN AKUN DAN REPOSITORY TELAH SELESAI SELANJUTNYA KITA AKAN ME-REMOTE REPOSITORY PADA GITBASH LOKAL.


### CARA ME-REMOTE REPOSITORY PADA GITBASH

  - Langkah pertama, kita harus menyalin terlebih dahulu link URL git kita yang ada pada Github, dengan cara tekan tombol 'Code' lalu kalian pilih pada kolom 'https://' dan setelahnya kalian Copy.

![12](https://user-images.githubusercontent.com/72906579/96370692-e8916800-1188-11eb-9b5c-e989f70e92e7.png)

  - Setelah Link URL git kita sudah tercopy. Selanjutnya, silahkan buka File Explorer pada Windows kalian. Kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. 
  
  - Kemudian kalian Klik Kanan, dan tekan pada kolom *'Git Bash Here'*.
  
![5](https://user-images.githubusercontent.com/72906579/96366931-f210d500-1174-11eb-9b6d-8a959f822937.png)

  - Setelahnya pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax: *'git clone "link URL yang sebelumnya telah kalian copy"'*.

![Screenshot (46)](https://user-images.githubusercontent.com/72906579/96674488-1fd36500-1393-11eb-89df-5f425ccaf686.png)

  - Setelah proses cloning telah selesai, pada saat ini kita masih berada pada folder awal yang dimana kita harus masuk kedalam folder yang telah kita cloning tadi yaitu *'LatihanVCS'* dengan cara mengetikkan syntax: *'cd LatihanVCS/'*

![Screenshot (47)](https://user-images.githubusercontent.com/72906579/96674490-219d2880-1393-11eb-91b5-f485cafb04de.png)

  - Setelahnya kita akan masuk kedalam folder *LatihanVCS* seperti gambar dibawah ini. Kalian bisa mengedit file README.md kalian yang ada pada File Explorer dengan menggunakan Text Editor (Sublime Text, Notepad, Notepad++, Visual Studio Code) sesuai dengan keinginan kalian. Tapi jika disini saya menggunakan notepad untuk mengeditnya.
  
  - Setelah selesai mengedit jangan lupa untuk menyimpannya dengan cara menekan tombol file yang berada dipojok kiri  atas dan pilihlah kolom save.
  
![8](https://user-images.githubusercontent.com/72906579/96366941-f9d07980-1174-11eb-8641-6a1a6c7defca.png)

  - Setelah sudah dapat dipastikan benar-benar tersimpan. Langkah selanjutnya adalah membuka kembali App Gitbash dan mengetikan syntax: *'git add .'*
  
![9](https://user-images.githubusercontent.com/72906579/96366945-fe952d80-1174-11eb-9a24-c10601901933.png)

  - Jika sudah, langkah berikutnya kita akan melakukan *commit*. Yang dimana fungsi commit itu sendiri adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak terjadi perubahan pada remote repository. Caranya dengan mengetikan syntax: *'git commit "Update README.md'*.
  
![10](https://user-images.githubusercontent.com/72906579/96367987-415a0400-117b-11eb-8419-231fd0855537.png)

  - Setelah git commit selesai di lakukan. Untuk saat ini kita akan melakuka Git Push, yang dimana arti Git Push itu sendiri berfungsi untuk mengirimkan perubahan file yang telah di commit ke remote repository. Kalian hanya perlu mengetikan syntax: *'git push'*.
  
![11](https://user-images.githubusercontent.com/72906579/96367990-4323c780-117b-11eb-877a-cae54ba73aa4.png)

JIKA SEMUA PROSES DIATAS SUDAH DILAKUKAN SEMUA TANPA ADA YANG TERLEWAT. KALIAN BISA LANGSUNG MELIHAT ATAU MENGECEK PERUBAHAN REPOSITORY YANG TELAH DI COMMIT DAN DI PUSH DARI REMOTE DENGAN CARA MEMBUKANYA PADA GITHUB KALIAN SENDIRI.


![Screenshot (48)](https://user-images.githubusercontent.com/72909858/96850633-3d7ef800-1481-11eb-92cc-7d92a7dd74eb.png)
![Screenshot (49)](https://user-images.githubusercontent.com/72909858/96850639-3fe15200-1481-11eb-8156-8db4f2ea3ae4.png)

![Screenshot (50)](https://user-images.githubusercontent.com/72909858/96850640-41ab1580-1481-11eb-8676-b16e25f5aabc.png)


![Screenshot (55)](https://user-images.githubusercontent.com/72909858/96850657-45d73300-1481-11eb-8f94-93d3e6f1a2ec.png)
![Screenshot (56)](https://user-images.githubusercontent.com/72909858/96850660-466fc980-1481-11eb-92c6-70de2a1b6c46.png)
