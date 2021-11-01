# Rangkuman Pertemuan 8

Hari ini saya belajar tentang Laravel yang menggunakan API yang telah dijelaskan oleh Farid Maulana.
1. Membuat database dan mengatur koneksi database pada file env yang ada pada project Laravel
2. Kemudian membuat model, contoh yang tadi dipraktekkan oleh Farlan adalah Category
3. Kemudian membuat file migration, di dalam demo tadi terdapat id, name, dan timestamp. Selanjutnya dilakukan php artisan migrate seperti biasa
4. Selanjutnya membuat Controller. Karena sebelumnya penamaan model adalah Category, maka Controller diberi nama CategoryController.
   Buat atau modifikasi 5 function yaitu index, store, show, update dan destroy.
5. Selanjutnya, controller API dibuat dengan syntax **php artisan make:controller CategoryController --api**
   Opsional, kita dapat membuat folder Request untuk meletakkan rules yang diperlukan oleh controller atau folder Resource untuk memodifikasi output
6. Terakhir, mengatur routes api.php agar Controller yang sebelumnya dibuat dapat dipanggil. Penggunaan api.php tidak jauh berbeda dengan web.php

Postman dapat digunakan untuk mengecek data dengan method GET, POST, PATCH, PUT dan DELETE. Sebelum dilakukan pengecekan data, sebaiknya membuat alamat URL pada API Laravel yang telah terhubung dengan controller.
Fitur method pada postman memiliki kegunaannya masing - masing seperti :
- GET : Menampilkan data
- POST : Membuat data baru
- PATCH : Update data yang sebelumnya sudah ada (beberapa field)
- PUT : Update data yang sebelumnya sudah ada (utuh)
- DELETE : Menghapus data yang sudah ada
