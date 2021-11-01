Secara garis besar: List View & RyclerVew
List View:
1. Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor.
2. Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.
Ilustrasi List View: DataSource(cursor, arraylist)< ---- >Adapter< ---- >AdapterView(list view, grid view, spinner)
Custom ArrayAdapter:
1. Tentukan modelnya
2. Buat tampilan template
3. Tentukan adaptor -> Warisan ArrayAdapter
4. Memasang adaptor ke ListView
5. mengisi data ke ListView

RecyclerView:
RecyclerView adalah versi ListView yang lebih canggih dan fleksibel. Widget ini adalah kontainer untuk menampilkan rangkaian data besar yang bisa digulir secara sangat efisien dengan mempertahankan tampilan dalam jumlah terbatas.
Komponen RecyclerView
RecyclerView(Layour Manager) ---- > Adapter ---- > Dataset.
Layout Managers:
Tampilan Pendaur Ulang menyediakan pengelola tata letak bawaan ini:
1. LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
2. GridLayoutManager menampilkan item dalam kotak.
3. StaggeredGridLayoutManager menampilkan item dalam kisi terhuyung.
Adaptor
Adapter menghubungkan data Anda dengan RecyclerView. Adapter menyiapkan data dan cara menampilkan data dalam view holder. Bila data berubah, adapter akan memperbarui materi tampilan item daftar terkait dalam RecyclerView.
Adapter juga merupakan ekstensi dari RecyclerView.Adapter. Adapter menggunakan ViewHolder untuk menampung tampilan yang menyusun setiap item dalam RecyclerView, dan mengikat data untuk ditampilkan dalam tampilan yang menampilkannya.

Kode program pada adapter inilah yang menjadi bagian paling penting pada Recyclerview. Pada umumnya Adapter menerima dua input yaitu data dan layout item yang digunakan pada adapter inilah data dan layout di hubungkan(binding).

RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
Anda perlu mengganti tiga metode:
1. onCreateViewHolder()
2. onBindViewHolder()
3. getItemCount()
View holder adalah bagian dari adapter yang berisi tampilan informasi untuk menampilkan satu item dari layout item.

Pada case praktikum mahasiswa mempelajari bagaimana cara menginstall flutter, menampahkan path dll, selain itu kita juga di ajarkan untuk membuat project Bahasa dart dan mengkonfigurasikan reala device dengan visual studio code.
