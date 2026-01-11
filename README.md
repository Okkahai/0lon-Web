# 0lon Web Sitesi

0lon oyunu için modern, profesyonel landing page.

## Özellikler

- 🎮 Oyun estetiğine uygun pixel art temalı tasarım
- 📱 Tam responsive (mobil, tablet, desktop)
- ⚡ Hızlı yükleme ve smooth animasyonlar
- 🎨 Modern UI/UX tasarımı
- 🔥 Vampire Survivors tarzı roguelike survival teması

## Yerel Geliştirme

```bash
# Basit bir HTTP sunucusu ile çalıştır
npx serve .

# veya Python ile
python -m http.server 8000
```

Tarayıcıda `http://localhost:8000` adresini açın.

## Vercel'e Deploy

### Yöntem 1: Vercel CLI

```bash
# Vercel CLI'yi yükle (eğer yoksa)
npm i -g vercel

# Projeyi deploy et
vercel

# Production'a deploy et
vercel --prod
```

### Yöntem 2: GitHub ile

1. Bu projeyi bir GitHub repository'sine push edin
2. [Vercel](https://vercel.com) hesabınıza giriş yapın
3. "New Project" butonuna tıklayın
4. GitHub repository'nizi seçin
5. Vercel otomatik olarak ayarları algılayacak
6. "Deploy" butonuna tıklayın

### Yöntem 3: Vercel Dashboard

1. [Vercel Dashboard](https://vercel.com/dashboard)'a gidin
2. "Add New..." → "Project" seçin
3. GitHub repository'nizi import edin veya manuel olarak dosyaları yükleyin
4. Deploy edin

## Dosya Yapısı

```
0lon-Web/
├── index.html          # Ana HTML dosyası
├── styles.css          # CSS stilleri
├── script.js           # JavaScript dosyası
├── vercel.json         # Vercel konfigürasyonu
├── package.json        # NPM paket bilgileri
├── README.md          # Bu dosya
└── images/            # Oyun ekran görüntüleri
    ├── gameplay-1.jpg
    ├── gameplay-2.jpg
    └── gameplay-3.jpg
```

## Görseller

Görselleri `images/` klasörüne ekleyin:
- `gameplay-1.jpg` - Ana hero görseli
- `gameplay-2.jpg` - Galeri görseli 1
- `gameplay-3.jpg` - Galeri görseli 2

Görseller yoksa, site otomatik olarak placeholder gösterir.

## Özelleştirme

### Renkler

`styles.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary-color: #ff4444;
    --secondary-color: #ff8800;
    --dark-bg: #0a0a0a;
    /* ... */
}
```

### İçerik

`index.html` dosyasındaki metinleri düzenleyin.

## Teknolojiler

- HTML5
- CSS3 (CSS Variables, Grid, Flexbox)
- Vanilla JavaScript
- Google Fonts (Press Start 2P, Orbitron)

## Lisans

MIT License

## Geliştirici

dnzmnv - [GitHub](https://github.com/dnzmnv)
