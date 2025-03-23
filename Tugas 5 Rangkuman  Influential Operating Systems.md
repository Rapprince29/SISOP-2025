# Rangkuman Sistem Operasi yang Berpengaruh

---

## A.1 Migrasi Fitur
- **Migrasi Fitur**: Fitur yang awalnya hanya ada di sistem besar (mainframe) akhirnya diadopsi oleh sistem yang lebih kecil (microcomputer). Ini menunjukkan bagaimana konsep yang awalnya dirancang untuk sistem besar dapat diterapkan pada sistem yang lebih kecil seiring dengan perkembangan teknologi.
- **Contoh**: MULTICS, sistem operasi yang dikembangkan pada 1960-an, mempengaruhi perkembangan sistem operasi modern seperti UNIX. MULTICS memperkenalkan konsep seperti proteksi berbasis ring dan sistem file hierarkis, yang kemudian diadopsi oleh sistem operasi modern.

---

## A.2 Sistem Awal
- **Sistem Dedikasi**: Pada awal perkembangan komputer, programmer juga berperan sebagai operator. Mereka harus memuat program secara manual ke dalam memori menggunakan panel depan, pita kertas, atau kartu berlubang. Program kemudian dijalankan dan dimonitor melalui lampu display di konsol.
- **Sistem Berbagi**: Untuk meningkatkan efisiensi, operator profesional diperkenalkan. Operator ini memiliki pengalaman lebih dalam mengelola sistem, sehingga mengurangi waktu setup. Selain itu, pekerjaan dengan kebutuhan serupa dikelompokkan (batching) untuk mengurangi waktu setup.
- **I/O Tumpang Tindih**: Untuk mengatasi masalah kecepatan I/O yang lambat, tape magnetik digunakan sebagai perantara antara perangkat input/output (seperti pembaca kartu dan printer) dengan CPU. Ini memungkinkan CPU untuk bekerja lebih efisien tanpa harus menunggu perangkat I/O yang lambat.

---

## A.3 Atlas
- **Atlas**: Dikembangkan di Universitas Manchester pada akhir 1950-an, Atlas adalah salah satu sistem operasi pertama yang menggunakan manajemen memori dengan paging.
- **Fitur Utama**: 
  - **Spooling**: Atlas menggunakan spooling untuk menjadwalkan pekerjaan berdasarkan ketersediaan perangkat periferal.
  - **Manajemen Memori**: Atlas menggunakan drum sebagai memori utama dan sejumlah kecil memori inti sebagai cache. Sistem ini juga menggunakan demand paging untuk mentransfer informasi antara memori inti dan drum secara otomatis.

---

## A.4 XDS-940
- **XDS-940**: Sistem operasi time-sharing yang dikembangkan di UC Berkeley pada awal 1960-an.
- **Fitur Utama**: 
  - **Paging**: XDS-940 menggunakan paging untuk relokasi, meskipun tidak menggunakan demand paging.
  - **Time-Sharing**: Sistem ini memungkinkan beberapa pengguna untuk berbagi sumber daya komputer secara bersamaan.

---

## A.5 THE
- **THE**: Dikembangkan di Technische Hogeschool Eindhoven pada pertengahan 1960-an.
- **Fitur Utama**: 
  - **Struktur Lapisan**: THE memiliki desain yang bersih dengan struktur lapisan yang jelas.
  - **Sinkronisasi Proses**: Sistem ini menggunakan semaphore untuk sinkronisasi proses.
  - **Deadlock Control**: THE menggunakan algoritma banker untuk menghindari deadlock.

---

## A.6 RC 4000
- **RC 4000**: Dikembangkan oleh Brinch-Hansen pada akhir 1960-an.
- **Fitur Utama**: 
  - **Kernel**: RC 4000 dirancang sebagai kernel yang dapat digunakan untuk membangun sistem operasi lengkap.
  - **Sistem Pesan**: Komunikasi antar proses dilakukan melalui sistem pesan, yang disimpan dalam buffer dari pool buffer umum.

---

## A.7 CTSS
- **CTSS**: Sistem time-sharing eksperimental yang dikembangkan di MIT pada 1961.
- **Fitur Utama**: 
  - **Multilevel Feedback Queue**: CTSS menggunakan algoritma penjadwalan CPU dengan multilevel feedback queue untuk mengelola waktu CPU yang diberikan kepada setiap pengguna.
  - **Swapping**: Memori pengguna ditukar antara memori utama dan drum yang cepat.

---

## A.8 MULTICS
- **MULTICS**: Dikembangkan oleh MIT, GE, dan Bell Labs dari 1965 hingga 1970.
- **Fitur Utama**: 
  - **Sistem File Hierarkis**: MULTICS memperkenalkan sistem file hierarkis yang memungkinkan pengguna untuk membuat struktur direktori mereka sendiri.
  - **Proteksi Berbasis Ring**: Sistem ini menggunakan proteksi berbasis ring untuk mengontrol akses ke sumber daya sistem.

---

## A.9 IBM OS/360
- **OS/360**: Dikembangkan oleh IBM pada pertengahan 1960-an.
- **Fitur Utama**: 
  - **Keluarga Komputer**: OS/360 dirancang untuk keluarga komputer IBM/360, yang mencakup berbagai ukuran dan kemampuan.
  - **Kompleksitas**: OS/360 mencoba untuk menjadi sistem operasi yang serbaguna, tetapi mengalami masalah kompleksitas dan performa.

---

## A.10 TOPS-20
- **TOPS-20**: Dikembangkan oleh DEC pada 1970-an.
- **Fitur Utama**: 
  - **Manajemen Memori Virtual**: TOPS-20 menggunakan manajemen memori virtual untuk meningkatkan efisiensi penggunaan memori.
  - **Time-Sharing**: Sistem ini dirancang untuk mendukung banyak pengguna secara bersamaan.

---

## A.11 CP/M dan MS-DOS
- **CP/M**: Sistem operasi awal untuk komputer mikro yang dikembangkan oleh Gary Kildall.
- **MS-DOS**: Dikembangkan oleh Microsoft untuk IBM PC, menjadi sistem operasi dominan pada 1980-an.
- **Fitur Utama**: 
  - **Kemudahan Penggunaan**: MS-DOS memiliki set perintah yang lebih kaya dibandingkan CP/M, membuatnya lebih mudah digunakan.

---

## A.12 Macintosh Operating System dan Windows
- **Mac OS**: Sistem operasi dengan antarmuka grafis (GUI) yang dirilis pada 1984.
- **Windows**: Sistem operasi yang dikembangkan oleh Microsoft, menjadi pesaing utama Mac OS.
- **Fitur Utama**: 
  - **Antarmuka Grafis**: Kedua sistem operasi ini memperkenalkan antarmuka grafis yang memudahkan pengguna untuk berinteraksi dengan komputer.

---

## A.13 Mach
- **Mach**: Dikembangkan di Carnegie Mellon University pada 1980-an.
- **Fitur Utama**: 
  - **Kernel Mikro**: Mach dirancang sebagai kernel mikro yang mendukung multiprosesor dan komunikasi berbasis pesan.
  - **Kompatibilitas dengan UNIX**: Mach dirancang untuk meniru 4.3 BSD UNIX, memungkinkan file executable dari sistem UNIX untuk berjalan di Mach.

---

## A.14 Sistem Berbasis Kemampuan (Capability-based Systems)
- **Hydra**: Sistem proteksi berbasis kemampuan yang fleksibel, memungkinkan pengguna untuk mendefinisikan hak akses mereka sendiri.
- **CAP**: Sistem proteksi berbasis kemampuan yang lebih sederhana dibandingkan Hydra, tetapi masih dapat digunakan untuk melindungi objek yang didefinisikan oleh pengguna.

---

## A.15 Sistem Lainnya
- **MCP dan SCOPE**: Sistem operasi awal yang mendukung multiprosesor dan memiliki desain yang baik untuk koordinasi dan sinkronisasi proses.

---

# Timeline Sistem Operasi yang Berpengaruh

Berikut adalah timeline perkembangan sistem operasi yang memiliki pengaruh besar dalam sejarah teknologi komputer:

| Tahun | Sistem Operasi          | Deskripsi Singkat                                                                 |
|-------|-------------------------|-----------------------------------------------------------------------------------|
| 1949  | Manchester Mark 1       | Komputer stored-program pertama yang berhasil dijalankan.                         |
| 1951  | Ferranti Mark 1         | Komputer komersial pertama.                                                       |
| 1961  | CTSS                    | Sistem time-sharing eksperimental pertama di MIT.                                 |
| 1962  | XDS-940                 | Sistem time-sharing dengan paging untuk relokasi.                                 |
| 1965  | MULTICS                 | Sistem operasi time-sharing dengan sistem file hierarkis.                         |
| 1966  | THE                     | Sistem batch dengan struktur lapisan dan semaphore untuk sinkronisasi.            |
| 1969  | UNIX                    | Dikembangkan oleh Bell Labs, menjadi dasar banyak sistem operasi modern.          |
| 1970  | TOPS-20                 | Sistem time-sharing dengan manajemen memori virtual.                              |
| 1974  | CP/M                    | Sistem operasi untuk komputer mikro.                                              |
| 1981  | MS-DOS                  | Sistem operasi untuk IBM PC, menjadi dominan pada 1980-an.                        |
| 1984  | Mac OS                  | Sistem operasi dengan antarmuka grafis untuk Macintosh.                           |
| 1985  | Windows 1.0             | Versi pertama Microsoft Windows.                                                  |
| 1987  | Mach                    | Kernel mikro yang mendukung multiprosesor dan komunikasi berbasis pesan.          |
| 1991  | Linux                   | Sistem operasi open-source yang dikembangkan oleh Linus Torvalds.                |
| 2000  | Windows 2000            | Versi Windows yang ditujukan untuk pasar bisnis.                                  |
| 2001  | macOS X                 | Sistem operasi Apple yang berbasis UNIX.                                          |

---

## Penjelasan Timeline

### 1949: Manchester Mark 1
- **Manchester Mark 1**: Komputer stored-program pertama yang berhasil dijalankan. Ini adalah langkah penting dalam evolusi komputer modern, di mana program dan data disimpan dalam memori yang sama.

### 1951: Ferranti Mark 1
- **Ferranti Mark 1**: Komputer komersial pertama yang dijual ke publik. Ini adalah turunan dari Manchester Mark 1 dan menjadi salah satu komputer pertama yang digunakan untuk aplikasi bisnis.

### 1961: CTSS
- **CTSS (Compatible Time-Sharing System)**: Sistem time-sharing eksperimental pertama yang dikembangkan di MIT. CTSS memungkinkan beberapa pengguna untuk berbagi sumber daya komputer secara bersamaan.

### 1962: XDS-940
- **XDS-940**: Sistem operasi time-sharing yang dikembangkan di UC Berkeley. Sistem ini menggunakan paging untuk relokasi memori dan mendukung beberapa pengguna secara bersamaan.

### 1965: MULTICS
- **MULTICS**: Dikembangkan oleh MIT, GE, dan Bell Labs, MULTICS adalah sistem operasi time-sharing yang memperkenalkan konsep seperti proteksi berbasis ring dan sistem file hierarkis.

### 1966: THE
- **THE**: Dikembangkan di Technische Hogeschool Eindhoven, THE adalah sistem operasi batch dengan struktur lapisan yang bersih dan menggunakan semaphore untuk sinkronisasi proses.

### 1969: UNIX
- **UNIX**: Dikembangkan oleh Bell Labs, UNIX menjadi dasar bagi banyak sistem operasi modern seperti Linux dan macOS. UNIX memperkenalkan konsep seperti shell, file system hierarkis, dan multitasking.

### 1970: TOPS-20
- **TOPS-20**: Dikembangkan oleh DEC, TOPS-20 adalah sistem operasi time-sharing dengan manajemen memori virtual. Sistem ini populer di kalangan pengguna komputer besar.

### 1974: CP/M
- **CP/M (Control Program/Monitor)**: Sistem operasi awal untuk komputer mikro yang dikembangkan oleh Gary Kildall. CP/M menjadi standar de facto untuk komputer mikro pada masanya.

### 1981: MS-DOS
- **MS-DOS**: Dikembangkan oleh Microsoft untuk IBM PC, MS-DOS menjadi sistem operasi dominan pada 1980-an. MS-DOS adalah sistem operasi berbasis teks yang digunakan di komputer pribadi awal.

### 1984: Mac OS
- **Mac OS**: Sistem operasi dengan antarmuka grafis (GUI) yang dirilis oleh Apple untuk Macintosh. Mac OS memperkenalkan konsep seperti desktop, ikon, dan mouse.

### 1985: Windows 1.0
- **Windows 1.0**: Versi pertama Microsoft Windows, yang memperkenalkan antarmuka grafis berbasis jendela (windows) untuk PC. Windows menjadi pesaing utama Mac OS.

### 1987: Mach
- **Mach**: Kernel mikro yang dikembangkan di Carnegie Mellon University. Mach dirancang untuk mendukung multiprosesor dan komunikasi berbasis pesan, serta kompatibel dengan UNIX.

### 1991: Linux
- **Linux**: Sistem operasi open-source yang dikembangkan oleh Linus Torvalds. Linux menjadi sangat populer di kalangan pengembang dan server, serta menjadi dasar bagi banyak distribusi seperti Ubuntu dan Fedora.

### 2000: Windows 2000
- **Windows 2000**: Versi Windows yang ditujukan untuk pasar bisnis. Windows 2000 memperkenalkan fitur-fitur seperti Active Directory dan dukungan untuk sistem file NTFS.

### 2001: macOS X
- **macOS X**: Sistem operasi Apple yang berbasis UNIX. macOS X menggabungkan antarmuka grafis yang ramah pengguna dengan kekuatan dan stabilitas sistem operasi UNIX.
