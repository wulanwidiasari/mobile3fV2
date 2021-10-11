APLIKASI DENGAN STATEFULL WIDGET
1. Design Aplikasi
   Design aplikasi, dapat dimulai dengan membuat wireframe atau design utuh di perangkat lunak seperti adobe xd, sketch, dsb.
2. Mengkonversi Desain ke Stateless Widget
   Langkah ini harus memperhatikan item-item pada design, widget yang terlibat, juga widget layout yang digunakan.
3. Membuat Aplikasi Interaktif
   Setelah membuat layout selanjutnya adalah membuat aplikasi dengan langkah sebagai berikut :
   a. Convert ke Statefull Widget
   b. Membuat State
   c. Mengambil Data Input
   d. Membuat Event
   e. Menampilkan Output Result
4. Membagi ke Widget Yang Lebih Kecil
   Untuk proses development yang baik widget yang ada di main.dart harus dipotong potong menjadi widget yang lebih sederhana sehingga mudah untuk di maintain dan di perbaiki.
   Berikut ini nama-nama widget dan ekstraksi yang dapat dicontoh untuk ekstraksi widget :
   a. Input : Berisi Widget TextFormField dan controllernya.
   b. Result : Berisi widget hasil konversi yang memiliki variabel nama dan hasil.
   c. Convert : Berisi button dan reference ke function yang digunakan untuk melakukan setState().
   Membagi widget dapat dilakukan dengan melakukan konversi widget antara lain :
   a. Send Parameter ke Child, widget dapat mengirim parameter ke child melalui constructor yang dimiliki oleh widget tersebut.
   b. Send Event Handler ke Child, widget parent dapat mengirim fungsi turun ke child widget dimana fungsi ini akan dipanggil lagi oleh parent widget yang memiliki state. 

