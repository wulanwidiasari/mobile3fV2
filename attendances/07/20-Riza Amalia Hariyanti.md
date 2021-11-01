Rangkuman Minggu 07
--

Pada pertemuan minggu lalu, saya mempelajari tentang beberapa hal terkait dengan project konverter suhu. Antara lain sebagai berikut :

Membuat Layouting Konverter Suhu
--

- Membuat program sederhana terkait konverter suhu

- Mendefinisikan Row dan column pada aplikasi tersebut.

- Membuat _state_ (bagian yang berubah) dan _event_ (bagian yang mentrigger).

- Menerapkan _Scaffold_ pada _Material App_.

- Membreakdown layout menjadi beberapa bagian berdasarkan itemnya terlebih dahulu.

- Membuat _input_ menggunakan _TextFormField_ dan _TextField_, perbedaan dari kedua inputan tersebut adalah terletak pada penerapannya, _TextFormField_ digunakan untuk inputan yang mempunya validasi (lebih kompleks), dan _TextField_ merupakan inputan yang tidak memiliki validasi, pada umumnya digunakan untuk penggunaan standar saja.

- Mempelajari tentang penggunaan _container_, dan _wrapping_ secara _column_ dan _row_ pada saat _layouting_.

- Menerapkan penggunaan _button_ yang dapat melakukan aksi pada saat ditekan menggunakan _RaisedButton_ dengan _method_ _onPressed_.

- Membuat dekorasi pada _input value_ menggunakan _keyboardType_ _number_, dan juga formaternya menggunakan _digitOnly_ sehingga hanya menampilkan angka saja. Lalu membuat sebuah _controller_ yang memiliki nilai _etInput_ untuk menerima _value_ dari inputan.

Menentukan State dan Event
--

_State_ merupakan seuatu _value_ yang dapat memiliki perubahan, sedangkan _Event_ merupakan suatu _value_ yang melakukan _trigger_. Berikut ini merupakan konsep dari penerapannya.

1. App Logic

   - Melakukan koneksi Event

   - Membuat Set State

   - Menambahkan bebnerapa Logic

- Mendefinisikan penggunaan _state_, yakni variable yang dapat memiliki perubahan data, yakni pada inputan. Antara lain _inputUser, kelvin, fahrenheit, dan reamur_.

- Mendefinisikan penggunaan _event_ yaitu ketika inputan diberikan, maka tombol yang ditekan merupakan bagian dari _event_.

- Membuat _function_ untuk melakukan konversi nilai suhu.

2. Extract Widget

   Merupakan langkah yang dilakukan untuk membuat _source code program_ menjadi lebih rapi atau melakukan split dengan membentuk _widget_ yang lebih kecil dengan tujuan untuk memudahkan pada saat maintain program serta pembuatan kode progam. Langkah-langkahnya antara lain sebagai berikut.

   - Split jadi widget yang lebih kecil

   - memperhatikan cara data dikirim dan eventnya.

   - Membuat _Named Constructor_.

Link Repo WakaTime

https://github.com/Riza-Amalia/wakatime.git

