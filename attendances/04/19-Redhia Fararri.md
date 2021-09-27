# ListView and RecyclerView

## Tugas
- APLAS deadline minggu ini
- Jobsheet flutter deadline minggu ini

## Rangkuman
- Dalam pengembangan Android, jika ingin menampilkan daftar vertikal item yang scrollable maka dapat menggunakan ListView
- ListView digunakan karena memiliki data yang diisi dengan adaptor
- ArrayAdapter adalah adapter yang simple yang biasanya digunakan untuk mengubah ArrayList sebuah object menjadi View item yang dimasukkan ke dalam ListView Container
- Cara penggunaan ArrayAdapter dan customisasi :
  1. Tentukan model
  2. Membuat tmplate tampilan
  3. Menentukan adaptor --> ArrayAdapter inheritance
  4. Melampirkan adaptor ke ListView
  5. Mengisi data kedalam ListView

- RecycleView adalah komponen yang berfungsi untuk menampilkan data dalam bentuk list. Data yang ditampilkan bisa lebih dari satu
- Setuap elemen individu dalam daftar ditentukan oleh objek pemegang tampilan
- Menentukan pemegang tampilan dengan memperluas RecyclerView.ViewHolder
- RecyclerView meminta tampilan tersebut dan mengikat tampilan ke data dengan memanggil metode di adaptor
- Layout manager :
  1. LinearLayoutManager memperlihatkan item dalam daftar scrolling vertikal atau horizontal
  2. GridLayoutManager menampilkan item dalam grid
  3. StaggeredGridLayoutManager menunjukkan item dalam grid

- Adapter RecyclerView menyertakan jenis adaptor baru yang merupakan pendekatan yang mirip dengan yang sudah digunakan, tetapi dengan beberata karakter khusus seperti ViewHolder yang diperlukan.
- Diperlukan mengganti tiga metode
  1. onCreateViewHolder()
  2. onBindViewHolder()
  3. getItemCount()
