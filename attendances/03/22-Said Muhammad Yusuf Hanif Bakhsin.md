Pertemuan #

Widget and Navigation

1. Widget

- Salah satu komponen utama dari pembuatan UI pada Android
- Mewarisi dari class view
- Bisa dicek pada palette Android Studio untuk list apa saja yang tersedia untuk UI widget

2. Hirarki UI

- UI untuk Android dibuat berdasarkan hirarki dari layouts dan widgets
- Dibutuhkan id pada XML untuk manipulasi widget menggunakan java atau kotlin
- Set/Get Value dari widget a. Tergantung pada widget b. EditText : contoh Text dll c. ImageView : contoh ImageResource dll d. RadioButton : Text, checked e. Checkbox : Text, checked

Komponen Navigasi Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari UX

Prinsip-prinsip dasar untuk UX yang konsisten dan intuitif pada aplikasi Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip secara default dan pengguna dapat menerapkan pola yang sama dalam navigasi

Tujuan

Setiap aplikasi yang dibuat memiliki tujuan awal yang tetap
Sebagai layar pertama yang dilihat user ketika meluncurkan aplikasi dari peluncur
Sebagai layar terakhir yang dilihat user ketika kembali ke peluncur setelah menekan tombol kembali
Graph Navigasi
Tujuan : Area konten yang berbeda di aplikasi Anda
Aksi : koneksi logis antara tujuan anda yang mewakili jalur yang dapat diambil pengguna.
Editor Navigasi
Panel tujuan: Daftar host navigasi dan semua tujuan yang saat ini ada di Editor Grafik.
Editor Grafik: Berisi representasi visual dari grafik navigasi.
Dapat bberalih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
Atribut
Memperlihatkan atribut untuk item yang dipilih saat ini dalam grafik navigasi.
Penambahan NavHost ke dalam Activitity
Salah satu bagian inti dari komponen Navigasi
Sebagai wadah kosong di mana tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
Host navigasi harus berasal dari NavHost
