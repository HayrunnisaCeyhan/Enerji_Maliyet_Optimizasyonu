# ⚡ Veri Bilimi ve Maliyet Odaklı Enerji Analitiği ile Fabrika Operasyonlarının Optimizasyonu

Bu proje, serbest elektrik piyasasındaki (EPİAŞ) saatlik fiyat dalgalanmalarını makine öğrenmesiyle tahmin ederek endüstriyel tesislerin enerji maliyetlerini optimize eden bir **YBS Karar Destek Sistemi** tasarımıdır. 

Proje kapsamında, Kocaeli lokasyonunda faaliyet gösteren bir fabrika için **"Akıllı Yük Kaydırma (Load Shifting)"** simülasyonu yapılmış ve sıfır ek yatırım maliyetiyle **1.46 Milyon TL net tasarruf** elde edilmiştir.

---

## 📊 Proje Özeti ve Başarı Metrikleri

* **Veri Kümesi:** EPİAŞ ve Open-Meteo API entegrasyonu ile oluşturulan 8.760 saatlik (1 tam yıl) dinamik veri ambarı.
* **Özellik Mühendisliği (Feature Engineering):** Geliştirilen sektörel indeksler (`Talep_Yogunluk_Indeksi` vb.) sayesinde baz modelin tahmin başarısı **%68.59'dan %78.83'e ($R^2$)** yükseltilmiştir.
* **Açıklanabilir Yapay Zeka (XAI):** `Feature Importance` analizi ile model kararları şeffaflaştırılmış ve iş mantığı doğrulanmıştır.
* **Finansal Getiri:** Akşam pik saatlerindeki elektrik yükünün %20'si güvenli bir şekilde geceye kaydırılarak **1,464,430.20 TL net nakit tasarrufu** sağlanmıştır.

