
# Proyek Hand Tracking Menggunakan Python

Proyek **Hand Tracking** ini menggunakan Python untuk mendeteksi dan melacak posisi tangan secara real-time melalui webcam atau video input. Proyek ini cocok untuk aplikasi interaksi manusia-komputer (HCI), game berbasis gerakan, kontrol gestur, dan berbagai aplikasi yang memerlukan pelacakan tangan.

## Fitur

### 1. **Deteksi Tangan**
   - Deteksi tangan secara real-time menggunakan model machine learning.
   - Penentuan posisi landmark utama di tangan seperti jari dan pergelangan tangan.

### 2. **Pelacakan Gerakan**
   - Pelacakan gerakan tangan dengan frame rate tinggi.
   - Melacak posisi jari, posisi telapak tangan, dan arah gerakan.

### 3. **Gestur Tangan**
   - Deteksi berbagai gestur tangan seperti jempol ke atas, jari menunjuk, dan tanda OK.
   - Memungkinkan kustomisasi untuk mendeteksi gestur tertentu yang dibutuhkan oleh aplikasi.

### 4. **Integrasi Webcam**
   - Menggunakan webcam sebagai input untuk pelacakan tangan secara langsung.
   - Mendukung input video untuk analisis pasca proses.

### 5. **Interaksi Real-Time**
   - Menghubungkan hasil pelacakan tangan dengan aplikasi lain untuk interaksi real-time.
   - Cocok untuk kontrol berbasis gerakan atau antarmuka virtual tanpa sentuhan.

## Persyaratan

- Python 3.x
- OpenCV (untuk menangkap video dan gambar dari webcam)
- MediaPipe (untuk deteksi dan pelacakan tangan)
- NumPy (untuk pemrosesan array dan data gambar)

## Instalasi

1. **Clone Repositori:**
   ```bash
   git clone https://github.com/username/hand-tracking-python.git
   cd hand-tracking-python
   ```

2. **Install Dependencies:**
   Anda dapat menginstal pustaka yang diperlukan dengan perintah berikut:
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Jalankan Program:**
   Setelah dependensi terinstal, jalankan skrip utama untuk mulai melacak tangan:
   ```bash
   python hand_tracking.py
   ```

## Penggunaan

Setelah program dijalankan, webcam akan terbuka dan mendeteksi tangan secara otomatis. Pada tampilan video, Anda akan melihat titik-titik landmark pada jari dan telapak tangan yang dihasilkan oleh model deteksi.

Anda bisa menyesuaikan kode untuk mendeteksi gestur tertentu atau untuk menghubungkan pelacakan tangan dengan aplikasi lain seperti game atau antarmuka virtual.

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori ini, buat fitur baru di branch terpisah, dan kirimkan pull request.

## Lisensi

Proyek ini dilisensikan di bawah MIT License. Silakan baca berkas `LICENSE` untuk detail lebih lanjut.
