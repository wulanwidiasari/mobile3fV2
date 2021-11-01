Rangkuman Pertemuan Ke-2

**Android **
- Tumpukan perangkat lunak untuk perangkat seluler
- SDK menyediakan tools dan API untuk mengembangkan aplikasi

**Komponen Utama Android**
- Activities
- Services
- Content Providers
- Broadcast Receivers

**View & View Group**
“Layouts” subclass menyediakan arsitektur layout yang berbeda: 
1. LinearLayout – menampilkan Tampilan dalam arah linier baik secara horizontal maupun vertical, default adalah horizontal. Bidang teks, dua tombol radio, dan tombol dalam orientasi vertikal
2. RelativeLayout – menampilkan Tampilan dalam posisi relatif satu sama lain, id perlu ditetapkan ke elemen untuk referensi. Bidang teks, dua tombol radio, dan tombol dalam posisi relative

**ViewGroup Layout**
- TableLayout – menampilkan Tampilan dalam bentuk tabel dengan baris dan kolom Tombol.
- Beberapa layout lain dari android.view. 

**ViewGroup :**
1. AbsoluteLayout
2. FrameLayout
3. ScrollView

**Common Attributes**
Atribut View and ViewGroup :
1. layout_width
2. layout_height
3. layout_margintop
4. layout_marginbottom
5. layout_marginleft
6. layout_marginright
7. layout_x
8. layout_y

Atribut LinearLayout dan TableLayout :
1. layout_gravity – menentukan bagaimana tampilan diposisikan
2. layout_weight – menentukan berapa banyak ruang yang akan dialokasikan, total harus sama dengan 1

**Android MVVM DataBinding Java**
Pada intinya DataBinding adalah pintu gerbang dari MVVM. 

**Latihan Jurus Data Binding**
Ada beberapa Langkah yang harus dilakukan untuk membuat DataBinding pada project Android, yaitu :
1. Update Gradle
2. Update Layout
3. Layout Expression
4. Ganti Inflate
5. User Event
6. Observe
7. Binding Adapter

**Ringkasan container Android yang umum digunakan**
1. LinearLayout ( the box model ),
2. RelativeLayout ( a rule-based model ), dan
3. TableLayout ( the grid model ), 
4. ScrollView, a container designed to assist with implementing scrolling containers. 
5. Other ( ListView, GridView, WebView, MapView ) 

