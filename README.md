# 🎶 Music Apps

## 📝 Deskripsi Singkat
Music Apps adalah aplikasi streaming musik berbasis app yang memungkinkan pengguna mendengarkan lagu secara online, membuat playlist, dan menikmati berbagai genre musik dengan antarmuka yang sederhana dan responsif.

## 👥 Daftar Anggota Kelompok
- Nama:Winbert 
  NIM: 221111878
- Nama: Constantin
  NIM: 221112405
- Nama: Felix Luwinta
  NIM: 221111259
- Nama: Bayu Indra Syahputra
  NIM: 221111850

 🌐 URL Aplikasi Live
[https://link-aplikasi-mu.com](https://link-aplikasi-mu.com)

☁️ Arsitektur Cloud yang Digunakan
Dalam aplikasi ini, saya menggunakan dua layanan cloud, yaitu **Firebase** dan **Appwrite**, yang memiliki fungsi berbeda namun saling terintegrasi:

### 🔥 Firebase (Cloud Firestore)
Firebase digunakan sebagai **database utama** untuk menyimpan data lagu dan playlist. Informasi yang disimpan mencakup:
- ID lagu
- Judul lagu
- Nama penyanyi
- URL lagu (link ke Appwrite)
Firebase dipilih karena mudah diintegrasikan dengan Flutter, mendukung real-time database, dan memiliki dokumentasi yang lengkap.


### 📦 Appwrite (Storage)
Appwrite digunakan untuk **menyimpan file lagu/audio**. File disimpan di Appwrite Storage, lalu URL file tersebut disimpan di Firebase sebagai referensi untuk diputar oleh aplikasi.

Appwrite dipilih karena mendukung pengelolaan file dengan akses yang fleksibel, dan bisa digunakan secara self-hosted maupun cloud.


## 💡 Petunjuk Penggunaan Aplikasi
1. Buka URL aplikasi live pada browser.
2. Registrasi akun baru atau login menggunakan akun yang telah terdaftar.
3. Pilih lagu dari daftar musik yang tersedia.
4. Klik tombol play untuk memutar lagu, atur volume, dan tambahkan lagu ke playlist favorit.
5. Logout setelah selesai menggunakan aplikasi.

## 🛠️ Petunjuk Instalasi dan Cara Menjalankan Proyek di Lingkungan Lokal

### ⚙️ Prasyarat
Pastikan sudah menginstall:
- Node.js
- npm

### 🚀 Langkah-langkah Instalasi
1. Clone repository:
   ```bash
   git clone https://github.com/winbertt1/project-music-app.git
cd music-apps
npm install
npm start

