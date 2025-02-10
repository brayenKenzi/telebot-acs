# Bot GenieACS Telegram

Bot Telegram untuk mengelola dan memantau perangkat GenieACS dengan mudah. Bot ini memungkinkan admin dan pelanggan untuk mengakses informasi perangkat dan melakukan konfigurasi dasar melalui Telegram.

## 🚀 Fitur

### Fitur Admin
- Melihat daftar semua perangkat (`/devices`)
- Mengelola pelanggan (`/customers`, `/addcustomer`, `/delcustomer`)
- Mencari pengguna berdasarkan username PPPoE (`/finduser`)
- Memeriksa status perangkat (`/status`)
- Mengatur konfigurasi WiFi (`/setwifi`, `/setpass`)
- Mengatur kredensial WAN (`/addwan`)
- Me-reboot perangkat (`/reboot`)

### Fitur Pelanggan
- Memeriksa status perangkat (`/mystatus`)
- Memeriksa status WiFi (`/mywifi`)
- Mengubah password WiFi (`/changepass`)
- Mendapatkan ID Telegram (`/myid`)

## 📋 Prasyarat

- Node.js v12 atau lebih baru
- Server GenieACS yang sudah terkonfigurasi
- Token Bot Telegram

## ⚙️ Konfigurasi

1. Buat file `config.js` dengan format berikut:
