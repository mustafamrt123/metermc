# Meter Minecraft Sunucu Sitesi

Modern ve responsive bir Minecraft sunucu web sitesi. Turuncu renk teması ile tasarlanmıştır.

## Özellikler

- 🎨 Modern ve şık tasarım
- 📱 Tam responsive (mobil, tablet, masaüstü)
- 🚀 Smooth scroll animasyonları
- 🎯 Kullanıcı dostu arayüz
- 📦 Mağaza bölümü
- 📰 Haberler ve duyurular
- 💬 Discord entegrasyonu
- ⚡ Hızlı ve optimize edilmiş

## Dosya Yapısı

```
site/
├── index.html      # Ana HTML dosyası
├── styles.css      # CSS stilleri
├── script.js       # JavaScript işlevleri
└── README.md       # Bu dosya
```

## Kullanım

1. Tüm dosyaları bir klasöre kopyalayın
2. `index.html` dosyasını bir web tarayıcısında açın
3. Veya bir web sunucusu kullanarak çalıştırın

### Yerel Sunucu ile Çalıştırma

**Python ile:**
```bash
python -m http.server 8000
```

**Node.js ile:**
```bash
npx http-server
```

Sonra tarayıcınızda `http://localhost:8000` adresine gidin.

## Özelleştirme

### Renkleri Değiştirme

`styles.css` dosyasındaki CSS değişkenlerini düzenleyin:

```css
:root {
    --primary-color: #FF6B35;
    --secondary-color: #2c3e50;
    --accent-color: #FF8C42;
    /* ... */
}
```

### Sunucu Bilgilerini Güncelleme

`index.html` dosyasında şu bölümleri düzenleyin:

- Sunucu IP: `id="serverIp"` olan span elementi
- Oyuncu sayısı: `updatePlayerCount()` fonksiyonunu `script.js` içinde düzenleyin

### Logo Değiştirme

Logonuzu `logo.png` olarak kaydedin ve `index.html` dosyasındaki logo img etiketinin doğru yolu gösterdiğinden emin olun:

```html
<img src="logo.png" alt="Meter Logo">
```

## Özellikler Detayı

### Responsive Tasarım
- Mobil cihazlarda hamburger menü
- Tüm ekran boyutlarına uyumlu grid sistemleri
- Touch-friendly butonlar ve linkler

### Animasyonlar
- Sayfa yüklenirken fade-in efektleri
- Scroll sırasında elementlerin görünmesi
- Hover efektleri ve geçişler

### İşlevsellik
- Sunucu IP kopyalama
- Smooth scroll navigasyon
- Aktif menü linki gösterimi
- Bildirim sistemi

## Tarayıcı Desteği

- Chrome (son 2 versiyon)
- Firefox (son 2 versiyon)
- Safari (son 2 versiyon)
- Edge (son 2 versiyon)

## Lisans

Bu proje özgürce kullanılabilir ve özelleştirilebilir.

## Notlar

- Gerçek bir Minecraft sunucusu için API entegrasyonu eklemeniz gerekebilir
- Logo ve görselleri kendi içeriklerinizle değiştirmeyi unutmayın
- Discord webhook veya bot entegrasyonu için ek geliştirme yapılabilir

## İletişim

Sorularınız veya önerileriniz için issue açabilirsiniz.

