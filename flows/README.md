# Alur Gudang Lumbung

## Alur 1 — Terima Lot

1. Petugas memilih trip masuk dari daftar.
2. Pindai/ketik id lot dari `lapangan-mobile`.
3. Verifikasi komoditas dan asal kebun.

## Alur 2 — Timbang dan Fee

1. Timbang via USB/serial pada `gudang-desktop`.
2. Sistem menghitung susut (kebun vs gudang) dan fee.
3. Petugas meninjau angka sebelum cetak.

## Alur 3 — Cetak Struk Fee

1. Cetak ke printer thermal.
2. Struk memuat: nama gudang, id lot, berat kebun, berat gudang, susut, fee, total, waktu.
3. Simpan status cetak ke backend agar tidak cetak ganda.
