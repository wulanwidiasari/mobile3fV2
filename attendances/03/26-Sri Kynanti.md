Rangkumaan Pertemuan 3

Outline

Widget dan Navigation Component

Widget merupkan komponen utama untuk membangun sebuah UI(User Intereface) di Android yang mewarisi dari kelas View. Untuk mengetahui apakah daftar Widget UI yang ersedia dapat memeriksa palette di Android Studio.

Hirarki UI

UI untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget. Diperlukan pendefinisaian id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin.

Set/Get Value pada Widget
•	It’s depends on Widget
•	EditText: Text etc
•	ImageView: ImageResource etc
•	RadioButton: Text, Checked
•	CheckBox: Text, Checked
•	dll

Navigation Component

Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

Destination

Setiap aplikasi yang Anda buat memiliki tujuan awal yang tetap.
Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur. Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

Navigation Graph

Tujuan adalah area konten yang berbeda di aplikasi Anda
Tindakan adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna

Add NavHost into Activitity

Salah satu bagian inti dari komponen Navigasi adalah host navigasi.
Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
