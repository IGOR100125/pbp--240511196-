| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| Bahasa utama | JavaScript, TypeScript, HTML, CSS | C#, C++, Java, Swift, Python | Kotlin (Android), Swift (iOS), Dart (Flutter) |
| Arsitektur | Client-Server | Standalone atau Client-Server | Native, Hybrid, atau Cross-Platform |
| Cara distribusi | URL/Alamat Domain via Browser | Installer file exe atau App Store OS | Application Store (Play Store, App Store) |
| Keunggulan | Aksesibilitas tinggi, tanpa instalasi | Performa tinggi, bisa offline, akses hardware | Mobilitas tinggi, memanfaatkan sensor perangkat, bisa dibawa kemana-mana |
| Keterbatasan | Bergantung koneksi internet | Update manual, bergantung sistem operasi | Layar dan baterai terbatas |
| Contoh aplikasi | Gmail, Figma (Web), Spotify (Web) | Microsoft Office, Adobe Photoshop, Canva | WhatsApp, Instagram, Gojek, Grab |

### Refleksi
## 1. Platform mana yang paling menarik untuk dipelajari? Mengapa?
Platform Web adalah yang cukup menarik bagi saya, alasannya kemudahan akses yang sangat berguna. Tanpa perlu menunggu lama untuk install aplikasi, selain itu juga platform ini memiliki ruang lingkup yang sangat luas dan bisa diakses lintas perangkat.
## 2. Apa tantangan terbesar saat setup environment?
Tantangan terbesarnya buat saya itu waktu harus ngatur environment variables (seperti PATH untuk Java dan Node.js) supaya perintahnya bisa jalan di terminal. Selain itu, proses install Android Studio juga lumayan menantang karena ukuran file dan SDK-nya besar banget, jadi butuh waktu agak lama buat download dan lumayan makan ruang penyimpanan di laptop.
## 3. Bagaimana rencana Anda mengatasi tantangan tersebut?
Buat ngatasin masalah itu, saya mastiin koneksi internet lagi stabil dan bersih-bersih file di laptop dulu biar penyimpanannya cukup dan nggak bikin sistem lag pas install Android Studio. Kalau soal environment variables, saya pelan-pelan ngecek lagi tutorial atau dokumentasinya, mastiin alamat foldernya udah disalin dengan benar ke settingan sistem Windows, terus dites berkali-kali di terminal sampai beneran berhasil terbaca.

# Analisis Perbandingan Platform Pengembangan Perangkat Lunak

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Arsitektur** | Klien-Server (Browser menjalankan antarmuka, server memproses logika/data lewat HTTP/HTTPS). | Standalone / Client-Server Lokal (Berjalan langsung di atas sistem operasi tanpa perantara browser). | Mobile-Native / Cross-Platform (Berjalan di perangkat genggam, memanfaatkan arsitektur OS seluler seperti Android/iOS). |
| **Bahasa Utama** | HTML, CSS, JavaScript (serta bahasa back-end seperti Node.js, Python, PHP, dll.). | Java, C++, C#, Python, Swift, Kotlin. | Kotlin/Java (Android), Swift/Objective-C (iOS), Dart (Flutter), JavaScript/TypeScript (React Native). |
| **Distribusi** | Melalui URL/Domain web server; pengguna dapat langsung mengakses tanpa instalasi (Zero-install). | Melalui installer khusus (.exe, .msi, .dmg, `.deb`) atau App Store resmi (Microsoft Store, Mac App Store). | Melalui App Store (Google Play Store, Apple App Store) atau sideloading. |
| **Keunggulan** | • Akses instan tanpa unduh/instal.<br>• Pembaruan aplikasi sangat mudah di sisi server.<br>• Kompatibilitas lintas platform yang tinggi via browser. | • Kinerja (performance) sangat tinggi dan optimal.<br>• Akses penuh ke hardware perangkat (CPU, GPU, File System).<br>• Dapat berjalan secara offline dengan baik. | • Sangat portabel dan selalu dalam genggaman pengguna.<br>• Pemanfaatan fitur sensor perangkat secara maksimal (GPS, Kamera, Gyroscope, Push Notification). |
| **Keterbatasan** | • Ketergantungan penuh pada koneksi internet.<br>• Akses terbatas terhadap hardware/sistem perangkat keras lokal.<br>• Perbedaan performa rendering di berbagai jenis browser. | • Proses instalasi dan distribusi pembaruan lebih kompleks.<br>• Harus dibuat versi terpisah untuk OS yang berbeda (kecuali menggunakan *framework cross-platform*). | • Ukuran layar yang terbatas.<br>• Fragmentasi perangkat (terutama di Android) yang tinggi.<br>• Proses peninjauan (review) ketat saat publikasi ke Store. |
| **Contoh Aplikasi** | • Google Workspace (Docs, Sheets)<br>• Trello<br>• Netflix (Web) | • Microsoft Office (Word, Excel)<br>• Visual Studio Code<br>• VLC Media Player | • WhatsApp<br>• Instagram<br>• Google Maps |
