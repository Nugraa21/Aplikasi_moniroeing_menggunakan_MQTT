# iot_kolam_ikan

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

```
lib/
├── models/
│   └── sensor_data.dart           // Berisi model data sensor (misalnya suhu, pH, DO)
│
├── pages/
│   ├── about_page.dart            // Halaman informasi tentang aplikasi atau tim
│   ├── connection_page.dart       // Halaman untuk koneksi (kemungkinan MQTT atau jaringan)
│   └── dashboard_page.dart        // Halaman utama yang menampilkan dashboard kolam
│
├── services/
│   └── mqtt_service.dart          // Layanan untuk mengatur koneksi dan komunikasi MQTT
│
├── widgets/
│   └── sensor_card.dart           // Widget untuk menampilkan informasi sensor dalam bentuk kartu
│
└── main.dart                      // Entry point aplikasi, konfigurasi routing dan tema
```