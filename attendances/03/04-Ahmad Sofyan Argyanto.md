#Rangkuman Pertemuan 3

Widget
-	Widget adalah komponen utama untuk membangun UI di Android Widget mewarisi dari kelas   View Periksa palet di Android Studio untuk daftar Widget UI yang tersedia

UI Hierarchy
-	Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.
-	Anda perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin

Set/Get Value of Widget

-	Itu tergantung pada Widget
-	EditText: Teks dll
-	ImageView: ImageResource dll
-	RadioButton: Teks, Dicentang
-	Kotak Centang: Teks, Dicentang
-	Dll

Navigation Component

-	Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi.Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Destination

-	Setiap aplikasi yang dibuat memiliki tujuan awal yang tetap.Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur.Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

Add NavHost into Activitity

-	Salah satu bagian inti dari komponen Navigasi adalah host navigasi.
-	Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
-	Host navigasi harus berasal dari NavHost
