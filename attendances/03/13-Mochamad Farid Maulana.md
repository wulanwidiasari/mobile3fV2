# Rangkuman Mobile 20 Sept

Widget
--
- Widget merupakan komponen utama dalam membuat user interface di android. 
- Widget merupakan turunan dari kelas View. 
- Daftar widget yang tersedia dapat di liat pada bagian pallete yang ada di design user interface android.

UI Hierarchy
--
Dalam android, sebuah user interface memiliki hirarki dimana dalam hirarki tersebut terdiri dari layouts dan widgets. Untuk menyusunnya sendiri menggunakan xml dimana setiap layouts dan widgets tersebut harus memiliki sebuah id yang nantinya digunakan untuk memanipulasinya melalui bahasa pemrograman java atau kotlin. 

Navigation Component
--
Navigasi merupakan bagian penting dalam user experience, hal tersebut dikarenakan navigasi berperan untuk memberikan pengalaman dalam berpindah antar layar atau aplikasi yang berbeda.

Navigation Graph
--
Terbagi menjadi 2, yakni
1. Destinations, merupakan layar yang berbeda dengan aplikasi
2. Actions, merupakan jalur logis yang dapat ditempuh untuk ke tujuan (destinations)

Navigation Editor
--
Terbagi menjadi 3, yakni:
1. Destination panel, merupakan bagian yang menampilkan daftar host dan semua tujuan yang yang ada pada graph editor.
2. Graph editor, merupakan representasi visual dari navigation graph
3. Attributes, merupakan bagian yang menampilkan atribut untuk item yang saat ini dipilih dalam navigation graph

Menambahkan Host ke dalam Activity
--
Salah satu bagian yang terpenting dalam navigation component adalah host navigation yang merupakan wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna melakukan pindah layar atau aplikasi. Host navigasi tersebut harus berasal dari NavHost.
