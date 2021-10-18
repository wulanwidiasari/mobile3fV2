# Hasil belajar 1 minggu
- Melihat youtube 07 Mini Project Flutter Konverter Suhu Part 1 dan Part 2
- Latihan ngoding membuat miniproject konverter suhu
- Belajar layout dan menentukan widget harus bisa mendefinisikan ROW dan COLUMN dan MainAxisAligment
- State dan Event bisa diidentifikasi dengan melihat "apa yang berubah" dan "apa yang mentrigger"
- dalam flutter untuk input bisa menggunakan textfield atau textformfield
1. Textfield: jika belum tahu diapa2kan
2. Textformfield: jika ingin ada validasi,dll

pengunaan wrap with column:
untuk menambah widget dalam bentuk kolom kekanan

pengunaan wrap with row:
untuk menambah widget dalam bentuk kolom kebawah

membuat fungsi pada button untuk menghitung konversi

![3](https://user-images.githubusercontent.com/63260212/137657633-0dbacb23-0329-4d9e-ba32-db2491b0d889.png)

fungsi _konversiSuhu
- penjelasan pada class tersebut mendeklarasikan object etInput dengan class TextEditingCOntroller
- kemudian pendefinisian variabel untuk jenis satuan suhu (kelvin, reamur, fahrenheit, dan inputUser) dengan nilai 0
- fungsi _konversiSuhu dengan setState berisi logika untuk menghintung konversi suhu
- variabel inputUser memasukkan nilai untuk dikonversi dengan tipe data double
- definisikan rumus perhitungan suhu masing-masing satuan dengan metode perbandingan
4/5 untuk reamur
9/5 + 32 untuk fahrenheit
dan +273 untuk kelvin

untuk hasil konversi = variabel suhu yang diinginkan input user

## Screenshoot Wakatime
![Screenshot (1507)](https://user-images.githubusercontent.com/63260212/137657513-d35c8c36-eb9e-4119-87c9-3fdc833c4c36.png)
![Screenshot (1506)](https://user-images.githubusercontent.com/63260212/137657520-e631e4d3-97e9-46ea-ad88-bc5d151cacf7.png)
