Rangkuman Mobile 11 Okt
==

Pada minggu kemarin mencoba mengonversi user interface yang sudah disediakan pada jobsheet flutter chapter 3 ke dalam kodingan. Dalam prosesnya diperlukan untuk mengidentifikasi terlebih dahulu bagian bagian dalam UI. Dapat dibuat dalam bentuk tree untuk memudahkan dalam mengonversi desain ke kodingan.

Shortcut visual studio code yang dapat membantu dalam membangun aplikasi flutter yakni menggunakan ctrl + . yang dapat digunakan untuk wraping widget yang sudah ada atau untuk mengekstract widget yang sudah ada menjadi sebuah class baru.

Pada proses praktikum di chapter 3 juga mempelajari bagaimana caranya agar sebuah text field hanya dapat diisi dengan angka serta hanya menampilkan keyboard khusus angka ketika text field dalam keadaan aktif (onfocus).

Agar user dapat melakukan input ke dalam text field, widget harus diubah terlebih dahulu ke dalam statefullwidget agar menjadi dinamis.

Untuk mengambil data yang dihasilkan dari text field, perlu menggunakan TextEditingController untuk merekam dan menyimpannya.

Proses logika dalam sistem konversi suhu di chapter 3 adalah sebagai berikut:

1. User memasukkan data melalui text field
2. TextEditingController menyimpan hasil inputan user
3. Ketika button di klik, maka akan menjalankan sebuah event yang di dalamnya untuk mengonversi suhu ke dalam kelvin dan reamur. Namun sebelum dikonversi, hasil inputan user tersebut perlu dikonversi terlebih dahulu ke dalam double. Hal itu dikarenakan hasil inputan user masih dalam bentuk String.

Pada chapter 3 ini juga mempelajari bagaimana caranya memisah setiap widget agar di dalam setiap file nya tidak terlalu banyak kode baris. Dalam memisahkannya juga terkadang memerlukan sebuah parameter yang akan diproses di widget tersebut.
