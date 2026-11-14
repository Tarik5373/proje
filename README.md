# Satış Hepsi & Figürhane

Bu depo iki ayrı Türkçe, mobil uyumlu mağaza vitrini içerir:

- **Satış Hepsi:** Ana dizindeki `index.html` dosyasında.
- **Figürhane:** `figur/index.html` adresinde; anime, oyun, film-dizi ve mini figür kategorileri ile özel figür talep akışı sunar.

## Figürhane özellikleri
- Ürün arama, kategori filtreleme ve fiyat sıralama
- Ürün detay penceresi, favoriler ve sepet
- Sepet/favori bilgisini tarayıcıda saklama
- Sipariş özetini TXT dosyası olarak indirme
- Özel figür talep formu ve isteğe bağlı referans görseli seçimi
- Mobil uyumlu tasarım

## Çalıştırma
Herhangi bir derleme gerekmez. `figur/index.html` dosyasını tarayıcıda açabilirsin.

## GitHub Pages ile yayınlama
Depoda `.github/workflows/pages.yml` iş akışı bulunur. GitHub deposunda **Settings → Pages → Build and deployment → Source** bölümünden **GitHub Actions** seçildiğinde, `main` dalına yapılan gönderimlerle statik site yayınlanır.

Yayın adresi depo/hesap ayarlarına bağlıdır. Pages etkinleştirildikten ve dağıtım başarılı olduktan sonra Figürhane normalde `https://<kullanıcı-adı>.github.io/<depo-adı>/figur/` yolunda açılır.

## Demo sınırları
Ürün adları, açıklamaları ve fiyatları örnek katalog içeriğidir; gerçek stok, lisans veya satış ilanı olarak değerlendirilmemelidir. Sepet yalnızca bu tarayıcıda çalışır. Sipariş özeti ve özel figür talebi indirilebilir dosyalar üretir, işletmeye otomatik gönderim yapmaz. Çevrim içi ödeme, gerçek sipariş yönetimi, stok sistemi ve e-posta/form sunucusu henüz bağlı değildir. Yayına almadan önce işletme iletişim bilgilerini, gerçek ürün fotoğraflarını/fiyatlarını, lisans durumlarını, teslimat ve iade koşullarını ekle.
