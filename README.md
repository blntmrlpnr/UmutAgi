# UmutAgi
Umut Ağı (Hope Network) is a mobile app that connects people affected by natural disasters with volunteers and resources. It enables fast communication, support sharing, and coordination during crises — building a digital network of hope and resilience.
# Umut Ağı

Umut Ağı, afet ve acil durum senaryoları için geliştirilmiş bir Flutter uygulamasıdır. Bu proje:

- Afet bildirimleri oluşturma ve canlı akış takibi
- Kayıp ilanı oluşturma ve halka açık listeleme
- Harita üzerinde afet noktaları ve yardım ekiplerini gösterme
- Yetkili kullanıcılar için yardım tırlarının konumunu izleme

## Özellikler

- `Durum & Afet Bildir`: Afet türü seçip hızlı bildirim oluşturma.
- `Kayıp İlanları`: Ad Soyad, Yaş, T.C. No ve fotoğraf ekleme.
- `Harita`: Afet noktaları ve yardım ekipleri herkese açık şekilde görüntülenir.
- `Yetkili Paneli`: Yetkili kullanıcılar yardım tırlarının yollar üzerindeki konumlarını görür.
- `Canlı Afet Akışı`: Yetkili ekibin afet bildirimlerini listesi ve doğrulama işlemi.

## Gereksinimler

- Flutter 3.x / 4.x
- macOS, Linux veya Windows ortamı
- Flutter SDK yüklü ve yapılandırılmış

## Kurulum

1. Depoyu kopyalayın:

```bash
git clone <repo-url> afetsistem
cd afetsistem
```

2. Flutter paketlerini yükleyin:

```bash
flutter pub get
```

## Çalıştırma

### Mobil / Masaüstü

```bash
flutter run
```

### Sadece Android

```bash
flutter run -d android
```

### Sadece iOS

```bash
flutter run -d ios
```

### Masaüstü (macOS)

```bash
flutter run -d macos
```

## Proje Yapısı

- `lib/main.dart`: Uygulamanın ana kaynak kodu ve tüm ekranlar.
- `assets/`: Uygulamada kullanılan görseller ve ses dosyaları.
- `android/`, `ios/`, `macos/`: Platforma özel proje dosyaları.
- `.vscode/`: VS Code ayarları.

## Notlar

- `T.C. Kimlik No` kaydedilir fakat ilan listesinde halka açık şekilde gösterilmez.
- Yardım tırları, afet bildirimleri oluşturulduğunda yollar üzerinde rastgele yerleştirilir.
- Eğer GitHub için hafif bir paket gerekiyorsa, önceden temizlenmiş `afetsistem-clean.zip` arşivi kullanılabilir.

## Yardım

Daha fazla bilgi için Flutter dokümantasyonuna bakabilirsiniz:

- https://docs.flutter.dev
