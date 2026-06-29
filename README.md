# 📚 Les Jarimania - Manajemen Siswa

Sistem manajemen siswa berbasis web dengan database **Firebase Realtime Database** dan hosting **GitHub Pages**. Bisa diakses dari HP, laptop, atau perangkat manapun secara **real-time**!

---

## ✨ Fitur

- 🔐 **Login Admin** (Username & Password terenkripsi)
- ➕ **Tambah Siswa** (Nama, Kelas, Mapel, Status)
- ✏️ **Edit Siswa** (Update data kapan saja)
- 🗑️ **Hapus Siswa** (Dengan konfirmasi)
- 📊 **Statistik Otomatis** (Total siswa & tugas selesai)
- ☁️ **Cloud Database** (Firebase - akses dari mana saja)
- 🔄 **Real-time Sync** (Update otomatis di semua perangkat)
- 📱 **Responsive** (Cocok di HP, tablet, dan laptop)
- 💬 **Notifikasi Toast** (Feedback setiap aksi)

---

## 🖼️ Tampilan

### Halaman Login
![Login](https://via.placeholder.com/400x250?text=Halaman+Login)

### Dashboard
![Dashboard](https://via.placeholder.com/800x400?text=Dashboard+Manajemen+Siswa)

---

## 🛠️ Teknologi yang Digunakan

| Teknologi | Fungsi |
|-----------|--------|
| **HTML5** | Struktur halaman |
| **CSS3** | Styling & Responsive |
| **JavaScript** | Logic & Interaksi |
| **Firebase Realtime DB** | Database cloud |
| **GitHub Pages** | Hosting website |

---

## 🚀 Cara Setup

### 1. Buat Akun Firebase

1. Buka [Firebase Console](https://console.firebase.google.com/)
2. Klik **Create a project**
3. Nama project: `jarimania` (atau sesuai keinginan)
4. Matikan Google Analytics (opsional)

### 2. Buat Realtime Database

1. Di sidebar kiri, klik **Realtime Database**
2. Klik **Create Database**
3. Pilih **Start in test mode**
4. Klik **Enable**

### 3. Dapatkan Config Firebase

1. Klik ikon **</>** (Add app)
2. Pilih **Web**
3. Copy config yang muncul, contoh:

```javascript
const firebaseConfig = {
    apiKey: "AIzaSyABCDEFGHIJKLMNOPQRSTUVWXYZ",
    authDomain: "jarimania-12345.firebaseapp.com",
    databaseURL: "https://jarimania-12345-default-rtdb.firebaseio.com",
    projectId: "jarimania-12345",
    storageBucket: "jarimania-12345.appspot.com",
    messagingSenderId: "123456789",
    appId: "1:123456789:web:abcdef123456"
};