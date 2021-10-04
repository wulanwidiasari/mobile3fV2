Basic XML Layouts

Containers Linear Layout -> modeling tool paling umum , mirip dengan Java-Swing-Box-Layout Generally, UI design adalah hasil kombinasi dari simpler nested boxes menggunakan horizontal dan vertikal orientation Terdapat beberapa hal yang sering dipakai pada Android containers LinearLayout, relativeLayout,TableLayout, ScrollView, dan other(ListView, GridView, WebView, MapView, dll)
Frame Layout : layout manager dari android paling simpel Terdapat hirarki viewer

DecorVIew
LinearLayout
FrameLayout
TextView (dibawah lagi ada komponen" seperti checkbox, radiobutton, button)
LinearLayout :

Orientation(indikator sebagai representasi baris/kolom) bisa dengan menambahkan properti andorid:orientation pada elemen linearlayout Orientasi bisa di modifikasi dengan fungsi setOrientational()
Fill Model semua widget didalam linearlayout harus dengan atribut android:layout_width dan android:layout_height
Gravity berguna untuk mengontrol posisi button pada layar
Padding banyaknya space antara batasan widget sel dan isi widget content komponen properti : android:padding atau dengan setpadding()
Marging untuk mengatur space antara widget dan padding
Relative Layout adalah tempat widget berdasarkan dengan relationship antara widget lain dalam container beberapa properti relative layout : android:layout_allignParentTop android:layout_allignParentBottom android:layout_allignParentLeft android:layout_allignParentRight dll.

Table Layout untuk mengatur tata letak widget dalam sebuah grid (baris dan kolom) dengan komponen properti android:layout_span

Scroll View menggunakan scroll view saat kita memiliki banyak data yang harus ditampilkan pada single screen

MVVM Java Intro (video youtube)

Data Binding untuk mengikat data langsung ke file xml
ViewModel untuk menyimpan data yang lifecycle aware
Live Data untuk autoupdate, aplikasi jadi responsive
Navigation Comp untuk navigasi antar screen
RecyclerView widget wajib hampir selalu dipakai
Room Presistence untuk solusi database lokal di app
Retrofit Library untuk REST API
