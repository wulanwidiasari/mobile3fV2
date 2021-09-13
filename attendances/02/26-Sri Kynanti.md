Rangkuman2

Activity dan Intents

Aktifity adalah, komponen aplikasi yang biasanya mengisi layar tetapi dapat disematkan di layar lain.
Activity melakukan aktifitas seperti mengirim email, menangani interaksi pengguna seperti klik tombol, entri teks, atau verifikasi login, dapat memulai aktivitas lain diaplikasi yang sama, dan memiliki siklus seperti dibuat, dimulai, dijalankan, dihentikan, dan dihancurkan.
Contoh activity : kalulator, maps, dsb.

Intent adalah, deskripsi operasi yang harus dilakukan, intent adalah object yang digunakan untuk meminta tindakan dari yang lain.
Intent dapat melakukan activity, memulai layanan, dan mengirim siaran.

Explicit dan Implicit Intens
Explicit intents, memulai aktivitas tertentuu
  Seperti: Aktivitas utama memulai aktivitas ViewShoppingCart.
Implicit intents, meminta sistem untuk menemukan aktivitas yang dapat menangani permintaan
  Seperti: Mengklik berbagi ataupun membuka pemilih dengan daftar aplikassi

Semua aktivias dikella oleh runtime Android. Dimulai dengan intent, pesan ke runtie android untuk menjalankan aktivitas, begitulah cara Activities berjalan

Terdapat dua jenis pengiriman data dengan intent, yaitu:
1. data-one informasi yang lokasi datanya dapatt diwakili oleh URI
2. Ekstra-one atau lebih infrmasi sebagaii koleksi pasangan key-value daalam bundle

Databinding
Databinding adalah pintu gerbang atau penghubung MVVM.
Langkah - langkah yang dilakukan untuk membuat databinding:
1. update Gradle,
2. Update Layout,
3. Layout Expression,
4. Anti Inflate, 
5. User Event,
6. Observe, dan
7. Binding adapter.
