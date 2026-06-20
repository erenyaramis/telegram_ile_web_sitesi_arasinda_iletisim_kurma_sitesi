# 🚀 Telegram Bot Web Kontrol Paneli

Bu proje, hiçbir sunucuya (backend) ihtiyaç duymadan, doğrudan web tarayıcınız üzerinden Telegram botunuzla mesajlaşmanızı sağlayan tek sayfalık bir HTML uygulamasıdır. Hem metin hem de medya iletişimini kolayca tek bir arayüzden yönetmenizi sağlar.

---

## ✨ Özellikler

* **Anlık Mesajlaşma:** Web sayfasından Telegram'a, Telegram'dan web sayfasına canlı metin akışı.
* **Sesli Mesajlaşma:** Mikrofon aracılığıyla ses kaydedip doğrudan bota sesli mesaj olarak gönderme ve gelen sesleri dinleme.
* **Medya Desteği:** Fotoğraf, video ve her türlü belgeyi (PDF, Excel, RAR vb.) bilgisayardan yükleme veya Telegram'dan gelen dosyaları tek tıkla indirme.
* **Otomatik Hafıza:** Girilen API Token ve Chat ID bilgileri tarayıcının yerel hafızasına (Local Storage) kaydedilir; her girişte tekrar şifre istemez.

---

## 🛠️ Adım Adım Kurulum ve Kullanım Rehberi

Aşağıdaki adımları takip ederek sisteminizi sadece birkaç dakika içinde aktif hale getirebilirsiniz.

### 1. Proje Dosyasını Hazırlayın
Projenin temelini oluşturan HTML kodunu kopyalayın. Bilgisayarınızda `index.html` adında boş bir dosya oluşturun, kopyaladığınız kodu içine yapıştırın ve dosyayı kaydedin.

### 2. Telegram Botunuzu Oluşturun (API Token)
Telegram uygulamasına girin ve arama çubuğuna **BotFather** yazın (mavi tikli olan resmi hesabı seçin). 
Mesaj alanına `/newbot` yazarak botunuza bir isim ve kullanıcı adı belirleyin. 
İşlem tamamlandığında BotFather size uzun bir şifre verecektir. "Use this token to access the HTTP API:" yazısının altındaki şifreyi (Örn: `12345:ABCde...`) kopyalayın.

### 3. Hedef Chat ID Numaranızı Öğrenin
Mesajların doğrudan sizin hesabınıza veya grubunuza gelmesi için bir kimlik numarası (ID) belirtmeniz gerekir. 
Kendi ID'nizi öğrenmek için Telegram arama kısmına **@userinfobot** yazın ve başlatın. 
Ekranda beliren `Id:` karşısındaki numarayı (Örn: `1111111`) kopyalayın.

### 4. Panele Giriş Yapın
Bilgisayarınızda oluşturduğunuz `index.html` dosyasını Google Chrome, Edge veya Safari gibi modern bir web tarayıcısında çift tıklayarak açın.

### 5. Ayarları Tamamlayın ve Bağlanın
Sayfanın sağ üst köşesinde bulunan **⚙️ (Ayarlar)** butonuna tıklayın. 
BotFather'dan aldığınız **API Token** değerini ilk kutuya, @userinfobot'tan aldığınız **Chat ID** değerini ikinci kutuya yapıştırın. 
"Kaydet ve Bağlan" butonuna tıklayarak canlı sohbeti başlatın.

---

## ⚠️ Önemli Güvenlik Notu

> Bu sistem tamamen kişisel ve yerel (local) kullanımınız için tasarlanmıştır. Bu HTML dosyasını herkesin erişebileceği açık bir web sunucusuna (hosting) yüklerseniz, siteye giren diğer kişiler API Token bilgilerinize erişebilir. Güvenliğiniz için paneli sadece kendi cihazlarınızda yerel olarak kullanın.
