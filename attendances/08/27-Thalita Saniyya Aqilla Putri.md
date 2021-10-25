Pada Pertemuan kali ini mempelajari tentang langkah - langkah membuat API pada project Laravel

1. Langkah awal membuat database dan mengkoneksikannya di file env pada project Laravel
2. Selanjutnya membuat Model pada praktikum tadi membuat contoh model yaitu model Category.
3. Selanjutnya membuat File migration, terdapat table id, name, timestamp. Setelah itu lakukan php artisan migrate.
4. Membuat Controller yaitu CategoryController terdapat 5 function yaitu index, store, show, update, dan destroy. Membuat Controlle API dengan cara php artisan make:controller CategoryController  --api. 
Kita juga dapat membuat folder Request untuk meletakkan rules atau validated yang diperlukan di sebuah controller. Kita dapat juga folder resources untuk dapat memodifikasi output data yang ingin di tampilkan.
5. Langkah terakhir mesetting pada routes api.php agar dapat memanggil Controller yang diperlukan. Penggunaan api.php kurang lebih dengan penggunaan pada web.php.


Mempelajari Cara menggunakan postman dan cara menjalankannya. Pada praktikum ini juga mempelajari cara penggunaan method GET, PUT, DELETE dan POST.
Cara mengubah format data pada model yang awalnya Tahun/Bulan/Hari menjadi Hari/Bulan/Tahun.
