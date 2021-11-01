RecycleView & ListView

Dalam pengembangan Android, saat ingin menampilkan daftar vertikal item yang akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor

Adaptor paling sederhana disebut ArrayAdapter karena adaptor mengubah ArrayList objek menjadi item tampilan yang dimuat ke dalam wadah ListView.

Cara penggunaan ArrayAdapter dan customisasi
1. Tentukan Model
2. Membuat Template Tampilan
3. Tentukan Adaptor -> ArrayAdapter Inheritance
4. Melampirkan Adaptor ke ListView
5. Mengisi Data ke Dalam ListView

RecyclerView 
Adalah ViewGroup yang membuat tampilan berbasis adaptor dengan cara yang sama dan menjadi penerus ListView dan GridView. 

- Setiap elemen individu dalam daftar ditentukan oleh objek pemegang tampilan(Layout Manager).
- Menentukan pemegang tampilan dengan memperluas RecyclerView.ViewHolder.
- RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke data mereka, dengan memanggil metode di adaptor. 

Layout Manager
- LinearLayoutManager memperlihatkan item dalam daftar bergulir vertikal atau horizontal.
- GridLayoutManager menampilkan item dalam grid.
- StaggeredGridLayoutManager menunjukkan item dalam grid

Adapter
RecyclerView menyertakan jenis adaptor baru yang merupakan pendekatan yang mirip dengan yang sudah digunakan, tetapi dengan beberapa karater khusus, seperti ViewHolder yang diperlukan.
Perlu mengganti tiga metode:
onCreateViewHolder()
onBindViewHolder()
getItemCount()

