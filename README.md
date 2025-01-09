# MobileProject
## Burdur Mobil Uygulama Projesi

## Proje Hakkında
Bu proje, **Teknoloji Fakültesi Bilgisayar Mühendisliği** bölümü tarafından Burdur iline özel geliştirilmiş bir mobil uygulama ödevidir. Uygulama, görsel ve yapısal bir tasarım sunarak Burdur'un tanıtımını yapmayı amaçlamaktadır.

---

## Proje Bileşenleri

### 1. Mockup Tasarımı
- **Amaç:** Mobil uygulamanın görsel ve işlevsel prototipini oluşturmak.
- **Özellikler:**
  
**Kayıt Ol Sayfası:** Kullanıcıların uygulamaya üye olmasını sağlar.
  - <img width="162" alt="Ekran Resmi 2025-01-09 09 29 34" src="https://github.com/user-attachments/assets/07bed380-53b0-414d-9d14-ac9b3d46d1c8" />
**Kullanıcı Girişi Sayfası:** Kayıtlı kullanıcıların giriş yapmasını sağlar.

  - <img width="162" alt="Ekran Resmi 2025-01-09 09 29 48" src="https://github.com/user-attachments/assets/0306939f-5bb5-4f2c-9a34-1884a0fcfca6" />
  **Menü Sayfası:** Uygulama içindeki tüm bölümlere kolay erişim sunar.

  - <img width="177" alt="Ekran Resmi 2025-01-09 09 30 08" src="https://github.com/user-attachments/assets/487a39d5-1239-4ee9-aead-d9663d08d66d" />
  **Anasayfa:** Burdur'un tarihi ve kültürel özelliklerini kaydırılabilir görsellerle tanıtır.

  - <img width="145" alt="Ekran Resmi 2025-01-09 09 30 19" src="https://github.com/user-attachments/assets/ec8fcc7f-b158-4100-accb-a76282c0d498" />
  **Tarihi ve Turistik Yerler Sayfası:** Burdur'un önemli mekanlarının tanıtımını yapar.

  - <img width="153" alt="Ekran Resmi 2025-01-09 09 30 49" src="https://github.com/user-attachments/assets/e6b43abd-daa9-416f-946b-53520fc95c9b" />
   **Nüfus Dağılımı Sayfası:** İlçelere göre nüfus bilgilerini grafik ve tablolarla sunar.

  -<img width="149" alt="Ekran Resmi 2025-01-09 09 31 02" src="https://github.com/user-attachments/assets/1a1e13e8-8a45-44d0-905b-5b8c83d56c1b" />
  
  **İlçelerin Liste Sayfası:** 
  
  - <img width="133" alt="Ekran Resmi 2025-01-09 09 35 34" src="https://github.com/user-attachments/assets/c4597543-c4a4-4fa1-8d07-0f6a0a72ebef" />

  
  **İlçelerin Ekleme Sayfası:**
  - <img width="138" alt="Ekran Resmi 2025-01-09 09 35 11" src="https://github.com/user-attachments/assets/3dd0f410-0e79-4208-9d60-a1cc6fa40647" />

---

### 2. ER Diyagramı
- <img width="441" alt="Ekran Resmi 2025-01-09 09 38 08" src="https://github.com/user-attachments/assets/ca97420a-28b1-4db2-af48-c6f0cdcd065e" />

- **Amaç:** Uygulamanın veritabanı yapısını ve varlıklar arasındaki ilişkileri modellemek.
- **Varlıklar:**
  - Kullanıcı
  - Şehir Bilgisi
  - İlçe Bilgisi
  - Nüfus Bilgisi
  - Tarihi ve Turistik Yerler
- **İlişkiler:**
  - Şehirler ve ilçeler arasında bire-çok (1-N) ilişkisi.
  - Şehirler ve nüfus bilgisi arasında bire-bir (1-1) ilişkisi.
  - Tarihi ve turistik yerler ile şehirler/ilçeler arasında bire-çok (1-N) ilişkisi.

---

### 3. UML Diyagramı
- **Amaç:** Veritabanı yapısını nesne yönelimli bir yaklaşımla modellemek.
- **Sınıflar ve Özellikler:**
  - **Kullanıcı Sınıfı:** KullanıcıID, AdSoyad, E-Posta, Şifre.
  - **Şehir Bilgisi Sınıfı:** ŞehirID, Şehir Adı, Açıklama, Görsel Slayt.
  - **İlçe Bilgisi Sınıfı:** İlçeID, ŞehirID (FK), İlçe Adı, Nüfus.
  - **Nüfus Bilgisi Sınıfı:** NüfusID, ŞehirID (FK), Yıl, Nüfus Değeri.
  - **Tarihi ve Turistik Yerler Sınıfı:** YerinAdı, ŞehirID (FK), İlçeID (FK), Açıklama.

---

## Projenin Amacı
Bu mobil uygulama, Burdur'un kültürel, tarihi ve demografik özelliklerini kullanıcı dostu bir platform ile tanıtmayı hedeflemektedir.

Daha fazla detay için mockup, ER diyagramı ve UML tasarımını inceleyebilirsiniz.
