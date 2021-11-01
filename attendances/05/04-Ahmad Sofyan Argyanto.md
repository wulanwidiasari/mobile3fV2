#Rangkuman Pertemuan 05

#Flutter

- Apa itu Flutter
	
	Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat
flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native 
dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada 
smartphone google juga membuat flutter untuk desktop, web dan embedded device.

- Widget dan Element pada Flutter

	Gaya pengembangan aplikasi menggunakan flutter sedikit berbeda dengan gaya 
pengembangan aplikasi pada umumnya, dimana UI pada flutter dibuat menggunakan Widget. 
Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah 
bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat 
dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang 
lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.

#Basic Apilikasi Flutter

- Struktur folder

	Ketika membuat project flutter secara default berikut adalah struktur folder dan 
filenya. Dapat kita lihat strukturnya terdiri dari .dart_tool, .idea, android, ios, lib, test, 
.gitignore, .metadata, .packages, .flutter_basic.iml, pubspec.lock, pubspec.yaml, 
README.md.

Berikut adalah penjelasan yang lebih detail tentang struktur files dari flutter.
1. .dart_tools : Konfigurasi untuk dart language
2. .idea : Konfigurasi untuk android studio
3. gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan 
berguna jika developer sudah bekerja dengan git.
4. metadata : File yang berisi metadata dari project
5. packages : File yang berisi alamat path
6. flutter_basic.iml: File yang berisi detail dari project.
7. pubspec.lock : File yang berisi versi library atau package yang digunakan pada 
project yang degenerate sesuai dengan file pubspec.yaml.
8. pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk 
pengembangan aplikasi.
9. Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup
aplikasi atau informasi penting yang perlu untuk diketahui oleh 
developer lain.
