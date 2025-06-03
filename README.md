# detect_healt_grape

# Deteksi Kesehatan Anggur (`detect_healt_grepe`)

Proyek ini menggunakan model YOLOv8 terlatih (`best.pt`) untuk mendeteksi kesehatan daun buah anggur dari gambar. Program utama dijalankan melalui `main.py`, dan gambar uji coba dapat berupa file seperti `image.jpg`.


![daun_anggur](https://github.com/user-attachments/assets/583e6184-7f34-4325-8b82-7258f3d94061)


![image](https://github.com/user-attachments/assets/703c8287-efbc-4dce-a462-088469cb5091)

Catatan Penting
📌 Pastikan Anda mengatur path (direktori) file dengan benar di dalam main.py.
Ubah bagian berikut di main.py sesuai dengan lokasi sebenarnya dari file best.pt dan image.jpg. Contoh:

Gantilah "path/ke/folder/" dengan path asli di komputer Anda, misalnya:
"C:/Users/Username/Documents/detect_healt_grepe/best.pt"


## Kebutuhan

- Python 3.8 atau lebih baru
- Library yang diperlukan:
  - `ultralytics` (YOLOv8)
  - `opencv-python`
  - `torch`

### Instalasi Paket yang Diperlukan

```bash
pip install ultralytics opencv-python torch





