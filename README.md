# libur-nasional
Data hari libur nasional Indonesia mulai tahun 2020 dalam format yang dapat dibaca mesin.

## Format
Setiap file berisi array dari hari libur untuk 1 tahun. Berisi tanggal, deskripsi dan tipe.

Saat ini. tipe ada 2 jenis:

- `national-holiday` adalah hari libur nasional
- `joint-holiday` adalah cuti bersama

## Penggunaan dalam API Call
Untuk mendapatkan data dari API, silakan gunakan fitur jsdelivr dengan melakukan GET request ke URL berikut:  
`GET https://cdn.jsdelivr.net/gh/niyoko/libur-nasional/data/{tahun}.json`.  
Lihat https://stackoverflow.com/a/18049842.

Contoh: https://cdn.jsdelivr.net/gh/niyoko/libur-nasional/data/2020.json

## Kontribusi
Silakan ajukan pull request jika Anda ingin menambah data atau memperbaiki kesalahan data yang ada. Terima Kasih.
