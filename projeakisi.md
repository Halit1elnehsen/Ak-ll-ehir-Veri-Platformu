# Akıllı Şehir Veri Platformu - Proje Akış Dosyası

## 📅 1. Hafta: Planlama ve Altyapı Araştırması (Teslim: 12 Mart 2026)

### 1. Proje Analizi ve Kapsam Tanımı (Halid ELNEHSEN)
* Projenin ana hedefi; trafik, hava kalitesi ve enerji verilerini bulut üzerinde toplamak ve analiz etmektir.
* Kapsam: Veri toplama altyapısı, analiz araçları, API desteği ve güvenlik çözümleri.

### 2. Bulut Teknoloji Karşılaştırması (Furkan Durkaç)
* **Seçilen Platform:** Microsoft Azure.
* [cite_start]**Gerekçe:** %99,9 SLA garantisi, Azure Digital Twins desteği ve güçlü KVKK/GDPR uyumluluğu. [cite: 23, 25]
* [cite_start]**Maliyet:** 10.000 sensör için yıllık tahmini ~$65.400. [cite: 31]

### 3. Altyapı Kodlama (IaC) ve Mimari (Muhammet Eren Alptekin)
* [cite_start]**Seçilen Araç:** Terraform (Multi-cloud esnekliği için). [cite: 217]
* [cite_start]**Mimari Bileşenler:** Azure IoT Hub (10.000 sensör kapasiteli), HDInsight Kafka ve CosmosDB (MongoDB API). [cite: 233, 242, 257]
* [cite_start]**Otomasyon:** `terraform apply/destroy` komutlarıyla hızlı kurulum ve maliyet optimizasyonu sağlandı. [cite: 275, 276]

### 4. Gereksinim Analizi ve Kullanıcı Hikayeleri (Efe Kaan Durmaz)
* Şehir yöneticileri için trafik yoğunluk haritaları ve vatandaşlar için anlık Hava Kalitesi İndeksi (AQI) uyarı senaryoları oluşturuldu.

---
*Bu dosya her hafta yapılan çalışmalarla güncellenecektir.*
