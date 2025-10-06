# 🧩 MetadataExtractor Tool

Dosyaların EXIF ve diğer metadata verilerini kolayca görüntülemenizi sağlayan güçlü bir **C# (.NET 8.0)** uygulamasıdır.  
Basit bir arayüz üzerinden yalnızca bir dosya seçerek hem özet (Simple) hem de detaylı (Full) metadata bilgilerine erişmenizi sağlar.

> ⚙️ Bu proje, [MetadataExtractor](https://github.com/drewnoakes/metadata-extractor) kütüphanesini kullanmaktadır



## ⚙️ Gereksinimler

- **.NET 8.0 SDK veya Runtime**
- **Windows 10+, Linux veya macOS**
- IDE: Visual Studio, Rider, veya VS Code

---


---

## 🚀 Genel Bakış

Modern cihazlarla çekilen fotoğraf, video ve ses dosyaları; konum, tarih, kamera modeli, lens tipi gibi birçok **gizli metadata** içerir.  
Bu araç, bu bilgileri sade ve şık bir şekilde görüntülemek için geliştirilmiştir.

Proje, iki farklı görünüm sunar:

- **Simple View** → Temel EXIF bilgilerini gösterir.  
- **Full Exif View** → Tüm metadata kategorilerini (EXIF, IPTC, XMP, ICC, vb.) ayrıntılı olarak gösterir.

---




## ✨ Özellikler

### 🧾 Simple View
- Kullanıcıdan bir dosya seçimi alır.
- Cihaz, model, lens, çekim zamanı ve GPS koordinatlarını gösterir.
- Google Maps bağlantısı otomatik oluşturulur.

**Örnek çıktı:**

📱 Primary Platform: Apple Computer, Inc.
Model: iPhone 7 Plus
Lens Model: iPhone 7 Plus front camera 2.87mm f/2.2
Capture Time: 2023:08:18 20:58:05

🌍 GPS Coordinates:
Latitude: 37.7749
Longitude: -122.4194
Google Maps: https://www.google.com/maps?q=37.7749,-122.4194


---

## 📦 Desteklenen Formatlar

| Tür        | Formatlar                                                                 |
|------------|---------------------------------------------------------------------------|
| 📸 Görüntü | JPEG, TIFF, WebP, PSD, PNG, BMP, GIF, ICO, PCX, RAW                      |
| 🎥 Video   | MOV, MP4, M4V, 3G2, 3GP                                                  |
| 🎵 Ses     | MP3, WAV                                                                 |

---

---

### 🔍 Full Exif View
Full Exif modu, seçilen dosyadaki **tüm metadata etiketlerini** gösterir.

Desteklenen metadata türleri:

- EXIF (kamera bilgileri, tarih, pozlama süresi, ISO vb.)
- IPTC (başlık, açıklama, copyright)
- XMP (Adobe metadata formatı)
- ICC Profile (renk profili)
- Photoshop metadata
- WebP, PNG, BMP, GIF, ICO, PCX metadata
- RAW dosya bilgileri (Canon, Nikon, Sony, vb.)
- MOV, MP4, M4V, 3G2, 3GP (video metadata)
- MP3 ve WAV (audio metadata)

---
