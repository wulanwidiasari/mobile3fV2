PEMROGRAMAN SELULER
Secara garis besar pemrograman seluler terbagi menjadi 2 yaitu:
Widget dan
Navigasi 
---
Widget:
Merupakan komponen utama untuk membangun UI pada android. Widget mewarisi dari kelas ttampilan.
Hirarki UI:
Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hirarki tata letak dan widget.
Berikut contoh dari Hirarki UI:
 <EditTeks
  android:id="@+id/editTeks"
  android:layout_width="0dp"
  android:layout_height="wrap_content"
  android:layout_marginStart="16dp"
  android:layout_marginLeft="16dp"
  android:layout_marginTop="16dp"
  android:ems="10"
  android:hint="@string/edit_message"
  android:inputType="textPersonName" />
Menetapkan nilai widget:
 Nilai widget itu tergantung kepada widget itu sendiri antara lain: 
     EditTeks: Teks dll
     ImageView: ImageResource dll
     RadioButton: Teks, Dicentang
     Kotak Centang: Teks, Dicentang
     Dll
---
Navigasi:
     Navigasi antara layer dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan 
     intuitif di seluruh aplikasi. Ns navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristic dan pola yang sama 
     dalam navigasi saat mereka berpindah antar aplikasi. Tujuannya ialah: Setiap applikasi yang dibuat memiliki tujuan awal yang tetap, ini juga merupakan layer pertama yang dilihat 
     pengguna saat mereka meluncurkan aplikasi yang dibuat melalui peluncur, tujuan ini juga merupakan layer terakhir yang dilihat pengguna Ketika mereka Kembali ke peluncur setelah 
     menekan tombol Kembali.
Setup: 
 dependensi {
 def nav_version = "2.3.5"

 // Implementasi bahasa Java
 implementasi "androidx.navigation:navigation-fragment:$nav_version"
 implementasi "androidx.navigation:navigation-ui:$nav_version"

 // Kotlin
 implementasi "androidx.navigation:navigation-fragment-ktx:$nav_version"
 implementasi "androidx.navigation:navigation-ui-ktx:$nav_version"

 // Dukungan modul fitur
 implementasi "androidx.navigation:navigation-dynamic-features-fragment:$nav_version"

 // Menguji Navigasi
 androidTestImplementation "androidx.navigation:navigation-testing:$nav_version"

 // Integrasi Pembuatan Jetpack
 implementasi "androidx.navigation:navigation-compose:2.4.0-alpha08"
}
Grafik Navigasi:
      Tjuan adalah area konten yang berbeda di applikasi anda.
      Tindakan adalah koeksi logis antara tujuan anda yang mewakili jalur yang anda dapat diambil pengguna.
Editor Navigasi:
     Panel tujuan: mencantumkan host navigasi anda dan semua tujuan saat ini di editor grafik.
     Editor grafik: berisi representasi visual dari grafik navigasi anda. Anda dapat beralih di antara desain tampilan dan representasi XML yang mendasarinya di TEKS melihat.
     Atribut: Menampilkan atribut untuk item yang saat ini dipilih dalam grafik navigasi.
Tambahkan Nav Hots kedalam Aktivitas:
     Salah satu bagian inti dari komponen Navigasi adalah tuan rumah navigasi.
     Host navigasi adalah wadah kosong tempat tujuan ditukar masuk dan keluar saat pengguna menavigasi melalui aplikasi Anda.
     Host navigasi harus berasal dari NavHost

