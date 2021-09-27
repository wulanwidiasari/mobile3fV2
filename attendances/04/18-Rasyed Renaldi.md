# Rangkuman 4

ListView adalah sebuah komponen yang berfungsi untuk menampilkan daftar vertical yang kemudian memiliki data yang diisi menggunakan Adaptor. 
Dalam android development, setiap kali ingin menampilkan daftar vertical yang dapat di scroll, maka yang digunakan adalah ListView yang memiliki data yang diisi menggunakan Adaptor. 
Adaptor paling sederhana digunakan disebut ArrayAdapter karena adaptor mengonversi object ArrayList menjadi item View yang dimuat ke dalam container ListView.
Terdapat 2 cara yang dapat digunakan, yaitu menggunakan ArrayAdapter dan menggunakan Custom ArrayAdapter.
Custom ArrayAdapter dapat digunakan untuk menentukan model, membuat template View, menentukan Adapter, memasang Adapter ke ListView, dan mengisi data ke ListView.

RecycleView adalah ViewGroup yang dapat merender tampilan berbasis adaptor dengan cara yang serupa. Merupakan successor dari ListView dan GridView.
Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Dapat menentukan view holder dengan extend ke RecycleView.ViewHolder.
RecycleView meminta tampilan tersebut dan mengikat tampilan ke datanya dengan dengan memanggil method di adaptor. Dapat menentukan adapter dengan extend ke RecycleView.Adapter.
Layout manager mengatur elemen individual di dalam daftar. Dapat menggunakan salah satu layout manager yang disediakan Pustaka RecycleView, atau dapat menentukannya sendiri. 

Flutter adalah sebuah framework open source yang bertujuan untuk pembuatan desain UI modern, native dan reactive yang dapat berjalan di system operasi Android maupun IOS. 
Dalam bahasa pemrograman yang dipakai ialah bahasa Dart. Selain itu flutter juga memiliki 2 jenis widget, yaitu StatelessWidget dan StatefullWidget. Dalam penggunaannya StatelessWidget digunakan ketika
value tidak berubah sedangkan StatefullWidget digunakan ketika value dari widget dapat berubah.
