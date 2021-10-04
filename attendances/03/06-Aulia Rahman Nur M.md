# Rangkuman Pertemuan 3

## Widget
Widget adalah komponen utama untuk membuat atau membangun UI dalam android, widget mewarisi dari kelas view, kita dapat memeriksa palette di Android Studio untuk melihat daftar Widget UI tersedia.

## UI Hierarchy
UI untuk aplikasi Android dibangun sebagai hirari tata letak dan widget, kita perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin.

## Set/Get Value of Widget
Tergantung pada widget
contoh:
- EditText: Text dll 
- ImageView: ImageResource dll
- RadioButton: Text, Checked
- CheckBox: Text, Checked.

## Navigation Component
Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi. 

## Destination
Setiap aplikasi yang kita buat memiliki destinasi awal yang tetap. Ini adalah layar pertama yang dilihat pengguna saat mereka buka aplikasi dari _launcher_. Destinasi ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

## Navigation Graph
- _Destinations_ adalah area konten yang berbeda di aplikasi Anda.
- _Actions_ adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna/

## Navigation Editor
- _Destinations Panel_ Mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di _Graph Editor_.
- _Graph Editor_ Memuat visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
- _Attributes_ Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

## Add NavHost into Activitity
Salah satu bagian inti dari komponen Navigasi adalah _navigation host_. Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda. Host navigasi harus berasal dari NavHost
