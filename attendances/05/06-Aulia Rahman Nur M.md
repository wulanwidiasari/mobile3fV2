# Rangkuman Pertemuan 5

## Flutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device. Flutter menggunakan Dart untuk membuat User Interface, sehingga memudahkan dalam membuat aplikasi karena menggunakan satu bahasa (Dart) dalam pembuatan UI maupun logika program. Flutter menggunakan pendekatan declarative dimana Flutter membangun UI mengikuti “State” yang dimiliki oleh aplikasi. Ketika state berubah maka UI akan digambar ulang.

## Widget dan Elemen pada Flutter
Widget dan Elemen Pada FLutter: Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi. Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget menjadi parent dan widget lain menjadi child. Masing masing widget dapat diberikan konfigurasi sesuai dengan kebutuhan aplikasi. Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah. Baik StatelessWidget maupun StatefullWidget sama sama memiliki sebuah method bernama “build” yang memiliki BuildContext untuk mengatur posisi widget didalam widget tree.

## Struktur Preject Flutter
- t_tools : Konfigurasi untuk dart language
- idea : Konfigurasi untuk android studio
- gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git.
- metadata : File yang berisi metadata dari project
- packages : File yang berisi alamat path
- flutter_basic.iml: File yang berisi detail dari project.
- pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
- pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
- Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain.

# Link Tugas

## Praktikum 1
1. Flutter-hello-world: https://github.com/Aulia-Rnm/flutter-hello-world.git
2. polinema_mobile_flutter_hello: https://github.com/Aulia-Rnm/polinema_mobile_flutter_hello.git

## Praktikum 2
