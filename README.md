# KASTORA — Social Intelligence · Kurulum dosyaları

Bu depo **yalnızca imzalı Windows kurulum dosyalarını** içerir. Kaynak kod özel depoda tutulur.

## Kurulum
1. [Releases](https://github.com/celilbilici/Kastora-Releases/releases/latest) sayfasından `Kastora_Setup_vX.Y.Z.exe` dosyasını indirin.
2. Çift tıklayıp Türkçe kurulum sihirbazını izleyin (yönetici yetkisi gerekmez).
3. İlk açılışta kendi yönetici parolanızı oluşturun.

## Doğrulama
Her sürümde `manifest.json` + `manifest.json.sig` (Ed25519 imzası) ve `SHA256SUMS.txt` bulunur.
Uygulama içi güncelleyici imzayı ve SHA-256 değerini doğrulamadan kurulum yapmaz.

> Kod imzalama sertifikası kullanılmadığı için Windows SmartScreen ilk çalıştırmada uyarı gösterebilir
> ("Ek bilgi" › "Yine de çalıştır").