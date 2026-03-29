# Kanji Notları Sistemi Yönetimi

## Hızlı Başlangıç

1. **Yeni kanji eklemek:**
   - Uygun N seviyesine gidin (`n5/`, `n4/` vb.)
   - `TEMPLATE.md` dosyasını referans alın
   - Yeni dosya oluşturun: `XXX-kanji.md`
   - `INDEX.md` güncelleyin

2. **Durum takibi:**
   - INDEX.md'de tablo ikonu güncelleyin (✅ 🔄 ⬜ 📌)
   - Son güncelleme tarihini kaydedin

3. **Gözden geçirme:**
   - Her hafta INDEX.md'ye bakın
   - Zayıf alanları tanımlayın

## Klasör Yapısı
```
kanji-notes/
├── README.md           # Genel açıklama
├── TEMPLATE.md         # Kanji notu şablonu
├── n5/
│   ├── INDEX.md        # N5 kanji listesi
│   ├── 001-日.md
│   ├── 002-月.md
│   └── ...
├── n4/
│   ├── INDEX.md
│   └── ...
└── (n3, n2, n1 aynı yapı)
```

## İpuçları
- **Markdown düzenleyici**: VS Code, Obsidian, Notion
- **Git entegrasyonu**: Değişiklikleri commit edin (`git add kanji-notes && git commit`)
- **Arama**: Grep/Ctrl+F ile kanji ya da kelime arayın
- **Takvim**: Her kanji öğrendiğinizde tarih yazın (ilerleme görmek için)

## Gelecek Geliştirmeler
- Python ile basit bir CLI quiz aracı
- Spaced repetition sistemi
- Radikal gruplama
