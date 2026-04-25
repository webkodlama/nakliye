# 🚛 Anadolu Express Nakliyat - Modern Web Sitesi

SEO uyumlu, animasyonlu ve tam responsive nakliyat firması web sitesi.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![SEO](https://img.shields.io/badge/SEO-Optimized-success.svg)
![Responsive](https://img.shields.io/badge/Responsive-100%25-green.svg)

## 📋 İçindekiler

- [Özellikler](#-özellikler)
- [Teknolojiler](#-teknolojiler)
- [SEO Özellikleri](#-seo-özellikleri)
- [Kurulum](#-kurulum)
- [Dosya Yapısı](#-dosya-yapısı)
- [Kullanım](#-kullanım)
- [Lisans](#-lisans)

## ✨ Özellikler

### 🎨 Tasarım Özellikleri
- ✨ Modern ve profesyonel tasarım
- 📱 Tam responsive (mobil, tablet, masaüstü)
- 🌙 Koyu/açık tema kombinasyonu
- 🎯 Gradient ve gölgelendirme efektleri
- 🖼️ Yüksek kaliteli görseller

### ⚡ Animasyon Özellikleri
- 🚛 Kamyon yükleme ekranı
- 📜 Scroll reveal animasyonları
- 🎭 Hero section parallax efekti
- 🔢 Sayı sayaç animasyonları
- 💧 Buton ripple efektleri
- 🎪 Hover animasyonları
- ⏱️ Timeline süreç animasyonu

### 📱 Sayfa Bölümleri
1. **Hero Section** - Büyük animasyonlu başlık
2. **Özellikler Bar** - 4 ana özellik kartı
3. **Hakkımızda** - 40+ yıllık tecrübe vurgusu
4. **Hizmetler** - 6 farklı nakliyat hizmeti
5. **Popüler Güzergahlar** - SEO için şehir kombinasyonları
6. **Süreç** - 6 adımlı taşıma süreci
7. **Neden Biz?** - Avantajlar ve istatistikler
8. **Müşteri Yorumları** - Slider testimonial
9. **SSS (FAQ)** - Akordeon soru-cevap bölümü
10. **CTA** - Çağrı bölümü
11. **İletişim** - Form ve iletişim bilgileri
12. **Footer** - Detaylı footer + şehir listesi

## 🛠️ Teknolojiler

- **HTML5** - Semantic HTML5 yapısı
- **CSS3** - Modern CSS özellikleri, Grid, Flexbox
- **JavaScript** - Vanilla JS, AOS kütüphanesi
- **Font Awesome** - İkon kütüphanesi
- **Google Fonts** - Poppins font ailesi
- **AOS** - Animate On Scroll kütüphanesi

## 🔍 SEO Özellikleri

### ✅ Tamamlanan SEO Çalışmaları

| Özellik | Durum |
|---------|-------|
| Meta Title & Description | ✅ |
| Open Graph & Twitter Cards | ✅ |
| Schema.org (8 tip) | ✅ |
| Canonical URL | ✅ |
| Robots.txt | ✅ |
| Sitemap.xml (50+ URL) | ✅ |
| Semantic HTML | ✅ |
| ARIA Labels | ✅ |
| H Tag Hiyerarşisi | ✅ |
| Internal Linking | ✅ |
| FAQ Schema | ✅ |
| Breadcrumb | ✅ |
| Mobile Friendly | ✅ |
| Page Speed Optimized | ✅ |

### 📊 Schema.org Yapısal Veriler
- Organization
- LocalBusiness
- WebSite
- WebPage
- Service (2 adet)
- FAQPage
- BreadcrumbList
- AggregateRating

## 🚀 Kurulum

### 1. Dosyaları İndir
```bash
git clone https://github.com/anadoluexpress/nakliyat-websitesi.git
cd nakliyat-websitesi
```

### 2. Sunucuya Yükle
FTP veya cPanel aracılığıyla dosyaları sunucuya yükleyin.

### 3. Yapılandırma
- `.htaccess` dosyasındaki yönlendirmeleri kontrol edin
- `index.html` dosyasındaki iletişim bilgilerini güncelleyin
- Görselleri kendi görsellerinizle değiştirin

### 4. SEO Ayarları
- `sitemap.xml` dosyasındaki URL'leri kendi alan adınıza göre güncelleyin
- Schema.org verilerini kendi firma bilgilerinize göre düzenleyin
- Meta tag'leri güncelleyin

## 📁 Dosya Yapısı

```
nakliyat-websitesi/
├── index.html              # Ana sayfa
├── styles.css             # Ana CSS dosyası
├── script.js              # JavaScript dosyası
├── robots.txt             # Robots.txt
├── sitemap.xml            # XML Sitemap
├── .htaccess              # Apache yapılandırması
├── SEO_REHBERI.md         # SEO rehberi
├── README.md              # Bu dosya
├── favicon/               # Favicon dosyaları
│   ├── apple-touch-icon.png
│   ├── favicon-32x32.png
│   ├── favicon-16x16.png
│   └── site.webmanifest
└── images/                # Görsel dosyaları
    ├── og-image.jpg
    ├── logo.png
    └── company-photo.jpg
```

## 📖 Kullanım

### Temel Özelleştirme

#### Renk Değişimi
`styles.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary: #2563eb;        /* Ana renk */
    --secondary: #f59e0b;      /* İkincil renk */
    --accent: #10b981;         /* Vurgu rengi */
    --dark: #0f172a;           /* Koyu renk */
}
```

#### İletişim Bilgilerini Değiştirme
`index.html` dosyasındaki aşağıdaki alanları güncelleyin:

```html
<!-- Telefon -->
<a href="tel:+905001234567">0500 123 45 67</a>

<!-- E-posta -->
<a href="mailto:info@anadoluexpressnakliyat.com">

<!-- Adres -->
Merkez Mahallesi, Nakliyat Caddesi No:1
```

#### Schema.org Verilerini Güncelleme
`index.html` dosyasındaki JSON-LD script'ini düzenleyin:

```json
{
    "@type": "LocalBusiness",
    "name": "Sizin Firma Adınız",
    "telephone": "+90-XXX-XXX-XXXX",
    "address": {
        "streetAddress": "Sizin Adresiniz",
        "addressLocality": "İlçeniz",
        "addressRegion": "İliniz",
        "postalCode": "Posta Kodunuz"
    }
}
```

## 🔧 Gelişmiş Özelleştirme

### Yeni Hizmet Sayfası Ekleme

1. HTML içinde yeni bir section oluşturun
2. CSS'te gerekli stilleri ekleyin
3. Sitemap.xml'e URL ekleyin
4. Schema.org Service verisi ekleyin

### Blog Sistemi Ekleme

Statik blog için:
1. `/blog/` klasörü oluşturun
2. Her yazı için yeni HTML dosyası
3. Ana sayfaya blog bölümü ekleyin
4. Sitemap.xml'i güncelleyin

## 🎯 Performans Optimizasyonu

### Öneriler

1. **Görselleri Optimize Edin**
   - WebP formatına dönüştürün
   - Sıkıştırma uygulayın (TinyPNG)

2. **CDN Kullanın**
   - Cloudflare
   - AWS CloudFront
   - Google Cloud CDN

3. **Önbellekleme Ayarları**
   - Browser caching (`.htaccess` içinde ayarlı)
   - Server-side caching

4. **Sıkıştırma**
   - Gzip/Brotli aktif (`.htaccess` içinde ayarlı)

## 📞 Destek

Sorularınız için:
- 📧 info@anadoluexpressnakliyat.com
- 📞 0500 123 45 67

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

---

**Hazırlayan:** Anadolu Express Nakliyat Web Ekibi  
**Son Güncelleme:** 15 Ocak 2024  
**Versiyon:** 1.0.0
