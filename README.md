
# Pertemuan 11 - Dictionary/Map

Nama: Aulia Citra Aljazeera Jan's
NIM: 2225250012
Kelas: 3F

## Tujuan
Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data
Program menggunakan dictionary bernama data_mahasiswa.

Key utama berupa NIM mahasiswa, seperti A001, A002, A003, A004, A005, dan A006.

Setiap NIM memiliki value berupa dictionary yang memuat:
- nama: nama mahasiswa
- kelas: kelas mahasiswa
- nilai: nilai mahasiswa

Folder latihan berisi enam file Python:
1. 01_dasar_dictionary.py
2. 02_akses_get.py
3. 03_manipulasi_dictionary.py
4. 04_iterasi_dictionary.py
5. 05_dictionary_bersarang.py
6. 06_fungsi_dictionary.py

Folder praktik berisi:
- data_mahasiswa.py

## Cara Menjalankan
Buka folder proyek di VS Code.

Jalankan program melalui terminal:

py praktik/data_mahasiswa.py

## Test Case

| No | Input/Aksi | Hasil yang Diharapkan | Hasil Aktual | Status |
|----|------------|-----------------------|--------------|--------|
| 1 | Pencarian A003 | Data Citra ditampilkan | Data Citra ditampilkan | Berhasil |
| 2 | Pencarian A999 | Data tidak ditemukan | Data tidak ditemukan | Berhasil |
| 3 | Mengubah nilai A002 menjadi 82 | Nilai A002 menjadi 82 | Nilai A002 menjadi 82 | Berhasil |
| 4 | Menambahkan A006 | Key A006 tersedia | Key A006 tersedia | Berhasil |
| 5 | Rekap menggunakan items() | Seluruh NIM dan data tampil | Seluruh NIM dan data tampil | Berhasil |
| 6 | Menghitung rata-rata | Rata-rata = 83.50 | Rata-rata = 83.50 | Berhasil |

## Refleksi
Saya memahami bahwa dictionary digunakan untuk menyimpan data dalam bentuk pasangan key-value. Dalam program ini, NIM digunakan sebagai key karena setiap mahasiswa memiliki identitas yang berbeda.

Saya juga memahami bahwa mengakses key yang tidak tersedia menggunakan tanda kurung siku dapat menyebabkan KeyError. Kesalahan tersebut dapat dihindari dengan menggunakan method get() atau memeriksa keberadaan key menggunakan operator in.

Melalui latihan ini, saya belajar menambahkan data mahasiswa, memperbarui nilai, menampilkan seluruh data menggunakan items(), dan menghitung rata-rata nilai menggunakan fungsi.

## Sumber dan Bantuan
- Bahan Ajar Algoritma dan Pemrograman Pertemuan 11: Dictionary/Map dan Pasangan Key-Value dalam Python, Dr. Aan Hendrayana, S.Si., M.Pd.
- Bantuan ChatGPT untuk memahami materi, menyusun kode, dan mengikuti langkah praktik di VS Code.
