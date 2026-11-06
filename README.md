# WinApp Upgrade

Windows uygulamalarınızı tek yerden güncel tutan hafif bir araç. `winget` üzerinde çalışır: güncellemesi olan uygulamaları listeler, tek tek ya da toplu günceller ve sistem tepsisinde arka planda çalışır.

## İndir

**[WinAppUpgrade.exe — son sürüm](https://github.com/pienart/WinApp-Upgrade-Releases/releases/latest/download/WinAppUpgrade.exe)**

Tüm sürümler: [Releases](https://github.com/pienart/WinApp-Upgrade-Releases/releases)

Kurulum gerekmez; indirdiğiniz dosyayı kalıcı bir klasöre koyup çalıştırmanız yeterli. Uygulama sonraki sürümleri kendisi denetler ve günceller.

## Gereksinimler

- Windows 10 (1903+) veya Windows 11
- [winget](https://learn.microsoft.com/windows/package-manager/winget/) (Uygulama Yükleyicisi)
- [.NET 10 Desktop Runtime](https://dotnet.microsoft.com/download/dotnet/10.0)

## İlk çalıştırmada Windows uyarısı

Dosya henüz bir kod imzalama sertifikasıyla imzalanmadığı için Windows ilk açılışta "Windows bilgisayarınızı korudu" uyarısını gösterebilir. **Ek bilgi → Yine de çalıştır** ile devam edebilirsiniz.

## Güvenlik

- Her sürümün SHA-256 özeti sürüm notlarında yazar.
- Uygulamanın kendi güncellemeleri dijital olarak imzalanır; imzası doğrulanamayan güncelleme kurulmaz.

© 2026 Pienart
