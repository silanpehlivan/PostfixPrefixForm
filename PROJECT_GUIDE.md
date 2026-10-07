<div align="center">

# Expression Converter

### İfade dönüşümünü ekranda gör.

![C#](https://img.shields.io/badge/C%23-2563eb?style=for-the-badge)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0891b2?style=for-the-badge)
[![MIT](https://img.shields.io/badge/MIT-16a34a?style=for-the-badge)](LICENSE)

Infix, postfix ve prefix gösterimleri arasındaki dönüşümü Windows Forms arayüzünde sunan algoritma uygulaması.

**Görsel ifade dönüşümü**

[Projeyi keşfet](https://github.com/silanpehlivan/PostfixPrefixForm/tree/master) · [Kurulum ve ayrıntılar](#projeyi-çalıştırmak-ve-incelemek)

</div>

---

## İçeride neler var?

- **01** · Infix → postfix ve prefix dönüşümü
- **02** · Operatör önceliğine göre ifade işleme
- **03** · Kullanıcı arayüzü ve hatalı ifade bildirimleri

## Projeyi çalıştırmak ve incelemek

<details>
<summary><strong>Kurulum, kod yapısı ve teknik notları aç</strong></summary>

## Öne Çıkanlar

- Infix → postfix ve prefix dönüşümü
- Operatör önceliğine göre ifade işleme
- Kullanıcı arayüzü ve hatalı ifade bildirimleri

## Teknolojiler

C# · Windows Forms

### Teknik yaklaşım

Form olayları infix girdisini yığın tabanlı dönüştürme metotlarına iletir; sonuçlar aynı arayüzde gösterilir. Algoritma ile kullanıcı etkileşimi birlikte incelenebilir.

### Kodu incelemeye başlayın

- [Form1.cs](Form1.cs)
- [Program.cs](Program.cs)

### Kapsam ve sınırlar

Karakter bazlı dönüşüm bir genel amaçlı matematik parser’ı olarak değerlendirilmemelidir.



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
