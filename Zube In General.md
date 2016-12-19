
![Zube](https://zube.io/images/45001cebe04ef1725a03259b174cf3a6.combo_blue.svg)


---

# Zube in General

  Zube merupakan *Agile Kanban Board* yang dirancang untuk pengembang (developer), manajer *issue* untuk team leaders, *tiket* untuk dukungan pelanggan, *sprint*, dan *analisis*. Semua data dapat disinkronkan dengan **GitHub** secara real-time.


## Features

> * **Projects**
>

>  Proyek adalah wadah tingkat tertinggi dalam Zube. Anda memasang satu atau lebih sumber data (GitHub Repositori) untuk Proyek dan yang mendefinisikan informasi apa yang dapat Anda mengelola dalam Proyek. Proyek terdiri dari ruang kerja, Isu Manager, dan Tiket. Sebuah proyek juga memungkinkan Anda untuk mengontrol anggota tim memiliki akses ke data Anda. Hanya anggota tim Anda yang pengguna proyek akan dapat melihat komponen dari sebuah Proyek. Admin proyek dapat menambahkan atau menghapus pengguna proyek atau membuat pengguna lain menjadi admin proyek. Daftar Proyek Anda dapat ditemukan pada homepage Zube, setelah masuk. Jika saat ini Anda tidak tergabung dalam Proyek, akan disediakan form yang memungkinkan Anda untuk membuat proyek pertama Anda.
>

> * **Workspaces**
>

>  Ruang kerja memungkinkan Anda memisahkan kartu Anda ke dalam ruang yang terpisah. Ruang kerja berisi papan Kanban, papan Sprint, Sprint, dan grafik Burndown. Setiap proyek memiliki setidaknya satu Workspace, tetapi Anda dapat membuat beberapa ruang kerja untuk Proyek Anda. Setiap Workspace pada Project akan memiliki akses ke repositori sumber yang sama yang telah ditambahkan ke Proyek. Namun, kartu hanya bisa berada pada satu Workspace pada waktu, yang memungkinkan Anda untuk segmen kartu Anda yang sesuai. Kartu dapat dipindahkan antara ruang kerja sehingga Anda dapat membuat alur kerja di tim yang berbeda.
>

> * **Kanban Board**
>

>  Papan Kanban diatur kolom yang memungkinkan Anda untuk melacak kemajuan tugas ketika mereka bergerak melalui alur kerja Anda. Sebuah papan Kanban adalah komponen dari Workspace, dan papan kanban di ruang kerja yang berbeda dapat memiliki berbagai kolom. Hal ini memungkinkan Anda mengatur alur kerja dengan baik disesuaikan untuk setiap Workspace. Kolom dapat disesuaikan pada halaman pengaturan Workspace.
>

> * **Sprint Board**
>

>  Papan Sprint memungkinkan Anda untuk mengatur tugas-tugas Anda ke Sprint. Sprint Agile adalah durasi waktu tertentu pembangunan di mana pekerjaan yang harus diselesaikan. Kolom pada sisi kiri papan sprint adalah tugas-tugas yang belum menjadi bagian dari sprint apapun. Biasanya, untuk menambahkan kartu untuk sprint, Anda akan menyeret kartu dari Backlog, yang merupakan kolom global yang dimaksudkan untuk digunakan sebagai jaminan produk Anda, untuk kolom Ready, yang merupakan kolom sprint dan seharusnya digunakan sebagai sprint backlog anda.

>  Anda dapat mengubah kolom yang berfungsi sebagai sprint backlog pada halaman pengaturan Workspace dan setiap kolom kanan sprint backlog akan menjadi kolom sprint di papan Sprint.
>


> * **Issue Manager**
>

>  Isu Manager adalah cara yang paling ampuh untuk mencari, update, dan memindahkan kartu Anda di seluruh proyek Anda. Isu Manager memberikan Anda akses ke setiap kartu di Proyek Anda. Cari, filter, dan semacam untuk menemukan apa yang Anda cari dan mudah memperbarui atau memindahkan mereka semua sekaligus. Zube juga menyediakan ekspor JSON kartu Anda dari Masalah Manajer sehingga Anda selalu memiliki akses mudah ke data Anda. Sebuah ekspor JSON berarti bahwa Anda bebas untuk menghasilkan laporan kustom dan analisis, atau hanya mengambil data Anda dengan Anda.
>

> * **Tickets**
>

>  Zube Tiket memungkinkan anggota tim Anda untuk log bug, permintaan fitur, dan barang-barang lain yang tidak menjadi GitHub Issue. Tiket adalah cara yang bagus untuk semua orang untuk berkomunikasi dengan tim pengembangan. Kartu Zube dapat dilampirkan ke Tiket, dan Ticket akan melacak kemajuan isu-isu tersebut dan secara otomatis memperbarui untuk mencerminkan keadaan tugas yang dilakukan.
>


## Let's Start

Untuk menjalankan **Zube**, kita perlu membuat *Project* terlebih dahulu. Dibawah ini merupakan langkah pembuatan project pada **Zube**

![Fill all field](https://lh3.googleusercontent.com/-OBksglMHMLk/WFcv_PkVS6I/AAAAAAAAAPM/c-KJ4UcmvSM5nKuV4neN0MQZvVWIlB-qQCLcB/s0/5.png "5.png")

> 1. Isi `Project Name` dengan nama yang di inginkan, misal _"Software Engineering"_.
> 2. Isi `Project Description` dengan deskripsi yang di inginkan, misal _"This is my first project"_.
> 3. Pilih `GitHub Organization`, misal _"jawarawahyu"_.
> 4. Pada kolom `Add a GitHub repository to your project` tambahkan repository yang telah dibuat di GitHub, misal _"Develover"_. Kemudian klik **Create Project**.

 * Tampilan menu *Kanban Board* dari `workspace` **Zube**

![Kanban Board](https://lh3.googleusercontent.com/-kkVwErY3Bbs/WFc5VrCNaoI/AAAAAAAAAP0/xYNQ6QuESxQFo2370jul1gcvSb_M-lB4QCLcB/s0/6.png "6.png")

* Tampilan menu *Sprints* dari `workspace` **Zube**

![Sprints](https://lh3.googleusercontent.com/-bm8vUcPymQo/WFd5ImbYUjI/AAAAAAAAAQU/0Bzdy9IsN9AQ3J9evrcCKkxNmI-OytKawCLcB/s0/7.png "7.png")

* Tampilan menu *Burndown* dari `workspace` **Zube**

![Burndown](https://lh3.googleusercontent.com/-dKlQd30rRxo/WFd53AOPSyI/AAAAAAAAAQc/0rkAtS1emJUOoZ5qtIPGCMiUk2BozutDQCLcB/s0/8.png "8.png")

* Tampilan menu *Issue Manager* dari `project` **Zube**

![Issue Manager](https://lh3.googleusercontent.com/-7C-0tIR1YOs/WFd6NueAkTI/AAAAAAAAAQs/LhyVezNBQq4hKcOPbU08_P3LuYRnu_NYACLcB/s0/9.png "9.png")

* Tampilan menu *Labels* dari `project` **Zube**

![labels](https://lh3.googleusercontent.com/-Usx8_KINSQo/WFd61pnQ89I/AAAAAAAAAQ8/l5jyxh_xcYsZ-0M10W9Kg69_6AUyhY5NACLcB/s0/10.png "10.png")

* Tampilan menu *Tickets* dari `Tickets` **Zube**

![Tickets](https://lh3.googleusercontent.com/-9fNXWUHsKcE/WFd78WPUyrI/AAAAAAAAARY/e4yvHxQJY2crgnoowqShMMN44PzA-jbIwCLcB/s0/11.png "11.png")

* Tampilan menu *Milestones* dari `GitHub Components` **Zube**

![Milestones](https://lh3.googleusercontent.com/-KZDN20XYz1A/WFd8eZk_pNI/AAAAAAAAARk/WUrAgtLArwwUu8JqrR4ZH8j07eGBzxMLQCLcB/s0/13.png "13.png")


---

> Oleh : [Jawara Wahyu Al Faraday](https://www.twitter.com/jawarawahyu) `145150400111054` *DPSI - P*

---
