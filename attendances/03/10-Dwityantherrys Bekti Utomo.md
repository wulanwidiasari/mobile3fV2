<h1>Rangkuman Pertemuan ke-3</h1>
<br>
Pada pertemuan hari ini materi yang saya dapatkan adalah tentang Widget dan navigasi, arti daripada widget disini adalah komponen komponen yang terdapat pada andoid Studio , widget ini termasuk dalam komponen main dalam Design UI. Beberapa komponennya yaitu TestView,Button,ImageView,RecyclerView,FragmentContainerView,ScrolView, dan Switch. Widget ini adalah pewarisan dari View CLass.
<br>
Kemudian juga membahas tentang Hirarki UI yang peranannya untuk membuat layout hirarki dalam design UI yang akan di buat dengan menggunakan XML.
Untuk set/get value pada widget, ini bergantung pada widget apa yang kita buat. Seperti EditText, ImageView : ImageResource... , RadioButton,Checkbox dan yang lainnya.
Pentingnya penggunaan ini adalah kita bisa mengedit widget dengan detail seperti warnanya, textValuenya, dan juga posisi maupun fontnya juga.
<br>
Navigasi adalah interaksi yang memungkinkan user dalam menelurusi masuk , dan keluar dari konten aplikasi.
Seperti misal terdapat tombol menu Home,Profile. jika kita menekan button profile maka akan pindah ke halaman profile. Nah perpindahan tampilan atau UI ini menggunakan Navigasi.
Komponen navigasi juga didasarkan pada seperangkat prinsip yang telah ditentukan sebelumnya untuk memastikan pengalaman pengguna yang konsisten dan dapat diprediksi. Kita juga dengan mudah me replace suatu menu tanpa memberikan code kembali karena pada menu kita hanya memanggil fungsi fragmentnya saja.
Navigation Graph adalah gambaran dari semua informasi dari satu lokoasi terpusat. Dan juga dengan adanya Navigation graph ini kita bisa menentukan jalur tujuan dari pengguna aplikasi.
Navigation Editor adalah alat untuk mengedit atau membuat navigasi pada aplikasi kita. Terdapat panel Destination yang menunjukkan navigasi dari host ke semua arah yang sudah ditentukan di navigation graph. Kemudian pada bagian Graph Editor terdapat gambaran navigasi yang kita buat dengan menampilkan halaman aplikasi 1 dengan lainnya dan memunculkan garis penghubung sebagai petunjuk tujuan. Pada bagian atribut, gunanya untuk menampilkan atribut pada halaman yang dituju.
Satu bagian penting dari komponen navigasi ini adalah navigation host. Ini adalah tampilan kosong yang digunakan untuk swap dari tampilan satu ke yang lainnya.bisa dibilang seperti transisi,tetapi fungsinya sangat penting karena dengan adanya ini bisa mebersihkan dari tampilan awal ke tampilan tujuan dengan aman. karena akan memberikan load time juga yang sangat penting.
