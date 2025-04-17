## TUGAS SISTEM BILANGAN

**Nama:** Muhammad Yoga Ananda Satria  
**NRP:** 3124500036  
**Dosen Pengajar:** Dr. Ferry Astika Saputra ST, M.Sc  
**Program Studi:** D3 Teknik Informatika  
**Institusi:** Politeknik Elektronika Negeri Surabaya (PENS)  
**Tahun:** 2025  

---

# Konsep Single Thread dan Multithread

## Single Thread

Single thread adalah model eksekusi program di mana hanya terdapat satu jalur eksekusi instruksi yang berjalan secara berurutan dari awal hingga akhir. Dalam sistem ini, setiap tugas atau proses dilakukan satu per satu. Jika suatu proses membutuhkan waktu tunggu, seperti menunggu input dari pengguna atau akses file, maka seluruh program akan berhenti sampai proses tersebut selesai. Hal ini membuat single thread menjadi kurang efisien, terutama pada aplikasi yang membutuhkan banyak proses secara simultan. Contoh penggunaannya biasa ditemukan pada program sederhana atau sistem lama yang tidak memerlukan performa tinggi.

## Multithread

Multithread, di sisi lain, memungkinkan program menjalankan beberapa jalur eksekusi (thread) secara bersamaan dalam satu proses. Setiap thread dapat menjalankan tugas yang berbeda atau saling berbagi kerja dari satu tugas besar, yang membuat program menjadi lebih responsif dan efisien. Multithreading sering digunakan pada aplikasi modern seperti browser, game, atau server yang menangani banyak permintaan secara bersamaan. Dengan memanfaatkan kemampuan prosesor multi-core, multithreading dapat meningkatkan performa aplikasi secara signifikan, walaupun juga menambah kompleksitas pengelolaan thread.

## Ilustrasi

![](https://github.com/Rapprince29/SISOP-2025/blob/a82a6eeea0637607bbe0e4aa789fedf26af9b804/single%20thread%20multi%20thread.png)
