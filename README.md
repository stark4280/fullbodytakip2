# 💪 Batman Full Body — PWA Antrenman Takipçisi

Minimal ve mobil-öncelikli tam vücut antrenman takipçisi. Pzt/Çrş/Cuma program akışı, egzersiz başına PR girme, egzersiz bazlı Rank (Rookie → Dark Knight), TR rehber ve offline çalışma.

[![PWA](https://img.shields.io/badge/PWA-Installable-5a29e4?style=for-the-badge)](#) [![Mobile First](https://img.shields.io/badge/Mobile-First-0ea5e9?style=for-the-badge)](#)

## 🚀 Öne Çıkanlar

- 🗓️ Sabit program: Pazartesi (Kuvvet), Çarşamba (Posterior Chain + Core), Cuma (Volüm & Detay)
- ✅ Set bazlı takip: Her egzersiz için set checkbox’ları ve ilerleme barı
- ⏱️ Akıllı dinlenme: Son setten sonra otomatik daha uzun dinlenme, titreşim uyarısı
- 🏷️ PR ve Rank: Her egzersizde PR girişi; rozet ile seviye (Rookie → Dark Knight) + “bir sonraki seviyeye x kg”
- 👁️ Açılışta rank görünümü: Sayfa açılır açılmaz egzersiz rozetleri hesaplanır (PR girmeden Rookie görünür)
- 📚 Rehber (TR): Arama, mobil okunaklı paragraf akışı, ana ve aksesuar hareketler için rank-chip grid’leri
- 📦 Offline/PWA: Service worker cache; ana ekrana ekle
- ☁️ İsteğe bağlı bulut senkron: Firestore (anonim oturum)

## 📅 Haftalık Program (Özet)

- Pazartesi — Back Squat, Bench Press, Row, DB OHP, Face Pull, Plank, Wrist Curl
- Çarşamba — Deadlift, Lat Pulldown, Incline DB Press, Leg Curl, Hip Thrust, Side Plank, Reverse Wrist Curl
- Cuma — Front/Goblet Squat, OHP, Romanian Deadlift, Seated Row, Lateral Raise, Hanging Knee Raise, Wrist Roller

## 🏷️ Rank (Seviye) Sistemi — Ana Hareketler

- Bench: 40×5 → 60×5 → 80×5 → 100×5 → 120×5 → 140×5
- Squat: 60×5 → 80×5 → 100×5 → 140×5 → 160×5 → 180×5
- Deadlift: 80×5 → 100×5 → 140×5 → 180×5 → 200×5 → 220×5
- OHP: 25×5 → 35×5 → 45×5 → 55×5 → 65×5 → 75×5
- Row: 40×5 → 60×5 → 80×5 → 100×5 → 120×5 → 140×5
- Lat Pulldown: 40×8 → 60×8 → 80×8 → 100×8 → 120×8 → 140×8

> Aksesuarlar için de eşikler eklenmiştir (incline DB, front/goblet, RDL, leg curl, hip thrust, DB OHP, lateral raise, face pull, seated row, core/grip) ve rehberde chip olarak listelenir.

## 📚 Rehber (TR)

- Arama: “bench, uyku, protein” gibi anahtarlarla içerik filtreleme
- İçerik başlıkları: Programın Amacı, Haftalık Program, Rank Özetleri, Aksesuar Eşikleri (chip grid), Uygulama Adımları, 12 Haftalık Periyodizasyon, SSS & Güvenlik

## 📱 Kullanım

1) Üstten “Program / Rehber” arasında geçiş yapın

2) Gün seçin (Pazartesi/Çarşamba/Cuma) ve egzersiz setlerini işaretleyin (başlık sadece gün adını gösterir)

3) PR değerinizi egzersiz kartındaki alanlara girin; rank rozetleri ve “sonraki seviyeye x kg” otomatik güncellenir (PR olmadan Rookie görünür)

4) Dinlenme süresi bitince titreşim uyarısı gelir; isterseniz iptal edin

5) Offline/PWA: Ana ekrana ekleyin ve internet olmadan da kullanın

## 🛠️ Teknik

- Vanilla JS + HTML + CSS (framework yok)
- LocalStorage (offline veri), Firestore (opsiyonel bulut)
- PWA: `manifest.webmanifest`, `sw.js` (network-first HTML, cache-first varlıklar)

## 🔧 Geliştirme

```bash
git clone <repo>
cd <repo>
# Geliştirme için herhangi bir statik sunucu ile açın (ör. VS Code Live Server)
```

## 📁 Yapı

```
fullbody-takip-main/
├── index.html
├── README.md
├── sw.js
├── manifest.webmanifest
└── icons/
```

## 📄 Lisans

MIT
