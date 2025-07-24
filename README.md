# TR
# PowerPulse - QA Final Projesi BugBusters Ekibi

PowerPulse test projesi deposuna hoş geldiniz!  
Bu proje, **Yazılım Test Uzmanlığı Kursu Final Projesi** kapsamında, **12–24 Haziran 2025** tarihleri arasında gerçekleştirilmiştir.

PowerPulse, kullanıcıların günlük besin tüketimlerini ve çeşitli egzersizlerle yaktıkları kalorileri takip etmelerini sağlayan bir web uygulamasıdır. BugBusters QA ekibi, uygulamanın temel fonksiyonları üzerinden manuel kullanıcı arayüzü ve API testleri gerçekleştirmiştir.

---

## 📋 Proje Özeti

- **Takım:** BugBusters  
- **Takım Büyüklüğü:** 7 aktif QA Mühendisi  
- **Proje Süresi:** 12–24 Haziran 2025  
- **Test Kapsamı:**  
  - Kullanıcı Arayüzü Testleri  
  - API Testleri  
  - Statik Testler  

---

## 🛠 Kullanılan Araçlar ve Teknolojiler

- **Proje Yönetimi:** Trello, Slack  
- **API Testleri:** Postman, Swagger  
- **Çapraz Tarayıcı Testleri:** Responsively  
- **Kullanılan Cihazlar:**  
  - Windows 11 (Chrome, Opera, Edge)  
  - macOS Sequoia (Safari, Chrome, Opera)  
  - Android 13 (Chrome)  
  - iOS 18 (Safari)  

---

## 📄 Dokümantasyon

- ✅ [Test Planı](#)  
- 📑 [Test Raporu](#)  

---

## 🔢 Test Özeti

| Kategori      | UI  | API | Statik | Toplam |
|---------------|-----|-----|--------|--------|
| Test Senaryosu| 351 | 53  | 6      | 410    |
| Geçen         | 291 | 45  | 0      | 336    |
| Başarısız     | 60  | 8   | 0      | 68     |
| Hata Raporu   | 60  | 8   | 0      | 68     |

---

## ❗ Önemli Kritik Hatalar

| ID   | Açıklama                                                                   | Modül                 | Tür          |
|------|----------------------------------------------------------------------------|-----------------------|--------------|
| BR2  | Hesap oluşturulduktan sonra onay maili gönderilmemesi                     | Kimlik Doğrulama      | Fonksiyonel  |
| BR24 | İnaktivite nedeniyle otomatik çıkış süresi ideal değil                     | Oturum Yönetimi       | UX/Fonksiyonel |
| BR30 | Egzersiz tamamlandıktan sonra "Add to Diary" tıklanınca yanlış kalori hesabı | Hesaplama             | Fonksiyonel  |
| BR34 | Egzersiz modal dışına tıklanınca veri kaybı                                | UI/Modal Kontrolü     | UX/Fonksiyonel |
| BR46 | "İsim" alanı sadece boşluk kabul ediyor                                    | Kimlik Doğrulama      | Fonksiyonel  |
| BR49 | Ağırlık sütununda "g" (gram) birimi eksik                                 | Ürünler Tablosu       | Fonksiyonel  |

---

## 👥 Takım Üyeleri

| İsim                | Rol                     |
|---------------------|-------------------------|
| Handan Çileli       | Takım Lideri & QA       |
| Damla Patterson     | Scrum Master & QA       |
| Begüm Dökmetaş      | QA Mühendisi            |
| Dilan Balaman       | QA Mühendisi            |
| Merve Gamze Bal     | QA Mühendisi            |
| Musa Eren Tanrıöver | QA Mühendisi            |
| Nuray Elmas         | QA Mühendisi            |

---

## 🚀 Proje İş Akışı

- 12 Haziran 2025’te Kick-off toplantısı  
- Takım rolleri atandı (Takım Lideri ve Scrum Master)  
- Görev dağılımı ve takip için Trello panoları oluşturuldu  
- Her gün saat 20:00’de günlük toplantılar yapıldı  
- Slack üzerinden iletişim ve iş birliği sağlandı  
- Test kapsamı ve ilerleme düzenli olarak takip edildi ve dokümante edildi  

---

## 🧪 Test Türleri

- ✅ Fonksiyonel Testler  
- 🔁 API Testleri  
- 🧭 Keşif Testleri  
- 📄 Statik Testler  
- ❗ Hata Tahmin Testleri  
- 🖥️ Sistem Testleri  

---

## 📬 İletişim

Herhangi bir soru veya iş birliği için takım üyeleriyle iletişime geçebilirsiniz!

---

# ENG
# PowerPulse - QA Final Project by BugBusters Team

Welcome to the **PowerPulse** testing project repository!  
This project was conducted as part of the **Software Testing Specialization Course Final Project** between **June 12–24, 2025**.

PowerPulse is a web application that allows users to track their daily food intake and calories burned through various exercises. The BugBusters QA team performed manual UI and API testing based on the application's core functionalities.

---

## 📋 Project Overview

- **Team:** BugBusters  
- **Team Size:** 7 active QA Engineers  
- **Project Duration:** June 12–24, 2025  
- **Test Scope:**  
  - UI Testing  
  - API Testing  
  - Static Testing  

---

## 🛠 Tools & Technologies

- **Project Management:** Trello, Slack  
- **API Testing:** Postman, Swagger  
- **Cross-browser Testing:** Responsively  
- **Devices Used:**  
  - Windows 11 (Chrome, Opera, Edge)  
  - macOS Sequoia (Safari, Chrome, Opera)  
  - Android 13 (Chrome)  
  - iOS 18 (Safari)  

---

## 📄 Documentation

- ✅ [Test Plan](#)  
- 📑 [Test Report](#)  

---

## 🔢 Test Summary

| Category     | UI  | API | Static | Total |
|--------------|-----|-----|--------|-------|
| Test Cases   | 351 | 53  | 6      | 410   |
| Passed       | 291 | 45  | 0      | 336   |
| Failed       | 60  | 8   | 0      | 68    |
| Bug Reports  | 60  | 8   | 0      | 68    |

---

## ❗ Notable Critical Bugs

| ID   | Description                                                                | Module              | Type          |
|------|----------------------------------------------------------------------------|---------------------|---------------|
| BR2  | No confirmation email sent after account creation                         | Authentication      | Functional    |
| BR24 | Inactivity auto logout time not ideal                                     |
