Rangkuman Mobile 27 Sept
==

ListView
--
Dalam pengembangan aplikasi android, untuk menampilkan data dalam jumlah banyak diperlukan ListView agar layar dapat di scroll secara vertikal. Dalam penggunaannya diperlukan sebuah adapter yang menampung semua datanya. Adapter yang paling sederhana adalah ArrayAdapter karena adapter tersebut mengubah dari ArrayList menjadi komponen View yang nantinya ditampilkan ke dalam ListView.

RecyclerView
--
Merupakan pengembangan dari ListView dimana RecyclerView ini digunakan menampilkan semua adapter yang berbasis view. Dalam RecyclerView,  setiap elemen dalam list didefinisikan dengan objek view holder. Selain itu, RecyclerView juga memiliki layout manager yang dapat mengatur tata letak setiap elemen di dalam list. Beberapa layout manager yang ada, yaitu:
- LinearLayoutManager
- GridLayoutManager
- StaggeredGridLayoutManager

RecylerView juga menyertakan adapter baru yang hampir sama dengan adapter lainnya namun terdapat tambahan berupa ViewHolder. Dalam penggunaan adapter tersebut diperlukan untuk override tiga method yang sudah ada, yakni:
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()

Flutter
--
Merupakan sebuah framework open source buatan Google yang bertujuan untuk membuat UI yang modern serta dapat berjalan di multi platform. Flutter menggunakan bahasa pemrograman Dart untuk pembuatan UI maupun logika program.

Dalam pengembangan aplikasi menggunakan flutter, UI dibangun menggunakan sebuah widget yang saling tersusun sehingga menghasilkan UI yang modern.

Flutter memiliki fitur hot reload yang digunakan untuk mencompile source code ketika terdapat tambahan fitur baru dengan cepat. Proses compile tersebut dapat berjalan lebih cepat dikarenakan flutter masih mempertahankan state ketika proses compile.

Selain itu flutter juga memiliki fitur hot restart yang digunakan untuk mencompile source code dengan cara mereset state yang sudah ada.
