# Pertemuan 4

## ListView

- Dalam pengembangan Android, ListView adalah populasi data yang diisi menggunakan Adaptor yang digunakan untuk menampilkan daftar vertikal item yang dapat discroll.

- Adaptor paling sederhana untuk digunakan disebut _ArrayAdapter_ karena adaptor ini mengonversi objek _ArrayList_ menjadi item View yang dimuat ke dalam _container ListView_.

## RecyclerView

- _RecyclerView_ adalah _ViewGroup_ yang merender tampilan berbasis adaptor yang menjadi penerus dari ListView dan GridView.

- Setiap elemen ditentukan oleh objek _view holder_. Untuk menentukan view holder terdapat pada _RecyclerView.ViewHolder_.

- _RecyclerView_ meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Untuk menentukan adaptor terdapat pada _RecyclerView.Adapter._

- _Layout Manager_ berfungsi untuk mengatur tata letak pada tiap elemen yang tersedia pada library _RecyclerView_ atau dapat didefinisikan sendiri. _Layout Manager_ didasarkan pada library dari _abstract class_.

## Fluter

- Sebuah framework open source yang dibuat Google, yang bertujuan untuk membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di system operasi android maupun IOS.

- Menggunakan bahasa Dart, sebuah Bahasa modern yang dapat dicompile ke arsitektur processor ARM atau Javascript.

- Flutter menggunakan widget sebagai balok dasar pembangunan aplikasi.

- Widget dapat disusun dan dikombinasikan dalam satu layar, sama seperti xml pada pemrograman android native.

- Flutter memiliki 2 jenis widget, yaitu _StatelessWidget_ dan _StatefullWidget_. Perbedaan dari 2 jenis ini adalah dimana _StatelessWidget_ digunakan Ketika value dari widget tidak pernah berubah, sebaliknya _StatefullWidget_ digunakan ketika value dari widget dapat berubah.
