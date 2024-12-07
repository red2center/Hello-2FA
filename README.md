
# Hello 2FA : Şifre Yöneticisi - Kullanım ve Gereksinimler

Bu dökümantasyon, Python Flask kullanılarak geliştirilmiş Şifre Yöneticisi programı hakkında bilgi ve kurulum talimatları içermektedir.

## Özellikler
- Kullanıcı adı, şifre, OTP anahtarı, e-posta, telefon numarası ve notlar gibi bilgileri güvenli bir şekilde saklama.
- JSON formatında veri depolama.
- OTP (One-Time Password) kodlarını otomatik olarak oluşturma ve yenileme.
- Kullanıcı dostu bir arayüz ile verileri görüntüleme ve düzenleme.

---

## Sistem Gereksinimleri

Bu programın çalışabilmesi için aşağıdaki gereksinimlerin sisteminizde kurulu olması gerekmektedir:

1. **.NET Desktop Runtime 8**  
   [Microsoft .NET Desktop Runtime 8 İndir](https://dotnet.microsoft.com/download/dotnet/8.0)
   
2. **WebView2 Runtime**  
   [Microsoft WebView2 Runtime İndir](https://developer.microsoft.com/en-us/microsoft-edge/webview2/)

---

## Kurulum Talimatları

1. **Gerekli Bileşenlerin Kurulumu**  
   - Yukarıdaki bağlantılardan .NET Desktop Runtime 8 ve WebView2 Runtime'ı indirip kurunuz.

2. **Programın İndirilmesi ve Çalıştırılması**  
   - Programın `.exe` dosyasını indirip sisteminizde istediğiniz bir klasöre yerleştirin.
   - İki kez tıklayarak çalıştırın.

---

## Kullanım Kılavuzu

1. **Veri Görüntüleme**  
   - Ana ekranda, kaydedilmiş olan tüm şifre bilgileri görüntülenir.
   - Üzerine tıklayarak detayları görebilirsiniz.

2. **Yeni Veri Ekleme**  
   - Sağ üstteki "Yeni Ekle" butonuna tıklayarak yeni bir hesap ekleyebilirsiniz.
   - Web sitesi adı, kullanıcı adı, şifre, OTP anahtarı, e-posta ve diğer bilgileri girin.
   - "Kaydet" butonuna basarak veriyi kaydedin.

3. **OTP Yenileme**  
   - OTP kodu her 30 saniyede bir otomatik olarak yenilenir. Kalan süre arayüzde gösterilir.

4. **Veri Silme**  
   - Bir kaydın yanındaki "Sil" butonuna basarak o kaydı silebilirsiniz.

---

## Sorun Giderme

Eğer program çalışmazsa aşağıdaki adımları izleyin:

1. .NET Desktop Runtime 8 ve WebView2 Runtime'ın doğru şekilde kurulu olduğundan emin olun.
2. Programın en son sürümünü indirdiğinizden emin olun.
3. Hata mesajlarını kontrol edin ve gerektiğinde teknik destek alın.

---

