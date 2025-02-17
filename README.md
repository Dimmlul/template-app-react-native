# 📱 React Native Template - Navigation with TypeScript

Ini adalah template React Native yang dilengkapi dengan navigasi menggunakan TypeScript. Template ini dikembangkan menggunakan **Expo** dan dirancang untuk memberikan fondasi yang baik untuk pengembangan aplikasi React Native dengan TypeScript dan navigasi.

---

## 🛠️ Langkah-langkah Instalasi

### **1️⃣ Clone Repository atau Download ZIP**

Untuk memulai proyek, Anda bisa meng-clone repository ini menggunakan Git:

```sh
git clone https://github.com/username/template-app-react-native.git
cd template-app-react-native
```

Atau jika Anda ingin menggunakan ZIP, unduh file dan ekstrak ke folder pilihan Anda.

### **2️⃣ Instal Dependensi**

Setelah repository di-clone, jalankan perintah berikut untuk menginstal semua dependensi yang diperlukan:

```sh
npm install
```

### **3️⃣ Jalankan Aplikasi**

Untuk menjalankan aplikasi pada perangkat Anda atau simulator, gunakan perintah berikut:

```sh
npm start
```

Ikuti instruksi yang muncul pada terminal untuk menjalankan aplikasi menggunakan Expo Go.

---

## 📌 Deskripsi Template

Template ini menggunakan `npx create-expo-app@latest` dengan parameter `--template navigation-typescript` untuk membuat proyek React Native yang sudah siap dengan konfigurasi navigasi dan TypeScript.

---

## 🏷️ Struktur Proyek

Berikut adalah struktur folder utama yang terdapat dalam proyek ini:

| **Folder/File**                | **Deskripsi**                                                     |
| ------------------------------ | --------------------------------------------------------------- |
| `.expo`                         | Konfigurasi terkait Expo                                         |
| `assets/`                       | Berisi aset seperti gambar, font, dll.                           |
| `src/`                          | Berisi kode sumber aplikasi.                                    |
| `src/app/`                      | Struktur folder untuk halaman aplikasi seperti navigasi dan routing. |
| `src/components/`               | Berisi komponen-komponen UI reusable.                           |
| `src/tests/`                    | Berisi unit tests dan pengujian komponen.                        |
| `src/constants/`                | Berisi konstanta yang digunakan dalam aplikasi, seperti warna atau tema. |
| `.gitignore`                    | Menyimpan file atau folder yang tidak ingin diikutsertakan dalam version control |
| `app.json`                      | Konfigurasi utama untuk aplikasi Expo                            |
| `package.json`                  | Menyimpan metadata aplikasi serta dependensi yang digunakan      |
| `tsconfig.json`                 | Konfigurasi TypeScript                                           |
| `README.md`                     | Dokumentasi proyek ini                                           |

---

## 📂 Struktur Folder & Isi

Berikut adalah penjelasan lebih detail mengenai folder `src` dan `assets`:

### **Struktur Folder `src/`**

| **Folder/File**                | **Deskripsi**                                                     |
| ------------------------------ | --------------------------------------------------------------- |
| `src/app/`                      | Menyimpan file terkait aplikasi seperti layout dan routing       |
| `src/app/tabs/`                 | Folder untuk tab navigasi utama dalam aplikasi.                  |
| `src/components/`               | Komponen UI reusable yang digunakan di seluruh aplikasi.         |
| `src/constants/`                | Berisi definisi warna, font, dan nilai konstan lainnya.          |
| `src/tests/`                    | Unit tests untuk menguji aplikasi secara keseluruhan.            |

### **Struktur Folder `assets/`**

| **Folder/File**                | **Deskripsi**                                                     |
| ------------------------------ | --------------------------------------------------------------- |
| `assets/fonts/`                 | Berisi font yang digunakan dalam aplikasi, seperti `SpaceMono-R`. |
| `assets/images/`                | Berisi gambar yang digunakan dalam aplikasi.                     |
| `assets`                        | Folder umum untuk menampung berbagai jenis file aset lainnya.    |

---

## 🚀 Fitur Utama

- **Navigasi dengan TypeScript**: Menggunakan React Navigation untuk navigasi antar halaman.
- **Komponen Reusable**: Komponen UI yang dapat digunakan kembali untuk memudahkan pengembangan.
- **Responsif**: Dapat berjalan baik di perangkat mobile dan desktop menggunakan Expo.
- **TypeScript**: Menggunakan TypeScript untuk memastikan keamanan tipe dan pengalaman pengembangan yang lebih baik.

---
