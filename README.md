# WORDPRESS-FITNESS-TEMA

Spor salonları, fitness merkezleri ve kişisel antrenörler için geliştirilmiş, PayTR ödeme, QR kod, üyelik ve rezervasyon sistemlerine sahip, kapsamlı ve modern WordPress teması.


# Novafit - Fitness & Spor Salonu WordPress Teması 🏋️‍♂️

Novafit, spor salonları, fitness merkezleri, stüdyolar ve kişisel antrenörler için uçtan uca dijital bir yönetim ve sunum imkanı sağlayan, yüksek performanslı bir WordPress temasıdır.

Sadece bir arayüz sunmakla kalmaz; rezervasyon yönetimi, QR kod ile geçiş kontrolü, PayTR ile ödeme alma, bekleme listeleri ve üyelik (VIP/Pro) sistemleri gibi bir spor işletmesinin ihtiyaç duyacağı tüm arka plan operasyonlarını tek bir merkezde toplar.

## ✨ Öne Çıkan Özellikler

* **Gelişmiş Rezervasyon & Takvim Sistemi:** Üyeler, grup derslerine veya özel eğitimlere kolayca rezervasyon yapabilir. Kontenjan dolduğunda otomatik **Bekleme Listesi (Waitlist)** devreye girer.

* **PayTR Sanal POS Entegrasyonu:** Türkiye'nin lider ödeme kuruluşu PayTR altyapısı ile kredi kartı veya taksitle güvenli ödeme alma.

* **Üyelik & Pro İçerik (Membership):** Aylık/Yıllık paketler, indirim kuponları ve sadece VIP üyelere özel "Pro İçerikler".

* **QR Kod Entegrasyonu:** Etkinlik yoklamaları ve salon giriş/çıkış süreçleri için dahili QR kod oluşturma ve tarama altyapısı.

* **Özel İçerik Türleri (Custom Post Types):** Antrenörler, Salonlar ve Etkinlikler için özel sayfalar ve yönetim menüleri.

* **Gelişmiş Güvenlik:** Cloudflare Turnstile CAPTCHA entegrasyonu ve dahili hesap doğrulama (Verify) sistemi.

* **Topluluk & İletişim:** Antrenörler ve üyeler arası dahili mesajlaşma ve mail/hatırlatıcı altyapısı.

* **SEO ve Performans Odaklı:** Arama motorları için optimize edilmiş, temiz ve modern kod yapısı.

## 🚀 Kurulum

Temayı kurmak oldukça basittir. Standart bir WordPress tema kurulum adımlarını izleyebilirsiniz:

1. Bu depoyu (repository) bilgisayarınıza `.zip` formatında indirin veya git üzerinden klonlayın.

   ```
   git clone https://Moutlouu/novafit.git
   
   ```

2. WordPress yönetici panelinize giriş yapın (`/wp-admin`).

3. **Görünüm > Temalar** menüsüne gidin.

4. **Yeni Ekle** -> **Tema Yükle** adımlarını izleyerek indirdiğiniz `novafit.zip` dosyasını (veya klasörü zipleterek) yükleyin.

5. Temayı **Etkinleştirin**.

6. (Opsiyonel) Görünüm > Novafit Ayarları sekmesinden **Demo İçeriği Yükle** seçeneği ile başlangıç verilerini sitenize aktarabilirsiniz.

*Not: Detaylı manuel kurulum adımları için tema dizinindeki `KURULUM.txt` dosyasına göz atabilirsiniz.*

## 📂 Dosya ve Klasör Yapısı

Projenin temel mimarisi şu şekildedir:

```
novafit/
├── assets/                  # CSS (nova.css, pro.css), JS (main.js, qr.js) ve görseller
├── inc/                     # Temanın çekirdek fonksiyonları ve modülleri
│   ├── paytr.php            # Ödeme entegrasyonu
│   ├── reservation.php      # Rezervasyon mantığı
│   ├── qr.js / turnstile    # QR ve Güvenlik modülleri
│   ├── membership.php       # Üyelik paketleri yönetimi
│   └── ...                  # Dil dosyaları, SEO, kuponlar, vb.
├── single-*.php             # Özel içerik türleri (etkinlik, antrenör, salon) şablonları
├── archive-*.php            # Listeleme ve arşiv şablonları
├── functions.php            # Temel WP entegrasyonları
└── style.css                # Tema tanım dosyası

```

## ⚙️ Gereksinimler

* WordPress 6.0 veya üzeri

* PHP 7.4 veya üzeri (PHP 8.x önerilir)

* (Opsiyonel) Ödeme altyapısı için onaylanmış bir PayTR mağaza hesabı.

## 🤝 Katkıda Bulunma (Contributing)

Bu proje açık kaynak geliştirmeye uygundur. Katkıda bulunmak isterseniz:

1. Projeyi fork'layın.

2. Yeni bir özellik veya hata düzeltmesi için kendi dalınızı (branch) oluşturun. (`git checkout -b feature/YeniOzellik`)

3. Değişikliklerinizi commit'leyin. (`git commit -m 'Yeni bir özellik eklendi'`)

4. Dalınıza push'layın. (`git push origin feature/YeniOzellik`)

5. Bir **Pull Request (PR)** açın.

## 📄 Lisans

Bu proje **GPLv2** (veya üzeri) lisansı ile lisanslanmıştır. Detaylar için `LICENSE` dosyasına bakabilirsiniz. (İşletmenize veya telifinize özel bir durum varsa bu alanı düzenlemeyi unutmayın).

*Proje ile ilgili geri bildirimleriniz ve sorun bildirimleriniz için lütfen GitHub **Issues** sekmesini kullanın.*
