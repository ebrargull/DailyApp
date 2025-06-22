# 📓 DailyApp – SwiftUI & Firebase ile Kişisel Günlük Uygulaması / Personal Diary App with SwiftUI & Firebase

🇹🇷**DailyApp**, **SwiftUI** ve **Firebase** kullanılarak geliştirilmiş, gizliliğe öncelik veren kişisel bir günlük uygulamasıdır. Kullanıcıların günlük düşüncelerini kaydetmesine, duygularını emojilerle ifade etmesine ve anılarını fotoğraflarla zenginleştirmesine olanak tanır. Tüm kayıtlar etkileşimli bir takvim üzerinde görselleştirilir ve sade bir kullanıcı deneyimi sunar.

**DailyApp** tamamen **çevrimdışı** çalışır, verileri hem cihazda hem de **Firebase** üzerinde güvenli şekilde saklar. Ek olarak **Face ID** desteği ile girişler korunur. Tema özelleştirme ve e-posta ile geri bildirim gönderme gibi özellikler de içerir.

--

🇬🇧**DailyApp** is a privacy-focused personal diary application developed using **SwiftUI** and **Firebase**.  
It allows users to record their daily thoughts, express their emotions through emojis, and enrich their memories with photos.  
All entries are visualized on an interactive calendar, offering a clean and intuitive user experience.

**DailyApp** works entirely **offline**, securely storing data both on the device and in **Firebase**.  
Additionally, entries are protected with **Face ID** support.  
The app also includes features like theme customization and feedback submission via email.


---

## 🚀 Özellikler / Features

- Başlık ve içerik ile günlük girişi oluşturma / Create diary entries with title and rich text  
- Anılara fotoğraf ekleme / Add photos to your memories  
- Duyguları ifade etmek için emoji seçme / Select emojis to reflect your mood  
- Takvim görünümünde geçmiş kayıtları görüntüleme / Visualize entries in an interactive calendar  
- Tema seçimi ve özelleştirme / Choose from various themes or customize your own  
- Face ID ile güvenli erişim / Use Face ID for secure access  
- E-posta yoluyla geri bildirim gönderme / Submit feedback via email  
- Başlangıçtan sonra çevrimdışı çalışma / Works offline after initial setup

---

## 🧰 Kullanılan Teknolojiler / Tech Stack

- SwiftUI – Deklaratif arayüz yapısı / SwiftUI – Declarative UI framework  
- Firebase – Veri saklama ve kimlik doğrulama / Firebase – For data storage and user authentication  
- MVVM Mimarisi – Katmanlı yapı / MVVM Architecture – Clean separation of logic and UI  
- Face ID – Biyometrik güvenlik / Face ID / LocalAuthentication – Enhanced app security  
- MailComposeViewController – E-posta ile geri bildirim / MailComposeViewController – For feedback via email

---

## 🔧 Nasıl Çalıştırılır / How to Run

```bash
1. Depoyu klonlayın / Clone the repository
2. `.xcodeproj` dosyasını Xcode ile açın / Open the `.xcodeproj` file in Xcode
3. iOS 16+ destekli gerçek cihazda veya simülatörde çalıştırın / Run on a simulator or real iOS device (iOS 16+)
4. Gerekirse Firebase yapılandırmasını tamamlayın / Configure your Firebase project if needed
