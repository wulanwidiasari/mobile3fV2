## Rangkuman Minggu 06

Pada minggu kemaren saya mempelajari tentang konsep basic layouting pada flutter, antara lain sebagai berikut :

## Widget

Merupakan sebuah objek dari sebuah class dan memiliki konstruktor untuk pembentukan aplikasi flutter, serta konsep widget ini disusun dalam bentuk tree.

- Stateless Widget

  Merupakan widget yang tidak membutuhkan sebuah state dan berdiri sendiri (State tidak pernah berubah).

- Statefull Widget

  Merupakan widget yang membutuhkan state lain untuk dapat menjalankan peosesnya (State dapat berubah).

- Hirarki Widget Tree

  Material App -> Scaffold -> Widget Lain

Lalu saya mempelajari tentang konversi desain ke dalam bentuk widget, langkah pertama yaitu melakukan analisa terhadap bagian-bagian UI kedalam bentuk tree untuk memudahkan dalam penerapan pada kode progam. Setelah analisa dilakukan, layout dibentuk berdasarkan Row dan Column yang dibungkus pada sebuah Scaffold. Kemudian saya mempelajari bagaimana cara membuat kode program yang clean dengan cara mengelompokkan antar widget menjadi sebuah folder dan melakukan import widget tersebut pada file `main.dart`.
