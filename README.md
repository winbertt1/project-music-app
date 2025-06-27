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
  NIM: 211111850


## ☁️ Arsitektur Cloud yang Digunakan
Dalam aplikasi ini, saya menggunakan dua layanan cloud, yaitu **Firebase** dan **Appwrite**, yang memiliki fungsi berbeda namun saling terintegrasi:

## Link Url : https://mikroskilacid-my.sharepoint.com/:f:/g/personal/221111878_students_mikroskil_ac_id/EqqOFXYXnzJKqSHAcyqu7HoBtCUjjlLRnvkGsbt9I6ZqDw?e=gNsURb

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
1. Buka aplikasi
2. kalau ingin play cukup tekan icon play
3. secara default aplikasi akan berada dalam mode online
4. jika ingin masuk ke dalam mode offline ubah menjadi offline
5. kalau ingin membuat playlist tekan tombol + pada setiap ujung kanan atas lagu
6. cukup mudah karena memang user interface aplikasi ini di buat sangat simple

## 🛠️ Petunjuk Instalasi dan Cara Menjalankan Proyek di Lingkungan Lokal

### ⚙️ Prasyarat
Pastikan sudah menginstall:
- Flutter
- emulator

### 🚀 Langkah-langkah Instalasi
1. clone file github ini
2. jalankan flutter di terimanal dengan flutter pub get
3. hidupkan emulator
4. ke main.dart
5. run without debugging
6. app berhasil jalan

