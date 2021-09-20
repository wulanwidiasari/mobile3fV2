Rangkuman Minggu ke-3

1. Widget
	Widget adalah komponen utama untuk membangun UI di Android
	Widget mewarisi dari kelas View
2. UI Hierarchy
	Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget.
	Perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin
3. Set/Get Value of Widget
	Tergantung pada widget contoh:
	a. EditText: Text dll 
	b. ImageView: ImageResource dll
	c. RadioButton: Text, Checked
	d. CheckBox: Text, Checked
4. Navigation Component
	Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi
	Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi. 
5.  Destination
	Setiap aplikasi yang Anda buat memiliki tujuan awal yang tetap.
	Ini adalah layar pertama yang dilihat pengguna saat mereka meluncurkan aplikasi Anda dari peluncur.
	Tujuan ini juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.
6. Navigation Graph
	Tujuan adalah area konten yang berbeda di aplikasi Anda
	Tindakan adalah koneksi logis antara tujuan Anda yang mewakili jalur yang dapat diambil pengguna
7. Navigation Editor
	1. Panel tujuan: Mencantumkan host navigasi Anda dan semua tujuan yang saat ini ada di Editor Grafik.
	2. Editor Grafik: Berisi representasi visual dari grafik navigasi Anda. Anda dapat beralih antara tampilan Desain dan representasi XML yang mendasarinya dalam tampilan Teks.
	3. Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.
8. Menambahkan NavHost ke Activitiy
	Salah satu bagian inti dari komponen Navigasi adalah host navigasi.
	Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
	Host navigasi harus berasal dari NavHost
