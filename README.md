
# 🚀 Order-DomainDrivenDesign

Bu proje, **Domain-Driven Design (DDD)** prensiplerine uygun olarak geliştirilmiş bir sipariş yönetim sistemidir. Katmanlı mimari ve temiz kod prensipleri kullanılarak yapılandırılmıştır. Mikroservis mimarilerine geçiş öncesinde güçlü bir domain modeli ve iş mantığı sunar.

---

## 🏗️ Proje Yapısı

```
├── Order.WepApi            # API katmanı (Controller, DTO, Dependency Injection)
├── Order.Application       # Uygulama katmanı (CQRS, servisler, use case'ler)
├── Order.Domain            # Domain katmanı (Entity, Value Object, Aggregate, Domain Event)
├── Order.Infrastructure    # Altyapı katmanı (EF Core, Repository implementasyonları)
```

---

## 🎯 Amaçlar

- 🧩 Domain-Driven Design prensiplerine uygun, temiz ve sürdürülebilir bir mimari oluşturmak  
- 🔗 Katmanlar arası bağımlılıkları **Application → Domain → Infrastructure** yönünde yönetmek  
- ⚙️ SOLID prensiplerine bağlı, test edilebilir bir yapı sağlamak  
- 🚦 CQRS ve MediatR ile iş süreçlerini düzenlemek

---

## 🛠️ Teknolojiler

- .NET 8  
- ASP.NET Core Web API  
- Entity Framework Core  
- MediatR

---


## ✨ Öne Çıkan Özellikler

- 🏛️ Katmanlı mimari ve DDD uygulaması  
- 🧱 Aggregate Root ve Value Object kullanımı  
- 🎉 Domain Event altyapısı  
- 🔄 CQRS deseni ile iş akışı yönetimi  
- 🧹 Temiz ve okunabilir kod yapısı

---

## 📬 İletişim

**Büşra Akay**  
[LinkedIn Profilim](https://www.linkedin.com/in/busraakay/)

---
