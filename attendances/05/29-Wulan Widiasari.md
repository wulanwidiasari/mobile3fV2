# FLUTTER

- Flutter adalah sebuah framework open source yang dibuat oleh Google. Tujuannya adalah membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone, google juga membuat flutter untuk desktop, web dan embedded device.
- Flutter diprogram dengan menggunakan bahasa Dart.
- Dart merupakan sebuah bahasa modern yang dapat dicompile ke arsitektur processor ARM atau javascript. Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart menjadi kode native, oleh karena itu aplikasi yang dibangun menggunakan flutter memiliki kecepatan yang hampir sama dengan aplikasi native.
- Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.

## Struktur files dari flutter :

- .dart_tools : Konfigurasi untuk dart language
- .idea : Konfigurasi untuk android studio
- gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git.
- metadata : File yang berisi metadata dari project
- packages : File yang berisi alamat path
- flutter_basic.iml: File yang berisi detail dari project.
- pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
- pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
- Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain

## Fungsi Flutter Hot Reload dan Hot Restart

- Hot reload mencompile source code yang baru ditambahkan dan dikirimkan ke dart virtual machine diupdate, setelah itu dart virtual machine akan memperbarui UI sesuai dengan perubahan.
- Hot restart mencompile ulang aplikasi dan mereset (destroy) state yang ada. Hot restart akan membuild ulang widget tree sesuai dengan code yang telah diperbarui. 

## Widget

- Stateless Widget (Statis) : nilai atau konfigurasi telah diinisiasi sejak awal, nilai variabel pada widget ini hanya dapat diubah oleh parent widget StatefullWidget.
- Statefull Widget (Dinamis): widget ini dapat diperbarui ketika dibutuhkan sesuai dengan action pengguna atau jika ada ada perubahan data.
- Text Widget : digunakan untuk menampilkan string yang dapat terdiri satu baris maupun beberapa baris.
- Image Widget: digunakan untuk menampilkan image.
- Cupertino Widget : digunakan untuk mendesain sesuai dengan standar desain pada iOS.
- Dialog widget : AlertDialog dan SimpleDialog.
- Button widget : ButtonBar, DropdownButton, FlatButton, FloatingActionButton, IconButton, OutlineButton, PopupMenuButton, dan RaisedButton. 
- Scaffold Widget : digunakan untuk mengatur tata letak sesuai dengan material design.
- Input dan Selection Widget : Checkbox, Date and Time Pickers, Radio Button, Slider, Switch, TextField, dan Date and Time Picker.
- Container widget berguna untuk menyimpan berbagai macam attribute dan menampung berbagai macam fungsi objek. 
- Container merupakan single child objek yang artinya hanya dapat memiliki satu buah child widget, akan tetapi dalam sebuat container kita dapat menempatkan row, column, text dan container lain.
- Column Widget digunakan untuk mangatur tata letak widget secara vertikal. 
- Row Widget digunakan untuk mengatur tata letak widget secara horizontal.
- Properti dari container :
  1. Property child
  2. Property alignment
  3. Property color
  4. Property height dan width
  5. Property margin
  6. Property padding
  7. Property transform
  8. Property decoration
- Stack Widget digunakan untuk menumpuk beberapa widget pada beberapa lapisan.
- ListView widget digunanakan untuk menampilkan data dalam bentuk list dan jika datanya melebihi dari render box maka halaman tersebut dapat di scroll.
- Gridview digunakan untuk menata tata letak widget pada list 2 dimensi.
