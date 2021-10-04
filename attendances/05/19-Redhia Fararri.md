# Flutter

## Apa itu flutter?
- Flutter adalah sebuah framework open source yang dibuat oleh Google
- Flutter dibuat dengan tujuan membangun framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun android
- Google juga membuat flutter untuk desktop, web dan embedded device
- Flutter diprogram dengan menggunakan bahasa Dart
- Dart menggunakan metode AOT (Ahead of Time) untuk mengubah code menjadi code natce
- Dart menggunakan konsep JIT (Just In Time) yang memungkinkan programmer membuat perubahan dan langsung melihat hasilnya

## Widget dan Elemen pada Flutter
- Widget adalah sebuah bentuk baru yang dapat disusun dan masing masing dapat dikombinasikan satu sama lain sehingga membentuk bentuk baru yang lebih kompleks
- Widget dapat disusun dan dikombinasikan dalam satu layar
- Widget dapat disusun dalam bentuk tree dimana satu widget menjadi parent dan yang lain menjadi child
- Terdapat 2 jenis widget yaitu :
  1. StatelessWidget : Digunakan ketika value dari widget tidak pernah berubah
  2. StatefullWidget : Digunakan ketika value dari widget dapat berubah
- StatelessWidget dan StatefullWidget sama sama memiliki sebuah method bernama **build** yang memiliki BuildContext untuk mengatur posisi widget

## Struktur Project Flutter
### Struktur folder
1. .dart_tools : config untuk dart language
2. .idea : config untuk android studio
3. gitignore : file git yang digunakan untuk mengelola source code
4. metadata : berisi metadata dari project
5. packages : file yang berisi alamat path
6. flutter_basic.iml : berisi detail dari project
7. pubspec.lock : berisi versi library atau package yang digunakan pada project yang degenerate dengan file pubspec.yaml
8. pubspec.yaml : berisi library atau package yang dibutuhkan untuk pengembangan aplikasi
9. readme.md : file markdown yang dapat digunakan untuk menjelaskan informasi penting yang perlu untuk diketahui

### Multi OS iOS dan Android
Flutter dapat membuat aplikasi berbasis ios dan android dalam satu project

### Folder Android
Berisi  file file pendukung untuk mengenerate project android dan akan dikompilasi menjadi sebuah apk pada folder build.

### Folder lib
Berisi kode program dengan bahasa dart yang berupa widget yang dapat dibuat sesuai dengan kebutuhan aplikasi

### Folder test
Berisi source code dart yang digunakan untuk melakukan test secara otomatis pada aplikasi flutter

### Pubspec.yaml
Berisi konfigurasi konfigurasi project flutter yang dibuat dimana anda dapat mendata asset berupa font, gambar dan lain lain

## Flutter Hot Reload dan Restart
1. Flutter hot reload : mengcompile source codeyang baru ditambahkan dan dikirimkan ke dart virtual machine diupdate
2. Flutter hot restart : mengcompile ulang aplikasi dan mereset state yang ada
