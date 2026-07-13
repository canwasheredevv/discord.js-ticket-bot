# 🎫 Gelişmiş Discord Ticket (Destek) Sistemi

Bu proje, **Discord.js v14** kullanılarak geliştirilmiş, modern ve kullanıcı dostu arayüz bileşenlerine (Components V2, Menüler, Seçim Panelleri) sahip gelişmiş bir Destek (Ticket) Botu kodudur. Yönetim paneli ve detaylı loglama sistemini içerir.

---

## 🔥 Özellikler

* ⚙️ **Dinamik Kurulum Paneli:** `.destek-ayarlar` komutu ile yetkili rolünü, ticket kategorisini, log ve panel kanallarını tamamen Discord arayüzü üzerinden sıfırdan yapılandırın.
* 📊 **Seçim Menülü Panel:** Kullanıcılar tek bir tıklama ile Genel, Teknik, Satış veya Şikayet kategorilerinde destek talebi oluşturabilir.
* 🔒 **Gelişmiş Yetkilendirme:** Ticket kanalları açıldığında sadece talebi açan kullanıcı, yöneticiler ve belirlenen destek ekibi kanalı görebilir.
* 📞 **Yetkili Çağır Sistemi:** Kullanıcılar tek butonla aktif destek ekibinin DM (Özel Mesaj) kutusuna doğrudan bildirim gönderebilir.
* 📜 **Transcript (Loglama):** Ticket kapatıldığında kanaldaki son 100 mesajı log kanalına düzenli bir metin geçmişi olarak yedekler.
* 🔊 **Ses Kanalı Bağlantısı:** Bot açıldığında otomatik olarak belirlenen bir ses kanalına giriş yapar ve aktif kalır.
* 🔄 **Otomatik Durum Değiştirici:** Botun oynuyor durumu belirli aralıklarla dinamik olarak güncellenir.

---

## 🛠️ Kurulum ve Çalıştırma

Projeyi yerel bilgisayarınızda veya bir sunucuda çalıştırmak için aşağıdaki adımları takip edin:

### 1. Dosyaları İndirin
Kodu bilgisayarınıza indirin ve bir klasöre çıkartın.

### 2. Bağımlılıkları Yükleyin
Klasörün içinde bir terminal (komut satırı) açarak gerekli modülleri yükleyin:
```bash
npm install
```

### 3. Ayar Dosyasını Düzenleyin
Ana dizinde ayarlar.js adında bir dosya oluşturun ve bot ayarlarınızı projenize uygun şekilde yapılandırın.

### 4. Botu başlatın
Gerekli modülleri indirdikden sonra "node lamie.js" yazarak botu başlatın!

### 👥 Yapımcılar
Geliştiriciler: 25f4, katliamcxn

## 📜 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır. Detaylar için LICENSE dosyasına göz at!
