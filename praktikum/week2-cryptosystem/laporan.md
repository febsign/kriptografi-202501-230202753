# Laporan Praktikum Kriptografi
Minggu ke-: 2  
Topik: [Cryptosystem (Komponen, Enkripsi & Dekripsi, Simetris & Asimetris)]  
Nama: [FAVIAN RIZKY FEBRIANSYAH]  
NIM: [230202753]  
Kelas: [5IKRB]  

---

## 1. Tujuan
Setelah mengikuti praktikum ini, mahasiswa diharapkan mampu:

1.Mengidentifikasi komponen dasar kriptosistem (plaintext, ciphertext, kunci, algoritma).
2.Menggambarkan proses enkripsi dan dekripsi sederhana.
3.Mengklasifikasikan jenis kriptosistem (simetris dan asimetris).


---

## 2. Dasar Teori
(Ringkas teori relevan (cukup 2–3 paragraf).  
Contoh: definisi cipher klasik, konsep modular aritmetika, dll.  )

---

## 3. Alat dan Bahan
(- Python 3.x  
- Visual Studio Code / editor lain  
- Git dan akun GitHub  
- Library tambahan (misalnya pycryptodome, jika diperlukan)  )

---

## 4. Langkah Percobaan
(Tuliskan langkah yang dilakukan sesuai instruksi.  
Contoh format:
1. Membuat file `caesar_cipher.py` di folder `praktikum/week2-cryptosystem/src/`.
2. Menyalin kode program dari panduan praktikum.
3. Menjalankan program dengan perintah `python caesar_cipher.py`.)

---

## 5. Source Code
(Salin kode program utama yang dibuat atau dimodifikasi.  
Gunakan blok kode:

```python
# contoh potongan kode
def encrypt(text, key):
    return ...
```
)

---

## 6. Hasil dan Pembahasan
(- Lampirkan screenshot hasil eksekusi program (taruh di folder `screenshots/`).  
- Berikan tabel atau ringkasan hasil uji jika diperlukan.  
- Jelaskan apakah hasil sesuai ekspektasi.  
- Bahas error (jika ada) dan solusinya. 

Hasil eksekusi program Caesar Cipher:

![Hasil Eksekusi](screenshots/output.png)
![Hasil Input](screenshots/input.png)
![Hasil Output](screenshots/output.png)
)

---

## 7. Jawaban Pertanyaan
(Jawab pertanyaan diskusi yang diberikan pada modul.  
- Pertanyaan 1: 🔑 Kriptosistem Simetris (Kunci Rahasia)
Prinsip Kunci: Menggunakan satu kunci yang sama untuk proses Enkripsi dan Dekripsi. Kunci ini harus dirahasiakan oleh kedua belah pihak (pengirim dan penerima). *

Kecepatan: Jauh lebih cepat dalam memproses data dalam jumlah besar.

Contoh Algoritma: AES (Advanced Encryption Standard), DES, Triple DES.

Kelemahan Utama: Masalah dalam distribusi kunci (bagaimana cara mengirim kunci rahasia secara aman kepada pihak lain).

🗝️ Kriptosistem Asimetris (Kunci Publik)
Prinsip Kunci: Menggunakan sepasang kunci yang terkait secara matematis:

Kunci Publik (Public Key): Digunakan untuk Enkripsi dan dapat dibagikan secara terbuka.

Kunci Privat (Private Key): Digunakan untuk Dekripsi dan harus dijaga kerahasiaannya oleh pemiliknya.

Kecepatan: Lebih lambat dibandingkan simetris karena melibatkan perhitungan matematika yang lebih kompleks.

Contoh Algoritma: RSA, ECC (Elliptic Curve Cryptography), ElGamal.

Keuntungan Utama: Mengatasi masalah distribusi kunci dan menyediakan fitur seperti Tanda Tangan Digital (digital signatures).

- Pertanyaan 2:  Kriptosistem Simetris (Symmetric)Kelebihan (+)Kelemahan (-)Sangat Cepat (Ideal untuk enkripsi data dalam jumlah besar).Masalah Distribusi Kunci (Kunci harus dikirim secara rahasia sebelum komunikasi).Algoritma lebih sederhana dan efisien secara komputasi.Tidak Scalable (Setiap pasangan pengguna harus memiliki kunci uniknya sendiri).Ukuran kunci relatif pendek (e.g., 128-bit AES).Tidak mendukung Non-Repudiation (tidak bisa membuktikan siapa pengirimnya secara unik).2. Kriptosistem Asimetris (Asymmetric)Kelebihan (+)Kelemahan (-)Tidak ada masalah distribusi kunci (Kunci publik dapat dibagikan secara terbuka).Sangat Lambat (Membutuhkan daya komputasi yang tinggi, jauh lebih lambat dari simetris).Mendukung Tanda Tangan Digital, Otentikasi, dan Non-Repudiation.Ukuran kunci sangat panjang (e.g., 2048-bit RSA).Lebih Scalable (Hanya satu pasangan kunci publik/privat per pengguna).Kompleksitas manajemen kunci privat.

- Pertanyaan 3: Distribusi kunci menjadi masalah utama dalam kriptografi simetris karena dua alasan kunci:1. Kunci Harus Rahasia SepenuhnyaMasalah Inti: Dalam kriptografi simetris, kunci yang digunakan untuk mengenkripsi pesan sama persis dengan kunci yang digunakan untuk mendekripsi pesan .Implikasi: Kunci tersebut harus dikirim dari pengirim ke penerima melalui saluran yang benar-benar aman dan rahasia sebelum komunikasi terenkripsi dimulai. Jika kunci dicegat, semua pesan yang dienkripsi menggunakan kunci tersebut akan terkompromi.2. Skalabilitas yang Buruk (Jaringan Besar)Masalah Logistik: Jika ada $N$ orang yang ingin berkomunikasi secara aman satu sama lain, setiap pasangan harus memiliki kunci rahasia uniknya sendiri.Jumlah Kunci: Jumlah total kunci yang dibutuhkan bertambah secara eksponensial ($N(N-1)/2$). Dalam jaringan besar, mengelola, menyimpan, dan mendistribusikan ribuan kunci unik secara fisik atau melalui saluran aman menjadi tidak praktis dan mahal.Singkatnya, kelemahan mendasar dari sistem simetris adalah tidak adanya metode bawaan yang aman dan efisien untuk mengirimkan kunci rahasia yang menjadi pondasi keamanannya.
)
---

## 8. Kesimpulan
(Tuliskan kesimpulan singkat (2–3 kalimat) berdasarkan percobaan.  )

---

## 9. Daftar Pustaka
(Cantumkan referensi yang digunakan.  
Contoh:  
- Katz, J., & Lindell, Y. *Introduction to Modern Cryptography*.  
- Stallings, W. *Cryptography and Network Security*.  )

---

## 10. Commit Log
(Tuliskan bukti commit Git yang relevan.  
Contoh:
```
commit abc12345
Author: Nama Mahasiswa <email>
Date:   2025-09-20

    week2-cryptosystem: implementasi Caesar Cipher dan laporan )
```
