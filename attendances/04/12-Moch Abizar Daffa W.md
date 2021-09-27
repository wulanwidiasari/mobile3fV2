Rangkuman Pertemuan ke-4
UI Hierarchy

Antarmuka pengguna (UI) untuk aplikasi Android dibangun sebagai hierarki tata letak dan widget. 
Anda perlu mendefinisikan id dalam XML untuk memanipulasi Widget menggunakan Java atau Kotlin Navigasi adalah interaksi yang memungkinkan user dalam menelurusi masuk , dan keluar dari konten aplikasi. 
Seperti misal terdapat tombol menu Home,Profile. jika kita menekan button profile maka akan pindah ke halaman profile. Nah perpindahan tampilan atau UI ini menggunakan Navigasi. 
Komponen navigasi juga didasarkan pada seperangkat prinsip yang telah ditentukan sebelumnya untuk memastikan pengalaman pengguna yang konsisten dan dapat diprediksi. 
Kita juga dengan mudah me replace suatu menu tanpa memberikan code kembali karena pada menu kita hanya memanggil fungsi fragmentnya saja. 
Navigation Graph adalah gambaran dari semua informasi dari satu lokoasi terpusat. Navigasi adalah interaksi yang memungkinkan user dalam menelurusi masuk , 
dan keluar dari konten aplikasi. Seperti misal terdapat tombol menu Home,Profile. jika kita menekan button profile maka akan pindah ke halaman profile.

Komponen navigasi juga didasarkan pada seperangkat prinsip yang telah ditentukan sebelumnya untuk memastikan pengalaman pengguna yang konsisten dan dapat diprediksi. 
Kita juga dengan mudah me replace suatu menu tanpa memberikan code kembali karena pada menu kita hanya memanggil fungsi fragmentnya saja. 
Navigation Graph adalah gambaran dari semua informasi dari satu lokoasi terpusat.

Navigation Component Navigasi antara layar dan aplikasi yang berbeda adalah bagian inti dari pengalaman pengguna. 
Prinsip-prinsip berikut menetapkan dasar untuk pengalaman pengguna yang konsisten dan intuitif di seluruh aplikasi 
Komponen Navigasi dirancang untuk menerapkan prinsip-prinsip ini secara default, memastikan bahwa pengguna dapat menerapkan heuristik dan pola yang sama dalam navigasi saat mereka berpindah antar aplikasi

List View adalah Dalam pengembangan Android, setiap kali kami ingin menampilkan daftar vertikal item yang dapat digulir, kami akan menggunakan LisView yang memiliki data yang diisi menggunakan Adaptor
Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

RecyclerView :RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
Setiap elemen individu dalam daftar ditentukan oleh objek view holder. Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.
Manajer tata letak mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.
