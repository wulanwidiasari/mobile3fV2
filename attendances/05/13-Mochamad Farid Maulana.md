Rangkuman Mobile 4 Okt
==

Membuat Project Flutter
--
Terdapat 2 cara untuk membuat project baru flutter, yakni
1. Menggunakan perintah "create flutter nama_project" yang dijalankan pada command line
2. Melalui vscode yang sudah terinstall plugins flutter, yakni dengan ctrl+shift+p kemudian pilih New Application Project

Widget Flutter
--
Flutter tersusun dari kumpulan widget. Berbeda dengan android native yang membutuhkan file layout (.xml) dan activity (.java) untuk membuat aplikasi mobile, flutter hanya membutuhkan file main.dart untuk membuat sebuah aplikasi mobile. 
Terdapat banyak sekali widget dalam flutter, seperti
- Text
- Image
- ListView
- Container
- Button
- Scaffold
- Dialog
- Input
- Dan yang lainnya

Widget dalam flutter memiliki dua jenis, yakni StatelessWidget dan StatefulWidget. StatelessWidget digunakan untuk membuat tampilan yang datanya statis, dalam artian user tidak dapat mengubah data yang ada di dalam StatelessWidget. Sedangkan StatefulWidget digunakan untuk membuat tampilan yang datanya dapat diubah-ubah oleh user, contohnya ialah widget input yang harus berada di StatefulWidget.

Widget di dalam flutter memiliki konsep parent-child, dimana setiap widget memiliki anak dan jumlah anaknya pun berbeda-beda. Jumlah anak tersebut menunjukkan jika widget tersebut dapat menampung berapa banyak widget lain di dalamnya. Contoh widget yang dapat memiliki banyak anak ialah Row, Column, ListView. 

Hot Reload vs Hot Restart
--
Fitur ini merupakan kelebihan flutter, dimana ketika hanya mengubah tampilan dari aplikasi dapat dilakukan dengan hot reload yang lebih cepat karena pada proses hot reload tersebut tetap mempertahankan state atau data yang ada. Sedangkan hot restart dilakukan ketika ada perubahan pada state atau data.

Link Repository Tugas Flutter
--
[https://github.com/farid-maulana/flutter-HelloWorld](https://github.com/farid-maulana/flutter-HelloWorld)

[https://github.com/farid-maulana/polinema_mobile_flutter_hello](https://github.com/farid-maulana/polinema_mobile_flutter_hello)

[https://github.com/farid-maulana/flutter-SoccerNews](https://github.com/farid-maulana/flutter-SoccerNews)
