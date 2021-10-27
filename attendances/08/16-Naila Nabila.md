**Rangkuman Pertemuan 8**

Pada pertemuan 8, yaitu mempelajari tentang project Laravel dengan menggunakan API.
- Pertama, mempelajari membuat database dengan mengatur koneksi database pada file .env yang terdapat pada project Laravel
- Kedua, mempelajari membuat model dengan contoh model yang dibuat yaitu model Category.
- Ketiga, mempelajari membuat file migration, tabel yang dibuat terdapat id, name, dan timestamp. Lalu melakukan **php artisan migrate**.
- Keempat, mempelajari membuat controller yaitu CategoryController, pada CategoryController terdapat 5 function yaitu index, store,
show, update dan destroy. Setelah itu, membuat Controller API dengan cara **php artisan make:controller CategoryController --api**.
Kita juga dapat membuat folder request untuk meletakkan rules atau validated yang diperlukan di sebuah controller dan juga kita dapat
juga folder resources untuk memodifikasi output data yang akan ditampilkan.
- Kelima, mempelajari cara mengatur routes **api.php** agar Controller yang sebelumnya dibuat dapat dipanggil. Untuk penggunaan **api.php** tidak
jauh berbeda dengan **web.php**
- Keenam, mempelajari cara menggunakan postman dan cara menjalankannya. Dan juga mempelajari cara penggunaan method 
**GET, PUT, DELETE dan POST**.
