# Rangkuman Materi Activities and Intents dan JAVA DataBinding

Minggu Ke-02 Mata Kuliah Mobile
--

            Nama           : Rasyed Renaldi
            NIM            : 1941720177
            No.Absen       : 18
            Dosen Pengampu : Putra Prima Arhandi, S.T., M.Kom.

Contents
--

- Activities -> Salah satu komponen aplikasi yang berfungsi untuk interaksi pengguna ke sistem.

- Intents -> Adalah suatu object yang digunakan untuk mengeksekusi apa yang akan dilakukan oleh pengguna melalui sistem Android.

- Sending and Receiving Data -> Terdapat dua cara pengiriman yaitu, dengan URL dan key-value.

Dalam aktivitas (pengiriman) pertama:

1. Buat objek Intent
2. Masukkan data atau ekstra ke dalam maksud itu
3. Mulai aktivitas baru dengan startActivity()

Dalam aktivitas (penerimaan) kedua:

1. Dapatkan objek maksud saat aktivitas dimulai
2. Ambil data atau ekstra dari objek Intent.

- Navigation -> Adalah suatu komponen yang bisa memudahkan pengguna dalam menggunakan aplikasi.

Android MVVM DataBinding Java
--

DataBinding adalah pintu gerbang MVVM, yang mana ketika penggunaan databindingnya benar maka secara otomatis sudah tidak ada lagi findViewByld proses inflate layout jauh lebih cepat, aplikasi pun bisa lebih responsive dan binding di xml bisa di hubungkan dengan ViewModel dan LiveData.

Berikut adalah langkah-langkah yang harus dilakukan untuk membuat databinding pada project android:

1. Update Gradle
2. Update Layout XML di Activity/Fragment ke DataBinding Layout
3. Update Layout XML dengan Layout Expression
4. Ganti Inflate di Fragment/Activity
5. User Event (Handle Event dari XML)
6. Observe value dari ViewModel
7. Binding Adapter
