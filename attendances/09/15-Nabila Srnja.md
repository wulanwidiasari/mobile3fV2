link : https://github.com/nsenja/mobile-3f-15.git

Resource : mentransfrom isi data

Penggunaan php artisan tinker untuk insert data pada tabel database sebagai alternatif pengganti form (memakai query eloquent laravel)

membuat login, register, dan logout
1. memakai auth sanctum
2. ketika ingin menggunakan apiResource category dan transaction harus melakukan login terlebih dahulu, jika tidak maka status masih unauthenticated
3. pada postman bagian header jangan lupa checklist bagian key menjadi Accept untuk mengubah hasilnya supaya pakai session
4. cek document laravel untuk membuat login
5. buat terlebih dahulu route login sanctum
6. memakai hash untuk mengenerate passowrd(memakai library facades
7. untuk mendapat token login menggunakan library validation exception
8. percobaan isi data untuk user menggunakan tinker, password menggunakan bcrypt untuk mengenkripsi password
9. cek di postman untuk route api/sanctum/token menggunakan method post
10. lakukan login menggunakan postman pada bagian body isi key dan value sesuai dengan atribut tabel user
11. setelah berhasil login maka akan mendapat token 
12. masukkan token pada authorization, pilih type bearer token dan method get, akses ke route categories/transactions jika berhasil muncul data dari tabel maka berhasil
13. selanjutnya membuat auth controller dengan 3 function (login, logout, register)
14. ubah route menjadi route post sesuai dengan 3 method pada controlelr
15. mencoba register dengan create user baru pada method resgister
16. membuat logout dengan mencari user kemudian terdapat pengecekan jika user tersebut ada maka token akan dihapus dan berhasil logout

 
