Rangkuman Minggu ke-8

Project Menggunakan Laravel API
1. Mempelajari cara membuat project laravel menggunakan API
2. Mempelajari cara membuat database pada project laravel tepatnya difile .env
3. Mempelajari cara membuat category yaitu index,store,show,update,destroy
4. Mempelajari migration untuk tabel categories dengan kolom id, name, dan timestamp (created at dan updatetd at) dan jalankan menggunakan artisan migrate, lalu cek pada database apakah tabel sudah terbuat atau belum
5. Membuat controller API dengan perintah diterminal yaitu php artisan make:controller CategoryController --api-
6. Penggunaan aplikasi postman sebagai isi data, dan methodnya seperti contoh GET,PUT,DELETE,POST

Langkah-Langkah membuat API pada Laravel

1. Membuat database dan mengkoneksikan di file .env pada project laravel
2. Membuat model yaitu model category
3. Membuat file migration, dimana terdapat table id,nama,timestamp, setelah selesai data tersebut akan dimasukan kedalam Database dengan perintah php artisan migrate
4. Membuat Controller yaitu CategoryController yang dimana terdapat 5 function index,show,update,dan destroy
   Kita juga dapat membuat folder request untuk meletakkan rules atau validated yang diperlukan di sebuah controller
5. Setting pada routes api.php supaya bisa memanggil Controller yang diperlukan
