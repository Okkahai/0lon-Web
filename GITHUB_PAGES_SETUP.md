# GitHub Pages Kurulum Kontrol Listesi

## ✅ Adım Adım Kontrol

### 1. Repository Adını Kontrol Et
- GitHub'da repository adı: `0lon-Web` (sıfır ile başlıyor)
- URL: `https://github.com/Okkahai/0lon-Web`
- Eğer farklıysa, Pages URL'i de farklı olacak

### 2. GitHub Pages Ayarları

**Settings → Pages** bölümünde:

- ✅ **Source:** "Deploy from a branch" seçili olmalı
- ✅ **Branch:** `main` seçili olmalı (veya `master`)
- ✅ **Folder:** `/ (root)` seçili olmalı
- ✅ **Save** butonuna tıklanmış olmalı

### 3. İlk Deployment

- İlk deployment 1-2 dakika sürebilir
- Pages ayarlarını kaydettikten sonra birkaç dakika bekleyin
- Tarayıcıyı yenileyin (Ctrl+F5)

### 4. URL Kontrolü

Doğru URL formatı:
- ✅ `https://okkahai.github.io/0lon-Web` (repository adı ile)
- ❌ `https://okkahai.github.io/0lon-Web/` (sonunda slash olmamalı)

### 5. Dosya Kontrolü

Repository'de şu dosyalar root'ta olmalı:
- ✅ `index.html` (root'ta)
- ✅ `styles.css` (root'ta)
- ✅ `script.js` (root'ta)
- ✅ `images/` klasörü (root'ta)

## 🔧 Sorun Giderme

### Hala 404 alıyorsanız:

1. **Repository adını kontrol edin:**
   ```bash
   git remote -v
   ```
   Çıktı: `https://github.com/Okkahai/0lon-Web.git` olmalı

2. **Pages ayarlarını tekrar kontrol edin:**
   - Settings → Pages
   - Branch: `main` seçili mi?
   - Folder: `/ (root)` seçili mi?

3. **Yeni bir commit yapın:**
   - Küçük bir değişiklik yapın (README'ye bir satır ekleyin)
   - Commit ve push edin
   - Bu, Pages'i yeniden tetikleyebilir

4. **Pages deployment'ını kontrol edin:**
   - Repository'de "Actions" sekmesine gidin
   - Pages deployment'ı görünüyor mu?
   - Hata var mı?

## 📝 Notlar

- GitHub Pages büyük/küçük harfe duyarlıdır
- Repository adı `0lon-Web` ise URL de `0lon-Web` olmalı
- İlk deployment biraz zaman alabilir
- Her push'ta otomatik güncellenir
