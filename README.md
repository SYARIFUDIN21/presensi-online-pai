# 📋 Web Absensi Kelas (SIAKAD Style)

Aplikasi Presensi Perkuliahan Online berbasis web untuk kelas PAI C 2023 – IAINU Kebumen. Aplikasi ini dirancang menyerupai sistem SIAKAD dengan tampilan modern, responsif, dan mudah digunakan tanpa login mahasiswa. Seluruh alur presensi dibuat sederhana agar dapat digunakan dengan cepat oleh Penanggung Jawab kelas, dan hasil presensi dapat langsung dikirim melalui WhatsApp.

## 🎯 Fitur Utama
- Tampilan modern (Gen Z style) dan mobile friendly
- Alur sederhana: Home → Pilih Mata Kuliah → Kelas Perkuliahan → Presensi → Kirim WhatsApp
- Presensi hanya dapat dilakukan oleh Penanggung Jawab (PJ)
- Admin dapat mengatur mata kuliah, dosen pengampu, kelas, semester, dan pertemuan
- Data presensi otomatis dikirim ke WhatsApp
- Penyimpanan data menggunakan LocalStorage
- Tidak menggunakan database eksternal
- Tidak memerlukan login mahasiswa

## 🔐 Hak Akses Pengguna
Mahasiswa dapat mengakses halaman presensi tanpa login namun tidak dapat mengubah data perkuliahan. Penanggung Jawab (PJ) bertugas mengisi nama PJ, mengelola status kehadiran mahasiswa, dan mengirim hasil presensi ke WhatsApp. Admin memiliki akses penuh melalui halaman admin untuk mengatur mata kuliah, dosen pengampu, serta mengelola dan mereset pertemuan, dengan perubahan yang langsung berlaku pada halaman presensi.

## 🧭 Alur Penggunaan Aplikasi
Pengguna membuka halaman Home, memilih mata kuliah, masuk ke halaman kelas perkuliahan, mengisi nama Penanggung Jawab, melakukan presensi mahasiswa, lalu mengirim hasil presensi melalui WhatsApp.

## 📂 Struktur File Project
presensi-online-pai/
├─ index.html (Halaman Home)
├─ pilih-matkul.html (Pilih mata kuliah)
├─ kelas-perkuliahan.html (Informasi kelas dan input Penanggung Jawab)
├─ absensi.html (Presensi mahasiswa dan kirim WhatsApp)
├─ admin.html (Panel admin)
├─ assets/ (Aset gambar dan logo)
└─ README.md (Dokumentasi project)

## 🛠️ Teknologi yang Digunakan
HTML5, CSS3 (Modern UI & Glassmorphism), JavaScript (Vanilla JS), LocalStorage, WhatsApp API (wa.me), dan GitHub Pages.

## 🚀 Deployment
Aplikasi ini dideploy menggunakan GitHub Pages dan dapat diakses melalui browser tanpa instalasi tambahan.

## 📌 Catatan Penting
Project ini bersifat client-side tanpa backend, data tersimpan di browser menggunakan LocalStorage, dan direkomendasikan digunakan pada browser modern seperti Google Chrome atau Microsoft Edge.

## 👨‍💻 Pengembang
Nama: Syarifudin  
Project: Presensi Online PAI  
Institusi: IAINU Kebumen  

Product by SyarifProject
