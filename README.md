# Kampüs Kapında - Mobil Uygulama Sanal Kopyası

Bu proje, **Kampüs Kapında** mobil uygulamasının birebir arayüz ve deneyim prototipini sunan, sıfır kurulum gerektiren modern ve interaktif bir web prototipidir.

Tüm paydaşlar, ekip arkadaşları ve geliştiriciler herhangi bir Node.js veya build aracı kurmaya gerek kalmadan doğrudan tarayıcı üzerinden inceleyebilir ve kodları üzerinde kolayca değişiklik yapabilir.

---

## 🚀 Hızlı Başlangıç

1. `index.html` dosyasına çift tıklayarak doğrudan Google Chrome, Edge veya Safari'de açın.
2. Ya da GitHub Pages üzerinden canlı yayınlayarak linki herkese gönderebilirsiniz.

---

## 📱 İçerilen Ekranlar ve Özellikler

### 1. 🎓 Üniversite Seçimi ve Filtreleme
Sistemdeki aktif 5 üniversite eklenmiştir:
- **Sabancı Üniversitesi** (Ana Kampüs - Tuzla)
- **Medipol Üniversitesi** (Kavacık Güney / Kuzey Kampüsü)
- **Okan Üniversitesi** (Tuzla Kampüsü)
- **Koç Üniversitesi** (Ana Kampüs - Rumelifeneri & Batı Kampüsü)
- **Ömer Halisdemir Üniversitesi** (Merkez Kampüs)

Üniversite değiştirildiğinde ilgili üniversiteye ait işletmeler, teslimat bölgeleri ve bilgiler dinamik olarak güncellenir.

### 2. 🏠 Ana Sayfa (Dashboard)
- Üst bar: Seçili üniversite, profil kısayolu ("Asım Özgür")
- Kırmızı Karşılama Kartı: *"Kampüs Kapında - Üniversitelinin tüm ihtiyaçları tek platformda!"*
- İki ana operasyon kutusu: **Yemek** ve **Eğlence**
- **Yeniden Sipariş Ver** yatay kaydırılabilir geçmiş siparişler listesi (Çiğ Köfteci Ömer Usta, Pizza Bulls vb.)
- **Öne Çıkan Etkinlik** afişi

### 3. 🛵 İşletmeler (Restoranlar) Listesi
- **Kampüs İçi** ve **Kampüs Çevresi** hızlı geçiş sekmeleri
- İşletme kartları: Restoran kapak fotoğrafı, açık/kapalı durumu rozeti, minimum sepet tutarı, değerlendirme puanı, teslimat saatleri ve kampüs teslimat etiketleri (Pizza Bulls, Kuzey Döner, Mezesell, Zekeriyaköy Fırını vb.)

### 4. 🍽️ Restoran Menü & Sipariş Ekranı
- Restoran detay bilgileri (Minimum tutar, puan, çalışma saatleri, teslimat bölgeleri)
- Kategori sekmeleri (*Tümü*, *Coca-Cola Fırsat Menüleri*, *Menemen & Omlet Çeşitleri*, *Pizzalar* vb.)
- Ürün kartları (Görsel, açıklama, fiyat, tek tıkla sepete ekleme `+` butonu)

### 5. 🎟️ Kampüs Etkinlikleri (Eğlence Modülü)
- `kampuskapinda.com` canlı API verileriyle uyumlu parti ve etkinlik listesi (RIDDIM Welcome Party, Halloween Party, BOAZ Middle vb.)
- Tarih, mekan, yaş sınırı rozeti ve bilet inceleme butonları

### 6. 🛒 Canlı Sepet & Sipariş Sistemi
- Yüzen kırmızı sepet butonu ve sepet sayacı
- Ürün adedi arttırma / azaltma / silme
- Ücretsiz kampüs teslimatı hesabı
- Sipariş tamamlama ve otomatik olarak "Sipariş Geçmişi"ne ekleme simülasyonu

### 7. 📄 Sipariş Geçmişim & 👤 Profilim
- Aktif ve geçmiş sipariş durumu takibi (Hazırlanıyor, Tamamlandı, İptal)
- Kullanıcı profil bilgileri ve doğrudan WhatsApp destek hattı (+90 553 730 51 00) bağlantısı

---

## 🎨 Tasarım & Kod Yapısı
- **Framework**: Tailwind CSS (CDN - Kurulumsuz)
- **İkonlar**: Font Awesome 6
- **Font**: Plus Jakarta Sans (Google Fonts)
- **Ekran Görünümü**: Masaüstünde zarif bir mobil telefon çerçevesi (Dynamic Island / iPhone mockup), mobilde ise tam ekran gerçek uygulama deneyimi. İstenirse üstteki butonla tek tıkla tam ekrana geçilebilir.
