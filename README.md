# LatihanVCS1

nama:faizal dwianto

kelas:TI.20.A1

nim:312010467
LANGKAH AWAL MENGGUNAKAN GIT
CARA MENDOWNLOAD GIT
Hal pertama yang perlu kita lakukan jika ingin menggunakan aplikasi git tentu saja yaitu mendownloadnnya. Bagaimana caranya? Pertama kalian bukalah situs resmi dari git itu sendiri yaitu git-scm.com.

Setelah kalian mendapat tampilan seperti dibawah ini kalian bisa langsung saja mendownloadnya dengan cara memilih terlebih dahulu yang sesuai dengan komputer atau laptop kalian apakah itu 32bit atau 64bit. Setelahnya kalian bisa langsung menekannya dan akan terdownload otomatis.

1

Setelah installasi terbuka, kalian bisa langsung membuka software gitbash pada menu windows kalian dan melakukan pengecekan versi dari git kalian dengan mengetikan syntax: git --version

jika sudah mendapat tampilan seperti gambar dibawah ini, itu mengartikan bahwa git kalian telah berhasil terinstall.

2

Selanjutnya yang perlu kita lakukan adalah mengkonfigurasikan username & email kita pada git dengan mengetikan syntax: 'git config --global user.name "Nama Anda"' 'git config --global user.email "Email Anda"'. Seperti pada gambar dibawah.
3

Jika sudah, lakukanlah pengecekan untuk mengetahui apakah kita sudah terdaftar atau belum dengan mengetikan syntax: 'git config --global user.name' 'git config --global user.email'. Seperti pada gambar dibawah.
4

LANGKAH AWAL MENGGUNAKAN GITHUB
LOGIN AKUN GITHUB
Bukalah Github pada situs resminya yaitu github.com. Setelah itu pilih menu Sign Up yang terletak pada pojok kanan atas jika memang belum mempunyai akun.
Screenshot (19)

Kemudian, isilah data & email kalian dengan benar.
Screenshot (20)

Setelah itu lakukanlah verifikasi gambar, dan tekan pada bagian 'create account'.
Screenshot (22)

Silahkan mengecek email yang sama dengan yang digunakan pada saat mendaftar tadi untuk melakukan verifikasi.
Inked4_LI

Setelah terdapat notif dari Github pada email kalian, segera lakukanlah verifikasi sebelum terjadi error (kadaluarsa).
Inked5_LI

SELANJUTNYA ADALAH LANGKAH MEMBUAT REPOSITORY..
CARA MEMBUAT REPOSITORY PADA GITHUB
Bukalah profile kalian, kemudia pilih dibagian start a project, atau bisa juga dengan menekan lambang (+) pada bagian pojok kanan atas.
Setelahnya kamu dapat pergi pada tulisan 'New Repository'
Screenshot (9)

Tulislah judul yang kalian inginkan. Kalian'pun juga bisa mengatur Repository yang akan kalian buat menjadi Privasi ataupun Publik.
Screenshot (10)

Pilih kolom yang bertuliskan 'README file' pada pilihan yang diberikan.
Screenshot (11)

Setelah itu arahkan kursor pada bagian 'Create Repository'
Screenshot (12)

Setelah mendapat tampilan seperti gambar dibawah, berarti Repository kalian sudah berhasil dibuat. dan kalian juga bisa tekan pada tulisan 'README' yang berwarna biru untuk membukanya.
Screenshot (13)

Jika ingin menulis sesuatu atau mengedit sebuah teks yang sudah ada sebelumnya pada lembar kerja, kalian bisa menekan gambar pensil seperti pada gambar dibawah ini.
Screenshot (14)

Tekan pada kolom 'Commit Changes' jika kalian ingin menyimpan hasil kerja kalian ataupun setelah kalian melakukan perubahan pada lembar kerja kalian.
Screenshot (22)

SETELAH PEMBUATAN AKUN DAN REPOSITORY TELAH SELESAI SELANJUTNYA KITA AKAN ME-REMOTE REPOSITORY PADA GITBASH LOKAL.
CARA ME-REMOTE REPOSITORY PADA GITBASH
Langkah pertama, kita harus menyalin terlebih dahulu link URL git kita yang ada pada Github, dengan cara tekan tombol 'Code' lalu kalian pilih pada kolom 'https://' dan setelahnya kalian Copy.
12

Setelah Link URL git kita sudah tercopy. Selanjutnya, silahkan buka File Explorer pada Windows kalian. Kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal.

Kemudian kalian Klik Kanan, dan tekan pada kolom 'Git Bash Here'.

5

Setelahnya pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax: 'git clone "link URL yang sebelumnya telah kalian copy"'.
Screenshot (46)

Setelah proses cloning telah selesai, pada saat ini kita masih berada pada folder awal yang dimana kita harus masuk kedalam folder yang telah kita cloning tadi yaitu 'LatihanVCS' dengan cara mengetikkan syntax: 'cd LatihanVCS/'
Screenshot (47)

Setelahnya kita akan masuk kedalam folder LatihanVCS seperti gambar dibawah ini. Kalian bisa mengedit file README.md kalian yang ada pada File Explorer dengan menggunakan Text Editor (Sublime Text, Notepad, Notepad++, Visual Studio Code) sesuai dengan keinginan kalian. Tapi jika disini saya menggunakan notepad untuk mengeditnya.

Setelah selesai mengedit jangan lupa untuk menyimpannya dengan cara menekan tombol file yang berada dipojok kiri atas dan pilihlah kolom save.

8

Setelah sudah dapat dipastikan benar-benar tersimpan. Langkah selanjutnya adalah membuka kembali App Gitbash dan mengetikan syntax: 'git add .'
9

Jika sudah, langkah berikutnya kita akan melakukan commit. Yang dimana fungsi commit itu sendiri adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak terjadi perubahan pada remote repository. Caranya dengan mengetikan syntax: 'git commit "Update README.md'.
10

Setelah git commit selesai di lakukan. Untuk saat ini kita akan melakuka Git Push, yang dimana arti Git Push itu sendiri berfungsi untuk mengirimkan perubahan file yang telah di commit ke remote repository. Kalian hanya perlu mengetikan syntax: 'git push'.
11

JIKA SEMUA PROSES DIATAS SUDAH DILAKUKAN SEMUA TANPA ADA YANG TERLEWAT. KALIAN BISA LANGSUNG MELIHAT ATAU MENGECEK PERUBAHAN REPOSITORY YANG TELAH DI COMMIT DAN DI PUSH DARI REMOTE DENGAN CARA MEMBUKANYA PADA GITHUB KALIAN SENDIRI.