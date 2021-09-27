- Pertemuan 3

Pemrogaman mobile terbagi menjadi 2 yaitu : Widget dan Navigasi
Widget : adalah komponen utama untuk membangun UI pada android. Widget mewarisi dari kelas tampilan. Widget merupakan turunan dari kelas View.
- Hirarki UI : (UI) untuk aplikasi Android dibangun sebagai hirarki tata letak dan widget.
- Id di XML dibutuhkan untuk memanipulasi widget yang digunakan Java ataupun Kotlin Set/Get Value di Widget
- EditText : untuk teks dll
- ImageView : untuk ImageResource dll
- RadioButton : untuk Teks, Checked
- CheckBox : untuk Text,Checked
Navigasi : Navigasi merupakan bagian penting dalam user experience, hal tersebut dikarenakan navigasi berperan untuk memberikan pengalaman dalam berpindah antar layer.
- Navigation Graph terbagi menjadi 2 yaitu : Destinations dan Actions.
- Komponen Navigasi di desain untuk mengimplemantasikan prinsip – prinsip secara umum, untuk memastikan pengguna dapat menerapkan heuristic dan pola yang sama di navigasi saat berpindah antar aplikasi. Destination
Setiap aplikasi memiliki start destination yang tetap
- Merupakan layer pertama yang dilihat pengguna Ketika membuka aplikasi dari launcher.
- Destinasi ini juga halaman terakhir yang dilihat oleh pengguna Ketika mereka Kembali ke launcher setelah menekan tombol back. Navigation Graph
- Destination adalah content area yang berbeda di aplikasi.Actions adalah logical connections antara destinations yang memberikan path yang bisa digunakan pengguna. Navigation Editor
- Destination panel : adalah list dari host navigasi dan semua destination yang sedang berada di graph editor
- Graph editor : mengandung representasi visual dari grafik navigasi. Bisa dipindah antara design view dan representasi XML di text view.
- Attributes : memperlihatkan atribut untuk item yang dipilih di grafik navigasi.
