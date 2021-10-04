# Rangkuman Pertemuan 5 :
# Chapter 1
## Flutter
- Flutter adalah sebuah framework open source yang dibuat oleh Google. 
- Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart menjadi kode native untuk sistem operasi yang digunakan.
- Dart juga menggunakan konsep just-in-time (JIT) sehingga memungkinkan programmer dapat membuat perubahan pada kode program dan langsung melihat hasilnya melalui fitur hot reaload yang dimiliki Flutter.
## Widget
- Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO,
- Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi. 
Flutter memiliki dua jenis widget yaitu :
- Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah.
- StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.
# Chapter 2
## Struktur Folder pada Project Flutter
Berikut adalah penjelasan yang lebih detail tentang struktur files dari flutter.
- .dart_tools : Konfigurasi untuk dart language 
- .idea : Konfigurasi untuk android studio 
- gitignore : File git yang digunakan untuk mengelola source code.
- metadata : File yang berisi metadata dari project 
- packages : File yang berisi alamat path 
- flutter_basic.iml : File yang berisi detail dari project.
- pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml. 
- pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi. 
- Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain.
## Multi os ios dan android 
Pada folder project flutter terdapat dua folder yaitu folder ios dan folder android.
## Folder android
Folder android berisi file file pendukung untuk mengenerate project android dan akan dikompilasi menjadi sebuah apk pada folder build.
## Folder ios
Berisi project ios, folder ini sama dengan folder android, sangat jarang dan bahkan tidak perlu untuk mengubah apapun pada folder ios. 
## Folder lib
Folder lib berisi kode program dengan bahasa dart yang berupa widget yang dapat dibuat sesuai dengan kebutuhan aplikasi anda.
## Folder test
Berisi source code dart yang digunakan untuk melakukan test secara otomatis pada aplikasi flutter.
## Pubspec.yaml
file ini berisi konfigurasi konfigurasi project flutter yang dibuat dimana anda dapat mendata asset berupa font, gambar dan lain lain. 

## Link Repo Flutter Chapter 1
Praktikum :
- https://github.com/nailanabilaaaaaa/flutter-hello-world.git
Tugas :
- https://github.com/nailanabilaaaaaa/polinema_mobile_flutter_hello.git

## Link Repo Flutter Chapter 2
https://github.com/nailanabilaaaaaa/flutter-basic.git
