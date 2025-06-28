# 🧠 YZTA Bootcamp – Takım 25

## 📝 Proje Başlığı  
**💊 İlaç Etkileşim ve Yan Etki Kontrol Sistemi**

## 📌 Proje Tanımı  
Bu proje, hastaların veya doktorların kullandıkları ilaçları sisteme girmeleriyle birlikte, ilaçlar arasındaki potansiyel tehlikeli etkileşimleri ve yaygın yan etkileri analiz eden, yapay zekâ destekli bir karar destek sistemi geliştirmeyi hedefler.

## 🎯 Hedef Kitle  
- Polifarmasi (birden çok ilaç kullanan) hastalar  
- Yaşlı bireyler  
- Doktorlar ve eczacılar

## 👣 Kullanıcı Akışı  
1. Kullanıcı, kullandığı ilaçların isimlerini arama kutusuna yazar.  
2. Sistem, bu ilaçları büyük bir etkileşim veritabanı ile karşılaştırır.  
3. Yapay zekâ modülü, literatür ve veri kaynaklarından bilgi çıkarımı yapar.  
4. Kullanıcıya anlaşılır uyarılar sunar:  
   > “A ilacı ile B ilacı arasında Ciddi düzeyde bir etkileşim riski vardır. Kanama riskini artırabilir. Lütfen doktorunuza danışın.”

## 🔍 Açık Veri Setleri  
- [Ilacprospektusu.com - İlaç Prospektüsü](/www.ilacprospektusu.com/ilac)  

## 🤖 Kullanılan Yapay Zekâ Teknikleri

| Teknik | Açıklama |
|--------|----------|
| 🧠 Doğal Dil İşleme (NLP) | İlaç isimleri ve tıbbi metinleri anlayarak bilgi çıkarımı yapmak |
| 🌐 Bilgi Grafikleri (Knowledge Graphs) | İlaçlar arası ilişkileri modellemek ve sorgulamak |
| 📈 Örüntü Tanıma | Etkileşim geçmişlerinde tehlikeli örüntüleri tespit etmek |
| 💬 LLM (Gemini) | Uzun etkileşim raporlarını sade ve anlaşılır bir dile çevirmek |

## 🧑‍💻 Takım Üyeleri

| İsim | Rol |
|------|-----|
| Mükerrem Temelli | Veri Bilimci |
| [İsim] | Fullstack Geliştirici |
| [İsim] | PO (Ürün Sahibi) |
| [İsim] | Scrum Master |

## 📁 Klasör Yapısı

yzta-team23/
├── data/
├── notebooks/
├── app/
├── images/
├── README.md
└── sprint1-report.md

## 🛠️ Sprint 1 Hedefleri (20 Haziran – 6 Temmuz)

- [x] Proje fikri belirlendi  
- [x] Açık veri kaynakları araştırıldı  
- [x] NLP için örnek ilaç isimleriyle test yapıldı  
- [ ] Streamlit tabanlı demo geliştiriliyor  
- [ ] GitHub dokümantasyonu tamamlanacak  

## 📌 Notlar

- Bu ürün MVP niteliğindedir (Minimum Viable Product).  
- Nihai hedef: kullanıcıya hızlı, açık ve doğru uyarılar sunan basit bir karar destek aracı geliştirmek.

## 📜 Lisans & Etik  
Kullanılan tüm veri setleri kamuya açık kaynaklardan alınmıştır.  
Sistem tanı koymaz, sadece bilgilendirici analiz sunar.

