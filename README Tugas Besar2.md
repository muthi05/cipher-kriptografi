# 🧩 Tugas Besar 2 – Kriptografi  
**Implementasi Algoritma Modern (RSA + Digital Signature)**  

---

## 👩‍💻 Anggota Kelompok  
- **Nabilla Maesaroh** – 20123027  
- **Muthi Nur Aisyah** – 20123003  

Program Studi S1 Informatika  
Universitas Teknologi Digital – Tahun Ajaran 2024/2025  

---

## 📘 Deskripsi Proyek  
Proyek ini merupakan implementasi algoritma **RSA (Rivest–Shamir–Adleman)** sebagai bagian dari praktikum mata kuliah **Kriptografi**.  
RSA digunakan untuk proses enkripsi–dekripsi serta tanda tangan digital (digital signature) dengan skema **PSS** dan fungsi hash **SHA-256**.  
Tujuan utama proyek ini adalah memahami prinsip kerja algoritma kriptografi asimetris dan membuktikan integritas data melalui tanda tangan digital.  

Implementasi dibuat menggunakan **Python** dengan library **PyCryptodome**.  

---

## ⚙️ Fitur Utama  
- ✅ Generate pasangan kunci **RSA 2048-bit** (private & public key)  
- 🔒 Enkripsi pesan dengan **RSA + OAEP padding**  
- 🔓 Dekripsi ciphertext ke plaintext  
- ✍️ Digital signature dengan **RSA-PSS + SHA-256**  
- 🔎 Verifikasi tanda tangan digital (True / False)  
- 📄 Simpan hasil ke file:  
  - `private.pem`, `public.pem`  
  - `ciphertext.txt`, `signature.txt`  

---

## 🧠 Teori Singkat  
- **RSA** bekerja dengan dua kunci berbeda: publik untuk enkripsi dan privat untuk dekripsi. Keamanan RSA bergantung pada kesulitan faktorisasi bilangan prima besar.  
- **OAEP (Optimal Asymmetric Encryption Padding)** digunakan agar ciphertext aman terhadap serangan padding.  
- **PSS (Probabilistic Signature Scheme)** memberikan keamanan probabilistik untuk tanda tangan digital.  
- **SHA-256** berfungsi menghasilkan nilai hash unik dari pesan yang akan ditandatangani.  

---

## 💻 Cara Menjalankan Program  

### 1️⃣ Instalasi  
Pastikan Python 3.8+ sudah terpasang.  
Lalu jalankan perintah berikut di terminal atau Google Colab:
```bash
pip install pycryptodome
