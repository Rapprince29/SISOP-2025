
# 🧵 Thread Programming Exercise

📚 **Sumber Referensi**: [osc10e - ch4 GitHub Repository](https://github.com/ferryastika/osc10e/tree/master/ch4)

---

## 🔢 a. Penerapan Thread pada `SumTask.java` (Java)

### 📘 Penjelasan

`SumTask.java` menggunakan pendekatan _multithreading_ di Java untuk melakukan operasi penjumlahan elemen array secara paralel. Kelas ini mengimplementasikan interface `Runnable`, memungkinkan tiap objeknya dijalankan sebagai thread terpisah.

Dengan membagi array menjadi beberapa bagian dan mengeksekusi penjumlahan di thread berbeda, program dapat memanfaatkan _multi-core processor_ secara efisien untuk meningkatkan performa komputasi.

### 🧩 Struktur Kode: `SumTask.java`

```java
public class SumTask implements Runnable {
    private int[] array;
    private int start;
    private int end;
    private int sum;

    public SumTask(int[] array, int start, int end) {
        this.array = array;
        this.start = start;
        this.end = end;
    }

    public int getSum() {
        return sum;
    }

    @Override
    public void run() {
        sum = 0;
        for (int i = start; i < end; i++) {
            sum += array[i];
        }
    }
}
```

### 🔍 Highlight Fitur:
- **`Runnable` Interface**: Menyediakan kemampuan dasar threading.
- **Pemrosesan Parsial**: Array dibagi berdasarkan indeks `start` dan `end`.
- **Akses Hasil**: Disediakan melalui metode `getSum()`.

---

## 🐧 b. Penerapan Thread di Linux dan Windows

### 1️⃣ Penerapan Thread di **Linux** (`thrd-posix.c`)

#### 📘 Penjelasan

File `thrd-posix.c` menggunakan **POSIX Threads (pthread)** yang merupakan API standar di lingkungan UNIX/Linux untuk membuat dan mengelola thread. Program ini:
- Membuat thread dengan `pthread_create()`
- Menunggu thread selesai dengan `pthread_join()`

### 🧩 Fitur Utama:
- **Multitasking Efisien**: Cocok untuk server dan aplikasi performa tinggi di Linux.
- **Portable**: Dapat dijalankan di berbagai distribusi UNIX/Linux.

---

### 2️⃣ Penerapan Thread di **Windows** (`thrd-win32.c`)

#### 📘 Penjelasan

File `thrd-win32.c` menggunakan **Win32 API** untuk membuat thread di sistem operasi Windows. Mekanismenya meliputi:
- Membuat thread menggunakan `CreateThread()`
- Menunggu penyelesaian dengan `WaitForSingleObject()`
- Membersihkan sumber daya dengan `CloseHandle()`

### 🧩 Fitur Utama:
- **Kontrol Lengkap**: Penggunaan API tingkat rendah memungkinkan pengelolaan memori dan proses yang lebih rinci.
- **Kompatibel dengan Windows OS**: Cocok untuk aplikasi desktop atau sistem operasi berbasis Windows.

---

## 🎯 Kesimpulan

Penggunaan thread, baik di Java, Linux (POSIX), maupun Windows (Win32), memberikan kemampuan **komputasi paralel** dan **optimasi performa** dalam aplikasi yang memerlukan eksekusi tugas secara bersamaan. Memahami berbagai pendekatan ini memungkinkan kita membangun software yang lebih cepat, efisien, dan scalable.

