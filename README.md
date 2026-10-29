
# Pertemuan 11 - Dictionary/Map

**Nama:** Muhammad Rizky Ramzy Ramadhan  
**NIM:** 2225250199  
**Kelas:** 3E

## Tujuan
Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data
Program menggunakan NIM sebagai key utama.
Setiap value berupa dictionary yang berisi nama, kelas, dan nilai mahasiswa.

## Struktur Folder
- `latihan/`: enam latihan dictionary Python.
- `praktik/data_mahasiswa.py`: program sistem data mahasiswa.

## Cara Menjalankan
Jalankan setiap file latihan melalui VS Code.

Untuk program utama, jalankan:

```bash
python praktik/data_mahasiswa.py
```

## Test Case
| Kasus | Input/Aksi | Hasil yang Diharapkan |
|---|---|---|
| Pencarian tersedia | A003 | Data Citra ditampilkan |
| Pencarian tidak tersedia | A999 | Data tidak ditemukan |
| Pembaruan nilai | A002 menjadi 82 | Nilai A002 berubah menjadi 82 |
| Penambahan data | A006 | Data Fajar tersedia |
| Rekap | items() | Semua data mahasiswa ditampilkan |
| Rata-rata | Seluruh nilai | 83.50 |

## Refleksi
Kesalahan yang perlu dihindari adalah KeyError
ketika mengakses key yang tidak tersedia.
Untuk mengatasinya, gunakan metode get() agar
pencarian dapat dilakukan dengan lebih aman.

## Bantuan dan Referensi
- Python Software Foundation, Python 3 Documentation: Dictionaries.
- Bahan Ajar Algoritma dan Pemrograman Pertemuan 11.
- Bantuan AI digunakan untuk membantu memahami dan menyusun latihan.
