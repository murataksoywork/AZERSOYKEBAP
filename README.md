# Azersoy Kebap — Premium Restaurant Website

## 🚀 Nasıl Kullanılır?

### Lokal Açmak için:
Sadece `index.html` dosyasını tarayıcıda aç — hepsi bu kadar.

### GitHub Pages Deploy:
1. GitHub'da yeni repo oluştur: `azersoy-kebap`
2. Bu klasördeki tüm dosyaları push et:
   ```bash
   git init
   git add .
   git commit -m "Azersoy Kebap website"
   git branch -M main
   git remote add origin https://github.com/KULLANICI_ADIN/azersoy-kebap.git
   git push -u origin main
   ```
3. GitHub → Settings → Pages → Source: "Deploy from a branch" → `main` → `/root`
4. Site birkaç dakika sonra yayında olacak!

### Telefon Numarasını Güncelle:
`index.html` içinde `905555555555` yazan yerleri gerçek numara ile değiştir.

### Adres Bilgilerini Güncelle:
"Atatürk Caddesi No:42" yazan kısımları gerçek adres ile güncelle.

## 📁 Klasör Yapısı
```
azersoy-kebap/
├── index.html          ← Ana sayfa (tek dosya!)
├── images/             ← Tüm fotoğraflar
│   ├── azersoy_kebap_1.jpg
│   ├── azersoy_mekan_1.jpg
│   └── ...
└── logo/
    └── azersoy_logo.jpg
```

## ✨ Özellikler
- Premium dark theme, cinematic tasarım
- GSAP ile sayfa açılış animasyonları
- Scroll-triggered reveal animasyonlar
- Sticky navbar (scroll'da opaklık kazanır)
- Hero bölümü: stagger title animation
- Text marquee (sonsuz döngü)
- Fotoğraf galerisi (hover zoom)
- Menü listesi (hover animasyonlar + ok ikonu)
- WhatsApp rezervasyon formu
- Google Maps embed (dark style)
- Fotoğraf marquee (grayscale → renkli hover)
- Floating WhatsApp butonu
- Tam responsive (mobil hamburger menü)
- Powered by Aksoy Creative footer
