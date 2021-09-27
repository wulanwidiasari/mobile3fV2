List View, Recycler View dan Flutter
1. List View
Penjelasan mengenai ListView ada beberapa, yaitu :
a. Dalam pengembangan Android, setiap kali ingin menampilkan daftar vertikal item yang dapat digulirkan, biasanya akan menggunakan List View yang memiliki data yang diisi menggunakan Adaptor
b. Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengubah ArrayList objek menjadi Item Tampilan yang dimuat ke dalam wadah ListView.
2. Custom Array Adapter
Cara kerja Custom Array Adapter sebagai berikut :
a. Tentukan Model 
b. Membuat Template Tampilan
c. Tentukan Adaptor -> ArrayAdapter Inheritance 
d. Melampirkan Adaptor ke ListView 
e. Mengisi Data ke Dalam ListView
3. Recyler Vier
Untuk penjelasan mengenai recycler view ada beberapa seperti :
a. RecyclerView adalah ViewGroup yang membuat tampilan berbasis adaptor dengan cara yang sama. Ini seharusnya menjadi penerus ListView dan GridView. 
b. Setiap elemen individu dalam daftar ditentukan oleh objek pemegang tampilan. Anda menentukan pemegang tampilan dengan memperluas RecyclerView.ViewHolder.
c. RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke data mereka, dengan memanggil metode di adaptor, dengan menentukan adaptor dengan memperluas RecyclerView.Adapter.
d. Layout Manager mengatur elemen individual dalam daftar sehingga dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau juga dapat menentukan sendiri. Pengelola tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.
4. Layout Manager
Pada Recycler View menyediakan beberapa built dari layout manager, yaitu :
a. LinearLayoutManager memperlihatkan item dalam daftar bergulir vertikal atau horizontal.
b. GridLayoutManager menampilkan item dalam grid.
c. StaggeredGridLayoutManager menunjukkan item dalam grid.
5. Adapter
Penjelasan mengenai adapter ini ada beberapa seperti :
a. RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan. 
Sehingga diperlukan untuk mengganti 3 metode, yaitu :
a.	onCreateViewHolder()
b.	onBindViewHolder()
c.	getItemCount()
6. Flutter
Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device.
Flutter juga memudahkan programmer karena dari satu kode program dapat dikompilasi ke kode native ARM, menggunakan GPU dan mengakses fitur spesifik dari smartphone baik yang mengunakan sistem operasi iOS ataupun yang menggunakan sistem operasi Android. Jadi dengan satu kali membuat program dapat membuat 2 aplikasi yang sama untuk sistem operasi yang berbeda (iOS atau Android).
7. Widget dan Element pada Flutter
Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi.
Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.
