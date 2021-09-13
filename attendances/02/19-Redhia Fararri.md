# Basic XML Layouts :
## 1. Containers

### 1. Linear Layout
- Modeling tool paling umum, mirip dengan Java-Swing-Box-Layout
- Umumnya, desain UI yang kompleks dihasilkan dari kombinasi kotak bersarang sederhana yang menunjukkan potongan dalamnya menggunakan orientasi horizontal atau vertikal
- Kontainer android yang umum digunakan
  1. LinearLayout
  2. RelativeLayout
  3. TableLayout
  4. ScrollView
  5. Other
- Layout manager ter sederhana android adalah **Frame Layout**
- Linear Layout : Merupakan model kotak (widget) yang berbaris di kolom atau baris, satu demi satu
  1. Orientation (menunjukkan apakah LinearLayout mewakili baris atau kolom)
  2. Fill Model : semua widget di dalam LinearLayout harus menyediakan atribut dimensi android:layout_width dan android:layout_height untuk membantu mengatasi masalah ruang kosong
  3. Gravity : digunakan untuk menunjukkan bagaimana kontrol akan sejajar pada layar
  4. Padding : digunakan untuk menentukan berapa banyak ruang yang ada antara batas widget sel dan konten widget
### 2. Relative Layout
- Menempatkan widget berdasarkan relationship
- Beberapa properti relative layout :
  1. android:layout_alignParentTop
  2. android:layout_alignParentBottom
  3. android:layout_alignParentLeft
  4. android:layout_alignParentRight
  5. dll

### 3. Table Layout
- Untuk memposisikan widget dalam grid yang terbuat baris dan kolom yang dapat diidentifikasi

### 4. ScrollView Layout
- ScrollView digunakan jika memiliki banyak data lebih dari satu layar
- Mirip dengan browsing halaman besar yang membuat pengguna scroll up untuk melihat bottom page.
