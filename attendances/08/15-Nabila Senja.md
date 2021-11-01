Pada hari ini saya belajar tentang flutter api dengan project laravel, langkah-langkah yang saya lakukan yaitu :

1. untuk langkah yang pertama yaitu membuat project laravel dengan api (laravel new api)
2. setelah itu menginstall postman untuk mengecek data 
3. membuat database pada mysql sesuai keinginan
4. lalu mengoneksikan project dengan database pada file env, tuliskan pada line db_database sesuai dengan nama database yang telah dibuat tadi
4. selanjutnya membuat migration untuk tabel categories dengan kolom id, name, dan timestamp (created at dan updatetd at) dan jalankan menggunakan artisan migrate, lalu cek pada database apakah tabel sudah terbuat atau tidak
5. lalu membuat controller yaitu CategoryController resource api yang memiliki beberapa crud method antara lain index, store untuk input, show untuk menampilkan data, update untuk memperbarui data, dan destroy untuk menghapus data
6. untuk memanggil controller yang telah dibuat bisa menggunakan routes web.php, berhubung kali ini menggunakan api maka dengan api.php 
7. untuk pengecekan isi data bisa dilakukan dengan postman menggunakan perintah get 
8. ada beberapa method pada postman get/put/delete and post
9. get : untuk membaca data dan bersifat read only
10. put : untuk mengirim data pada server dan membuat resource baru
11. delete : untuk menghapus data
12. post : untuk mengupdate resource yang sudah ada
