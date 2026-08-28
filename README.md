# kalkulator-sederhana

Kalkulator web sederhana dalam satu berkas HTML — tanpa dependensi, tanpa proses build.

## Cara pakai

Buka `index.html` langsung di browser, atau jalankan server statis:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```

## Fitur

- Operasi dasar: tambah, kurang, kali, bagi, persen
- Panel riwayat (maks. 50 perhitungan); klik salah satu entri untuk memakai hasilnya kembali
- Dukungan keyboard: angka, `+` `-` `*` `/`, `Enter`/`=`, `Backspace`, `Escape`, `%`
- Koma sebagai pemisah desimal, pembagian dengan nol ditampilkan sebagai `Error`
