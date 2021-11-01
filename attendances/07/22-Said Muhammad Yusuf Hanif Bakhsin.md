yang saya pelajari selama seminggu kemarin :
# Struktur Project Flutter
Ketika membuat project flutter secara default berikut adalah struktur folder dan filenya. Dapat kita lihat strukturnya terdiri dari .dart_tool, .idea, android, ios, lib, test, .gitignore, .metadata, .packages, .flutter_basic.iml, pubspec.lock, pubspec.yaml, README.md.
1. .dart_tools : Konfigurasi untuk dart language
2. .idea : Konfigurasi untuk android studio
3. gitignore : File git yang digunakan untuk mengelola source code. Hal ini akan berguna jika developer sudah bekerja dengan git.
4. metadata : File yang berisi metadata dari project
5. packages : File yang berisi alamat path
6. flutter_basic.iml: File yang berisi detail dari project.
7. pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
8. pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
9. Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain.
# Flutter Hot Reload
Pada flutter terdapat fungsi hot reload dan hot restart yang digunakan untuk
pengembangan aplikasi dengan flutter. Hote reload mencompile source code yang baru
ditambahkan dan dikirimkan ke dart virtual machine diupdate. Setelah selesai update, dart
virtual machine akan memperbarui UI sesuai dengan perubahan. Keunggulan hot reload
adalah waktu prosenya cepat disbanding hot restart. Akan tetapi hot reload mempertahan
state yang ada sehingga jika menggunakan state maka nilai dari widget tidak akan berubah.
# Flutter Hot Restart
Hot restart akan mencompile ulang aplikasi dan mereset (destroy) state yang ada. Jadi
hot restart akan membuild ulang widget tree sesuai dengan code yang telah diperbarui. 
# Stateless Widget
Flutter menggunakan Widget sebagai elemen elemen pembangun UI, widget ini adalah
kode program yang diterjemahkan menjadi tampilan yang dapat dilihat dan diinteraksikan
oleh pengguna. Stateless widget bersifat statis / final dimana nilai atau konfigurasi telah
diinisiasi sejak awal, nilai variabel pada widget ini tidak dapat diubah oleh widget ini sendiri
tetapi dapat diubah oleh parent widget nya jika parent nya adalah StatefullWidget
# Statefull Widget
Statefull widget bersifat dinamis, widget ini dapat diperbarui ketika dibutuhkan sesuai
dengan action pengguna atau jika ada ada perubahan data. Perubahan data pada statefull
widget di trigger oleh perubahan state oleh karena itu sebuah StatefullWidget selalu memiliki
State

Link Repo Wakatime

https://github.com/SaidMuhammadYusuf/Flutter_Wakatime/blob/6f6cbeea0c05277fb99f500756e70834b2705ab6/1.PNG
