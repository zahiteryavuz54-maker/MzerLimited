# MizerLimited Site

Tamamen statik, bedava çalışabilen modern bir proje sitesi.

## Özellikler

- 9 farklı tema (Koyu, Açık, Neon, Kurumsal, Doğa, Agresif, Midnight, Enerjik, Minimal)
- 7 dil desteği (Türkçe, English, Deutsch, Français, Español, Português, Русский)
- Proje yönetimi (açıklama, görsel, video, indirme linki)
- Kategori sistemi
- Reklam sistemi (üst / alt / sol / sağ, max 4)
- Nova asistan (basit kural tabanlı sohbet)
- Yönetim paneli (şifreli)
- Veriler tarayıcıda localStorage ile saklanır + JSON export/import

## Kurulum

1. Bu klasörü Cloudflare Pages, GitHub Pages veya herhangi bir statik hosting'e yükle.
2. `admin.html` adresine git.
3. Giriş bilgileri (ilk kurulum):
   - E-posta: `mzerlimited@gmail.com`
   - Şifre: `ZahitZeyn2016zz`
4. Yönetim panelinden şifreni hemen değiştir.

## Notlar

- Değişiklikler tarayıcının localStorage'ında tutulur.
- Farklı cihazlarda aynı veriyi görmek için "Veri Yedekle" bölümünden JSON indirip diğer cihazda yükleyebilirsin.
- Gerçek bir GitHub entegrasyonu istersen daha sonra eklenebilir.

## Dosya Yapısı

```
mizer-limited/
├── index.html          # Ana sayfa
├── projects.html       # Projeler listesi
├── project.html        # Proje detay
├── about.html
├── contact.html
├── nova.html           # AI asistan
├── admin.html          # Yönetim paneli
├── css/style.css
├── js/
│   ├── main.js
│   ├── i18n.js
│   ├── nova.js
│   └── admin.js
└── data/default-data.json
```
