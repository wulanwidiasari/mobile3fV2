Rangkuman Minggu Ke-2

7 Jurus Data Binding

	1. Update Gradle
	2. Update Layout
	3. Layout Expression
	4. Ganti Inflate
	5. User Event
	6. Observe
	7. Binding Adapter 

Container Adnroid yang biasa digunakan:
	1. LinearLayout (the box model)
	2. RelativeLayout (a rule-based model), and
	3. TableLayout ( the grid model), along with
	4. ScrollView, sebuah container yang di desain untuk membantu menngimplementasikan scrolling containers.
	5. Other(ListView, GridView, WebView, MapView, dst)
  
1. Linear Layout(box model)
	LinearLayout mewakili sebuah baris atau sebuah column, tambah properti andorid:orientation ke elemen LinearLayout di XML Layout, sesuaikan isi menjadi horizontal untuk baris atau vertical untuk column.
	orientation bisa di modifikasi pada runtime dengan memanggil: setOrientation()
	ada 5 area utama selain container content:
	  1. orientation
	  2. fill model
	  3. weight
	  4. gravity
	  5. padding
	  6. margin
2. Relative Layout
	relativeLayout meletakkan widgets berdasarakan relasi ke widgets lainnya di container dan parent container.
3. Table Layout
	1. android TableLayout menginzinkan kamu untuk posisikan widgets di sebuah grid dibuat dari baris dan kolom yang dapat diidentifikasi.
	2. Kolom mungkin menyusut atau meregang untuk mengakomodasi isinya.
	3. TableLayout bekerja bersama dengan TableRow.
4. ScrollView Layout
	Ketika kami memiliki lebih banyak data daripada yang dapat ditampilkan pada satu layar, Anda dapat menggunakan kontrol ScrollView.
5. Miscellaneous.Absolute Layout
	Layout yang memungkinkan Anda menentukan lokasi yang tepat (koordinat x/y) dari turunannya.
