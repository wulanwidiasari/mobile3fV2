Rangkuman Pertemuan 3 :

Widget and Navigation

Outline : 
Widget, Navigation Component

Widget
-	Widget adalah komponen utama untuk membangun UI di Android
-	Widget mewarisi dari kelas View
-	Periksa palet di Android Studio untuk daftar Widget UI yang tersedia

UI Hierarchy
-	Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.
-	Anda perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin.

Set/Get Value of Widget
-	EditText: Teks dll
-	ImageView: ImageResource dll
-	RadioButton: Teks, Dicentang
-	Kotak Centang: Teks, Dicentang

Navigation Component
-	Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi
-	Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Destination
-	Setiap aplikasi yang Anda buat memiliki tujuan awal yang tetap.
-	Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur.
-	Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali

Navigation Graph
-	Tujuan adalah area konten yang berbeda di aplikasi Anda
-	Tindakan adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna

Navigation Editor
-	Panel tujuan: Mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di Editor Grafik.
-	Editor Grafik: Berisi representasi visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
-	Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.
