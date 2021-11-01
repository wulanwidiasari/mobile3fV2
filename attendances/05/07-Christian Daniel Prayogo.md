<h1> Rangkuman Minggu Ke-5 </h1>
<h2> Flutter </h2>
Flutter adalah sebuah framework open source yang dibuat oleh Google.
Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android.
Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter menggunakan Dart untuk membuat User Interface, sehingga memudahkan dalam membuat aplikasi karena menggunakan satu bahasa (Dart) dalam pembuatan UI maupun logika program.
Flutter menggunakan pendekatan declarative dimana Flutter membangun UI mengikuti “State” yang dimiliki oleh aplikasi. Ketika state berubah maka UI akan digambar ulang.


<h2> Widget dan Elemen Pada FLutter </h2>
Widget dan Elemen Pada FLutter: Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO,
sebuah bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang lebih kompleks.
Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.
Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget menjadi parent dan widget lain menjadi child.
Masing masing widget dapat diberikan konfigurasi sesuai dengan kebutuhan aplikasi. Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget.
Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.
Baik StatelessWidget maupun StatefullWidget sama sama memiliki sebuah method bernama “build” yang memiliki BuildContext untuk mengatur posisi widget didalam widget tree.

<h2> Struktur Project Flutter </h2>
1. t_tools : Konfigurasi untuk dart language
2. idea : Konfigurasi untuk android studio
3. gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git.
4.  metadata : File yang berisi metadata dari project
6. packages : File yang berisi alamat path
7. flutter_basic.iml: File yang berisi detail dari project.
8. pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
9. pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
10. Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain.

https://github.com/christiandaniel1505/flutter_hello_word.git
https://github.com/christiandaniel1505/polinema_mobile_flutter_hello.git
