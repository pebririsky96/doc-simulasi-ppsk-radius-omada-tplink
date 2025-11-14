# 🚀 Simulasi Implementasi PPSK dengan Omada Controller, TP-LINK AP, dan RADIUS (FreeRADIUS + MariaDB + DaloRADIUS)

Dokumentasi ini berisi langkah-langkah konfigurasi dan simulasi penerapan PPSK (Private Pre-Shared Key) pada Omada Controller yang terhubung dengan perangkat Access Point TP-LINK, serta integrasi autentikasi menggunakan FreeRADIUS dengan backend database MariaDB dan antarmuka manajemen DaloRADIUS.

Simulasi ini bertujuan untuk memberikan pemahaman menyeluruh mengenai bagaimana PPSK dapat diimplementasikan sebagai mekanisme keamanan Wi-Fi yang lebih kuat, sekaligus tetap kompatibel dengan perangkat yang belum mendukung 802.1X. Dengan memanfaatkan RADIUS sebagai server autentikasi terpusat, administrator dapat mengelola kredensial, memonitor sesi, dan meningkatkan kontrol terhadap akses jaringan secara lebih fleksibel.

🎯 Tujuan Simulasi

Memahami arsitektur PPSK pada ekosistem Omada.

Mempelajari integrasi autentikasi Wi-Fi berbasis RADIUS + MariaDB.

Mengetahui cara manajemen user dan policy melalui DaloRADIUS.

Menciptakan skenario Wi-Fi yang aman dan tersegmentasi tanpa memerlukan 802.1X.

Menyediakan referensi konfigurasi yang dapat direplikasi pada lingkungan produksi.

🧩 Komponen yang Digunakan

Omada Software/Hardware Controller

TP-LINK Access Point (seri yang mendukung PPSK)

FreeRADIUS

MariaDB

DaloRADIUS (GUI untuk manajemen RADIUS)

Sistem operasi Linux (Ubuntu/Debian/CentOS)

📘 Isi Dokumentasi

Dokumentasi mencakup:

Instalasi FreeRADIUS, MariaDB, dan DaloRADIUS

Integrasi database RADIUS

Konfigurasi PPSK pada Omada Controller

Pembuatan user, group, dan key PPSK

Pengujian autentikasi

Troubleshooting umum

📌 Catatan

Simulasi ini dibuat sebagai panduan teknis dan dapat dijadikan referensi untuk implementasi nyata di lingkungan enterprise, pemerintahan, lembaga pendidikan, atau skenario Wi-Fi publik yang membutuhkan kontrol akses tingkat lanjut.
