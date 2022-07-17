# Unix Command Line

## Introducing CLI

![](/Picture/CLI.jpg "CLI")

Unix Command Line adalah antarmuka pengguna berbasis teks ( UI ) yang digunakan untuk menjalankan program, mengelola file komputer, dan berinteraksi dengan komputer. Command Line Interface juga disebut antarmuka pengguna baris perintah , antarmuka pengguna konsol , dan antarmuka pengguna karakter . CLI menerima sebagai perintah input yang dimasukkan oleh keyboard; perintah yang dipanggil pada prompt perintah kemudian dijalankan oleh komputer.

## Bagaimana Cara Kerja CLI? 

Setelah sistem komputer berjalan, CLI-nya terbuka di layar kosong dengan prompt perintah dan perintah dapat dimasukkan.

Jenis perintah CLI meliputi:

- perintah sistem yang dikodekan sebagai bagian dari antarmuka sistem operasi;
- program yang dapat dieksekusi yang, ketika berhasil dipanggil, menjalankan aplikasi  berbasis teks atau grafis ;
- dan program batch (atau file batch  atau shell script) yang merupakan file teks yang mencantumkan urutan perintah. Ketika berhasil dipanggil, program batch menjalankan

perintahnya yang mungkin mencakup perintah sistem dan program yang dapat dieksekusi.
CLI lebih dari sekadar sistem perintah/tanggapan sederhana, karena sebagian besar memiliki fitur tambahan yang membuat satu lebih disukai daripada yang lain.

## Shell

Shell adalah program yang menjembatani user dengan sistem operasi (kernel). Dengan adanya shell kita bisa menjalankan suatu perintah pada sistem operasi.

## Contoh CLI

- SH
- bash
- zsh
- cmd.exe

## File System
Jadi File System ini adalah sebuah proses yang mengatur di mana dan bagaimana sebuah data disimpan dan diakses dalam disk penyimpanan. Nah, disk penyimpanan yang paling umum digunakan adalah hard disk drive (HDD), hard drive, atau storage device lainnya.

Intinya, filesystem ini mengatur pengoperasian di dalam sebuah disk yang terhubung ke komputer, tetapi tidak bisa terlihat oleh user atau manusia yang menggunakan komputer tersebut. Hal-hal yang biasa diatur meliputi storage management, pemberian nama pada file, folder–folder, metadata, pengaturan mengenai akses data, dan lainnya.

## Command "pwd"
Perintah dasar Linux pwd berfungsi untuk mencari path dari direktori (folder) yang Anda gunakan saat ini. Perintah ini akan mengembalikan path yang absolut (penuh), yang pada dasarnya merupakan path semua direktori yang diawali dengan garis miring depan (/). Contoh dari path absolut adalah /home/username.

## Command "ls"
Is merupakan perintah dasar pada Linux yang digunakan untuk melihat konten atau isi direktori. Secara default, command ini akan menampilkan isi dari direktori yang Anda gunakan saat ini.

## command "cd"
Untuk menjelajahi file dan direktori Linux, gunakan perintah cd. Perintah Linux ini memerlukan path penuh atau nama direktori, tergantung pada direktori yang Anda gunakan saat ini.

## command "head"
Perintah head digunakan untuk melihat baris pertama dari semua file teks. Secara default, perintah ini akan menampilkan sepuluh baris pertama. Namun, jumlah baris tersebut dapat diubah sesuai keinginan Anda. Misalnya, jika Anda hanya ingin menampilkan lima baris pertama, ketik head -n 5 filename.ext

## command "tail"
Perintah tail memiliki fungsi yang sama dengan perintah head. Hanya saja, alih-alih baris pertama, perintah tail akan menampilkan sepuluh baris terakhir dari suatu file. Misalnya, tail -n filename.ext.

## command "cat"
cat (akronim dri concatenate) adalah salah satu perintah dasar sistem operasi Linux yang sering digunakan. Perintah ini berfungsi untuk membuat daftar konten atau isi file pada standard output (sdout). Untuk menjalankan command ini, ketik cat yang kemudian diikuti dengan nama dan ekstensi file.

## command "touch"
touch adalah perintah dasar Linux yang memperbolehkan Anda membuat file baru yang kosong melalui baris perintah Linux. Sebagai contoh, ketik touch /home/username/Documents/Web.html untuk membuat file HTML berjudul Web di bawah direktori Documents.

## command "mkdir"
Untuk membuat direktori baru, Anda bisa menggunakan perintah dasar Linux mkdir. Sebagai contoh, jika Anda mengetik mkdir Music, direktori baru yang muncul disebut Music.

## command "cp"
Gunakan perintah dasar Linux cp untuk menyalin file dari direktori saat ini ke direktori yang berbeda. Misalnya, command cp scenery.jpg /home/username/Pictures untuk membuat salinan scenery.jpg (dari direktori saat ini) ke direktori Pictures.

- "cp -R" untuk menyalin directory

## command "mv"
Fungsi utama command mv adalah untuk memindahkan file meskipun sebenarnya bisa digunakan untuk mengganti atau mengubah nama file.

Argumen yang ada di mv serupa dengan argumen yang ada di perintah cp. Ketik mv, nama file, dan direktori tujuan. Contoh: mv file.txt /home/username/Documents.

- "mv -R" untuk memindahkan directory

## command "rm"
rm adalah perintah dasar pada Linux yang berfungsi untuk menghapus direktori beserta isinya. Jika hanya ingin menghapus direktorinya saja – alternatif command selain rmdir – gunakan rm -r.

# GIT

## Mengenal GIT
Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.

Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.

Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

## Perintah Dasar GIT
Beerikut ini beberapa perintah dasar dari GIT :

- GIT init ini untuk membuat sebuah repository yang berada pada file lokal dimana nantinya file tersebut bernama .git.
- GIT status ini untuk mengetahui status dari sebuah repository lokal.
- GIT add ini untuk menambahkan file baru yang ada pada repository yang telah dipilih.
- GIT commit ini untuk menyimpan perubahan yang telah dilakukan.
- GIT push ini digunakan untuk mengirimkan perubahan file setelah di commit ke remote repository.
- GIT branch ini melihat seluruh branch yang ada dalam repository.
- GIT checkout ini dapat menukar branch yang aktif dengan branch yang telah dipilih.
- GIT merge ini untuk menggabungkan branch yang aktif dan yang telah dipilih.
- GIT clone ini dapat membuat salinan repository lokal.

## Fitur GIT

Berikut fitur-fitur yang ada pada GIT:

1. **Version control system yang terdistribusi**

    GIT ini menggunakan pendekatan peer to peer, dimana tidak seperti Subversion atau SVN dimana menggunakan model client server.

2. **GIT memungkinkan developer untuk memiliki branch kode**

    GIT disini memungkinkan para developer memiliki branch kode yang independent dan juga massive. Membuat, menghapus dan juga menggabungkan branch menjadi lebih cepat, lancar serta tidak membutuhkan waktu lama.

3. **GIT bersifat atomic**

    Bersifat atomic merupakan sebuah tindakan yang akan benar-benar diselesaikan dengan lengkap atau bisa juga sama sekali gagal.

    Hal ini akan sangat penting karena pada beberapa version control system seperti CVS operasinya bersifat non atomic.

    Bila ada operasi yang tergantung dan terkait dengan repository maka kondisi repository akan menjadi tidak stabil.

4. **Media penyimpanan GIT berada dalam folder .git**

    Berbeda dari VCS lain seperti CVS dan atau SVN dimana metadata file disimpan dalam folder yang tersembunyi seperti .svn, .cvs, dan juga .etc.

5. **GIT memiliki data model**

    GIT ini memiliki data model yang bisa membantu memastikan integritas cryptographic yang berada di dalam repository. Sehingga pada setiap kali sebuah file ditambahkan ataupun di commit, checksum nya akan diciptakan sama seperti retrieve melalui checksum nya juga.

6. **GIT memiliki staging area atau index**

    Dengan adanya stagin area ini, para developer dapat memformat commit serta dapat membuatnya dapat di review sebelum benar diterapkan.

7. **GIT sederhana dalam penggunaannya**

    Untuk dapat memulai Anda dapat membuat repository ataupun men checkout yang telah ada.

# HTML

![](/Picture/HTML.jpg "HTML")

## Pengertian HTML

Hypertext Markup Language atau HTML adalah bahasa markup yang digunakan untuk membuat sebuah halaman web. Isinya terdiri dari berbagai kode yang dapat menyusun struktur suatu website.

HTML terdiri dari kombinasi teks dan simbol yang disimpan dalam sebuah file. Dalam membuat file HTML, terdapat standar atau format khusus yang harus diikuti. Format tersebut telah tertuang dalam standar kode internasional atau ASCII (American Standard Code for Information Interchange). Mengenal Tag HTML, Elemen, dan Atribut Setelah mengetahui bagaimana sejarah dari HTML, sekarang Anda perlu tahu komponen-komponen yang terdapat pada HTML.

## TAG HTML

| Syntax | Description |
| ----------- | ----------- |
| html | Tag untuk membuat sebuah dokumen HTML |
| title | Tag untuk membuat judul dari sebuah halaman |
| body | Tag untuk membuat tubuh dari sebuah halaman |
| h1 to h6 | Tag untuk membuat heading |
| p | Tag untuk membuat paragraf |
| br | Memasukan satu baris putus |
| hr | Tag untuk membuat perubahan dasar kata didalam isi |
| !--..-- | Tag untuk membuat komentar |

untuk tag HTML lebih lengkap bisa akses link [W3SCHOOL](https://www.w3schools.com/)

# CSS

![](/Picture/css.png "CSS")

## Pengertian CSS

CSS adalah singkatan dari cascading style sheets, yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website. Dengan CSS, Anda bisa mengatur jenis font, warna tulisan, dan latar belakang halaman. CSS digunakan bersama dengan bahasa markup, seperti HTML dan XML untuk membangun sebuah website yang menarik dan memiliki fungsi yang berjalan baik.CSS juga berguna untuk mengatasi keterbatasan HTML dalam mengatur format halaman website.

## Contoh CSS

    body {
    background-color: lightblue;
    }
    h1 {
    color: white;
    text-align: center;
    }
    p 
    {
    font-family: verdana;
    font-size: 20px;
    }

## Jenis Jenis CSS

Jenis jenis CSS dibagi menjadi tiga berdasarkan penempatan kodenya, yaitu:

1. Inline CSS

    Inline CSS adalah kode CSS yang dituliskan di dalam file HTML. Jenis CSS ini hanya mempengaruhi satu baris kode HTML.

    Perhatikan baris kode di bawah ini sebagai contohnya:

        <h1  style="font-size:30px;color:blue;">Cek beritama utama ini!</h1>

    Dengan kode tersebut, Anda akan mendapatkan hasil ini:

     <h1  style="font-size:30px;color:blue;">Cek beritama utama ini!</h1>

     Inline CSS tidak bisa diaplikasikan ke semua halaman website sekaligus. Namun, jenis CSS ini tepat digunakan ketika Anda ingin membuat elemen HTML dengan format khusus di sebuah halaman.

2. Internal CSS

    Internal CSS dituliskan di bagian header file HTML. Fungsinya untuk menentukan tampilan sebuah halaman. 

    Contohnya, jika Anda ingin agar halaman memiliki latar belakang biru dan teks berukuran 20px yang berwarna putih, kodenya seperti di bawah ini:

        <head>
        <style>
        Body  { background-color:blue;  }
        P  { font-size:20px;  color:white;  }
        </style>
        </head>

        <p>Ini adalah contoh kalimat.</p>

    Internal CSS sangat membantu ketika Anda ingin membuat halaman website yang tampilannya berbeda dari halaman lain.

3. External CSS

    Sesuai namanya, external CSS adalah kode CSS yang diletakkan di luar dokumen HTML sebagai file .css. Jenis CSS ini berfungsi untuk mengatur tampilan semua halaman website yang Anda tentukan. Jadi, external CSS berguna ketika Anda ingin mengatur tampilan beberapa halaman sekaligus.

    Agar halaman website bisa menggunakan external CSS, Anda perlu menambahkan kode di bagian header kode HTML-nya. Contohnya seperti berikut ini:

        <head>
        <link rel="stylesheet"  type="text/css"  href=fileCSSAnda.css">
        </head>
        
    Dengan kode tersebut, halaman website Anda akan menggunakan fileCSSAnda.css untuk mengatur tampilannya.

    Sekarang Anda sudah tahu bagaimana masing-masing jenis CSS dibuat dan dampaknya pada halaman website, kan? Tapi, bagaimana cara kerja CSS ketika website dimuat? Mari simak penjelasannya di bawah ini.