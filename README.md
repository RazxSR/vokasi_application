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
![Screenshot Halaman Landing](https://raw.githubusercontent.com/RazxSR/vokasi_application/9f37360da116db36b51313941e294c2139a5e856/images/landing.jpeg)

### Halaman Masuk
![Screenshot Halaman Masuk](https://raw.githubusercontent.com/RazxSR/vokasi_application/9f37360da116db36b51313941e294c2139a5e856/images/masuk.jpeg)

### Halaman Pendaftaran Akun
![Screenshot Halaman Pendaftaran Akun](https://raw.githubusercontent.com/RazxSR/vokasi_application/9f37360da116db36b51313941e294c2139a5e856/images/daftar.jpeg)

### Halaman Detail Akun
![Screenshot Halaman Detail Akun](https://raw.githubusercontent.com/RazxSR/vokasi_application/9f37360da116db36b51313941e294c2139a5e856/images/detail.jpeg)

### Halaman Profil (Light Mode)
![Screenshot Halaman Profil Light Mode](https://raw.githubusercontent.com/RazxSR/vokasi_application/9f37360da116db36b51313941e294c2139a5e856/images/light.jpeg)

### Halaman Profil (Dark Mode)
![Screenshot Halaman Profil Dark Mode](https://github.com/RazxSR/vokasi_application/blob/9f37360da116db36b51313941e294c2139a5e856/images/dark.jpeg)

## Implementasi Kode (Screenshots Kode)

### Implementasi `ThemeService`
![Kode ThemeService](https://raw.githubusercontent.com/RazxSR/vokasi_application/refs/heads/main/images/themeservice2.png)

### Pengaturan Tema di `main.dart`
![Kode Main Dart Theme Setup](https://raw.githubusercontent.com/RazxSR/vokasi_application/refs/heads/main/images/maintheme.png)

### Theme Button
![Kode ThemeToggleButton](https://raw.githubusercontent.com/RazxSR/vokasi_application/refs/heads/main/images/light%20dark.png)

### Contoh Navigasi
![Kode Navigasi](https://raw.githubusercontent.com/RazxSR/vokasi_application/refs/heads/main/images/navigator.png)









