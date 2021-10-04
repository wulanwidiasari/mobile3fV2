<h1> Rangkuman 04 </h1>
  
  <h2> List View </h2>
<p> List View adalah sebuah komponen yang berfungsi untuk menampilkan daftar vertical yang kemudian memiliki data yang diisi menggunakan Adaptor.
  Dalam android development, setiap kali ingin menampilkan daftar vertical yang dapat di scroll, maka yang digunakan adalah ListView yang memiliki data yang diisi menggunakan Adaptor.
  Adaptor paling sederhana digunakan disebut ArrayAdapter karena adaptor mengonversi object ArrayList menjadi item View yang dimuat ke dalam container ListView.
  Terdapat 2 cara yang dapat digunakan, yaitu menggunakan ArrayAdapter dan menggunakan Custom ArrayAdapter.
  Custom ArrayAdapter dapat digunakan untuk menentukan model, membuat template View, menentukan Adapter, memasang Adapter ke ListView, dan mengisi data ke ListView.</p>
  
  <h2> Recycle View </h2>
  RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa.
  Itu seharusnya menjadi penerus ListView dan GridView.
  Setiap elemen individu dalam daftar ditentukan oleh objek view holder.
  Anda menentukan view holder dengan memperluas RecyclerView.ViewHolder.
  RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor.
  Anda menentukan adaptor dengan memperluas RecyclerView.Adapter.
  Manajer tata letak mengatur elemen individual dalam daftar Anda.
  Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri.
  Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan
  
  <h2> Fluter </h2>
  Flutter adalah platform yang digunakan para developer untuk membuat aplikasi multiplatform hanya dengan satu basis coding (codebase).
  Artinya, aplikasi yang dihasilkan dapat dipakai di berbagai platform, baik mobile Android, iOS, web, maupun desktop.
  Flutter adalah sejenis framework yang digunakan untuk membantu developer membuat aplikasi mobile multiplatform.
  Flutter memiliki dua komponen penting, yaitu, Software Development Kit (SDK) dan juga framework user interface.
