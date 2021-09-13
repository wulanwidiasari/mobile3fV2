W01 : 

Android merupakan kumpulan perangkat lunak untuk perangkat seluler atau SDK yang menyediakan alat dan API dalam mengembangkan aplikasi. 
Komponen utamanya terbagi menjadi empat bagian, terdapat aplikasi yang terdiri dari home, contacts, phone, browser, dan lainnya. Kedua terdapat application framework yang terdiri dari activiticy manager
, window manager, content providers, view system, package manager, telephony manager, resources manager, location manager, dan notification manager. Ketiga terdapat libraries yang terdiri dari surface manager, media framework, SQLite, OpenGL, Free type, WebKit, SGL, SSL, dan libc. Terakhir terdapat linux kernel terdiri dari display driver, camera driver, flash memory driver, binder (IPC driver, keypad driver, WiFi Driver, Audio Drivers, dan terakhir Power Management. Pertama terdapat applications yang dikirim dengan kumpulan aplikasi utama, yang ditulis dalam Java. Pemrogram dapat mengembangkan melalui akses ke API inti untuk tampilan yang digunakan dalam membangun dan mengembangkan aplikasi, penyedia konten untuk mengakses data dari aplikasi lain, manajer sumber daya untuk akses kestring local grafik, manajer notifikasi untuk tampilan lansiran khusus, serta manajer aktivitas untuk mengelola siklus hidup aplikasi. Selanjutnya, ialah libraries yang terdapat komponen berupa C/C++, Media libraries – A/V, images, Surface manager – 2D/3D graphic layers, LibWebCore – web browser engine, SGL – 2D graphics engine, 3D – hardware or software acceleration, FreeType – BMP and vector fonts, dan SQLite – database engine.  

MVVM intinya adalah databinding yang 
bertujuan untuk membind data ke file xml

MVVM DataBinding jika penggunaannya benar otomatis proses akan jauh lebih 
cepat dan DataBinding ini sebagai pintu gerbang MVVM 

W02 :

MVVM DataBinding jika penggunaannya benar otomatis proses akan jauh lebih 
cepat dan DataBinding ini sebagai pintu gerbang MVVM

Ada 7 step untuk membuat DataBinding
- Update Gradle
	file build.grade di module.app
- Update Layout
	Layout Xml di activity/Fragment ke databinding layout
- Layout Expression
	Sama seperti di blade atau di Laravel
- Ganti Inflate
Biasanya Android Studio akan auto generate sendiri. Jika gagal ada 3 cara yang dapat dilakukan yaitu Clear Project, lalu Clear Project, jika masih tidak bisa Close Android Studio lalu buka lagi dan ini adalah Worse case.
- User Event
- Observe
- Binding Adapter
