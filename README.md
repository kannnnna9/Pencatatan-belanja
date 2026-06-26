# Keranjang Analog

App pencatat belanja dengan scan kamera. Arahkan ke label harga, nanti terbaca sendiri. Tidak perlu internet — OCR jalan di perangkat, pakai Tesseract.js.

## Cara pakai

1. Buka `index.html` di browser HP, atau akses lewat GitHub Pages
2. Set budget kalau mau dipantau (opsional)
3. Tap **Mulai Belanja**
4. Arahkan kamera ke label harga → tahan stabil sebentar → otomatis jepret
5. Kalau ada beberapa angka harga, akan muncul pilihan — tap yang benar
6. Ketuk **Selesai** saat sudah cukup

Mode **Kilat**: scan harga saja, nama pakai emoji bar (🍜🥤🧹🍗🍞). Cocok kalau belanja cepat.

Toggle **Auto/Manual** ada di layar scan — kalau mau jepret sendiri, pakai Manual.

## Pasang di HP (PWA)

Buka di Chrome/Safari → **Add to Home Screen**. Setelah itu bisa dipakai offline seperti app biasa.

## Riwayat

Semua sesi tersimpan di perangkat. Lihat lewat ikon 🕐 di pojok kanan atas.

## File

Satu file: `index.html` (~73KB). Tidak ada server, tidak ada database, tidak ada data yang dikirim ke mana pun.

---

v1.0.0 · Built with [Tesseract.js](https://tesseract.projectnaptha.com/)
