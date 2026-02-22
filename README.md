# Özel Eğitim Kurumları İstatistik Paneli

Türkiye genelinde özel eğitim kurumlarının 1992'den günümüze yıllara bağlı sayısal değişimini gösteren etkileşimli gösterge paneli.

## Kontrol Çubuğu

**Tür Seçimi:** Açılır menüden incelemek istediğiniz özel eğitim kurumu türünü seçin. Tüm paneller seçilen türe göre güncellenir.

**Yıl Navigasyonu:** Ortadaki yıl göstergesi, o an hangi yılın verilerinin görüntülendiğini belirtir. Yanındaki ok butonlarıyla yıllar arasında ileri-geri geçiş yapabilirsiniz.

**Görüş Modu:** Aydınlık ve karanlık tema arasında geçiş yapar. Varsayılan olarak aydınlık temada açılır.

**Renk Paleti:** Grafiklerde kullanılan renk şemasını değiştirir. Lacivert, Turuncu ve Yeşil olmak üzere üç palet seçeneği sunulur.

**Animasyon:** Yıllar arasında otomatik geçiş başlatır. Oynatma hızı (0.5x, 1x, 2x, 3x) ve sürekli oynatma seçenekleri bu panelden ayarlanır.

## Paneller

**Özet Göstergeler:** Seçilen kurum türü ve yıl için dört temel bilgiyi bir arada sunar - o yılki kurum sayısı, bir önceki yıla göre yüzdelik değişim, tüm yıllar içindeki en yüksek kurum sayısı ve sıfırdan büyük en düşük kurum sayısı.

**Yıllık Trend:** Seçilen kurum türünün 1992'den günümüze kadarki sayısal seyrini çizgi grafik olarak gösterir. Üzerindeki noktalar tıklanabilir; tıklanan yıl aktif yıl olarak seçilir ve diğer paneller buna göre güncellenir.

**Tür Karşılaştırması:** Seçilen yıl için tüm kurum türlerini yatay çubuk grafik ile karşılaştırır. Hangi kurum türünün o yıl en fazla ya da en az sayıda olduğu bir bakışta görülür. Seçili kurum türü vurgulanır.

**Genel Bakış:** Tüm kurum türlerinin tüm yıllardaki değerlerini ısıl harita (heatmap) ile gösterir. Renk yoğunluğu kurum sayısıyla doğru orantılıdır; koyu tonlar yüksek değerleri, açık tonlar düşük değerleri ifade eder. Verisi olmayan hücreler nötr renkte görünür.

## Teknolojiler

- **D3.js v7** - Grafik oluşturma ve veri görselleştirme
- **HTML/CSS/JS** - Tek dosya mimarisi, harici bağımlılık yok (D3 CDN hariç)
- **CSS Custom Properties** - Tema ve renk paleti sistemi

## Kullanım

`index.html` dosyasını tarayıcıda açmanız yeterlidir.
