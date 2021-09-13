# Rangkuman Minggu Ke-2

Ketika kita membuat aplikasi Android, kita bisa menggunakan software bernama android studio. Dahulu sebelum adanya android studio, pelopor utamanya adalah Eclipse. Untuk membuat aplikasi android terdapat 2 bahasa pemograman dalam android studio yaitu java dan kotlin. Untuk menjalankan programnya tidak sulit, bisa menggunakan perangkat virtual atau dari handphone kita (menggunakan kabel USB) / bisa juga menggunakan mirroring ke laptop di handphone kita.

Didalam Android studio kita ada disediakan komponen yaitu Activity, Broadcast, Service, dan Content. Activity merupakan komponen yang bertujuan sebagai screen view jadi jika ingin masuk menu lainya activity ini sangat membantu. Broadcast yaitu merupkan komponen yang berfunsi sebagai notifikasi dari aplikasi lain sebagai contoh adalah telfon, sms OTP, dll. Selanjtunya Service yang merupakan komponen dimana bertujuan untuk melakukan proses dibelakang layar sebagai contoh play musik, GPS, penerima sms,dll. Dan yang terakhir ialah Content dimana komponen ini adalah memanajemen sebuat ada dari berbagai sumber.


## Didalam Android Studio juga ada proses development dan buildingnya diantaranya :
1.	UI Design
Proses ini bisa disebut front end atau kita menggunakan format XML Code untuk mendesain dan menampilkan sesuai kebutuhan pengguna.
2.	Aplication Development
Proses ini bisa disebut backend, atau kita memberikan perintah fungsi yang sudah dibuat dari frontend, misalnya jika kita mengklik tombol maka akan menyebabkan aktivitas lain.
3.	Grandle
Proses ini untuk me-building program yang kita buat, yang dapat dikatakan sebagai program yang dikompilasi 
4.	Testing
Dalam proses ini, kami akan mencari kesalahan (bug) untuk meminimalkan kesalahan (bug) dalam program, yang perlu diselesaikan sebelum dirilis ke public.

## Summary of Commonly-used Android containers  
1. LinearLayout (the box model)
LinearLayout adalah sebuah view group yang menyelaraskan semua children kedalam single direction / satu arah secara, secara vertikal atau horizontal. Anda dapat menentukan arah tata letak dengan atribut [android:orientation]
2. RelativeLayout (a rule-based model)
RelativeLayout adalah grup tampilan yang menampilkan tampilan child dalam posisi relatif. Posisi setiap tampilan dapat ditentukan sebagai relatif terhadap elemen sibling (seperti di sebelah kiri atau di bawah tampilan lain) atau dalam posisi relatif terhadap area RelativeLayout parent (seperti sejajar dengan bawah, kiri, atau tengah).
3. TableLayout (the grid model)
TableLayout menempatkan turunannya ke dalam baris dan kolom. Container TableLayout tidak menampilkan garis batas untuk baris, kolom, atau selnya. Tabel ini akan memiliki jumlah kolom sebanyak jumlah baris yang memiliki sel terbanyak. Tabel dapat membiarkan sel kosong. Sel dapat mencakup beberapa kolom, seperti dalam HTML. Anda dapat memperluas kolom menggunakan kolom span di class TableRow.LayoutParams.
4. ScrollView, a container designed to assist with implementing scrolling containers. 
5. Lainnya (ListView, GridView, WebView, MapView,…) 

