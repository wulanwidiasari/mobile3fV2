Pertemuan 05

# BASIC APLIKASI FLUTTER
  Untuk membuat project baru flutter melalui VS code, perlu dilakukan : 
  - Menginstall extension flutter dan dart -
  - Setelah extension terinstal, dengan menggunakan Ctrl+Shift+p, kemudian pilih Flutter: New Application Project.

STRUKTUR FILE FLUTTER:
- dart_tools : Konfigurasi untuk dart language
- idea : Konfigurasi untuk android studio
- gitignore : File git yang digunakan untuk mengelola source code.
- metadata : File yang berisi metadata dari project
- packages : File yang berisi alamat path
- flutter_basic.iml: File yang berisi detail dari project.
- pubspec.lock : File yang berisi versi library atau package yang digunakan pada project yang degenerate sesuai dengan file pubspec.yaml.
- pubspec.yaml : File yang berisi library atau package yang dibutuhkan untuk pengembangan aplikasi.
- Readme.md : File markdown yang dapat digunakan untuk menjelaskan cara setup aplikasi atau informasi penting yang perlu untuk diketahui oleh developer lain.

Flutter dapat membuat aplikasi berbasis ios dan android dalam satu project.

# Flutter Hot Reload:
Melakukan compile code yang baru ditambahkan dan dikirimkan ke virtual machine untuk melakukan update dengan mempertahankan state. 
keunggulannya lebih cepat dari hot Restart

# Flutter Hot Restart
 Hot restart akan mencompile ulang aplikasi dan mereset state yang ada. Jadi hot restart akan membuild ulang widget tree sesuai dengan code yang telah diperbarui.


