Pertemuan Ke-5

1.Flutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat
flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native 
dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada 
smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat 
dicompile ke arsitektur processor ARM atau javascript. 

2. Widget dan Element pada Flutter
	Gaya pengembangan aplikasi menggunakan flutter sedikit berbeda dengan gaya 
pengembangan aplikasi pada umumnya, dimana UI pada flutter dibuat menggunakan Widget. 

3. Flutter Hot Reload
    Pada flutter terdapat fungsi hot reload dan hot restart yang digunakan untuk 
pengembangan aplikasi dengan flutter. Hote reload mencompile source code yang baru 
ditambahkan dan dikirimkan ke dart virtual machine diupdate. 

4. Flutter Hot Restart
	Hot restart akan mencompile ulang aplikasi dan mereset (destroy) state yang ada. Jadi 
hot restart akan membuild ulang widget tree sesuai dengan code yang telah diperbarui. 

5. Stateless Widget
	Flutter menggunakan Widget sebagai elemen elemen pembangun UI, widget ini adalah 
kode program yang diterjemahkan menjadi tampilan yang dapat dilihat dan diinteraksikan 
oleh pengguna. Stateless widget bersifat statis / final dimana nilai atau konfigurasi telah 
diinisiasi sejak awal, nilai variabel pada widget ini tidak dapat diubah oleh widget ini sendiri 
tetapi dapat diubah oleh parent widget nya jika parent nya adalah StatefullWidget.

6. Statefull Widget
	Statefull widget bersifat dinamis, widget ini dapat diperbarui ketika dibutuhkan sesuai 
dengan action pengguna atau jika ada ada perubahan data. Perubahan data pada statefull 
widget di trigger oleh perubahan state oleh karena itu sebuah StatefullWidget selalu memiliki 
State.
	
Link Git Praktikum 1: 

	1. hello_world : https://github.com/thltsap/hello_world
	2. polinema_mobile_flutter_hello : https://github.com/thltsap/polinema_mobile_flutter_hello
  
Link Git Praktikum 2:

	1. MyAPP_01 : https://github.com/thltsap/MyAPP_01
