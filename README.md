# 🕵️‍♂️ Veri Dedektifi – Zaman Serisi Anomali Oyunu

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![VanillaJS](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black) ![Status](https://img.shields.io/badge/status-active-success.svg)

## 📌 Proje Tanımı
**Veri Dedektifi**, kullanıcıların zaman serisi verileri üzerindeki anomalileri (normal dışı durumları) tespit etmeye çalıştığı eğitici ve web tabanlı bir oyundur. Oyuncular bir siber güvenlik analisti rolünü üstlenerek verilen grafiklerdeki gizli anormal noktaları belirlemeye çalışırlar.

---

## 🎯 Projenin Amacı
Bu projenin temel hedefleri şunlardır:
- 📊 Kullanıcılara veri analizi mantığını eğlenceli ve interaktif bir şekilde öğretmek.
- 📈 Zaman serisi verilerinde anomali kavramını uygulamalı olarak göstermek.
- ⚛️ Modern Web Teknolojileri (HTML5, CSS3, ES6+) ile modüler bir mimariyi pratikte uygulamak.

---

## 🧠 Oyun Mantığı
- Ekranda dinamik bir zaman serisi grafiği gösterilir.
- Grafikte gizli bir anomali (ani bir yükselme veya düşüş) barınır.
- Oyuncunun görevi, analiz yeteneğini kullanarak bu anomaliyi bulmaktır.

---

## 🎮 Oynanış ve Kurallar

⏱️ **Süre:** Oyuncunun her tur için **10 saniyesi** vardır. Süre dolmadan grafikteki anormal noktaya tıklaması gerekir.

### 🏆 Puanlama Sistemi
- ✅ **Doğru Tahmin:** `+100 Puan`
- ❌ **Yanlış Tahmin:** `-50 Puan`

### 🧗 Zeka ve Zorluk Seviyeleri
Seviye arttıkça oyun zorlaşır:
- Grafik çok daha karmaşık hale gelir.
- Veriye **gürültü (noise)** eklenir.
- Anomali noktaları daha az belirgin (küçük sapmalar) olur.

---

## 📊 Veri Bilimi Yaklaşımı
Bu projede veri bilimi teknikleri kullanılarak gerçekçi senaryolar simüle edilmektedir:
- Zaman serisi verileri simüle edilir (Synthetic Data).
- Gerçek dünya verilerini taklit etmek için **rastgele gürültü (noise)** eklenir.
- Belirli noktalara yapay algoritmalarla anomali entegre edilir.

---

## 🧱 Proje Mimarisi ve Dizin Yapısı
Proje, düzenli ve sürdürülebilir bir dizin yapısına sahiptir:

```text
📂 veri-dedektifi
├── 📄 index.html      # Ana web sayfası
├── 📄 style.css       # Tasarım ve stil dosyası
├── 📄 script.js       # Oyun mantığı, anomali algoritması ve grafik render
└── 📄 README.md       # Proje dokümantasyonu
```

---

## ⚙️ Kullanılan Teknolojiler
Bu projeyi geliştirirken gücünü modern web teknolojilerinden aldık:
- **HTML5** (Semantik Yapı)
- **JavaScript (ES6+)** (Mantık ve Algoritmalar)
- **CSS3 / Vanilla CSS** (Özelleştirilmiş Stil ve Tasarım)
- **Chart.js** (Dinamik ve İnteraktif Grafikler)

---

## 🚀 Gelecek Geliştirmeler (Roadmap)
- [ ] Gerçek veri setlerinin projeye entegre edilmesi.
- [ ] Daha karmaşık gelişmiş anomali tespit algoritmalarının kullanılması.
- [ ] Oyuncuların globalde rekabet edebileceği bir online skorboard sistemi (Leaderboard).
- [ ] Farklı oyun modları (Time Attack, Survival vb.).

---


