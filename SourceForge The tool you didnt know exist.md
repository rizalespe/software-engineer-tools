# __SourceForge.__
## The tool you didn’t know exist.
Raga Saputra 145150400111023 | DPSI-P

**What is SourceForge ?**

SourceForge merupakan source code repository berbasis web, ia bertindak
sebagai tempat penyimpanan dan tool dari orang-orang yang ingin membuat projek software open source. Pada tahun 2013 pengguna sourceforge telah mencapai 3 juta orang, berbagai projek juga telah digarap dan memberikan feedback yang positif. Banyak sekali fitur yang bisa digunakan pada sourceforge seperti integrated issue tracking, threaded discusion forum, code repository, documentation, download & stat, dan open source directory

__Integrated issue tracking__, fitur ini memungkinkan para developer untuk berbagi permasalahan yang mereka hadapi dan menuliskanya pada suatu post, dari sini mereka bisa saling berbagi solusi serta mencatat permasalahan dan solusinya untuk membantu developer lain ketika mengalami permasalah yang serupa dikemudian hari.

![issue](https://cloud.githubusercontent.com/assets/17525413/21292368/3f0fb208-c535-11e6-87e8-bb25df8ae848.JPG)

__Threaded discusion forum__, tempat yang memungkinkan user untuk saling berdiskusi terkait ide, gagasan, atau sekedar memposting sesuatu untuk memulai topik percakapan. Pada forum ini biasanya juga digunakan untuk mencari volunter yang bisa membantu dalam pengembangan software open source yang digagas oleh developer.

![forum](https://cloud.githubusercontent.com/assets/17525413/21292373/8a79bd1a-c535-11e6-955d-c071de9ca961.JPG)

__Code repository__, bagian paling utama dalam pengembangan software adalah source code, pada code repository kita mampu berbagi code dengan volunter-volunter lain yang ikut menggarap project kita menggunakan git. Git memungkinkan kita untuk melacak setiap perubahan yang terjadi pada suatu file, dengan git kita bisa saling berkolaborasi dengan programmer/ volunter lain dan mempercepat proses pembuatan software.
Git project bisa didapatkan menggunakan 2 pendekatan. Pertama mengimport projek atau direktori yang sudah ada kedalam git. Kedua meng-kloning git repository dari server lain.

**IMPORT PROJEK KEDALAM GIT**

Pertama yang harus dilakukan adalah masuk kedalam direktori projek berada dan ketikan:
```
$ git init
```
Setelah sukses maka akan muncul sub direktori baru bernama .git , sub direktori ini masih belum men- tracking projek yang ingin kita masukan ke dalam git. Untuk melakukanya kita perlu melakukan git add dan git commit dengan cara:
```
$ git add *.c
$ git add LICENSE
$ git commit -m 'initial project version'
```
Setelah sukses maka akan dihasilkan git repository berserta folder projek yang telah di tracking.

**KLONING DARI SERVER LAIN**

Ketika kita ingin membuat repository berdsarkan repository lain yang telah kita miliki. Bisa digunakan cara `git clone [url]`, Sebagai contoh jika kita ingin clone dari repository yang berdapa pada link libgit2 maka bisa dilakukan:
```
$ git clone https://github.com/libgit2/libgit2
```
Jika sukses akan muncul direktori baru bernama libgit2. Jika kita menginginkan hasil clone dengan nama yang berbeda dari nama asli kita bisa melakukan seperti ini:
```
$ git clone https://github.com/libgit2/libgit2 mylibgit
```
Setelah sukses maka folder mylibgit lah yang akan muncul bukan libgit2.
Secara lengkap manual dasar pembuatan dan penggunaan git bisa dibaca [disini](https://git-scm.com/doc).

![code](https://cloud.githubusercontent.com/assets/17525413/21292381/b4cab682-c535-11e6-93fa-0483c74527f9.JPG)

__Documentation__, adalah tempat untuk developer memberikan dokumentasi terhadap software yang dibuatnya, hal ini dapat membantu user dalam menggunakan software tersebut. SourceForge sendiri menyediakan wiki untuk developer mendokumentasikan softwarenya, pada wiki tersebut developer bisa membuat halaman disertai atachment, thread discusion, sytax highlight, dl. Selain wiki sourceforge juga memberikan kebebasan kepada developer untuk mendokumentasikan software menggunakan tool lain.

![documenta](https://cloud.githubusercontent.com/assets/17525413/21292382/c3d2136e-c535-11e6-8a28-9b854ea6069e.JPG)

__Download and stats__, setelah software jadi developer bisa mem-publikasikanya kepada semua orang, fitur download and stats membantu developer untuk memonitor aktivitas download guna memberikan informasi siapa, berapa, dan dimana para pendownload berasal. Dengan menggunakan fitur ini kita juga bisa mendapatkan beberapa hal seperti :
- Link download yang bisa diakses oleh semua orang dipenjuru dunia.
- File download bisa di akses dari berbagai downloader platform.
- Mendapatkan grafik download berdasarkan waktu, platform, wilayah yang selalu ter-update setiap saat.

![stat](https://cloud.githubusercontent.com/assets/17525413/21292387/d32a8ab2-c535-11e6-864a-b37b5ea2ca2e.JPG)

__Open Source Directory__, Setelah project kita rilis sourceforge secara otomatis akan memposting software kita ke website utama sehingga memudahkan user untuk mengunduh aplikasi kita. Untuk lebih mengorganisir, software kita akan dimasukan kedalam kategori-kategori produk yang serupa, dari sini user juga bisa memberikan review dan komentar , membagikan software kita melalui akun twitter, facebook, dan googel+. Nantinya berdasarkan review dan jumlah download akan dipilih project of the month.

![opensource](https://cloud.githubusercontent.com/assets/17525413/21292391/e587ac1c-c535-11e6-90f7-f4c46f87ced1.JPG)

**The more you know**

Sourceforge ditemukan pada tahun 1999 oleh VA software, merupakan pemberi layanan pertama untuk pengembang software open source , guna mengontrol dan mengelola pembuatan software pada satu lokasi terpusat. Semua software yang berada pada sourceforge dikategorikan sebagai software open source. Seiring berjalanya waktu kepimilikan sourceforge berpindah ke CollabNet.

Sourceforge kerap kali diblokir di negara China, yakni pada september 2002, july 2008, agusuts 2012. Namun pemblokiran ini tidak pernah berlangsung lama. Pada november 2008 sourceforge pernah digugat oleh French collection society karena telah melakukan hosting untuk download software Shareaza secara gratis. Pada tahun 2009 sourceforge mengumumkan platform baru bernama Allura dibawah naungan Apache. Pada tahun 2012 geeknet membeli sourceforge dengan harga 20 juta dollar, pada tahun 2016 geeknet menjualnya kepada San Diego-based BizX untuk harga yang dirahasiakan.

Nah itulah sedikit tentang tool pengembangan software sourceforge yang mungkin kalian tidak tahu keberadaanya. Penasaran ? cek langsung ke [SourceForge](https://sourceforge.net/).
