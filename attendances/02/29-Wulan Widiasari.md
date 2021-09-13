**Materi dari video**

Databinding adalah Support library atau pintu gerbangnya MVVM (Model View View Model)

Langkah yang harus dilakukan untuk membuat databinding pada project android :
1. Update Grandle yang ada di module app
2. Update Layout XML di Activity/Fragment ke DataBinding Layout
3. Update Layout XML dengan Layout Expression yang sesuai
4. Ganti Inflate di Fragment/Activity
5. User Event (Handle event dari XML)
6. Observe value dari ViewModel
7. Binding Adapter

**Materi Android Basic XML Layouts**

- Pengelola tata letak paling sederhana android disebut Frame Layout.
- Frame Layout adalah wadah persegi panjang yang menyematkan each child ke sudut kiri atas.
- Menambahkan beberapa tampilan ke tampilan yang lain (tumpang tindih)

Commonly-used Android Containers
1. Linear Layout (the box mode - widget or child containers)
   a. Orientation
   b. Fill Model
   c. Weight
   d. Gravity
   e. Padding
   f. Margin
3. Relative Layout (menempatkan widget berdasarkan hubungannya dengan widget lain pada parent container)
4. Table Layout (berguna untuk memposisikan widget ke dalam kotak yang terbuat dari baris dan kolom)
5. ScrollView (untuk banyak data dalam satu layar sehingga memunggkinkan untuk scroll up)
6. Other(ListView, GridView, WebView, MapView, etc)

**Materi Activities and Intents**

_Activities_

- Activities adalah komponen aplikasi
- Mewakili satu window, satu hirarki tampilan
- Dapat mengisi layar dan dapat disematkan di layar lain (jendela mengambang)
- Activities dapat melakukan user interaction, seperti memverifikasi login, klik tombol, dan entri text
 
Implement new activities
1. Define layout in XML
2. Define Activity in Java Class
3. Connect Activity with Layout
4. Declare Activity in the Android manifest

_Intent_

Intent adalah deskripsi operasi yang akan dilakukan (digunakan untuk meminta tidakan dari orang lain melalui sistem android), antara lain :
1. Start Activitis
2. Start  services
3. Deliver broadcast

Intent dibagi 2  yaitu :
1. Explicit Intent (Memulai aplikasi yang spesifik)
2. Implicit Intent (Meminta sistem untuk menemukan aktifitas yang dapat menangani request tersebut)


