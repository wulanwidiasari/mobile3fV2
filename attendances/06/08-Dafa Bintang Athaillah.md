# Rangkuman Yang di Pelajari Selama 1 Minggu
Pada 1 minggu kemarin saya mempelajari cara meng extract widget dan saya mencoba untuk membuat UI dari konversi suhu,
pada UI konversi suhu terdapat Scaffold yang di dalamnya ada App bar dengan title text "Converter" dengan type cons, maksudnya
cons disini ialah data satis juka text "Converter" dijadikan sebuah variable dan datanya dinamis maka cons tadi harus di hapus
untuk menghindari error.
selanjutnya terdapat body dengan container dan di dalam container tadi terdapat 1 column yang membungkus 1 childers dengan 1 textfromfield,
lalu di bawah dari childer textfromfield tadi terdapat 1 row dengan mainaxisalignment bertype spaceAround, yang membungkus 3 column,
yang mana masing masing dari column merepresentasikan suhu apa dan berapa hasil knversinya.
lalu di bawah dari row yang membungkus 3 column tadi terdapat 1 container yang mana container ini merupakan container untuk button konversi
dan container ini terletak didalam dari column pertama yang membungkus row tadi.  jadi jika di jabarkan child: column pertama membungkus sebuah
childern textfromfield, lalu ada row dengan childern 3 column yang mana masing-masing column memiliki childern text, mengapa smua dari childern
dibungkus oleh 1 child column di awal?? karena pada struktur hasil/tampilan dari code itu menyusun kebawah dan ada 2 suhu yang menyusun ke samping.
makadari itu susunan code menjadi demikian seperti yang sudah saya sebutkan di awal.
lalu untkuk memcah masing masing widget kita bisa mengeztract widget misal pada bagian textfromfield inputan suhu kita ctrl+titik lalu pilih extract
widget lalu text editor akan meminta kita memberi nama dari hasil extract widget lalu widget yang telah di extract akan muncul sebagai class di bagian
bawah codingan dan kelas tersebut bisa kita pindahkan dengan cara membuat file pada folder lib atau membuat folder lagi pada lib lalu membuat file itu opsional.
jika saya di sini langsng membuat file pada folder lib dengan nama sesuai dengan nama widget yang di extract tadi lalu setelah itu pada file baru akan terlihat error
tapi jngan khawatir disini kita hanya tinggal meng import kan material.dart dan pada main dart kita importkan nama file baru/hasildari extract tadi .dart.
