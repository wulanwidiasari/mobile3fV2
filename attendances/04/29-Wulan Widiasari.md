## LIST VIEW

- List View digunakan untuk menampilkan daftar vertikal item yang dapat digulir, ListView yang memiliki data yang diisi menggunakan Adaptor.
- Adaptor paling sederhana yang digunakan disebut Array Adapter, adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container List View.

Array Adapter 
- Menentukan model
- Membuat Template View
- Menentukan Adapter -> Array Adapter Inheritance
- Memasang Adapter ke ListView
- Mengisi data ke ListView

## RECYLER VIEW

- RecyclerView adalah View Group yang berfungsi untuk merender tampilan berbasis adaptor dengan cara yang serupa. Recyler View menjadi penerus ListView dan GridView.
- Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Cara menentukan view holder adalah dengan memperluas RecyclerView.ViewHolder.
- RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Cara menentukan adaptor adalah dengan memperluas RecyclerView.Adapter.
- Manajer tata letak mengatur elemen individual dalam daftar, dengan menggunakan salah satu pengelola tata letak yang disediakan oleh library RecyclerView, atau individu dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada abstract class library Layout Manager.

Layout Manager 
Recycler View menyediakan pengelola tata letak bawaan yaitu:
- Linear Layout Manager berfungsi untuk menampilkan item dalam daftar gulir vertikal atau horizontal.
- Grid Layout Manager berfungsi untuk menampilkan item dalam kotak.
- Staggered Grid Layout Manager berfungsi untuk menampilkan item dalam staggered grid.

Adapter 
Recycler View menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang telah digunakan sebelumnya. Namun terdapat beberapa ciri khas seperti ViewHolder yang diperlukan.
Anda perlu mengganti tiga metode:
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()

## FLUTTER

- Flutter adalah sebuah framework open source yang dibuat oleh Google. Tujuannya adalah membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone, google juga membuat flutter untuk desktop, web dan embedded device.
- Flutter diprogram dengan menggunakan bahasa Dart.
- Dart merupakan sebuah bahasa modern yang dapat dicompile ke arsitektur processor ARM atau javascript. Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart menjadi kode native, oleh karena itu aplikasi yang dibangun menggunakan flutter memiliki kecepatan yang hampir sama dengan aplikasi native.
- Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.

Struktur files dari flutter :
1. .dart_tools : Konfigurasi untuk dart language
2. .idea : Konfigurasi untuk android studio
3. gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git.
4. metadata : File yang berisi metadata dari project
5. packages : File yang berisi alamat path
6. flutter_basic.iml: File yang berisi detail dari project.
7. pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
8. pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
9. Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain
