Rangkuman Pertemuan 2

Model View ViewModel(MVVM)
MVVM adalah sebuah pola arsitektur yang memisahkan antara user interface logic dari business logic. Tujuan penggunaan MVVM sendiri adalah menjaga kode UI agar tetap sederhana dan tanpa mengandung app logic agar mudah untuk dikelola antara lain:
1.Model
Model adalah representasi dari data dan business logic dari aplikasi. Salah satu dari strategi implementasi model adalah membuat model dapat terbuka melalui observables agar terpisah antara ViewModel atau observer/ consumer.
2.ViewModel
ViewModel berinteraksi dengan model dan juga menyiapkan observables yang akan diobservasi oleh View. ViewModel dapat menyediakan hooks untuk view dan mem-pass events kepada model.
3.View
Tugas dari view pada MVVM adalah untuk observe sebuah ViewModel observable untuk mendapatkan data yang akan mengupdate UI/ tampilan.
4.LiveData
LiveData adalah sebuah observable data holder yang memungkinkan components dalam sebuah aplikasi dapat observe/ mengamati objek LiveData ketika terjadi perubahan.
