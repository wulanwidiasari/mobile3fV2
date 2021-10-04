# Rangkuman Pertemuan 4

## List View
Komponen yang berfungsi untuk menampilkan daftar vertical yang kemudian memiliki data yang diisi menggunakan Adaptor. Dalam android development, setiap kali ingin menampilkan daftar vertical yang dapat di scroll, maka yang digunakan adalah ListView yang memiliki data yang diisi menggunakan Adaptor. Adaptor paling sederhana digunakan disebut ArrayAdapter karena adaptor mengonversi object ArrayList menjadi item View yang dimuat ke dalam container ListView. Terdapat 2 cara yang dapat digunakan, yaitu menggunakan ArrayAdapter dan menggunakan Custom ArrayAdapter. Custom ArrayAdapter dapat digunakan untuk menentukan model, membuat template View, menentukan Adapter, memasang Adapter ke ListView, dan mengisi data ke ListView.

## Recycler View
ViewGroup yang dapat merender tampilan berbasis adaptor dengan cara yang serupa. Merupakan successor dari ListView dan GridView. Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Dapat menentukan view holder dengan extend ke RecycleView.ViewHolder. RecycleView meminta tampilan tersebut dan mengikat tampilan ke datanya dengan dengan memanggil method di adaptor. Dapat menentukan adapter dengan extend ke RecycleView.Adapter. Layout manager mengatur elemen individual di dalam daftar. Dapat menggunakan salah satu layout manager yang disediakan Pustaka RecycleView, atau dapat menentukannya sendiri.

## Flutter
Framework open source yang dibuat oleh Google. Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device. Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat dicompile ke arsitektur processor ARM atau javascript.
