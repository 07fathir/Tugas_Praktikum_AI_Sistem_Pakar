# Sistem Pakar Diagnosa Penyakit  
### Metode Forward Chaining & Backward Chaining menggunakan Experta

Sistem ini merupakan implementasi sederhana dari *rule-based expert system* yang digunakan untuk mendiagnosa beberapa penyakit umum berdasarkan gejala yang dimasukkan oleh pengguna. Sistem ini menggunakan dua metode inferensi: **Forward Chaining** dan **Backward Chaining**, dengan bantuan pustaka Python `experta`.

---

## Penyakit yang Dapat Dideteksi:
- Flu  
- Pneumonia  
- Common Cold  
- Infeksi Tenggorokan  
- COVID-19  
- Rinitis Alergi  
- Asma  
- Tonsilitis  
- Sinusitis  
- Kondisi Sehat

---

## Menjalankan di Google Colab

1. Buka [Google Colab](https://colab.research.google.com)
2. Klik **File > Upload Notebook** atau ikon 📁
3. Unggah file `Sistem Pakar.ipynb`
4. Tambahkan cell baru di bagian atas dan jalankan perintah berikut:
   ```python
   !pip install experta

5. Jalankan seluruh cell dengan memilih Runtime > Run all atau tekan Ctrl + F9




---

Penjelasan Metode

Forward Chaining

Sistem mengumpulkan gejala dari pengguna

Aturan diterapkan berdasarkan gejala yang diberikan

Diagnosis disimpulkan dari aturan yang terpenuhi


Backward Chaining

Sistem memulai dari dugaan penyakit (hipotesis)

Menelusuri gejala yang mendukung hipotesis tersebut

Menerima atau menolak hipotesis berdasarkan fakta



---

Disclaimer

Sistem ini dibuat untuk tujuan edukasi dan tidak dimaksudkan sebagai pengganti diagnosis medis profesional. Untuk keakuratan dan penanganan yang tepat, selalu konsultasikan dengan dokter atau tenaga medis yang kompeten.

2306135 Fathir Miftah Nursalim 
