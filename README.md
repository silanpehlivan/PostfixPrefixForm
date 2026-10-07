<div align="center">

# Expression Converter

**Görsel ifade dönüşümü**

![C#](https://img.shields.io/badge/C%23-2563eb?style=flat-square)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0891b2?style=flat-square)
[![MIT License](https://img.shields.io/badge/License-MIT-16a34a?style=flat-square)](LICENSE)

Infix, postfix ve prefix gösterimleri arasındaki dönüşümü Windows Forms arayüzünde sunan algoritma uygulaması.

</div>

---

## Öne Çıkanlar

- Infix → postfix ve prefix dönüşümü
- Operatör önceliğine göre ifade işleme
- Kullanıcı arayüzü ve hatalı ifade bildirimleri

## Teknolojiler

C# · Windows Forms

<details>
<summary><strong>Kurulum, kullanım ve teknik ayrıntılar</strong></summary>

Bu proje, matematiksel ifadelerin **Infix**, **Postfix** ve **Prefix** gösterim biçimleri arasındaki dönüşümünü sağlayan ve bu süreçleri **C# Windows Forms** arayüzü ile görselleştiren bir algoritma uygulamasıdır.

---

## Teknik Özellikler
- **Dil:** C#
- **Arayüz:** Windows Forms (WinForms)
- **Veri Yapıları:** Stack (Yığın) tabanlı veri işleme
- **Kapsam:** Infix ifadeden Postfix ve Prefix dönüşümleri
- **Framework:** .NET 8.0 (Windows)

---

## Öne Çıkan İşlevler
- **Dönüşüm Algoritmaları**  
  Operatör önceliğine göre infix ifadelerin postfix ve prefix forma dönüştürülmesi  

- **Görsel Takip**  
  Windows Forms arayüzü ile dönüşüm adımlarının kullanıcı dostu şekilde görüntülenmesi  

- **Hata Yönetimi**  
  Geçersiz matematiksel ifadelerin tespit edilmesi ve kullanıcıya bildirilmesi  

---

## Kazanımlar
- Stack (yığın) veri yapısının algoritmalarda etkin kullanımı  
- WinForms ile backend mantığının entegrasyonu  
- Matematiksel ifade ayrıştırma (parsing) becerisi  
- Operatör önceliği ve hiyerarşi yönetimi  

---

## Proje Yapısı
```plaintext
PostfixPrefixForm-master/
├── Form1.cs              # Ana uygulama mantığı ve dönüşüm algoritmaları
├── Form1.Designer.cs     # Form arayüz tasarımı kodları
├── Form1.resx            # Form kaynak dosyaları
├── Program.cs            # Uygulama giriş noktası
├── Ödev_6.csproj         # Proje yapılandırma dosyası
├── Ödev_6.sln            # Visual Studio çözüm dosyası
├── LICENSE               # Lisans bilgileri
└── README.md             # Proje dökümantasyonu
```
## Kurulum ve Kullanım
1.  Projeyi klonlayın:
   ```bash
   git clone https://github.com/silanpehlivan/PostfixPrefixForm.git
   ```
2.  Visual Studio ile **Ödev_6.sln** dosyasını açın  
3.  Projeyi derleyin ve çalıştırın  
4.  Uygulama arayüzüne infix ifade girerek Postfix veya Prefix dönüşümünü görüntüleyin  

---


</details>

---

<div align="center">

**© 2024 Şilan PEHLİVAN**

Bu proje MIT lisansı kapsamında sunulmaktadır. Kullanım ve dağıtım koşulları: [LICENSE](LICENSE).

</div>
