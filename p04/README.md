# P04 Percabangan: if, if-else, switch, dan Operator Logika

Folder kode Pertemuan 4 Pemrograman Terstruktur. Setiap program di sini punya flowchart pasangannya
di modul (Gambar 2 sampai 7); baca gambarnya dulu, baru kodenya.

## Isi

| Berkas | Kegunaan |
|---|---|
| `if_dasar.cpp` | if satu cabang: peringatan bila nilai di bawah 60 | bedanya dengan < saja jika nilai adalah 60 tidak ada peringatan dan jika menggunakan <= maka muncul peringatan karena dengan itu jika nilainya 60 maka sama dengan syarat yg diberikan didalam kode 60, menggunakan <= akan sesuai kontrak | akan selalu dicetak entah nilainya sesuai ataupun tidak  
| `if_else.cpp` | if-else: lulus atau belum lulus | 
| `bertingkat.cpp` | if-else bertingkat tiga syarat; coba tukar urutannya |
| `logika.cpp` | `&&`, `||`, `!` dengan bool bernama; syarat ikut UAS |
| `switch_menu.cpp` | switch dengan break dan default; coba hapus break-nya |
| `sinilai_v03_awal.cpp` | Starter SiNilai v0.3: bagian v0.2 sudah jadi, lengkapi huruf mutu, status, keterangan |
| `contoh_masukan.txt` | Masukan uji yang sama dengan pertemuan sebelumnya |
| `.vscode/`, `.gitignore` | Sama dengan pertemuan sebelumnya |

## Kasus uji SiNilai v0.3

| Empat komponen | Nilai akhir | Huruf | Keterangan | Status |
|---|---|---|---|---|
| contoh_masukan.txt | 83.975 | A | Sangat baik | Lulus |
| 80 x4 | 80 | A | Sangat baik | Lulus |
| 79.9 x4 | 79.9 | B+ | Baik | Lulus |
| 60 x4 | 60 | C | Cukup | Lulus |
| 59.9 x4 | 59.9 | D | Kurang | Belum lulus |
| 30 x4 | 30 | E | Sangat kurang | Belum lulus |

## Yang dikumpulkan mahasiswa

Folder `p04` di repository `pt-NPM` berisi `sinilai_v03.cpp` dan  `README.md`. Lihat Modul Pertemuan 4 bagian E.

## Deklarasi AI
Tidak menggunakan AI tetapi dibantu teman

Tuliskan AI yang digunakan, prompt, dan umpan balik AI

## Tugas Mandiri
1. yang berulang adalah pola pengecekannya kalau di gambar 4 ada 4 sementara saya ada 7 dan pola pengecekan yang sama ada pada 80, 70, 60
4. untuk keluar bisa menggunakan pilihan 3 atau k dan pilihan dari integer berubah menjadi char dengan menggunakan ''
5. masih sama karena setiap input nilai seperti 79.9 misalnya akan langsung dibagi 10 yang mana mengaktifkan opsi ke 7 yaitu nilai B sementara Opsi 10-8 merupakan A.

