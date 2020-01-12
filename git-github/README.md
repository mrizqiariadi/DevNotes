# GIT & GITHUB FAST TRACK

Author: **Muhammad Rizqi Ariadi**

Linkedin: [Muhammad Rizqi Ariadi](https://www.linkedin.com/in/muhammad-rizqi-ariadi-bba168110/)

Facebook: [M Rizqi Ariadi](https://www.facebook.com/Muhammad.Rizqi.Ariadi)

Twitter : [M Rizqi Ariadi](https://twitter.com/MRizqiAriadi)

## Tujuan

Pada DevNotes kali ini, Anda akan mempelajari bagaimana cara membuat Repository pada GITHUB dan bagaimana menggunakan git dalam development aplikasi. Hasil dari DevNotes kali ini akan seperti ini:


## Tools yang dibutuhkan

* [GitHub Dekstop](https://desktop.github.com/) - GitHub Dekstop for Windows/Mac

* [Git](http://git-scm.com) - Git for All Platforms

Git distributions for Linux and POSIX systems are available on
the official Git SCM web site.

## Sejarah
Pada 2005, hubungan antara komunitas yang mengembangkan kernel Linux dan perusahaan komersil yang mengembangkan BitKeeper terputus, dan status bebas biaya dari alatnya dicabut. Hal ini mendesak komunitas pengembangan Linux (khususnya Linus Torvalds, pencipta Linux) untuk mengembangkan alat mereka sendiri berdasarkan beberapa pelajaran yang telah mereka pelajari ketika menggunakan BitKeeper. Beberapa sasaran dari sistem baru tersebut adalah sebagai berikut:

+ Kecepatan

+ Rancangan yang sederhana

+ Dukungan yang kuat untuk pengembangan non-linier (ribuan cabang paralel)

+ Benar-benar tersebar

+ Mampu menangani proyek besar seperti Linux secara efisien (kecepatan dan ukuran data)

Sejak kelahirannya pada 2005, Git telah berevolusi dan berkembang untuk dapat digunakan dengan mudah namun tetap memiliki kualitas awal tersebut. Git sangat cepat, sangat efisien dengan proyek-proyek besar, dan Git memiliki sistem percabangan yang hebat untuk pengembangan non-linear.
+ [Referensi](https://git-scm.com/book/id/v2/Memulai-Sejarah-Singkat-Git) - Sejarah GIT

## Join GITHUB
+ Membuka halaman [Join Github](https://github.com/join) → melakukan pendaftaran akun github → melakukan konfirmasi pada email anda.

  <img src="images/register_github.JPG" width="500" title="Join Github">

## DevNotes Buat Repositori dari GITHUB

1. Klik tombol → Tambah (__+__) → Memilih menu __new repository__.

    <img src="images/menu_create_github.JPG" width="350" title="Button +">

2. Buat *repository* baru di Github dengan kriteria sebagai berikut:

    | Perintah | Deskripsi |
    | --- | --- |
    | __Repository name__ | First-Repository |
    | __Description__ | Learning by doing |
    | __Public/Private__ | Public |
    | __Initialize this repository with a README__ | Check |

3. Klik tombol → *Create Repository* , maka akan membuat *repository* seperti ini:

    <img src="images/first_repository.JPG" width="800" title="Button +">
    
   - [x] Selamat anda telah berhasil membuat _repository_ baru


## DevNotes _Clone Repository_ dari GITHUB

1. Klik tombol → __Clone or download__ → memilih tombol copy URL / blok link URL (Copy)

    <img src="images/clone_repository.JPG" width="300" title="Button Clone">
    
    <img src="images/copy_link_repository.JPG" width="300" title="Button Copy Link URL">
    
2. Buka Command Prompt(CMD) anda, sebelum kita melakukan *clone repository* pastikan anda melihat *folder/directory* __Documents__ dengan menggunakan perintah __dir__ untuk menampilkan isi dari *folder* C:\Users\~username_anda.`Apabila anda sudah memahami perintah Command Prompt (CMD) silahkan letakkan pada folder/directory yang anda diinginkan.`

    ```diff
    Microsoft Windows [Version 6.3.9600]
    (c) 2013 Microsoft Corporation. All rights reserved.

    C:\Users\mhmmdrizqi>dir
     Volume in drive C has no label.
     Volume Serial Number is F6DF-BA88

     Directory of C:\Users\mhmmdrizqi

    01/12/2020  08:55 AM    <DIR>          .
    01/12/2020  08:55 AM    <DIR>          ..
    01/12/2020  08:55 AM               215 .gitconfig
    10/08/2019  07:03 PM    <DIR>          .LdVirtualBox
    07/13/2019  08:51 AM               186 .packettracer
    03/17/2019  11:41 PM    <DIR>          .ssh
    01/12/2020  07:37 AM               854 .viminfo
    02/17/2019  06:16 PM    <DIR>          .vscode
    07/13/2019  04:56 AM    <DIR>          Cisco Packet Tracer 7.2.1
    03/17/2019  04:03 PM    <DIR>          Contacts
    01/06/2020  10:18 PM    <DIR>          Desktop
    +01/12/2020  08:01 AM    <DIR>          Documents
    01/12/2020  07:04 AM    <DIR>          Downloads
    03/17/2019  04:03 PM    <DIR>          Favorites
    03/17/2019  04:03 PM    <DIR>          Links
    04/06/2019  11:28 AM    <DIR>          Music
    01/12/2020  09:52 AM    <DIR>          Pictures
    03/17/2019  04:03 PM    <DIR>          Saved Games
    04/17/2019  09:36 AM    <DIR>          Searches
    03/17/2019  04:03 PM    <DIR>          Videos
                   3 File(s)          1,255 bytes
                  17 Dir(s)  29,433,196,544 bytes free
    ```

3. Menggunakan perintah __CD__ untuk dapat masuk ke *folder/directory* __Documents__.

    ```
    C:\Users\mhmmdrizqi>cd Documents
    C:\Users\mhmmdrizqi\Documents>
    ```

4. Selanjutnya, lakukan _clone_ dengan perintah __git clone YOUR-URL-REPOSITORY__ sebagai berikut:

    ```diff
    C:\Users\mhmmdrizqi\Documents>git clone https://github.com/<username>/First-Repository.git
    ```
5. Tunggu sampai proses download _repository_ selesai seperti ini:

     <img src="images/clone_cmd_github.JPG" width="500" title="Clone CMD">
     
6. Selamat anda sudah berhasil melakukan clone dari GITHUB ke lokal komputer.

     <img src="images/folder_first_repository.JPG" width="500" title="Result Clone">
     
   - [x] Selamat anda telah berhasil melakukan _clone repository_
