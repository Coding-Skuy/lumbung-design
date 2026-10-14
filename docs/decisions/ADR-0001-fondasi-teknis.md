# ADR-0001 — Fondasi teknis lumbung-design

- Status: Diterima
- Tanggal: 2026-10-14

## Konteks

lumbung-design menyediakan token, flow, dan layar bagi app-kmp (Windows desktop 7 layar gudang, mobile sopir/petani) dan web (papan harga, dasbor admin).

## Keputusan

1. Desain di Figma; tautan berkas dan versi flow dicatat di README repo.
2. Token desain (warna, tipografi, radius, spasi) menjadi sumber tunggal bagi app-kmp dan web.
3. Keterbacaan gudang diutamakan: cahaya terang, sarung tangan, layar kecil.
4. Struk fee memuat nama gudang, id lot, berat, fee, total, dan waktu cetak (thermal 80 mm).
5. Perubahan flow besar memerlukan PRD/FSD versi baru di Lumbung-TownHall sebelum desain berubah.

## Konsekuensi

- Layar desktop gudang wajib 7 layar FSD/10 beserta bilah Online/Offline dan jumlah antrean.
- Angka (fee, grade, papan) pada desain hanya contoh dari dokumen; tidak dihitung di desain.
