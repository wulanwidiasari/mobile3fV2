# Rangkuman Mobile 13 Sept

Android Basic XML Layout
--
Jenis - jenis layout android:
- Linear Layout (box model)
- Relative Layout (rule-based model)
- Table Layout (the grid model)
- Scroll View (a container designed to assist with implementing scrolling containers)
- Frame Layout (simplest layout manager)

Linear Layout <br>
Jenis layout yang berbasis box, yakni setiap komponen di dalamnya disejajarkan dalam satu arah, secara horizantal atau vertikal. Atribut untuk mengonfigurasi Linear Layout:
- Orientation: digunakan untuk mengatur arah linear layout, horizontal (row) atau vertical (column). 
- Fill Model: digunakan untuk mengatur ukuran dari komponen yang ada di dalam linear layout, sehingga untuk setiap komponen harus memiliki atribut android:layout_width dan android:layout_height.
    - android:layout_width, untuk mengatur lebar komponen
    - android:layout_height, untuk mengatur tinggi komponen
- Weight
- Grafity: digunakan untuk mengatur alignment komponen.
- Padding: digunakan untk mengatur jarak antara isi dan batas komponen.
- Margin: digunakan untuk mengatur jarak antar komponen.

Relative Layout <br>
Jenis layout yang berbasis hubungan antar komponen. Sehingga setiap komponen harus ditentukan berada di bagian mana, seperti berada di sebelah kanan dari komponen B atau berada di bagian paling atas di sebuah layout.

Table Layout <br>
Jenis layout yang memposisikan komponen dalam sebuah grid atau tabel.

ScrollView Layout <br>
Jenis layout yang digunakan untuk menampilkan banyak data dalam satu layar.

Android Activity & Intent
--
Activity, merupakan komponen yang merepresentasikan satu layar dalam sebuah aplikasi android. Dalam satu aplikasi dapat terdiri dari banyak activity yang tiap activity nya memiliki daur hidup dan tampilkan (file xml) masing - masing.
Untuk menghubungkan antar activity di dalam sebuah aplikasi android diperlukan yang namanya intent. Terdapat 2 jenis intent, yakni intent explisit dan intent implisit.
- Intent explisit, yakni intent yang menghubungkan antar activity di dalam aplikasi android itu sendiri. Contoh berpindah dari layar utama ke layar detail.
- Intent implisit, yakni intent yang menghubungkan aplikasi android dengan aplikasi yang lainnya. Contoh membuka kamera dari aplikasi android kita.
Dalam proses perpindahan activity menggunakan intent juga dapat mengirimkan data sekaligus untuk di proses di activity yang dituju.

Langkah - Langkah Data Binding
--
1. Update gradle
2. Update layout
3. Layout expression
4. Ganti inflate
5. User event
6. Observe
