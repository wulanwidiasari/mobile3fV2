•	Pertemuan 3

•	Widget and Navigation Component
Widget :
- Widget adalah component utama dalam membangun UI di android.
- Widget adalah warisan(inherit) dari kelas View.
- Widget UI bisa dicari didalam palette di Android Studio, disana terdapat banyak jenis widget.
Hirarki UI :
- User interface (UI) untuk aplikasi android dibangun sebagai hirariki dari layout dan widget
- Id di XML dibutuhkan untuk memanipulasi widget yang digunakan Java ataupun Kotlin
Set/Get Value di Widget
- EditText : untuk teks dll
- ImageView : untuk ImageResource dll
- RadioButton : untuk Teks, Checked
- CheckBox : untuk Text,Checked
- Dll
Navigation Component
- Navigasi antara layer dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip -prinsip berikut mengikuti dasar untuk pengalaman pengguna yang intuitif dan konsisten di seluruh aplikasi.
- Komponen Navigasi di desain untuk mengimplemantasikan prinsip – prinsip secara umum, untuk memastikan pengguna dapat menerapkan heuristic dan pola yang sama di navigasi saat berpindah antar aplikasi.
Destination
- Setiap aplikasi memiliki start destination yang tetap
- Merupakan layer pertama yang dilihat pengguna Ketika membuka aplikasi dari launcher.
- Destinasi ini juga halaman terakhir yang dilihat oleh pengguna Ketika mereka Kembali ke launcher setelah menekan tombol back.
Navigation Graph
- Destination adalah content area yang berbeda di aplikasi.
- Actions adalah logical connections antara destinations yang memberikan path yang bisa digunakan pengguna.
Navigation Editor
- Destination panel : adalah list dari host navigasi dan semua destination yang sedang berada di graph editor
- Graph editor : mengandung representasi visual dari grafik navigasi. Bisa dipindah antara design view dan representasi XML di text view.
- Attributes : memperlihatkan atribut untuk item yang dipilih di grafik navigasi.

Add NavHost into Activity
- Salahsatu bagian inti dari Navigation component adalah navigation host
- Navigation host adalah container kosong dimana destination di tukar didalam dan diluar user navigate dari aplikasi.
- Navigation host harus diperoleh dari NavHost.
