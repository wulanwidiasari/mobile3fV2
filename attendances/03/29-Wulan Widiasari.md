**Widget**
- Merupakan salah satu komponen utama dari pembuatan UI pada Android
- Widget mewarisi class view
- Untuk mengetahui list apa saja yang tersedia untuk UI widget dapat dilihat pada palette android studio


**UI Hirarki**
- _User Interface (UI)_ untuk android dibuat berdasarkan hirarki dari layout dan widgets
- ID dibutuhkan pada XML untuk memanupulasi Widget menggunakan Java atau Kotlin

**Set/Get Value of Widget**
- EditText : Text dll
- ImageView : ImageResource dll
- RadioButton : Text, Checked
- CheckBox : Text, Checked

**Komponen Navigasi**
- Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari UX. Prinsip-prinsip berikut menetapkan dasar untuk UX yang konsisten dan intuitif di seluruh aplikasi
- Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi.

**Destination**
- Setiap aplikasi yang dibuat memiliki tujuan awal yang tetap.
- Destination adalah layar pertama yang dilihat pengguna saat meluncurkan aplikasi.
- Destination juga merupakan layar terakhir yang dilihat pengguna ketika mereka kembali ke peluncur setelah menekan tombol Kembali.

**Navigation Graph**
- Destination adalah area konten yang berbeda
- Action adalah koneksi logis antara tujuan yang mewakili jalur yang dapat diambil oleh pengguna

**Navigation Editor**
- _Destination Panel_: Mencantumkan host navigasi dan semua tujuan yang saat ada pada Graph Editor.
- _Graph Editor_: Berisi representasi visual dari grafik navigasi sehingga dapat beralih antara tampilan desain dan representasi XML yang mendasarinya dalam tampilan Teks.
- Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.

**Navigasi Host**
- Salah satu bagian inti dari komponen Navigasi adalah host navigasi
- Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi
- Host navigasi harus berasal dari NavHost
