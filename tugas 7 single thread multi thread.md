# ✨ **TUGAS SISTEM BILANGAN** ✨  

## **Identitas Mahasiswa**  
- 📛 **Nama:** Muhammad Yoga Ananda Satria  
- 🔢 **NRP:** 3124500036  
- 👨‍🏫 **Dosen Pengajar:** Dr. Ferry Astika Saputra ST, M.Sc  
- 🎓 **Program Studi:** D3 Teknik Informatika  
- 🏛 **Institusi:** Politeknik Elektronika Negeri Surabaya (PENS)  
- 📅 **Tahun:** 2025  

---

# 🧵 **Konsep Single Thread dan Multithread**  

## 🟦 **Single Thread**  
Single thread adalah model eksekusi program yang **sederhana dan linear**. Dalam pendekatan ini, hanya terdapat **satu jalur eksekusi instruksi** yang berjalan dari awal hingga akhir secara **berurutan**. Setiap perintah dieksekusi satu per satu sesuai urutan yang telah ditentukan.

Namun, sistem ini memiliki kelemahan:  
> Jika satu proses mengalami delay — misalnya sedang menunggu input dari pengguna, membaca file, atau menunggu respons jaringan — maka **seluruh program ikut berhenti** hingga proses tersebut selesai.

Hal ini tentunya mengurangi efisiensi, apalagi jika program dituntut menangani banyak tugas dalam waktu yang bersamaan. Meski demikian, model ini masih **relevan dan ideal** digunakan untuk program-program sederhana, skrip otomatisasi, atau sistem lama yang tidak membutuhkan performa tinggi.

📌 **Contoh Kasus Penggunaan:**
- Aplikasi kalkulator sederhana
- Program CLI (Command Line Interface)
- Sistem lama berbasis DOS

---

## 🟩 **Multithread**  
Berbeda dari single thread, **multithread** adalah metode eksekusi di mana sebuah program dapat memiliki **beberapa thread** yang berjalan **secara bersamaan (concurrently)** di dalam satu proses.

Setiap thread memiliki jalur eksekusi masing-masing dan dapat:  
✔ Menjalankan tugas yang berbeda  
✔ Bekerja sama menyelesaikan tugas besar  

Dengan sistem ini, program bisa menjadi **lebih cepat, efisien, dan responsif**. Hal ini sangat bermanfaat bagi aplikasi modern yang menangani banyak pekerjaan sekaligus (misalnya permintaan pengguna dalam jumlah besar).

Multithreading sangat efektif terutama bila dijalankan pada **prosesor multi-core**, karena bisa memproses beberapa thread secara paralel.

Namun, di balik performa yang meningkat, multithreading juga membawa tantangan baru:  
> Manajemen thread, kondisi balapan (race condition), dan deadlock adalah beberapa kompleksitas yang harus diatasi oleh programmer.

📌 **Contoh Kasus Penggunaan:**
- Web browser yang memuat banyak tab  
- Game dengan AI, rendering, dan audio berjalan bersamaan  
- Server aplikasi yang menangani banyak request client

---

## 🖼️ **Ilustrasi Visual**  

![Single vs Multi Thread](https://github.com/Rapprince29/SISOP-2025/blob/a82a6eeea0637607bbe0e4aa789fedf26af9b804/single%20thread%20multi%20thread.png)

---

> 🔍 **Kesimpulan:**  
Dalam dunia pemrograman modern, pemilihan antara single thread atau multithread sangat bergantung pada kebutuhan aplikasi dan sumber daya yang tersedia. Memahami kedua konsep ini sangat penting untuk membangun aplikasi yang efisien, scalable, dan mampu memenuhi kebutuhan pengguna dengan optimal.

