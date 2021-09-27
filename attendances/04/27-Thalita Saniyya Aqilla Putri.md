Rangkuman Minggu ke-4

1. List View
Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

2. RecyclerView
RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.

3. Flutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat
flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native
dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada
smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat
dicompile ke arsitektur processor ARM atau javascript.

4. Widget dan Element pada Flutter
Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.
Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml
pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget
menjadi parent dan widget lain menjadi child.
Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless
widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah,
dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.
