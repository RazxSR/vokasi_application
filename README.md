# Aplikasi Sekolah Vokasi UNPAK

## Deskripsi Proyek

Aplikasi ini adalah prototipe dasar untuk Sekolah Vokasi Universitas Pakuan, dirancang untuk memberikan alur pengalaman pengguna yang sederhana mulai dari layar pembuka, pendaftaran akun, hingga tampilan profil pengguna. Aplikasi ini dibuat menggunakan Flutter dan Dart, dengan fokus pada implementasi UI/UX sesuai prototipe Figma yang diberikan serta manajemen navigasi antar halaman.

## Fitur Utama

* **Halaman Landing (Pembuka):** Tampilan awal aplikasi dengan opsi "Masuk" dan "Daftar".
* **Alur Pendaftaran Akun:**
    * Halaman pendaftaran email dan kata sandi.
    * Halaman detail akun untuk informasi pribadi (nama, NPM, program studi, alamat).
* **Alur Masuk (Login):** Halaman masuk dengan input email dan kata sandi.
* **Halaman Profil Pengguna:** Menampilkan informasi detail pengguna seperti nama, email, nomor telepon, NPM, status keaktifan, program studi, jenjang pendidikan, dan alamat. Data profil dimuat secara simulasi (dummy data).
* **Dark Mode:** Fitur tema terang dan gelap yang dapat diaktifkan melalui tombol di halaman profil, dengan preferensi tema yang disimpan di perangkat.
* **Navigasi:** Implementasi navigasi `Navigator.push`, `Navigator.pop`, dan `Navigator.pushReplacement` untuk alur pengguna yang mulus.

## Tampilan Aplikasi (Screenshots UI)

Berikut adalah beberapa tangkapan layar dari antarmuka aplikasi ini:

### Halaman Landing
![Screenshot Halaman Landing](https://placehold.co/600x1000/cccccc/333333?text=SCREENSHOT+LANDING+PAGE)

### Halaman Masuk
![Screenshot Halaman Masuk](https://placehold.co/600x1000/cccccc/333333?text=SCREENSHOT+LOGIN+PAGE)

### Halaman Pendaftaran Akun
![Screenshot Halaman Pendaftaran Akun](https://placehold.co/600x1000/cccccc/333333?text=SCREENSHOT+REGISTER+PAGE)

### Halaman Detail Akun
![Screenshot Halaman Detail Akun](https://imgur.com/rRRUz4q)

### Halaman Profil (Light Mode)
![Screenshot Halaman Profil Light Mode](https://github.com/RazxSR/vokasi_application/blob/9f37360da116db36b51313941e294c2139a5e856/images/dark.jpeg)

### Halaman Profil (Dark Mode)
![Screenshot Halaman Profil Dark Mode](https://placehold.co/600x1000/333333/FFFFFF?text=SCREENSHOT+PROFILE+DARK+MODE)

## Implementasi Kode (Screenshots Kode)

Berikut adalah beberapa cuplikan penting dari implementasi kode:

### Struktur Proyek
![Struktur Proyek](https://placehold.co/600x400/cccccc/333333?text=SCREENSHOT+STRUKTUR+PROYEK)
*Tangkap layar struktur folder `lib/` Anda.*

### Implementasi `ThemeService`
![Kode ThemeService](https://placehold.co/800x600/cccccc/333333?text=SCREENSHOT+THEME_SERVICE.DART)
*Tangkap layar bagian penting dari `lib/theme_service.dart`.*

### Pengaturan Tema di `main.dart`
![Kode Main Dart Theme Setup](https://placehold.co/800x600/cccccc/333333?text=SCREENSHOT+MAIN.DART+THEME)
*Tangkap layar bagian `main()` dan `MyApp` di `lib/main.dart` yang relevan dengan tema.*

### Widget `ThemeToggleButton`
![Kode ThemeToggleButton](https://placehold.co/800x600/cccccc/333333?text=SCREENSHOT+THEME_TOGGLE_BUTTON.DART)
*Tangkap layar seluruh kode `lib/widgets/theme_toggle_button.dart`.*

### Contoh Navigasi
![Kode Navigasi](https://placehold.co/800x600/cccccc/333333?text=SCREENSHOT+NAVIGASI)
*Tangkap layar contoh kode `Navigator.push` atau `Navigator.pushReplacement` dari salah satu halaman Anda.*








