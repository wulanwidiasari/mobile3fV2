Rangkuman Minggu 6

Pada minggu kemarin saya mempelajari tentang apa itu flutter, mempelajari tentang widget dan pembuatan aplikasi sederhana yang memiliki statefull widget.

Flutter menggunakan Dart untuk membuat User Interface, sehingga memudahkan dalam membuat aplikasi karena menggunakan satu bahasa (Dart) dalam pembuatan UI maupun logika program. 
Flutter menggunakan pendekatan declarative dimana Flutter membangun UI mengikuti “State” yang dimiliki oleh aplikasi. 
Ketika state berubah maka UI akan digambar ulang. Flutter menggunakan Widget sebagai elemen elemen pembangun UI, widget ini adalah kode program yang diterjemahkan menjadi tampilan yang dapat dilihat dan diinteraksikan oleh pengguna. 
Stateless widget bersifat statis / final dimana nilai atau konfigurasi telah diinisiasi sejak awal, nilai variabel pada widget ini tidak dapat diubah oleh widget ini sendiri tetapi dapat diubah oleh parent widget nya jika parent nya adalah StatefullWidget.

Flutter memiliki dua jenis widget yaitu StatelessWidget dan StatefullWidget. 
Stateless widget digunakan ketika value (state /konfigurasi) dari widget tersebut tidak pernah berubah, dan StatefullWidget digunakan ketika value (state / konfigurasi) dari widget dapat berubah.

Mempelajari proses konversi desain ke stateless widget yang sudah di contohkan dan sudah di representasikan menjadi sebuah tree layout pada jobsheet flutter chapter 3, 
kemudian mempelajari bagaimana cara agar pada TextField hanya memiliki tampilan input keyboard khusus angka dan memiliki validasi hanya angka.
