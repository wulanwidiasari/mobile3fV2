Pemrogaman mobile terbagi menjadi 2 yaitu : Widget dan Navigasi
Widget : adalah komponen utama untuk membangun UI pada android. Widget mewarisi dari kelas tampilan. Widget merupakan turunan dari kelas View.
Hirarki UI : (UI) untuk aplikasi Android dibangun sebagai hirarki tata letak dan widget.  Untuk menyusun menggunakan xml dimana setiap layouts dan widgets tersebut harus memiliki sebuah id yang nantinya digunakan untuk memanipulasi melalui bahasa pemrograman java atau kotlin.
Navigasi : Navigasi merupakan bagian penting dalam user experience, hal tersebut dikarenakan navigasi berperan untuk memberikan pengalaman dalam berpindah antar layer.
Navigation Graph terbagi menjadi 2 yaitu : Destinations dan Actions.
-	Destinations, merupakan layar yang berbeda dengan aplikasi
-	Actions, merupakan jalur logis yang dapat ditempuh untuk ke tujuan (destinations)
Navigation Editor terbagi menjadi 3 :
-	Destination panel, merupakan bagian yang menampilkan daftar host dan semua tujuan yang yang ada pada graph editor.
-	Graph editor, merupakan representasi visual dari navigation graph
-	Attributes, merupakan bagian yang menampilkan atribut untuk item yang saat ini dipilih dalam bentuk navigation graph
 Menambahkan Host ke dalam Activity      
Salah satu bagian yang terpenting dalam navigation component adalah host navigation yang merupakan wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna melakukan pindah layar / aplikasi. Host navigasi tersebut harus berasal dari NavHost.


