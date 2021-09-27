#ListView & RecyclerView
•	ListView
•	RecyclerView
##ListView
•	Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
•	Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.
##RecyclerView
•	RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
•	Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
•	RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.
•	Manajer tata letak mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.
##LayoutManagers
•	RecyclerView menyediakan pengelola tata letak bawaan ini:
•	LinearLayoutManager menampilkan item dalam daftar gulir vertikal atau horizontal.
•	GridLayoutManager menampilkan item dalam kotak.
•	StaggeredGridLayoutManager menampilkan item dalam kisi terhuyung.
##Adapter
•	RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
•	Anda perlu mengganti tiga metode:
1.	onCreateViewHolder()
2.	diBindViewHolder()
3.	getItemCount()
##Flutter
Apa itu Flutter Flutter adalah sebuah framework open source yang dibuat oleh Google. Google membuat flutter dengan tujuan membangun sebuah framework untuk membuat UI yang modern, native dan reactive yang dapat berjalan di sistem operasi iOS maupun Android. 
Tidak hanya pada smartphone google juga membuat flutter untuk desktop, web dan embedded device. Flutter diprogram dengan menggunakan bahasa Dart sebuah bahasa moderen yang dapat dicompile ke arsitektur processor ARM atau javascript. Flutter menggunakan Skia 2D rendering engine yang dapat bekerja pada hardware atau software yang berbeda platform. Dart menggunakan metode compilasi ahead of time (AOT) untuk mengubah kode Dart menjadi kode native untuk sistem operasi yang digunakan, oleh karena itu aplikasi yang dibangun menggunakan flutter memiliki kecepatan yang hampir sama dengan aplikasi native. Dart juga menggunakan konsep just-in-time (JIT) sehingga memungkinkan programmer dapat membuat perubahan pada kode program dan langsung melihat hasilnya melalui fitur hot reaload yang dimiliki Flutter. Flutter menggunakan Dart untuk membuat User Interface, sehingga memudahkan dalam membuat aplikasi karena menggunakan satu bahasa (Dart) dalam pembuatan UI maupun logika program. Flutter menggunakan pendekatan declarative dimana Flutter membangun UI mengikuti “State” yang dimiliki oleh aplikasi. Ketika state berubah maka UI akan digambar ulang . Flutter juga memudahkan programmer karena dari satu kode program dapat dikompilasi ke kode native ARM, menggunakan GPU dan mengakses fitur spesifik dari smartphone baik yang mengunakan sistem operasi iOS ataupun yang menggunakan sistem operasi Android. Jadi dengan satu kali membuat program dapat membuat 2 aplikasi yang sama untuk sistem operasi yang berbeda (iOS atau Android).
##Widget dan Element pada Flutter 
Gaya pengembangan aplikasi menggunakan flutter sedikit berbeda dengan gaya pengembangan aplikasi pada umumnya, dimana UI pada flutter dibuat menggunakan Widget. Widget adalah sebuah konsep dimana UI dapat dianggap sebagai sebuah balok LEGO, sebuah bentuk baru dapat disusun dari beberapa balok dan masing masing kumpulan balok dapat dikombinasikan dengan kumpulan balok lain sehingga membentuk sebuah bentuk baru yang lebih kompleks. Flutter menggunakan widget ini sebagai balok dasar pembangunan aplikasi. Widget dapat disusun dan dikombinasikan dalam satu layar, sama halnya dengan xml pada pemrograman android native, widget dapat disusun dalam bentuk tree dimana satu widget menjadi parent dan widget lain menjadi child. Masing masing widget dapat diberikan konfigurasi sesuai dengan kebutuhan aplikasi. Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah. Baik StatelessWidget maupun StatefullWidget sama sama memiliki sebuah method bernama “build” yang memiliki BuildContext untuk mengatur posisi widget didalam widget tree detail mengenai widget dan bagaimana membuatnya akan dibahas pada bab selanjutnya.


