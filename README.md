# 🚗 Modul 6 - Aplikasi Sewa Mobil

Aplikasi mobile sewa mobil berbasis Flutter yang terhubung dengan REST API.

## 📱 Fitur

### Role USER
- 🔐 Login & Register
- 🚗 Lihat daftar mobil & pencarian
- 📅 Cek ketersediaan mobil per tanggal
- 📋 Buat pemesanan (booking)
- 💳 Pembayaran (Transfer Bank, Tunai, E-Wallet)
- 📜 Riwayat booking & status real-time
- ❌ Batalkan booking

### Role ADMIN
- 📊 Dashboard statistik (User, Mobil, Booking, Revenue)
- ✅ Konfirmasi & selesaikan booking
- ❌ Batalkan booking
- 💰 Verifikasi pembayaran

## 🔗 API
Base URL: `https://car-rental-api-silk.vercel.app`

## 🛠️ Tech Stack
- Flutter
- Dart
- HTTP Package
- Shared Preferences
- Device Preview

## 🚀 Cara Menjalankan

1. Clone repository
```bash
git clone https://github.com/Cleonixx/modul_6_car_rental.git
cd modul_6_car_rental
```

2. Install dependencies
```bash
flutter pub get
```

3. Jalankan aplikasi
```bash
flutter run
```

## 👤 Akun Demo

### Admin
- Email: admin@sewamobil.com
- Password: AkuAdmin

### User
- Register akun baru via aplikasi

## 📁 Struktur Project
```
lib/
├── config/         # Konfigurasi API
├── models/         # Data models
├── services/       # API services
├── screens/        # UI screens
│   ├── auth/       # Login & Register
│   ├── car/        # Daftar & detail mobil
│   ├── booking/    # Booking & pembayaran
│   └── admin/      # Admin panel
└── widgets/        # Reusable widgets
```
