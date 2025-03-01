# imsakiye
Ramazan 2025 için en güncel imsakiye, namaz vakitleri, iftar &amp; sahur saatleri

# 📖 Ramazan İmsakiyesi 2025 | e-icerik.net

Bu proje, **Ramazan 2025** için **Türkiye'nin en güncel sahur ve iftar saatlerini**, **namaz vakitlerini**, **günün hadisi ve duasını** ve **iftara geri sayımı** sunan bir imsakiye sistemidir.

## 🚀 Özellikler

✅ **Günlük Güncellenen İftar ve Sahur Saatleri**  
✅ **Günün Hadisi ve Günün Duası (Otomatik Güncellenir)**  
✅ **İftara Geri Sayım Sayacı**  
✅ **Ramazan Boyunca Namaz Vakitleri Tablosu**  
✅ **Şehir Seçme Özelliği (81 İl)**  
✅ **Sosyal Medyada Paylaşım Butonları**  
✅ **Mobil ve Masaüstü Uyumlu**  
✅ **Gelişmiş SEO Optimizasyonu (Sitemap.xml, Meta Etiketler, Open Graph)**  
✅ **Hız Optimizasyonu (GZIP, Cache, Minify)**  

---

## 📂 Proje Yapısı

/imsakiye 
│── api/ # API işlemleri (fetch_times, cache, geoip, iletisim) 
│── assets/ # CSS, JS, Resimler, Fontlar 
│── data/ # Önbelleklenen JSON dosyaları ve veriler 
│── views/ # HTML şablonları (header, footer, city selector vb.) 
│── .htaccess # SEO, güvenlik ve hız optimizasyonları 
│── sitemap.xml # Arama motorları için site haritası 
│── hakkimizda.php # Hakkımızda sayfası 
│── iletisim.php # İletişim sayfası 
│── index.php # Ana sayfa (İftar & Sahur bilgileri) 
│── README.md # Proje açıklaması


---

## 🛠️ Kurulum ve Kullanım

### 1️⃣ **Dosyaları Sunucuya Yükle**
- Projeyi web sunucunuzda `/imsakiye` klasörüne yükleyin.
- **Apache kullanıyorsanız `.htaccess` dosyasını etkinleştirin.**  
  _(SEO & yönlendirmeler için önemlidir)_

### 2️⃣ **API Bağlantısını Yapılandır**
- `api/config.php` dosyasını açın ve **API ayarlarını** düzenleyin.
- Şu API'leri kullanabilirsiniz:
  - **Diyanet API** (https://ezanvakti.diyanet.gov.tr)
  - **Aladhan API** (https://aladhan.com)
  - **CollectAPI** (https://collectapi.com)

### 3️⃣ **Sitemap.xml ve Google Dizine Ekleme**
- `sitemap.xml` dosyanızın düzgün çalıştığını test edin:  
  🔗 [https://e-icerik.net/imsakiye/sitemap.xml](https://e-icerik.net/imsakiye/sitemap.xml)  
- Google Search Console'da `Sitemap.xml` gönderin.

### 4️⃣ **Tarayıcı Bildirimleri (Opsiyonel)**
- Kullanıcıları iftar/sahur saatlerinde uyarmak için **Push Notification** eklenebilir.

---

## 🔧 Geliştirme ve Güncellemeler

Gelecekte eklenmesi planlanan özellikler:
- 📌 **Gece Modu (Dark Mode)**
- 📌 **Kullanıcının Seçtiği Şehri Kaydetme**
- 📌 **İftara Son 10 Dakika Bildirimi**
- 📌 **Ramazan'a Özel Dua ve Ayetler**

Herhangi bir hata raporlamak veya öneri sunmak için bizimle iletişime geçebilirsiniz.  

📧 **E-Posta:** [iletisim@e-icerik.net](mailto:iletisim@e-icerik.net)  

---

## 📜 Lisans
Bu proje **MIT Lisansı** altında sunulmaktadır.  

🚀 **Ramazan'ınızı en güzel şekilde geçirmeniz dileğiyle!** 🌙✨  
