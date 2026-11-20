# ☕ Kahve Sokağı

Kahve Sokağı, bir kafede barista olarak işe başladığın **kafe işletme oyunu**. Müşterilerin siparişlerini hazırla, para kazan, kafeni büyüt.

> 🚧 Proje geliştirme aşamasında. Oyun henüz oynanabilir değil.

## Oyun Fikri

- Barista olarak ilk günde işe başlarsın.
- Her gün müşteriler sırayla gelir ve kahve siparişi verir.
- Siparişi doğru hazırlarsan para kazanırsın.
- Kazandığın parayla yeni makineler ve yeni kahve malzemeleri alırsın.
- Oyun gün gün ilerler. Sabah, öğle ve akşam görüntü değişir.
- Müşteriler karakter karakterdir. Her karakterin kendine özgü bir özelliği vardır:
  - 💼 İş insanı: bahşişi fazla verir.
  - 🎓 Öğrenci: indirimli alışveriş yapar.
  - (Yeni karakterler eklenecek.)

Ayrıntılar için: [docs/oyun-tasarimi.md](docs/oyun-tasarimi.md)

## Teknolojiler

- C# ve .NET 10
- .NET MAUI Blazor Hybrid (Android, iOS, macOS, Windows)

## Proje Yapısı

```
src/
  KahveSokagi.App/             Uygulama ve arayüz (MAUI Blazor)
  KahveSokagi.Core/            Ortak modeller ve temel sınıflar
  KahveSokagi.Game/            Oyun mantığı
  KahveSokagi.Infrastructure/  Kayıt ve dış servisler
  KahveSokagi.Tests/           Testler
assets/                        Görseller ve sesler
docs/                          Tasarım notları
```

## Çalıştırma

Gereksinimler: [.NET 10 SDK](https://dotnet.microsoft.com/download) ve MAUI iş yükü.

```bash
dotnet workload install maui
dotnet build src/KahveSokagi.App
```

## Yol Haritası

Yapılacaklar listesi [docs/oyun-tasarimi.md](docs/oyun-tasarimi.md) dosyasında.
