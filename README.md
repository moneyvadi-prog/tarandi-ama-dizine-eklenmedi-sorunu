Taranan Verilere Eklenmedi Düzeltmesi — Claude Skill
Google Search Console'da "Tarandı ama dizine eklenmedi" (Tarandı - şu anda indekslenmemiş) uyarısı alan sayfaları için sistematik teşhis ve teknik SEO çözüm metodolojisi — Claude için hazır Skill formatı.

Bu Beceri; render kontrolü, içerik kalitesi analizi, meta direktif denetimi, iç linkleme haritası, hreflang çalışırlığı ve performans analizi adımlarını tek bir teşhis analizinde birleştirir.


Kimler İçin?

SEO uzmanları — Müşteri sitelerinde tekrarlayan indeksçiler, sistematik çözmek isteyenler
Teknik SEO içerir — JS ağırlıklı sitelerde (Next.js, React, Vue) render kaynaklı sorunları tanımak isteyenler
İçerik bileşenleri — Yayınladıkları içeriklerin neden indekslenmediğini isteyenler
Ajanslar — Müşterilere standartlaştırılmış bir teşhis raporu sunmak isteyenler
geliştiriciler — SSR/CSR/SSG kararlarının SEO puanlarını görmek isteyenler


Skill Ne Yapıyor?
Claude'a şu mesajları yazdığınız anda birleşiyor:

"Search Console'da 200 sayfa tarandı ama dizine eklenmedi, ne yapmalıyım?"
"Next.js sitesinde blog yazıları indekslenmiyor"
"Yeni programım sayfa 30 tarifede indekste yok"
"Tarandı, dizine eklenmedi sorunum var, teşhis et"

Ve size şunları üretiyor:
AşamaÇıktı0Bilgi toplama bilgileri (URL, teknoloji, hacim, geçmiş)1Render Ekseni Teşhisi — JS render mi sorunu?2İçerik Kalitesi Ekseni Tanı — ince/kopya var mı?3Meta ve Direktif Ekseni Tanı — noindex/canonical kontrol4Yapısal Eksen Tanı — iç linkleme & site haritası5Çok Dilli & Kanonik Eksen teşhisi — hreflang/duplicate URL6Performans Eksen Teşhis — tarama bütçesi & hız7Önceliklendirilmiş Konsolide Aksiyon Planı (acil / 1 hafta / 2-4 hafta)8Doğrulama Protokolü (24h / 48h / 7g / 14g)

Metodolojinin Özü
"Tarandı ama dizine eklenmedi" tek bir nedenle olmaz. 6 eksenden bir veya birkaçının çakışmasıyla oluşur:

Render — Googlebot’un içeriği gerçekten görülüyor mu?
İçerik kalitesi — Sayfa indekslenmeyen değer mi?
Meta & direktifler — Yanlışlıkla indeks engelleniyor mu?
Yapısal sinyal — Sayfa sitesine yeterince bağlı mı?
Çok dilli & kanonik — hreflang/canonical karışıklığı var mı?
Performans — Tarama bütçesi ve render süresi yeterli mi?

Beceri her hızda çalıştırır, kullanıcıdan veri ister, eksenler arası tutarsızlıkları yakalar ve parlaklıklandırılmış bir aksiyon planı çıkarır.

Kurulum (claude.ai)

Gereksinim: Claude Pro, Max, Team veya Enterprise planı (Özel Beceriler bu planlarda mevcuttur).


Bu repodaki crawled-not-indexed-fix.zippayı indirmek
claude.ai → sol menü → Kişiselleştir → Beceriler aç
Sağ üstteki + butonuna tıklayın → Beceri yükle
ZIP dosyalarını sürükle-birak ile yükleyin
Toggle'ı açın (mavi)

Yüklendikten sonra Claude'a aşağıdaki gibi mesajlar yazdığınızda Skill otomatik tetiklenir:

"Sitemde 'tarandı ama dizine eklenmedi' uyarısı var"
"Next.js sayfalarım indekslenmiyor, JS render sorunu olabilir mi?"
"GSC'de Taranan, indekslenmeyen sayfalar var, çözüm planı çıkar"


Kullanım Örnekleri
Senaryo 1: Next.js Blog Dizini Sorunu
Next.js ile kurulmuş bir blogda 50+ yazı tarandı ve indekslenmedi. Beceri, render sızıntısını öncelikle kontrol eder, CSR sorununu tespit ederse force-staticveya ISR önerir.
Senaryo 2: E-ticaret Kategori Sayfaları
hesaplanan ürün filtresi URL'i tarandığı halde indekste yok. Beceri, kanonik ve parametre işleme ayarlarının parlaklığını arttırır, neredeyse kopya konsolidasyonu önerir.
Senaryo 3: Çok Dilli Kurumsal Site
Türkçe versiyonu indeksli ama İngilizce versiyonu değil. Skill hreflang karşılıklı kontrol ve x-default tanımını önerir.
Senaryo 4: Yeni Yayınlanan Sayfalar
Bir blog 30 para biriminde yayında ama indeksli değil. Beceri içerik kalitesi (ince içerik) ve iç linkleme (orphan page) eksenlerinin görünürlüğünü sağlar.

Uygunluk Sınırları
Bu Skill uygundur:

✅ "Tarandı - şu anda dizine eklenmedi" / "Tarandı ama dizine eklenmedi" durumu
✅ JS ağırlıklı site indeksi sorunları
✅ Çok dilli site indeksi karışıklıkları
✅ İnce/kopya içerikten üretilen indeks reddi
✅ Yapısal (iç linkleme, site haritası) sorunları

Bu Skill uygun değildir:

❌ "Keşfedildi - şu anda indekslenmiyor" (henüz taranmamış — farklı sorun)
❌ Soft 404 / Yönlendirmeli sayfa / Sunucu hatası durumları
❌ Bilinçli noindexkonulmuş sayfalar (admin, sepet, giriş)
❌ Manuel ceza / spam algısı kaynaklı deindex


Beklenen sonuçları
Doğru tanı + doğru aksiyon ile tipik gözlemler:

Oluşturulan sorunlar: ayrılmadan sonra 3-7 gün içinde indeksleme başlar
İçerik kalitesinden kaynaklanır: İyileştirmeden sonra 7-21 gün Google yeniden değerlendirilir
Meta/direktif hatalar: başvurudan sonra 24-72 saat içinde indeks dönüşü mümkün
Yapısal sorunlar: Site haritasının yeniden gönderilmesi + iç linkleme sonrası 5-14 gün

Önemli: Google index dağıtım kullanıcı sinyalleriyle (CTR, bekleme süresi) revize edilir. kesin garanti değildir, olasılığı maksimize eder .

Lisans
MIT Lisansı — Bkz. LICENSE
Becerinizi kişisel veya ticari projelerinizde kullanabilir, fork'layabilir, geliştirebilirsiniz. Atıf zorunlu değildir ancak takdir edilir.

Katkı
Bu Skill canlı bir dokümandır — gerçek vaka deneyimleriyle iyileştirilir. Karşılaştığınız ilginç indeks sorunları ve çözümleri varsa Sorunlar veya Çekme İsteğini açarak paylaşabilirsiniz.

Yazar
SEO ve dijital pazarlama alanında çalışan bir uzman saha deneyimlerinden yararlanılmıştır.
Bu Skill'in temel kapsamlı analiz çerçeveleri: Teknik SEO ile "Tarandı Ama Dizine Eklenmedi" Sorunu Çözümü — Gülşah Arslan

İlgili Beceriler

tarama bütçesi manipülasyonu — Düşük rekabetli uzun kuyruklu kelimelerde hızlı indeks ve sıralama için proaktif kampanya becerisi. İki beceri birlikte fiyat: yeni içerik kampanyalarını tarama-bütçe-manipülasyon ile kurun, sorunlarınızın sayfalarının tarandığını-dizine eklenmediğini-düzeltildiğini tanıyın.
