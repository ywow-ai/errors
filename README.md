# 🎨 Enterprise Error Pages Collection

Koleksi lengkap **22 halaman error** yang profesional, user-friendly, dan siap pakai untuk website enterprise Anda.

## 📋 Daftar Lengkap

### Client Errors (4xx) - 14 Halaman
- ✅ **400.html** - Bad Request (Permintaan tidak valid)
- ✅ **401.html** - Unauthorized (Otentikasi diperlukan)
- ✅ **402.html** - Payment Required (Pembayaran diperlukan)
- ✅ **403.html** - Forbidden (Akses ditolak)
- ✅ **404.html** - Not Found (Halaman tidak ditemukan)
- ✅ **405.html** - Method Not Allowed (Metode tidak diizinkan)
- ✅ **408.html** - Request Timeout (Waktu permintaan habis)
- ✅ **409.html** - Conflict (Konflik data)
- ✅ **410.html** - Gone (Resource telah dihapus)
- ✅ **413.html** - Payload Too Large (File terlalu besar)
- ✅ **414.html** - URI Too Long (URL terlalu panjang)
- ✅ **415.html** - Unsupported Media Type (Format tidak didukung)
- ✅ **422.html** - Unprocessable Entity (Data tidak dapat diproses)
- ✅ **429.html** - Too Many Requests (Terlalu banyak permintaan)

### Server Errors (5xx) - 6 Halaman
- ✅ **500.html** - Internal Server Error (Kesalahan server internal)
- ✅ **501.html** - Not Implemented (Fitur belum tersedia)
- ✅ **502.html** - Bad Gateway (Gateway bermasalah)
- ✅ **503.html** - Service Unavailable (Layanan tidak tersedia)
- ✅ **504.html** - Gateway Timeout (Gateway timeout)
- ✅ **505.html** - HTTP Version Not Supported (Versi HTTP tidak didukung)

### Special Pages - 2 Halaman
- ✅ **maintenance.html** - Maintenance Mode (Sedang pemeliharaan)
- ✅ **offline.html** - Offline Mode (Tidak ada koneksi internet)

### Bonus
- ✅ **index.html** - Halaman demo navigasi untuk preview semua error pages

## ✨ Fitur Unggulan

### 🎨 Design & UX
- **Modern & Clean Design** - Tampilan profesional dengan warna yang konsisten
- **Responsive Mobile-First** - Sempurna di semua ukuran layar
- **Professional Color Scheme** - Primary blue (#3B82F6) dengan variasi sesuai severity
- **SVG Icons** - Icon unik dan relevant untuk setiap jenis error

### 📱 User Experience
- **Pesan yang Jelas** - Bahasa Indonesia yang mudah dipahami
- **Troubleshooting Tips** - Panduan kemungkinan penyebab dan solusi
- **Multiple Action Paths** - Berbagai pilihan navigasi untuk user
- **Technical Details** - Error code, timestamp, dan reference ID

### 🛠️ Technical
- **Tailwind CSS** - Via CDN, tidak perlu setup tambahan
- **No Dependencies** - Pure HTML dengan Tailwind CDN
- **Fast Loading** - Optimized untuk performa
- **Accessibility Ready** - Structure yang semantic dan accessible

## 📁 Struktur Halaman

Setiap halaman error mengandung:

1. **Header Section**
   - Logo/Brand
   - Navigation breadcrumb

2. **Hero Error Section**
   - SVG Icon yang relevant
   - Error Code (besar dan jelas)
   - Error Title
   - Error Description yang helpful

3. **Troubleshooting Section**
   - Kemungkinan penyebab
   - Langkah-langkah penyelesaian
   - Timeline resolusi (jika applicable)

4. **Action Buttons**
   - Primary: Kembali ke Homepage
   - Secondary: Kembali ke Halaman Sebelumnya
   - Tertiary: Contact Support
   - Quaternary: Coba Lagi (Refresh)

5. **Technical Details**
   - Error Code
   - Timestamp
   - Reference ID (untuk tracking)
   - Support Contact

6. **Footer Section**
   - Copyright
   - Additional Links
   - Legal Links

## 🚀 Cara Penggunaan

### Preview Lokal
1. Buka file `index.html` di browser untuk melihat semua halaman
2. Klik pada card error untuk preview masing-masing halaman

### Implementasi di Website
1. Copy file error yang dibutuhkan ke project Anda
2. Sesuaikan branding (logo, warna, contact) sesuai kebutuhan
3. Configure web server untuk redirect error ke halaman yang sesuai

### Kustomisasi Brand
Sesuaikan elemen berikut di setiap file:
- Brand name: Ganti "Enterprise" dengan nama perusahaan Anda
- Email support: Ganti "support@enterprise.com" dengan email Anda
- Phone: Update nomor telepon support
- Social media links: Update link social media
- Logo: Tambahkan logo perusahaan Anda

## 🎨 Color Scheme

- **Primary**: Blue #3B82F6
- **Client Errors**: Red, Yellow, Orange (sesuai severity)
- **Server Errors**: Red #DC2626
- **Special Pages**: Blue #2563EB, Gray #4B5563

## 📱 Browser Support

- ✅ Chrome (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Edge (Latest)
- ✅ Mobile Browsers

## 🔧 Web Server Configuration

### Apache (.htaccess)
```apache
ErrorDocument 400 /400.html
ErrorDocument 401 /401.html
ErrorDocument 403 /403.html
ErrorDocument 404 /404.html
ErrorDocument 500 /500.html
ErrorDocument 503 /503.html
```

### Nginx
```nginx
error_page 400 /400.html;
error_page 401 /401.html;
error_page 403 /403.html;
error_page 404 /404.html;
error_page 500 /500.html;
error_page 503 /503.html;

location = /400.html { internal; }
location = /401.html { internal; }
location = /403.html { internal; }
location = /404.html { internal; }
location = /500.html { internal; }
location = /503.html { internal; }
```

## 📊 File Size

Setiap file berukuran ~8-12KB (compressed), sangat ringan dan cepat loading.

## 🌐 Localization

Saat ini tersedia dalam **Bahasa Indonesia**. Untuk versi multi-bahasa, duplikasi file dan sesuaikan konten text.

## 📝 License

Silakan gunakan untuk project personal maupun komersial. Tidak ada batasan penggunaan.

## 💡 Tips & Best Practices

1. **Gunakan CDN** untuk Tailwind CSS agar selalu update
2. **Test di berbagai device** untuk memastikan responsive
3. **Sesuaikan tone** pesan error dengan brand voice Anda
4. **Monitor error frequency** untuk identify masalah website
5. **Update contact info** secara berkala

## 🎯 Use Cases

- Website Enterprise/Corporate
- SaaS Applications
- E-commerce Platforms
- Web Applications
- Portfolio & Landing Pages
- Content Management Systems

## 📞 Support

Untuk pertanyaan atau customization request, hubungi:
- Email: support@enterprise.com
- Website: https://enterprise.com

---

**Dibuat dengan ❤️ untuk Enterprise Indonesia**

© 2025 Enterprise. All rights reserved.
