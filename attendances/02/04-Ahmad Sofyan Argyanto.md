Rangkuman Pertemuan 2

Android Basic XML Layouts 

Designing Complex Uis :
Bisa dibilang, LinearLayout adalah alat pemodelan yang paling umum. Ia menawarkan model "kotak" yang mirip dengan Java-Swing Box-Layout.
Umumnya, desain UI yang kompleks dihasilkan dari kombinasi kotak bersarang yang lebih sederhana yang menunjukkan bagian dalamnya menggunakan 
orientasi horizontal atau vertikal.

Summary of Commonly-used Android containers :
1.LinearLayout (the box model), 
2.RelativeLayout (a rule-based model), and 
3.TableLayout (the grid model), along with 
4.ScrollView, a container designed to assist with implementing scrolling containers. 
5.Other (ListView, GridView, WebView, MapView,…) discussed later

Linear Layout :
LinearLayout adalah model kotak – widget atau wadah anak berbaris dalam kolom atau baris, satu demi satu.
Untuk mengonfigurasi LinearLayout, Anda memiliki lima area kontrol utama selain konten container:
orientasi,mengisi model,berat,gravitasi,bantalan,batas.

Relative Layout :
RelativeLayout menempatkan widget berdasarkan hubungannya dengan widget lain di wadah dan wadah induk.
Contoh:
A berada di atas orang tua
C di bawah A, di sebelah kanannya
B di bawah A, di sebelah kiri C

Table Layout :
Baris dideklarasikan dengan menempatkan widget sebagai anak-anak dari TableRow di dalam keseluruhan TableLayout.
Jumlah kolom ditentukan oleh Android ( Anda mengontrol jumlah kolom secara tidak langsung).
Jadi jika Anda memiliki tiga baris, satu dengan dua widget, satu dengan tiga widget, dan satu dengan empat widget, setidaknya akan ada empat kolom.

ScrollView Layout :
Ketika memiliki lebih banyak data daripada yang dapat ditampilkan pada satu layar, Anda dapat menggunakan kontrol ScrollView.
Ini menyediakan akses geser atau gulir ke data. Dengan cara ini pengguna hanya dapat melihat sebagian dari tata letak Anda pada satu waktu, tetapi sisanya tersedia melalui pengguliran.
Ini mirip dengan menjelajahi halaman web besar yang memaksa pengguna untuk menggulir halaman ke atas untuk melihat bagian bawah formulir.

Miscellaneous.Absolute Layout :
- Tata letak yang memungkinkan Anda menentukan lokasi yang tepat (koordinat x/y) dari turunannya.
- Tata letak absolut kurang fleksibel dan lebih sulit dipertahankan daripada jenis tata letak lain tanpa pemosisian absolut.


Activities and Intents
Pada activities terdapat materi yang kita pelajari yaitu:
- Activities
- Defining an activity 
- Starting a new activity with an intent
- Passing data between activities with extras
- Navigating between activities

Activities adalah komponen aplikasi mewakili satu jendela, satu hierarki tampilan
Biasanya mengisi layar, tetapi dapat disematkan di layar lain aktivitas atau muncul
sebagai jendela mengambang. Kelas Java, biasanya satu aktivitas dalam satu file

Activities melakukan Mewakili kegiatan, seperti memesan bahan makanan, mengirim 
email, atau mendapatkan petunjuk arah
- Menangani interaksi pengguna, seperti klik tombol, entri teks, 
atau verifikasi login
Dapat memulai aktivitas lain di aplikasi yang sama atau lainnya
- Memiliki siklus hidup — dibuat, dimulai, dijalankan, dihentikan, 
dilanjutkan, dihentikan, dan dihancurkan

Apps and activities
Activities terikat bersama untuk membuat aplikasi .Aktivitas pertama yang dilihat pengguna biasanya disebut "aktivitas utama"
Kegiatan dapat diatur dalam hubungan orang tua-anak di Manifes Android untuk membantu navigasi

Layouts and Activities
- Aktivitas biasanya memiliki tata letak UI
  Tata letak biasanya didefinisikan dalam satu atau lebih file XML
- Aktivitas "mengembang" tata letak sebagai bagian dari yang dibuat

Intents
intent adalah deskripsi operasi yang harus dilakukan. 
Intent adalah objek yang digunakan untuk meminta tindakan dari yang lain. 
komponen aplikasi melalui sistem Android. 

What can intents do?

Start activities
- Klik tombol memulai aktivitas baru untuk entri teks
- Mengklik Bagikan membuka aplikasi yang memungkinkan Anda memposting foto
Mulai layanan
- Memulai mengunduh file di latar belakang
Mengirimkan siaran
Sistem ini memberi tahu semua orang bahwa ponsel sekarang sedang mengisi daya.

Explicit and implicit intents
Explicit Intent :
- Memulai aktivitas tertentu
Minta Teh dengan Susu yang Dibawa Nikita
Aktivitas utama memulai aktivitas ViewShoppingCart

Implicit Intent
Meminta sistem untuk menemukan aktivitas yang dapat menangani permintaan ini

Selanjutnya terdapat Sending and Receiving Data 
Dalam Sending and Receiving Data mempelajari (Two types of sending data with intents, Two types of sending data with intents,

Model View ViewModel(MVVM)
MVVM adalah sebuah pola arsitektur yang memisahkan antara user interface logic dari business logic. Tujuan penggunaan MVVM sendiri adalah menjaga kode UI agar tetap sederhana dan tanpa mengandung app logic agar mudah untuk dikelola.
Model

1.Model
Model adalah representasi dari data dan business logic dari aplikasi. Salah satu dari strategi implementasi model adalah membuat model dapat terbuka melalui observables agar terpisah antara ViewModel atau observer/ consumer.
ViewModel
2.ViewModel
ViewModel berinteraksi dengan model dan juga menyiapkan observables yang akan diobservasi oleh View. ViewModel dapat menyediakan hooks untuk view dan mem-pass events kepada model.
Salah satu implementasi strategi dari ViewModel adalah untuk memisahkannya dengan View. Contohnya ViewModel tidak seharusnya mengetahui View berinteraksi dengan siapa.
View
3.View
Tugas dari view pada MVVM adalah untuk observe sebuah ViewModel observable untuk mendapatkan data yang akan mengupdate UI/ tampilan.
4.LiveData
LiveData adalah sebuah observable data holder yang memungkinkan components dalam sebuah aplikasi dapat observe/ mengamati objek LiveData ketika terjadi perubahan. Dengan begini LiveData object producer dengan LiveData object consumer akan terpisah.
ViewModel
