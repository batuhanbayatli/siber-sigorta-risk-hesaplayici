# 🛡️ Siber Sigorta Risk Değerlendirme Modeli (SME & Cyber-VaR)
> **bGroup // RiskOptima Labs**  
> *Siber Güvenlik Sigortalarında Dinamik Maruziyet Endeksi (SME) ve Cyber-VaR Aktüeryal Modelleme Platformu*

<p align="left">
  <a href="https://siber-sigorta-risk-hesaplayici.vercel.app/"><img src="https://img.shields.io/badge/Canlı%20Demo-Vercel-0284c7?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel Canlı Demo"></a>
  <img src="https://img.shields.io/badge/Ecosystem-bGroup-0f172a?style=for-the-badge" alt="bGroup">
  <img src="https://img.shields.io/badge/Research-SME%20%26%20Cyber--VaR-38bdf8?style=for-the-badge" alt="Model">
  <img src="https://img.shields.io/badge/Stack-Vanilla%20JS%20%7C%20Tailwind%20CSS-10b981?style=for-the-badge" alt="Tech Stack">
  <img src="https://img.shields.io/badge/License-MIT-gray?style=for-the-badge" alt="License">
</p>

---

## 📌 Proje Özeti

Geleneksel sigortacılıkta siber riskler statik anketlerle ölçülürken, bu platform kurumların siber tehdit maruziyetini ve olası finansal zararını (**Cyber-VaR**) dinamik aktüeryal formüllerle hesaplayan interaktif bir risk analiz aracıdır[cite: 3, 5, 6].

**Batuhan Bayatlı** tarafından geliştirilen metodoloji[cite: 3, 5, 6]; kurumun teknik açıklarını, sektörel saldırı frekansını, veri kritiklik derecesini ve toparlanma hızını tek bir kantitatif puana dönüştürerek doğru poliçe limitini ve teminat yapısını belirler[cite: 6, 7].

---

## ⚙️ Matematiksel Metodoloji & Formülasyon

### 1. Siber Maruziyet Endeksi (SME) Formülü
$$SME = (V \times T \times C) \cdot \alpha$$[cite: 5, 6]

* **$V$ (Vulnerability - Zayıflık):** Kurumun sistem açıkları ve personel zafiyet katsayısı $[0.1 - 1.0]$[cite: 7].
* **$T$ (Threat - Tehdit):** Sektöre yönelik saldırı yoğunluğu $[1.0 - 2.0]$[cite: 7].
* **$C$ (Criticality - Kritiklik):** İşlenen verinin niteliği (KVKK, kredi kartı, finansal kayıtlar) $[1.0 - 2.0]$[cite: 7].
* **$\alpha$ (Recovery - Direnç/Tepki):** Olası bir saldırı sonrası sistemleri ayağa kaldırma hızı $[0.1 - 1.0]$[cite: 7].

### 2. Cyber-VaR (Riske Maruz Değer) Modeli
* %95 güven aralığında Monte Carlo simülasyon yaklaşımıyla, kurumun günlük ciro hacmi ve SME katsayısı üzerinden **Maksimum Olası Finansal Zarar** projeksiyonunu üretir[cite: 3, 5, 6, 8].

---

## ✨ Temel Modüller

* 📊 **Dinamik SME & VaR Hesaplayıcı:** Girdiler değiştikçe gerçek zamanlı güncellenen finansal maruziyet ve risk sınıflandırması[cite: 3, 5, 6].
* 🛡️ **Otomatik Teminat Eşleştirme:** Risk profiline göre *İş Durması*, *Veri Koruma*, *KVKK İdari Para Cezaları* ve *Siber Fidye* teminat önerileri[cite: 3, 5, 6, 8].
* 📐 **Akademi & CIA Üçlüsü:** Siber güvenliğin temel direkleri olan Gizlilik (Confidentiality), Bütünlük (Integrity) ve Erişilebilirlik (Availability) eğitim modülü[cite: 5].

---

## 🛠️ Teknoloji Mimarisi

* **Arayüz / Tasarım:** Semantic HTML5 & Tailwind CSS (Slate / Light FinTech Design System)
* **İkonografi:** Lucide Icons CDN
* **Çekirdek Motor:** Vanilla ES6+ JavaScript (Sıfır framework bağımlılığı)
* **Dağıtım / CI-CD:** Vercel Edge Network

---

## 🚀 Yerel Kurulum ve Çalıştırma

```bash
# Repoyu klonlayın
git clone [https://github.com/batuhanbayatli/siber-sigorta-risk-hesaplayici.git](https://github.com/batuhanbayatli/siber-sigorta-risk-hesaplayici.git)

# Proje dizinine geçin
cd siber-sigorta-risk-hesaplayici

# index.html dosyasını tarayıcınızda açın veya canlı demoyu ziyaret edin:
# [https://siber-sigorta-risk-hesaplayici.vercel.app/](https://siber-sigorta-risk-hesaplayici.vercel.app/)
