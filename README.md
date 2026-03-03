# Tensai Bishoujo Sanshimai wa Isourou ni Dake Choro Kawaii

> Seorang pemuda biasa dan para jenius tinggal bersama di bawah satu atap — romcom harem penuh kekacauan dengan tingkat keimutannya MAX!“…Mau datang ke rumahku?”Setelah rumahnya tiba-tiba hangus terbakar, Riku akhirnya tinggal menumpang di rumah keluarga Tennousu — tiga kakak beradik cantik jelita berbakat yang selalu dipuja banyak orang.Melihat rumah mereka berantakan karena manajemen hidup yang parah, Riku pun memutuskan untuk menggunakan keahlian rumah tangganya untuk membantu mereka!?Para jenius itu pun perlahan mulai tertarik pada sosok Riku yang tulus dan selalu penuh perhatian…

---

## Info

| | |
|---|---|
| Judul | Tensai Bishoujo Sanshimai wa Isourou ni Dake Choro Kawaii |
| Judul Alternatif | 天才美少女三姉妹がちょろ可愛すぎる!? |
| Author | Akizuki Tsukihi |
| Artist | Shio Kazunoko, Akizuki Tsukihi |
| Tipe | Manga (Hitam Putih) |
| Status | Hiatus |
| Genre | Shounen · Comedy · Romance · School Life · Slice of Life |
| Chapter | 3 chapter |

## Link

- [MangaDex](https://mangadex.org/title/ee1eb629-79c9-410f-927c-dd7a4cd1d87b/tensai-bishoujo-sanshimai-wa-isourou-ni-dake-choro-kawaii)
- [Raw](https://comic-walker.com/detail/KC_006969_S)

---

## Struktur

```
TensaiBishoujo/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)