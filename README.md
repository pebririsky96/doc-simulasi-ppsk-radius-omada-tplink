# 🚀 Simulasi Implementasi PPSK dengan Omada Controller, TP-LINK AP, dan RADIUS (FreeRADIUS + MariaDB + DaloRADIUS)

Dokumentasi ini berisi langkah-langkah konfigurasi dan simulasi penerapan PPSK (Private Pre-Shared Key) pada Omada Controller yang terhubung dengan perangkat Access Point TP-LINK, serta integrasi autentikasi menggunakan FreeRADIUS dengan backend database MariaDB dan antarmuka manajemen DaloRADIUS.

Simulasi ini bertujuan untuk memberikan pemahaman menyeluruh mengenai bagaimana PPSK dapat diimplementasikan sebagai mekanisme keamanan Wi-Fi yang lebih kuat, sekaligus tetap kompatibel dengan perangkat yang belum mendukung IEEE 802.1X. Dengan memanfaatkan RADIUS sebagai server autentikasi terpusat, administrator dapat mengelola kredensial, memonitor sesi, dan meningkatkan kontrol terhadap akses jaringan secara lebih fleksibel.

## 🎯 Tujuan Simulasi

1. Memahami arsitektur PPSK pada ekosistem Omada.
2. Mempelajari integrasi autentikasi Wi-Fi berbasis RADIUS + MariaDB.
3. Mengetahui cara manajemen user dan policy melalui DaloRADIUS.
4. Menciptakan skenario Wi-Fi yang aman dan tersegmentasi tanpa memerlukan 802.1X.
5. Menyediakan referensi konfigurasi yang dapat direplikasi pada lingkungan produksi.

## 🧩 Komponen yang Digunakan

1. Omada Software/Hardware Controller
2. TP-LINK Access Point (seri yang mendukung PPSK)
3. FreeRADIUS
4. MariaDB
5. DaloRADIUS (GUI untuk manajemen RADIUS)
6. Sistem operasi Linux (Ubuntu/Debian/CentOS)

## 📘 Isi Dokumentasi

Dokumentasi mencakup:
1. Instalasi FreeRADIUS, MariaDB, dan DaloRADIUS
2. Integrasi database RADIUS
3. Konfigurasi PPSK pada Omada Controller
4. Pembuatan account user
5. Pengujian autentikasi

Troubleshooting umum

## 📌 Catatan

Simulasi ini dibuat sebagai panduan teknis dan dapat dijadikan referensi untuk implementasi nyata.
