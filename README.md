# Tugas 3 - Pengolahan Citra Digital

## Segmentasi Citra dengan Thresholding

**Nama:** Gibran Wicaksono  
**NIM:** 24260048

### Deskripsi
Proyek ini menerapkan metode *thresholding* untuk mengubah citra grayscale menjadi citra biner yang hanya memiliki dua nilai intensitas, yaitu hitam (0) dan putih (255).

### Teknologi
- Python
- Jupyter Notebook
- NumPy
- Pillow
- Matplotlib

### Metode
Thresholding menggunakan nilai ambang (*threshold*) sebesar 128.

- Piksel dengan intensitas kurang dari 128 diubah menjadi hitam (0).
- Piksel dengan intensitas sama dengan atau lebih dari 128 diubah menjadi putih (255).

### Struktur Proyek
```text
PCD2/
├── Tugas2.ipynb
├── foto.jpg
├── README.md
└── hasil_thresholding/
    ├── citra_grayscale.png
    └── citra_biner.png
```

### Cara Menjalankan
1. Buka `Tugas3_Thresholding.ipynb` di VS Code.
2. Pastikan Python dan library yang dibutuhkan sudah tersedia.
3. Letakkan foto input di folder yang sama dengan notebook.
4. Sesuaikan nama file foto pada kode.
5. Jalankan setiap cell dari atas ke bawah.
6. Periksa hasil citra grayscale, citra biner, dan histogram.

### Instalasi Library
Jalankan perintah berikut di terminal:

```bash
python -m pip install numpy pillow matplotlib
```

### Hasil
Program menghasilkan:
- Citra grayscale.
- Citra biner hasil thresholding.
- Histogram sebelum dan sesudah thresholding.
- Informasi jumlah tingkat intensitas piksel.

### Kesimpulan
Metode thresholding dapat menyederhanakan citra grayscale menjadi citra biner berdasarkan nilai ambang tertentu. Citra grayscale dapat memiliki hingga 256 tingkat intensitas, sedangkan citra biner menggunakan maksimal dua tingkat intensitas, yaitu 0 dan 255.

---

**Mata Kuliah:** Pengolahan Citra Digital (PCD)