# 🏛️ C# Eğitim Kampı 301 - OOP & Katmanlı Mimari

Nesne Yönelimli Programlama (OOP) prensipleri, Entity Framework, LINQ sorguları ve N-Tier (Çok Katmanlı) Mimari yapılarını pekiştirmek amacıyla geliştirilen çalışma reposudur.

---

## 🛠️ Kullanılan Teknolojiler ve Yaklaşımlar

- **Dil:** C# (.NET)
- **Geliştirme Ortamı:** Visual Studio
- **ORM / Veri Erişimi:** Entity Framework (Code First / Database First)
- **Veritabanı:** MS SQL Server
- **Sorgulama:** LINQ (Language Integrated Query)
- **Mimari:** N-Tier Architecture (DataAccess, Business, Entity, Presentation)

---

## 📂 Seri Kapsamında İncelenen Konular

- **OOP Prensipleri:** Sınıflar, Nesneler, Kapsülleme (Encapsulation), Kalıtım (Inheritance), Çok Biçimlilik (Polymorphism) ve Soyutlama (Abstraction).
- **Entity Framework & LINQ:** Tablolar arası ilişkiler, Lambda ifadeleri, CRUD operasyonları ve gelişmiş SQL sorgularının LINQ karşılıkları.
- **Katmanlı Mimari (N-Tier Architecture):**
  - **Entity Layer:** Veritabanı varlıklarının ve modellerinin tanımlandığı katman.
  - **DataAccess Layer:** Veritabanı CRUD operasyonlarının ve context yönetiminin yapıldığı katman.
  - **Business Layer:** İş kurallarının, veri doğrulamalarının (validation) kontrol edildiği katman.
  - **Presentation Layer:** Kullanıcı arayüzü veya konsol çıktılarının yönetildiği katman.

---

## 💻 Kurulum ve Çalıştırma

1. **Repoyu Klonlayın:**
```bash
git clone [https://github.com/dilaraaozcan/CSharpEgitimKampi301.git](https://github.com/dilaraaozcan/CSharpEgitimKampi301.git)
```

2. **Projeyi Açın:**
   `CSharpEgitimKampi301.slnx` dosyasını Visual Studio ile açın.

3. **Veritabanı & Migration:**
   - `App.config` dosyasındaki bağlantı dizesini (`connection string`) kendi yerel MS SQL Server ortamınıza göre düzenleyin.
   - Package Manager Console üzerinden gerekiyorsa migration komutlarını çalıştırın:
```bash
Update-Database
```

4. **Çalıştırma:**
   - Başlatmak istediğiniz katman veya sunum projesine sağ tıklayıp **"Set as Startup Project"** seçin ve `Ctrl + F5` ile çalıştırın.

---

## 👤 Geliştirici

- **Geliştirici:** Dilara Özcan
- **GitHub:** [@dilaraaozcan](https://github.com/dilaraaozcan)
