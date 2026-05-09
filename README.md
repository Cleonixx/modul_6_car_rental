# 🚗 Car Rental Application

Aplikasi Car Rental adalah sebuah aplikasi mobile Flutter yang dirancang untuk memudahkan pengguna dalam melakukan pemesanan kendaraan dengan antarmuka yang user-friendly dan fitur-fitur modern.

## 📋 Daftar Isi

- [Fitur Utama](#-fitur-utama)
- [Requirements](#-requirements)
- [Instalasi](#-instalasi)
- [Cara Penggunaan](#-cara-penggunaan)
- [Struktur Project](#-struktur-project)
- [Dependencies](#-dependencies)
- [Kontribusi](#-kontribusi)
- [License](#-license)

## ✨ Fitur Utama

- ✅ Browsing daftar kendaraan
- ✅ Pemesanan kendaraan (booking)
- ✅ Manajemen profil pengguna
- ✅ Penyimpanan data lokal dengan SharedPreferences
- ✅ Integrasi API untuk data real-time
- ✅ UI responsif dan modern

## 📦 Requirements

Pastikan Anda telah menginstal:

- **Flutter SDK** v3.8.1 atau lebih tinggi
- **Dart** v3.8.1 atau lebih tinggi
- **Android Studio** atau **Xcode** (untuk development)
- **Git**

### Cek Instalasi Flutter:
```bash
flutter --version
dart --version
```

## 🚀 Instalasi

### 1. Clone Repository
```bash
git clone https://github.com/HarsaIlham/modul_6_car_rental.git
cd modul_6_car_rental
```

### 2. Install Dependencies
```bash
flutter pub get
```

### 3. Jalankan Aplikasi
```bash
# Run di emulator/device yang sudah tersedia
flutter run

# Atau untuk platform tertentu
flutter run -d chrome          # Web
flutter run -d emulator-id     # Android Emulator
flutter run -d simulator       # iOS Simulator
```

### 4. Build untuk Production
```bash
# Android
flutter build apk

# iOS
flutter build ios

# Web
flutter build web
```

## 📱 Cara Penggunaan

1. **Membuka Aplikasi**: Jalankan aplikasi menggunakan perintah `flutter run`
2. **Browse Kendaraan**: Lihat daftar kendaraan yang tersedia
3. **Pesan Kendaraan**: Pilih kendaraan dan isi form booking
4. **Kelola Pesanan**: Lihat dan kelola pesanan Anda di bagian profil
5. **Penyimpanan Data**: Data disimpan secara lokal di device menggunakan SharedPreferences

## 📁 Struktur Project

```
modul_6_car_rental/
├── lib/                        # Folder utama source code
│   ├── main.dart              # Entry point aplikasi
│   ├── screens/               # UI screens/pages
│   ├── models/                # Data models
│   ├── services/              # API dan business logic
│   └── widgets/               # Reusable widgets
├── test/                       # Unit dan widget tests
├── android/                    # Konfigurasi Android
├── ios/                        # Konfigurasi iOS
├── web/                        # Konfigurasi Web
├── pubspec.yaml                # Dependencies dan konfigurasi
└── README.md                   # File ini
```

## 📚 Dependencies

Project ini menggunakan dependencies berikut:

```yaml
- cupertino_icons: ^1.0.8      # Icons untuk iOS style
- shared_preferences: ^2.5.5   # Local storage/caching
- http: ^1.3.0                 # HTTP client untuk API
- flutter_lints: ^5.0.0        # Lint rules
```

Untuk melihat semua dependencies, cek file `pubspec.yaml`.

## 🛠️ Development

### Menjalankan Tests
```bash
flutter test
```

### Code Analysis
```bash
flutter analyze
```

### Format Code
```bash
dart format .
```

### Rebuild Generated Files (jika ada)
```bash
flutter pub run build_runner build
```

## 🤝 Kontribusi

Kami menerima kontribusi dari siapa saja! Berikut cara berkontribusi:

1. **Fork** repository ini
2. Buat branch fitur baru: `git checkout -b feature/AmazingFeature`
3. Commit perubahan Anda: `git commit -m 'Add some AmazingFeature'`
4. Push ke branch: `git push origin feature/AmazingFeature`
5. Buat **Pull Request**

### Panduan Kontribusi:
- Ikuti dart style guide
- Tambahkan tests untuk fitur baru
- Update documentation jika perlu
- Pastikan code Anda tidak melanggar lint rules

## 🐛 Melaporkan Bug

Jika menemukan bug, silakan buat issue dengan informasi:
- Deskripsi bug
- Langkah untuk reproduce
- Expected behavior
- Actual behavior
- Screenshots (jika relevan)

## 📖 Referensi Tambahan

- [Flutter Documentation](https://docs.flutter.dev/)
- [Dart Documentation](https://dart.dev/guides)
- [SharedPreferences Package](https://pub.dev/packages/shared_preferences)
- [HTTP Package](https://pub.dev/packages/http)

## 📞 Kontak & Support

Jika ada pertanyaan, silakan:
- Buka issue di repository ini
- Hubungi: [@HarsaIlham](https://github.com/HarsaIlham)

## 📄 License

Project ini open source dan tersedia di bawah lisensi yang ditentukan. Lihat file LICENSE untuk detail lebih lanjut.

---

**Dibuat oleh:** [HarsaIlham](https://github.com/HarsaIlham)  
**Dibuat pada:** 2026  
**Status:** Active Development

⭐ Jika project ini membantu, jangan lupa untuk memberikan star! ⭐
