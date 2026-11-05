# GEÇİŞ · İstanbul öğrenci abonman takip

Tek sayfalık, kurulum gerektirmeyen, iPhone ana ekranına eklenebilir bir **PWA**.

## Kurulum

1. Bu klasörün **tüm dosyalarını** bir statik web sunucusuna koy (ör. GitHub Pages, Netlify veya Cloudflare Pages).
2. iPhone'daki **Safari** ile HTTPS adresini aç.
3. **Paylaş → Ana Ekrana Ekle → Web Uygulaması olarak aç → Ekle**.
4. Ayarlar'a girip gerçek abonman yükleme tarihini ve İstanbulkart Mobil'de görünen kalan kontörü gir.

Bu ZIP dosyasını doğrudan Safari'de açmak PWA kurulumu yerine geçmez: servis çalışanı için HTTPS gerekir.

## Özellikler
- 200 kontör öğrenci abonmanı varsayılanı.
- Kişisel sabah, eve dönüş ve arkadaş güzergâhları.
- Yolculukları ayrı ayrı kaydetme, geçmişten tek kaydı silme.
- Gerçek bakiyeyle manuel eşitleme ve Marmaray iade hatırlatması.
- Haftalık düzen / 30 günlük tüketim tahmini. Gece kalmada sabah rotası ayrı.
- Rota tutarlarını değiştirme veya yeni rota tanımlama.
- Dönem arşivi, JSON yedek alma / geri yükleme.
- LocalStorage ve servis çalışanıyla yerel veri ve çevrimdışı kullanım (ilk yükleme sonrası).

## Dikkat
- Bu uygulama İstanbulkart veya BELBİM ile bağlı değildir; gerçek zamanlı veri çekmez.
- Marmaray / metrobüs maliyetleri kullanılan mesafeye ve iadeye bağlı olabilir. Varsayılanlar *tahmini net* kontörlerdir. Gerçek düşümler İstanbulkart üzerinden doğrulanmalıdır.
- Telefonun Safari web sitesi verileri veya uygulama verileri silinirse yedeksiz kayıtlar kaybolabilir.
- Uygulama verileri sunucuya gönderilmez.
- 30 gün ve tarifeler ileride değişirse uygulamadaki varsayımları güncellemek gerekir.

## Dosyalar
`index.html`, `styles.css`, `app.js`, `manifest.webmanifest`, `sw.js`, `icons/*.png`.

© Kişisel kullanım için hazırlanmış bağımsız takip aracı.
