# 🌊 NAZZ — 3 Günlük Antrenman Takipçisi (PWA)

Mobil-öncelikli, sade ve okunaklı arayüz. Tek kullanıcı, mavi vurgu, set takibi ve modern dinlenme sayacı.

[![PWA](https://img.shields.io/badge/PWA-Installable-5a29e4?style=for-the-badge)](#) [![Mobile First](https://img.shields.io/badge/Mobile-First-0ea5e9?style=for-the-badge)](#)

## 🚀 Özellikler

- 🗓️ 3 gün seçimi: 1=Pazartesi, 2=Çarşamba, 3=Cuma
- ✅ Set bazlı takip ve ilerleme barı
- ⏱️ Modern dinlenme penceresi: degrade bar, blur, düzenli tipografi, İptal/Devam butonları
- 📚 Rehber (TR): Program amacı ve temel notlar
- 📦 Offline/PWA: Ana ekrana ekle, çevrimdışı çalışma
- ☁️ İsteğe bağlı bulut senkron (Firestore) — profil/preset ve setler (PR/Rank yok)

## 📅 Program (Özet)

- 1. Gün – Kalça & Bacak
  - Squat (barbell/smith) — 4×12
  - Hip Thrust (barbell/dumbbell) — 4×12
  - Walking Lunge (dambıl) — 3×12 (her bacak)
  - Romanian Deadlift (DB/BB) — 3×12
  - Leg Press — 3×12
  - Glute Kickback (kablo/lastik) — 3×15
- 2. Gün – Üst Vücut + Core (Hafif)
  - Lat Pulldown (geniş tutuş) — 3×12
  - Shoulder Press (hafif) — 3×12
  - Dumbbell Row — 3×12 (her kol)
  - Biceps Curl (hafif) — 2×15
  - Triceps Pushdown (hafif) — 2×12
  - Plank — 3×30–40 sn
  - Russian Twist (hafif DB) — 3×15
- 3. Gün – Kalça & Bacak (Daha Yoğun)
  - Bulgarian Split Squat (DB) — 3×12 (her bacak)
  - Hip Thrust (ağır) — 4×10
  - Sumo Deadlift (DB/BB) — 3×12
  - Side Lunge — 3×12 (her bacak)
  - Leg Curl (makine) — 3×12
  - Fire Hydrant (lastik) — 3×15

## 📱 Kullanım

1) Üstteki menüden “Program / Rehber” arasında geçiş yapın
2) Gün seçip egzersiz setlerini işaretleyin; ilerleme barı otomatik güncellenir
3) Dinlenme penceresi ile süreyi takip edin; isterseniz “İptal” ile kapatın
4) PWA olarak ana ekrana ekleyip çevrimdışı kullanın

## 🛠️ Teknik

- Vanilla JS + HTML + CSS
- LocalStorage (offline veri), Firestore (opsiyonel bulut)
- PWA: `manifest.webmanifest`, `sw.js`

## 🔧 Geliştirme

```bash
git clone <repo>
cd <repo>
# Herhangi bir statik sunucu ile açın (örn. VS Code Live Server)
```

## 📁 Yapı

```
fullbody-takip/
├── index.html
├── README.md
├── sw.js
├── manifest.webmanifest
└── icons/
```

## 📄 Lisans

MIT
