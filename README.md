# Market Context Indonesia

Dashboard market context saham Indonesia, diupdate setiap 2 minggu sekali.

**Live dashboard:** https://[username].github.io/market-context-id/

---

## Struktur folder

```
market-context-id/
├── index.html                         ← halaman utama (index arsip)
├── 2026/
│   ├── februari/
│   │   ├── minggu-1/
│   │   │   └── index.html             ← review 1–14 Feb 2026
│   │   └── minggu-3/
│   │       └── index.html             ← review 15–28 Feb 2026
│   ├── maret/
│   │   ├── minggu-1/
│   │   │   └── index.html             ← review 1–14 Mar 2026
│   │   └── minggu-3/
│   │       └── index.html             ← review 15–31 Mar 2026
│   └── ...
└── ...
```

## Konvensi penamaan

| Periode upload | Folder | Contoh link |
|---|---|---|
| Tanggal 1–14 tiap bulan | `minggu-1` | `/2026/maret/minggu-1/` |
| Tanggal 15–akhir bulan | `minggu-3` | `/2026/maret/minggu-3/` |

> Pakai `minggu-1` dan `minggu-3` (bukan minggu-2/4) agar lebih intuitif — mencerminkan paruh pertama dan paruh kedua bulan.

## Cara upload dashboard baru

1. Download file HTML dari Claude
2. Rename jadi `index.html`
3. Masukkan ke folder yang sesuai, misal: `2026/april/minggu-1/`
4. Update `index.html` di root (tambah link entry baru)
5. Commit & push ke GitHub

## Cara akses arsip lama

Semua review tersimpan permanen di folder masing-masing. Tidak ada yang terhapus otomatis.
