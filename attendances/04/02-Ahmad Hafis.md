# Pertemuan 4
## ListView
1.	Dalam android development, setiap kali kita ingin menampilkan daftar vertical yang dapat di scroll, kita akan menggunakan ListView yang memiliki data yang diisi menggunakan Adaptor. Adaptor paling sederhana digunakan disebut ArrayAdapter karena adaptor mengonversi object ArrayList menjadi item View yang dimuat ke dalam container ListView.
2.	Terdapat 2 cara yang dapat digunakan, yaitu menggunakan ArrayAdapter dan menggunakan Custom ArrayAdapter.
3.	Custom ArrayAdapter dapat digunakan untuk menentukan model, membuat template View, menentukan Adapter, memasang Adapter ke ListView, dan mengisi data ke ListView.
## RecycleView
1.	RecycleView adalah ViewGroup yang dapat merender tampilan berbasis adaptor dengan cara yang serupa. Merupakan successor dari ListView dan GridView.
2.	Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Dapat menentukan view holder dengan extend ke RecycleView.ViewHolder.
3.	RecycleView meminta tampilan tersebut dan mengikat tampilan ke datanya dengan dengan memanggil method di adaptor. Dapat menentukan adapter dengan extend ke RecycleView.Adapter.
4.	Layout manager mengatur elemen individual di dalam daftar. Dapat menggunakan salah satu layout manager yang disediakan Pustaka RecycleView, atau dapat menentukannya sendiri. Layout manager semuanya berdasarkan pada kelas abstrak di Pustaka layout manager.
## Flutter
1.	Sebuah framework open source yang dibuat Google, yang bertujuan untuk membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di system operasi android maupun IOS.
2.	Menggunakan bahasa Dart, sebuah Bahasa modern yang dapat dicompile ke arsitektur processor ARM atau Javascript.
3.	Flutter menggunakan widget sebagai balok dasar pembangunan aplikasi.
4.	Widget dapat disusun dan dikombinasikan dalam satu layar, sama seperti xml pada pemrograman android native.
5.	Flutter memiliki 2 jenis widget, yaitu StatelessWidget dan StatefullWidget. Perbedaan dari 2 jenis ini adalah dimana StatelessWidget digunakan Ketika value dari widget tidak pernah berubah, sebaliknya Statefull Widget digunakan Ketika value dari widget dapat berubah.
