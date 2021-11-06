Project menggunakan Laravel API
Langkah pertama yang harus dilakukan adalah membuat database dan mengkoneksikan di dalam file .env pada project laravel yang akan kita buat. Setelah kita membuat database kita harus membuat model pada praktikum tadi membuat contoh model yaitu model kategori. Lalu membuat file migration, yang isinya adalah table id, nama, timestamp yang dilanjutkan dengan melakukan php artisan migrate. Membuat Controller yaitu CategoryController terdapat 5 function yaitu index, store, show, update, dan destroy. Membuat Controlle API dengan cara php artisan make:controller CategoryController --api. Kita juga dapat membuat folder Request untuk meletakkan rules atau validated yang diperlukan di sebuah controller. Kita dapat juga folder resources untuk dapat memodifikasi output data yang ingin di tampilkan. Langkah terakhir adalah melakukan setting pada routes api.php agar dapat memanggil controller yang diperlukan. Penggunaan disini kurang lebih sama dengan penggunaan pada web.php.

Metode Postman ada beberapa yaitu GET, PUT, POST, dan DELETE, untuk peruntukannya sebagai berikut:

GET : metode yang digunakan untuk mengambil data informasi.

POST : metode yang berfungsi untuk menambah data informasi.

PUT : metode ini digunakan sebagai pembaharuan data informasi.

DELETE : metode untuk menghapus data informasi.


