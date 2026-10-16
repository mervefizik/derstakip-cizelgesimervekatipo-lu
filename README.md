# Fizik Öğretmeni Takip Sistemi

Telefon ve bilgisayara uyumlu başlangıç projesi.

## Hemen deneyin
1. ZIP klasörünü çıkarın.
2. `index.html` dosyasını modern tarayıcıda açın.
3. Öğrenciler bölümünden öğrenci ekleyin; diğer sekmelerde ders, deneme, ödev ve veli görüşmesi kayıtları oluşturun.
4. Düzenli olarak **Yedek al** düğmesine basın. JSON yedeğini güvenli bir yerde saklayın.

## Özellikler
- Öğrenci ve veli iletişim alanları
- Ders/konu, son kalınan yer, sonraki ders hedefi
- Deneme doğru/yanlış/boş ve net-puan kaydı
- Ödev, teslim tarihi, durum ve öğretmen geri bildirimi
- Veli görüşme kayıtları
- Basit rapor özeti
- JSON yedekleme ve içe aktarma
- Mobil uyumlu tasarım

## Klasörler
- `index.html`: sayfa yapısı
- `assets/style.css`: görünüm ve mobil uyum
- `src/app.js`: formlar ve uygulama mantığı
- `config.js`: gelecekteki bulut ayarları
- `docs/`: bulut rehberi ve SQL şeması

## Önemli
Şu an çalışan sürüm verileri yalnızca kullanılan tarayıcıda saklar. Bulut senkronizasyonu tamamlanmış değildir; farklı cihazlarda veri eşitleme için `docs/BULUT_KURULUMU.md` dosyasındaki entegrasyon adımları gerekir. Gerçek öğrenci bilgilerini girmeden önce yedekleme ve geri yüklemeyi test edin.
