# Rangkuman Minggu Ke-4
## ListView
Dalam pengembangan Android, setiap kali kita ingin menampilkan daftar vertikal yang dapat digulir, kita akan menggunakan ListView, yang diisi dengan data menggunakan Adaptor. Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

## RecyclerView 
Seperti namanya, RecyclerView mendaur ulang elemen individual ini. Saat item keluar dari layar, RecyclerView tidak akan merusak tampilannya. Sebagai gantinya, RecyclerView menggunakan kembali tampilan untuk item baru yang telah di-scroll di layar. Penggunaan kembali ini sangat meningkatkan kinerja, meningkatkan respons aplikasi, dan mengurangi konsumsi daya.
RecyclerView dapat menampilkan kumpulan data besar dengan mudah dan efisien. Anda menyediakan data dan menentukan tampilan setiap item, dan pustaka RecyclerView secara dinamis membuat elemen sesuai kebutuhan.

RecyclerView menyediakan pengelola tata letak bawaan sebagai berikut:
- LinearLayoutManager menampilkan item dalam daftar  vertical atau horizontal scrolling list.
- GridLayoutManager menampilkan item dalam kotak.
- StaggeredGridLayoutManager menampilkan item dalam staggered grid.

## FLUTTER
Flutter adalah kerangka kerja sumber terbuka yang dibuat oleh Google. Google membuat Flutter untuk membangun kerangka kerja guna membuat UI modern, asli, dan reaktif yang dapat berjalan di sistem operasi iOS dan Android. Tidak hanya di smartphone, Google juga membuat Flutter untuk desktop, web, dan perangkat yang disematkan. Tujuannya adalah untuk memungkinkan pengembang menghadirkan aplikasi berkinerja tinggi yang terasa alami di berbagai platform, merangkul perbedaan di mana mereka ada sambil berbagi kode sebanyak mungkin.

## Widget dan Element pada Flutter
Flutter menggunakan widget ini sebagai dasar untuk konstruksi aplikasi. Widget dapat diatur dan digabungkan di layar, seperti xml dalam pemrograman asli android, widget dapat diatur dalam bentuk pohon, di mana satu widget menjadi widget parent dan yang lainnya menjadi widget Child. Setiap widget dapat dikonfigurasi sesuai dengan kebutuhan aplikasi.
Flutter memiliki dua jenis widget, StatelessWidget dan StatefullWidget. Gunakan widget stateless saat nilai (status/konfigurasi) widget tidak akan pernah berubah, dan gunakan StatefullWidget saat nilai (status/konfigurasi) widget dapat berubah. StatelessWidget dan StatefullWidget memiliki metode yang disebut "build", yang memiliki BuildContext untuk mengatur posisi widget di widget tree.
