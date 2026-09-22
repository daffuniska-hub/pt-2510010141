## k1_sintaks
jenis kesalahan : kurangnya ; atau penanda akhir suatu sintaks
Pesan yang Muncul : k1_sintaks.cpp:7:5: error: expected ',' or ';' before 'std'
cara mengetahuinya : pada saat run test di terminal menunjukan error pada bagian int = 80 dan saya menyadari bahwa baris tersebut tidak diberi ; sebagai penanda akhir

## k2_nama
jenis kesalahan : tidak mengenali variabel yang harus di jalankan
Pesan yang Muncul : k2_nama.cpp:9:31: error: 'Nilai' was not declared in this scope; did you mean 'nilai'?
cara mengetahuinya : karena ada perbedaan pada nama variabel seperti huruf kapital

## k3_runtime
jenis kesalahan : tidak melanjutkan ke fungsi berikutnya
Pesan yang Muncul : tidak ada pesan warning/error yang muncul
cara mengetahuinya : test run 2 kali dengan mengetikkan 4  dan 0

- saat mengetikkan 0 tidak muncul apa-apa sementara disaat mengetikkan 4 memunculkan rata rata dari jumlah mahasiswa tersebut

## k4_logika
jenis kesalahan : kesalahan penggunaan tipe variabel
Pesan yang Muncul : tidak ada pesan error/warning yang muncul
cara mengetahuinya : saya mengingat kode yang ada di rerata.cpp yang mengharuskan menggunakan bilangan pecahan supaya int tidak membuang pecahannya

- walau sama2 tidak mengeluarkan warning untuk k4 cukup sederhana karena hanya perlu mengganti jenis tipe data

## Kesalahan paling Fatal
menurut saya kesalahan paling fatal adalah k3 dan k4
1. k3 dan k4 = dikarenakan tidak ada error atau warning yang muncul menyebabkan kita sulit untuk mencari penyebab masalah di suatu kode apalagi jika kode tersebut ada ribuan baris
2. k4 = jika membutukan mesin yang harus mencatat dan menghitung sesuatu secara akurat k4 bisa sangat fatal karna bisa saja membuat perhitungan melenceng yang menyebabkan laporan yang dibuat menjadi tidak valid