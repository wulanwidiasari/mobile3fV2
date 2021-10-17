## Rangkuman Minggu 06

Pada minggu kemaren saya mempelajari tentang konsep basic layouting pada flutter, antara lain sebagai berikut :

## Widget

Merupakan sebuah objek dari sebuah class dan memiliki konstruktor untuk pembentukan aplikasi flutter, serta konsep widget ini disusun dalam bentuk tree.

1 Stateless Widget

  Merupakan widget yang tidak membutuhkan sebuah state dan berdiri sendiri (State tidak pernah berubah).

2 Statefull Widget

  Merupakan widget yang membutuhkan state lain untuk dapat menjalankan peosesnya (State dapat berubah).

3 Hirarki Widget Tree

  Material App -> Scaffold -> Widget Lain


Lalu saya mempelajari tentang konversi desain ke dalam bentuk widget, langkah pertama yaitu melakukan analisa terhadap bagian-bagian UI kedalam bentuk tree untuk memudahkan dalam penerapan pada kode progam. Setelah analisa dilakukan, layout dibentuk berdasarkan Row dan Column yang dibungkus pada sebuah Scaffold. Kemudian saya mempelajari bagaimana cara membuat kode program yang clean dengan cara widget-widget yang menumpuk di satu file, yaitu main.dart menjadi beberapa kelas yang bisa dipanggil di main.dart. cara membuat class tersebut dengan cara memilih salah satu widget dan tekan ctrl + . dan pilih extract widget. Setelah itu nantinya kita harus memberi nama class widget tersebut sesuai yang diinginkan. Setelah class tersebut jadi, dapat dipindahkan ke dalam file berformat .dart , nantinya kita tinggal menghubungkan file class tersebut dengan main.dart menggunakan import.
