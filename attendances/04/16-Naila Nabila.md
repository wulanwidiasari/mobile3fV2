##List View
1.	Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
2.	Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.
##Recycle View
1.	RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
2.	Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
3.	RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.
4.	Manajer tata letak mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.
##LayoutManagers
1.	RecyclerView menyediakan pengelola tata letak bawaan ini:
2.	LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
3.	GridLayoutManager menampilkan item dalam kotak.
4.	StaggeredGridLayoutManager menampilkan item dalam kisi terhuyung.
##Adapter
1.	RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
2.	Perlu mengganti tiga metode:
a.	onCreateViewHolder()
b.	diBindViewHolder()
c.	getItemCount()
##Flutter
1.	Flutter sebuah framework open source yang dibuat oleh Google. Google membuat flutter bertujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. 
2.	Menggunakan bahasa Dart, sebuah bahasa moderen yang dapat dicompile ke arsitektur processor ARM atau javascript. 
3.	Dart menggunakan metode compilasi ahead of time (AOT).
4.	Dart menggunakan konsep just-in-time (JIT)
5.	Flutter menggunakan Dart untuk membuat User Interface
##Widget dan Element pada Flutter
1.	Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi. 
2.	Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml.
3.	Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. 
