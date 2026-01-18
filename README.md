

# Kütüphane Yönetim Sistemi (Console Application) 📚

Bu proje, C# programlama dili kullanılarak geliştirilmiş, 
Nesne Yönelimli Programlama (OOP) mantığını temel alan bir kütüphane yönetim simülasyonudur.
Yazılım mühendisliği eğitimim kapsamında, sınıflar arası ilişkiler ve veri yönetimi konularında pratik yapmak amacıyla geliştirilmiştir.

## 🚀 Özellikler

- **Kitap Kayıt:** Yeni kitapların ISBN, isim ve yazar bilgileriyle sisteme dahil edilmesi.
- **Üye Yönetimi:** Kütüphaneye yeni üyelerin kaydedilmesi.
- **OOP Mimarisi:** Proje; `Kitap`, `Uye` ve `Kutupane` gibi bağımsız sınıflardan (class) oluşur.
- **Konsol Arayüzü:** Kullanıcı dostu komut satırı etkileşimi.

## 🛠 Teknik Detaylar

- **Dil:** C#
- **Platform:** .NET Framework / .NET Core
- **Geliştirme Ortamı:** Visual Studio 2022
- **Kullanılan Yapılar:**
  - Sınıflar (Classes) ve Nesne Örnekleme (Instantiation)
  - Metot Parametreleri ve Geri Dönüş Tipleri
  - Tip Dönüşümleri (Type Casting/Parsing)

## 📸 Kod Yapısı

![Kod Ekran Görüntüsü](https://github.com/user-attachments/assets/73dc6bd7-ca94-41bc-ab3d-a39911a70cf2)
> *Not: Proje klasöründeki kod yapısını ve `Kutupane` sınıfındaki metotları yukarıdaki gibi görselleştirebilirsin.*

## 💻 Örnek Kullanım

Program çalıştığında `Kutupane` sınıfı üzerinden `Kitap_Ekleme` metodu çağrılır ve kullanıcıdan şu bilgiler istenir:
1. Kitabın ISBN numarası
2. Kitabın yazarı
3. Kitabın adı

## 🧠 Mühendislik Yaklaşımı

Bu projeyi geliştirirken şu prensiplere odaklandım:
* **Sorumlulukların Ayrılması (Separation of Concerns):** Kitap, Üye ve Kütüphane işlemlerinin ayrı sınıflarda tutulması.
* **Kod Okunabilirliği:** Değişken ve metot isimlendirmelerinde anlamlı (descriptive) isimlerin seçilmesi.

## ⚙️ Kurulum

1. Depoyu bilgisayarınıza indirin:
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/Kutupane_Yonetim_Sistemi.git](https://github.com/KULLANICI_ADIN/Kutupane_Yonetim_Sistemi.git)
