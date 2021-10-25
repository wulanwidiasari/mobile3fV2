## List
List adalah collection yang seperti pada bahasa pemrograman yang lain. Pada bahasa pemrograman Dart, array adalah list of object sehingga disebut juga dengan list. 
Contoh list :

var list = [1,2,3,…list];

List pada Dart menggunakan index 0 sebagai nilai awal dan list.lenght-1 adalah index nilai akhir.

Mulai Dart 2.3 dikenalkan spread operator (…) dan null-aware spread operator (…?)
yang digunakan insert banyak nilai ke collection. Contohnya pada source code di bawah ini,
digunakan untuk memasukkan nilai dari list ke list2.

var list = [1, 2, 3];
var list2 = [0, ...list];
print(list2.length == 4);

## Dropdown Widget
Pada praktikum minggu lalu, saya mempelajari widget Dropdown dimana pada project kemarin, jika pada hasil convert bisa menampilkan semua hasil convert suhu, dengan widget dropdownmenu item, bisa hanya menampilkan slah satu dari hasil convert suhu sesuai dengan suhu yang dipilih. 

## ListView Widget
ListView widget ini adlah widget dimana dapat menampilkan data secara list, yang dapat di scroll kebawah. Pada praktikum yang dilakukan minggu lalu, listview ini digunakan untuk menampilkan history hasil convert suhu.

## Flutter API
Pada hari ini saya belajar tentang Laravel dengan menggunakan API yang dijelaskan oleh Farlan (Farid Maulana). Yang pertama dibutuhkan adalah memiliki atau sudah menginstall aplikasi postman. Pertama membuat project Laravel, kemudian setting key pada file .env, kemudian membuat database dan sudah disesuaikan dengan project Laravel tadi. Lalu membuat model Bernama Category dan migration dari model Category. Kemudian membuat Controller yang dimana menggunakan type API. Berbeda dengan type resources, type API ini memiliki 5 function, yaitu index(), store(), show(), update(), destroy().Kemudian mensetting route api.php untuk memanggil Category. Setelah itu dijelaskan bagaimana melakukan CRUD dengan menggunakan Postman.
