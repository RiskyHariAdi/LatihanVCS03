# LatihanVCS03

**Nama :RiskyHariAdi** <br>

**Nim  :312010124** <br>

**Kelas:TI.20.A1** <br>

## Langkah-Langkah Penggunaan Git

* Dwonload git terlebih dahulu, dengan link berikut : [click here](https://git-scm.com) <br>

![gitscm](poto/GitScm.png)

* setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini : [Git installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) <br>


![installing](poto/installing.png) <br>

* setelah installasi selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan **versi**, dengan mengetik *syntax* berikut : <br>

`git --version` <br>

![git version](poto/version.png) <br>

* jika muncul tampilan **git version**,berarti Git sudah **berhasil di install** dan bisa di **gunakan** Langkah pertama kita harus **mengkonfirmasikan user name** dan **email di git**, dengan mengetikkan *syntax* berikut : <br>

`git commit --global user.name "masukkan nama anda"` <br>

`git commit --global user.email "masukkan email anda"` <br>

![Git Config](poto/gitnamaemailbaru.png) <br>

* Buat akun di **GitHub**, seperti contoh dibawah ini. Dan lakukan verifikasi akun melalui email yang sudah terdaftar.

* Jika akun  **GitHub** sudah selesai dibuat dan di verifikasi, proses selanjutnya silahkan buat Repository seperti gambar dibawah ini : <br>
**Penjelasan**

> * `Repository Name : (silahkan isi nama repository yang diinginkan seperti contoh saya ingin membuat repository Latihan VCS 03)` <br>

> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)` <br>

> * `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)` <br>

> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda` <br>

> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.` <br>

> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan` <br>

![Nama Repository](poto/githubrepisotory.png) <br>

* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini : <br>

![Akun File Baru](poto/hasilfile.png) <br>

* Pembuatan akun dan repository pada **GitHub** telah selesai, saat ini akan kita lakukan untuk me-remote repository **GitHub** pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di **GitHub**, dengan cara tekan tombol Code lalu klik Copy. <br> 

![Clone](poto/githublink.png) <br>

* Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari **GitHub** ke lokal. Kemudian Klik Kanan, Pilih **Git Bash Here.** <br>

![GitBash](poto/visual.png) <br>

*  *Pop Up* Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut : <br>

`git clone [URL] pada contohnya, saya akan memasukan git clone`https://github.com/RiskyHariAdi/LatihanVCS03.git
