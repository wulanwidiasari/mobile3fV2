#Rangkuman pertemuan 5

##Flutter:
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern,
native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat dicompile ke arsitektur processor ARM atau javascript.
Flutter menggunakan Skia 2D rendering engine yang dapat bekerja pada hardware atau software yang berbeda platform. 
Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart menjadi kode native untuk sistem operasi yang digunakan, 
oleh karena itu aplikasi yang dibangun menggunakan flutter memiliki kecepatan yang hampir sama dengan aplikasi native. 
Dart juga menggunakan konsep just-in-time (JIT) sehingga memungkinkan programmer dapat membuat perubahan pada kode program
dan langsung melihat hasilnya melalui fitur hot reaload yang dimiliki Flutter. Flutter menggunakan Dart untuk membuat User Interface,
sehingga memudahkan dalam membuat aplikasi karena menggunakan satu bahasa (Dart) dalam pembuatan UI maupun logika program. 
Flutter menggunakan pendekatan declarative dimana Flutter membangun UI mengikuti “State” yang dimiliki oleh aplikasi. Ketika state berubah maka UI akan digambar ulang .

##Widget dan Elemen Pada FLutter:
Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah bentuk baru dapat disusun dari beberapa balok 
dan masing masing kumpulan balok dapat dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang lebih kompleks. 
Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi. Widget dapat disusun dan dikombinasikan dalam satu layar, 
sama halnya dengan xml pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget menjadi parent dan widget lain menjadi child.
Masing masing widget dapat diberikan konfigurasi sesuai dengan kebutuhan aplikasi. Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. 
Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, 
dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah. Baik StatelessWidget maupun StatefullWidget 
sama sama memiliki sebuah method bernama “build” yang memiliki BuildContext untuk mengatur posisi widget didalam widget tree.

## Struktur Project Flutter
1. .dart_tools : config untuk dart language
2. .idea : config untuk android studio
3. gitignore : file git yang digunakan untuk mengelola source code
4. metadata : berisi metadata dari project
5. packages : file yang berisi alamat path
6. flutter_basic.iml : berisi detail dari project
7. pubspec.lock : berisi versi library atau package yang digunakan pada project yang degenerate dengan file pubspec.yaml
8. pubspec.yaml : berisi library atau package yang dibutuhkan untuk pengembangan aplikasi
9. readme.md : file markdown yang dapat digunakan untuk menjelaskan informasi penting yang perlu untuk diketahui

## Flutter Hot Reload dan Flutter Hot Restart
Flutter Hot Reload elakukan compile code yang baru ditambahkan dan dikirimkan ke virtual machine untuk melakukan update, sedangkan Flutter Hot Restart Melakukan compile ulang aplikasi dan mereset state yang ada.

