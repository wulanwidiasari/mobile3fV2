<h1>Rangkuman Pertemuan Ke-2</h1>

Pembuatan Aplikasi Android bisa menggunakan Apliaksi Android Studio. Yang pada dasarnya bisa menggunakan bahasa kotlin ataupun java. Tetapi pada mata kuliah Pemrograman Mobile ini di arahkan menggunakan Java.
Pemrograman dalam aplikasi ini tidaklah terlalu sulit karena banyak fitur pendukung. dan juga kita bisa mengguanakan hp kita untuk langsung dijadikan object perocbaan aplikasi yang kita buat.
penghubungannya menggunakan USB lalu di sambungkan ke Android Studio. Dengan adanya fitur ini, kita bisa leluasa melihat hasil pengerjaan kita secara live. atau bisa juga virtual dengan menggunakan tampilan yang disediakan di aplikasi Android Studio.

Dan juga pada pertemuan mata kuliah Pemrograman Mobile hari ini, saya telah mendapatkan beberapa poin penting.

*Komponen penting dalam sebuah android yaitu
 
  1. Activities yang dimaksudkan disini adalah single page user interface atau tampilan utama aplikasi.dan juga terdapat aplikasi yang punya lebih dari 1 activites.
  2. Service yaitu bagian aplikasi yang tidak terdapat tampilannya tetapi bekerja di background,bisa di run atau stop oleh aktivities
  3. Content Provider,bagian aplikasi untuk data handling dan juga memanage shared set data aplikasi.
  4. Broadcast receiver yaitu bagian aplikasi yang menerima masukan dari luar secara intents.

*Data biding

 Data biding adalah pintu gerbangnya daripada MVVP. terdapat beberapa jurus Data biding yang penting yaitu 
  1.Update Gradle
  2.Update layout
  3.Layout Expression
  4.Ganti Infalate
  5.User Event
  6.Observe 
  7.Biding adapter
  
 Jadi langkah awal adalah menyiapkan Gradle yang dibutuhkan untuk data biding.Dengan cara menambahkan source code di grandle yang module app "bulild features data biding true"
 Kemudan enter dan akan muncul dependencies secara otomatis ,dan lakukan sync.
 
 kemudian langkah kedua adalah melakukan update pada layout XML di activity.
 dengan menambahakn potongan kode 'layout xmlns:android'(biding) untuk ditaruh di bagian atas agar bisa menggunakan data biding layout.
 Atau bisa juga langsung ke activity_main.xml kemudian arahkan ke layout constraint dan tekan keyboard ctrl + enter kemudan pilih convert to data biding layout.
 
 langkah ketiga yaitu update layout menggunakan epression.sama seperti saat menggunakan laravel, penulisannya sama dan cara kerjanya sama.
 yaitu memanggil isi dari string / componen lain dengan cara memanggil expression dari data files lain yang sudah di sediakan.
 
 Dilangkah keempat ini yaitu cara infialte di fragment / activity.kita hanya perlu memasukkan fragment data biding dan kemudan akan di auto generate oleh Android studio.
 jika terdapat error pada saat menjalankannya, terdapat 3 cara yaitu dengan melakukan clean project,rebuild project,atau restart Android studio untuk merefresh semua file.
 
 Langkah kelima yaitu handle event dari XML ,cara kerjanya sama seperti A Href pada Web. jadi saat klik button kita akan ke halamam XML lainya yang sudah di arahkan.

 Kemudian langkan keenam yaitu Observe value dari ViewMdel yang berarti kita tidak perlu mengubah data secara manual, dan bisa dikerjakan otomatis oleh XML.
 terdapat syaratnya untuk menggunakan metode ini, yaitu live data dan mencantumkan setlifecicleowner. agar bisa update secara otomatis.
 
 
