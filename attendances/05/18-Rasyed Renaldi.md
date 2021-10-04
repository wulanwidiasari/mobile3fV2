# Rangkuman MataKuliah Mobile 

Untuk membuat project flutter terdapat 2 cara:
1. Menggunakan "create flutter nama_project" jika menjalankannya pada CMD
2. Dengan vscode, jika plugins flutter nya sudah terinstal hanya dengan mengetikkan
   shortcut ctrl+shift+p dan kemudian pilih New Application Project maka project baru
   akan otomatis dibuat.

Selain itu, flutter juga memiliki kumpulan widget diantaranya:
Text, ListView, Image, Button, Container, Scaffold, Dialog, Input, Dll. Kemudian Widget juga memiliki dua jenis yaitu, StatelessWidget dan StatefulWidget yang berarti
StatelessWidget itu dibuat untuk tampilan datanya statis sedangkan StatefulWidget itu dibuat untuk tampilan datanya dinamis atau dapat diubah-ubah oleh user.

Perbedaan antara Hot Reload dan Hot Restart, ialah jika Hot Reload dilakukan ketika hendak mengubah tampilan dengan cepat dan tetap mempertahankan state atau data yang sudah ada 
sedangkan Hot Restart dilakukan ketika ada perubahan pada state atau data.

Adapaun Struktur Project pada  Flutter
.dart_tools : config untuk bahasa Dart
.idea : config untuk Android Studio
gitignore : file git yang digunakan untuk mengelola source code
metadata : berisi metadata dari project
packages : file yang berisi alamat path
flutter_basic.iml : berisi detail dari project
pubspec.lock : berisi versi library atau package yang digunakan pada project yang degenerate dengan file pubspec.yaml
pubspec.yaml : berisi library atau package yang dibutuhkan untuk pengembangan aplikasi
readme.md : file markdown yang dapat digunakan untuk menjelaskan informasi penting yang perlu untuk diketahui
