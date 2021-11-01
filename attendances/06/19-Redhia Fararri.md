# Rangkuman Mobile 11 Oktober

Dalam satu minggu kemarin, saya mencoba mengkonversi UI yang telah dicontohkan dalam jobsheet flutter chapter 3 ke dalam kodingan. Didalam jobsheet telah dilampirkan bentuk tree yang memudahkan mengkonversi desain ke kodingan.

Terdapat shortcut visual studio code yang dapat membantu membangun aplikasi flutter yaitu menggunakan CTRL + . yang digunakan untuk wrapping widget yang sudah ada atau untuk mengekstrak widget yang sudah ada menjadi kelas baru.

Pada praktikum di chapter 3 mempelajari bagaimana agar suatu text field hanya dapat diisi dengan angka serta hanya menampilkan keyboard khusus angka ketika text field onfocus

Agar dapat melakukan input ke dalam text field, maka widget harus diubah terlebih dahulu kedalam statefull widget agar dinamis

Untuk mengambil inputan user yang berada di text field menggunakan TextEditingController dan membuat function yang dapat dipanggil

Terdapat proses logika dalam sistem konversi suhu yang dilakukan pada chapter 3 :
1. User memasukkan data melalui text field
2. TextEditingController menyimpan hasil inputan user
3. Ketika button di klik, maka akan menjalankan sebuah event yang didalamnya untuk mengonversi suhu, hasil dari inputan user tersebut perlu di konversi dulu ke double karena hasil inputan user masih dalam bentuk string
