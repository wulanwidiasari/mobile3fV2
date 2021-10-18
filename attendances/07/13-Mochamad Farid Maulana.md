Rangkuman Mobile 18 Okt
==

List
--
Pada bahasa pemrograman dart, list sama seperti array dimana terdapat index yang dimulai dari 0 untuk menunjukkan alamat dari sebuah data. 
Untuk versi dart 2.3 ke atas, terdapat **spread opreator(...)** dan **null-aware spread operator(...?)** untuk insert banyak nilai ke dalam list. Contoh penggunaannya sebagai berikut:

    var list = [0, ...list];
    var lists = [0, ...?list];

Selain itu dart juga menyediakan **collection if** dan **collection for** pada list untuk membuat list dengan kondisi atau perulangan. Contoh penerapannya sebagai berikut:

    var sidebar = [
      'Dashboard',
      'Buku',
      if (isAdmin) 'Manajemen User',
    ];

    var listOfInts = [1, 2, 3];
    var listOfStrings = [
      '#0', for (var i in listOfInts) ' #$i',
    ];

Navigate
--
Merupakan cara perpindahan layar dalam aplikasi flutter, terdapat 3 jenis navigate yang saya pahami:

1. push, yakni menumpuk layar yang sedang aktif dengan layar yang baru. Ini dipakai jika ingin membuat aplikasi yang setelah berpindah layar maka layar tersebut dapat dikembalikan ke layar sebelumnya (fitur back)
2. pop, yakni mengambil tumpukan layar yang sedang aktif. Ini biasanya digabungkan dengan push.
3. replace, yakni mengganti layar yang sedang aktif dengan layar yang baru. Jika menggunakan fitur ini maka tidak ada opsi back menggunakan pop

Starter Code
--
Selain belajar mengenai flutter melalui jobsheet, saya juga sedang mencoba membuat sebuah starter code untuk development laravel. Untuk saat ini baru progress layouting dan user management.

camp404 - Flutter
--
Minggu ini saya juga mulai mengikuti pelatihan flutter di camp404. Untuk ilmu yang sudah saya dapat dari pelatihan tersebut, yakni:

1. Shortcut flutter pada vscode
2. Membangun sebuah layout dari blank file
3. Menyimpan style widget pada sebuah variabel
4. Tips & trick dalam membangun aplikasi flutter

Link Repository Report Wakatime 18 Okt 2021
--
https://github.com/farid-maulana/wakatime-report/blob/main/18%20Okt%202021.md
