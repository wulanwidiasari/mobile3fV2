Rangkuman Minggu ke-4

1.	ListView
Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor.
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengubah ArrayList objek menjadi item View yang dimuat ke dalam wadah container ListView

2.	RecycleView
RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. 
Itu seharusnya menjadi penerus ListView dan GridView.Setiap elemen individu dalam daftar ditentukan oleh objek view holder. 
Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. 
Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.Manajer tata letak mengatur elemen individual dalam daftar Anda. 
Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. 
Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan

3.	Flutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat.
flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native
dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada
smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat
dicompile ke arsitektur processor ARM atau javascript. Flutter menggunakan Skia 2D
rendering engine yang dapat bekerja pada hardware atau software yang berbeda platform.
Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart
menjadi kode native untuk sistem operasi yang digunakan, oleh karena itu aplikasi yang
dibangun menggunakan flutter memiliki kecepatan yang hampir sama dengan aplikasi native

4.	Widget dan Element Pada Flutter
Gaya pengembangan aplikasi menggunakan flutter sedikit berbeda dengan gaya
pengembangan aplikasi pada umumnya, dimana UI pada flutter dibuat menggunakan Widget.
Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah
bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat
dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang
lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.
Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml
pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget
menjadi parent dan widget lain menjadi child. Masing masing widget dapat diberikan
konfigurasi sesuai dengan kebutuhan aplikasi.

