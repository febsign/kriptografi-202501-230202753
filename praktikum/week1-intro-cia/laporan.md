# Laporan Praktikum Kriptografi
Minggu ke-: X  
Topik: [judul praktikum]  
Nama: FAVIAN RIZKY FEBRIANSYAH
NIM: [230202753]  
Kelas: [5IKRB]  

---

## 1. Tujuan
(Tuliskan tujuan pembelajaran praktikum sesuai modul.)

---

## 2. Dasar Teori
(Ringkas teori relevan (cukup 2–3 paragraf).  
Contoh: definisi cipher klasik, konsep modular aritmetika, dll.  )

Cipher klasik merujuk pada algoritma enkripsi yang digunakan pada masa sebelum era komputer modern, di mana operasi penyandian dan penyahsandian (enkripsi dan dekripsi) dilakukan secara manual atau menggunakan alat mekanik sederhana. Metode ini beroperasi pada tingkat abjad, menangani teks sebagai urutan huruf tunggal, dan umumnya terbagi menjadi dua kategori utama: cipher substitusi dan cipher transposisi. Dalam substitusi, setiap huruf dalam plaintext (teks asli) diganti dengan huruf atau simbol lain (contohnya Caesar Cipher dan Vigenère Cipher), sedangkan dalam transposisi, urutan huruf-huruf diatur ulang atau diacak (contohnya Rail Fence Cipher). Keamanan dari cipher klasik ini sangat bergantung pada kerahasiaan kunci yang digunakan dan seringkali rentan terhadap teknik analisis frekuensi atau serangan brute force karena kompleksitasnya yang relatif rendah. 

Meskipun secara historis penting, cipher klasik saat ini tidak dianggap aman untuk komunikasi sensitif karena mudah dipecahkan dengan metode komputasi modern. Mereka membentuk dasar dari studi kriptografi dan berfungsi sebagai alat pedagogis yang baik untuk memahami konsep dasar enkripsi, kunci, dan serangan kriptanalisis. Secara inheren, mereka menunjukkan prinsip dasar bahwa enkripsi adalah proses matematis mengubah data yang dapat dibaca menjadi format yang tidak dapat dibaca oleh siapa pun tanpa kunci yang tepat, menggunakan teknik yang melibatkan aritmetika modular (khususnya untuk cipher substitusi) atau manipulasi posisi (untuk cipher transposisi) dalam batasan alfabet.

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
- Pertanyaan 1: …  
- Pertanyaan 2: …  
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
