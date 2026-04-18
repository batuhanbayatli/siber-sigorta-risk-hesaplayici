# 🛡️ Siber Sigorta Risk Değerlendirme Modeli (SME & Cyber-VaR)

Bu proje, geleneksel siber sigortacılık yaklaşımlarını dinamik, matematiksel ve veri odaklı bir modele dönüştüren interaktif bir analiz platformudur. **Batuhan BAYATLI** tarafından 2026 yılında geliştirilen bu metodoloji, kurumların siber maruziyetini ölçümlemek ve finansal zarar riskini (Value at Risk) somutlaştırmak için tasarlanmıştır.

## 🌟 Öne Çıkan Özellikler

- **Dinamik SME Hesaplayıcı:** Zayıflık (V), Tehdit (T), Kritiklik (C) ve Direnç ($\alpha$) parametrelerini kullanarak kuruma özel risk katsayısı oluşturur.
- **Cyber-VaR Modellemesi:** %95 güven aralığında, olası bir saldırı anında oluşabilecek maksimum finansal hasarı Monte Carlo simülasyon mantığıyla tahmin eder.
- **Anadolu Sigorta Entegrasyonu:** Hesaplanan risk skoruna göre Anadolu Sigorta'nın siber ürün gamından (İş Durması, KVKK Cezaları, Veri Koruma vb.) en uygun teminat eşleşmelerini yapar.
- **Modern UI/UX:** Glassmorphism ve Silent Luxury estetiğiyle tasarlanmış, yönetici dostu interaktif dashboard.

## 📂 Proje Yapısı

Dosyalar aynı dizinde çalışacak şekilde yapılandırılmıştır:

- `index.html`: Tüm modüllere erişim sağlayan ana kontrol merkezi (Dashboard).
- `BASIT_ANLATIM.html`: Siber güvenlik temelleri ve CIA üçlüsü eğitim modülü.
- `TAM_SISTEM.html`: Kapsamlı tehdit matrisi ve teminat eşleştirme paneli.
- `VAR_SIM.html`: Finansal zarar tahminleme ve simülasyon aracı.
- `SME_FORMULU.html`: Matematiksel modelin parametre bazlı çalışma rehberi.

## 🚀 Hızlı Başlangıç

1. Bu depoyu (repository) klonlayın veya indirin.
2. Tüm dosyaların aynı klasör içinde olduğundan emin olun.
3. `index.html` dosyasını herhangi bir modern tarayıcıda açarak analize başlayın.

## 🛠️ Metodoloji ve Kaynakça

Bu çalışma, **"Siber Güvenlik Sigortalarının Kapsamları Dahilinde Risk Değerlendirmesi"** başlıklı akademik raporu temel almaktadır. 
- **SME Formülü:** $SME = (V \times T \times C) \cdot \alpha$
- **Veri Kaynağı:** Doküman s.1-12 (2026)

## 👤 Geliştirici

**Batuhan BAYATLI** 

---
*Bu proje siber risklerin sadece birer "olasılık" değil, yönetilebilir birer "sayı" olduğunu kanıtlamak için geliştirilmiştir.*
