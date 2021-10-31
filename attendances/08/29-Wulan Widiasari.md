# Pertemuan 8 - Laravel dengan menggunakan API
Berikut adalah poin-poin yang saya rangkum dari penjelasan Farid Maulana.
1. Langkah pertama yaitu membuat database dan mengatur koneksi database pada file env yang ada pada project laravel
2. Setelah itu membuat model, pada penjelasan model yang dibuat adalah Category.
3. Selanjutnya yaitu membuat file migration, pada penjelasan terdapat atribut id, name, dan timestamp. Selanjutnya yaitu _php artisan migrate_
4. Lalu setelah itu membuat Controller. Sesuai dengan nama model yaitu Category, maka controller tersebut diberi nama CategoryController.
5. Langkah selanjutnya adalah controller API yang memiliki 5 function yaitu index, store, show, update, dan destroy. Controller api ini dibuat dengan syntax _php artisan make:controler CategoryController --api_ untuk meletakkan rules yang diperlukan controller atau folder Resource untuk memodifikasi output maka kita dapat membuat folder _request_
6. Menyetting route api.php agar controller yang sebelumnya dibuat dapat dipanggil. api.php tidak jauh berbeda dengan web.php
