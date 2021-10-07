Berikut adalah penjelasan yang lebih detail tentang struktur files dari flutter. 
1. .dart_tools : Konfigurasi untuk dart language 
2. .idea : Konfigurasi untuk android studio 
3. gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git. 
4. metadata : File yang berisi metadata dari project
5. packages : File yang berisi alamat path 
6. flutter_basic.iml: File yang berisi detail dari project. 
7. pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml. 
8. pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi. 
9. Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain

Stateless Widget Flutter menggunakan Widget sebagai elemen elemen pembangun UI, widget ini adalah kode program yang diterjemahkan menjadi tampilan yang dapat dilihat dan diinteraksikan oleh pengguna. Stateless widget bersifat statis / final dimana nilai atau konfigurasi telah diinisiasi sejak awal, nilai variabel pada widget ini tidak dapat diubah oleh widget ini sendiri tetapi dapat diubah oleh parent widget nya jika parent nya adalah StatefullWidget. 
Statefull Widget Statefull widget bersifat dinamis, widget ini dapat diperbarui ketika dibutuhkan sesuai dengan action pengguna atau jika ada ada perubahan data. Perubahan data pada statefull widget di trigger oleh perubahan state oleh karena itu sebuah StatefullWidget selalu memiliki State.

Link Repository Tugas Chapter 1
https://github.com/savinalintang/hello_world.git 
https://github.com/savinalintang/tugas_1_flutter.git

Link Repository Tugas Chapter 2
https://github.com/savinalintang/flutter_chapter2.git
