> Versi: v1.0.0 | Status: disetujui | Menggantikan: -
> Sumber: Lumbung-TownHall `platform/versions/v1.0.0/` pada commit `673a467`; [townhall-roadmap.md §2](https://github.com/Coding-Skuy/ChefGenie-TownHall/blob/main/townhall-roadmap.md); [KONTEKS §8/§9](https://github.com/Coding-Skuy/ChefGenie-TownHall/blob/main/KONTEKS-LINTAS-DIVISI.md)

# 60 — Blast Radius lumbung-design

Batas context v1.0.0 Lumbung (townhall-roadmap §2): 3 komoditas pilot, fee Rp1.500/kg dekat dan Rp2.500/kg jauh, radius 25 km; point of concern titik impas 18.000 kg/bulan dan susut <5%.

## Boleh disentuh

- Token, flow, layar, dan tautan Figma.
- Catatan perubahan token di `tokens/README.md`.

## Dilarang

- Menyentuh DB logis divisi lain (`pasaree`, `titipo`, `pedaree`, `pawonee`, `titeny`).
- Menambah `event_type` di luar registry KONTEKS §3 tanpa bump versi + 30 hari dual-read.
- Menambah komoditas keempat atau melayani di luar radius 25 km (non-goal PRD/30).
- Menaruh kode produk di repo ini.
- Mengubah flow besar tanpa PRD/FSD versi baru di TownHall.
- Menetapkan angka bisnis (tarif, grade, harga) di desain; gunakan contoh dari dokumen.

## Kontrak diproduksi

- Token dan spesifikasi layar untuk app-kmp dan web.
- Desain struk fee dan cetakan A3 papan harga.

## Kontrak dikonsumsi

- PRD/FSD Lumbung-TownHall (alur dan layar).
- Tidak ada kontrak API/event.

## Aturan perubahan

Perubahan di luar batas ini = PR requirement di Lumbung-TownHall lebih dulu, lalu ADR baru di repo ini. Perubahan angka lintas-divisi wajib memperbarui KONTEKS §terkait + dokumen divisi + CHANGELOG versi dalam PR yang sama (KONTEKS §9).
