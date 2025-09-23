# Proyek SCRAPING-DATA-SEKOLAH

Proyek ini adalah bagian pertama dari 5 bagian utama proyek **SKYLEARN**:

1. **SCRAPING-DATA-SEKOLAH**  
2. **SCRAPING-GOOGLE MAPS**  
3. **CLUSTERING-SEKOLAH**  
4. **KLASIFIKASI-SEKOLAH**  
5. **DEPLOYMENT**  

### Tujuan

Tujuan dari **SCRAPING-DATA-SEKOLAH** adalah menyiapkan **data sekolah Indonesia yang valid dan lengkap** dari website resmi Kemendikbud ([https://sekolah.data.kemendikdasmen.go.id/](https://sekolah.data.kemendikdasmen.go.id/)) sehingga dapat digunakan untuk **proses selanjutnya** dalam proyek SKYLEARN, seperti scraping Google Maps, clustering, dan klasifikasi sekolah.

### Struktur Folder

```
SCRAPING-DATA-SEKOLAH/
├── data/
│ └── README.md                 # Catatan sumber data
├── hasil/
│ ├── data_halaman/             # Hasil scraping halaman Kemendikbud (CSV)
│ │ └── sma/
│ ├── data_profil/              # Hasil scraping profil sekolah (JSON)
│ │ └── sma/
├── notebooks/
│ ├── 1_scraping_halaman.ipynb  # Notebook untuk scraping halaman
│ ├── 2_scraping_profil.ipynb   # Notebook untuk scraping profil sekolah
│ ├── dummy/                    # Contoh file HTML untuk testing
│ └── gambar/                   # Untuk kepentingan gambar di dalam notebook
```

### Keterangan

- **data/** → berisi catatan mengenai **asal dan penggunaan data**.  
- **hasil/** → menyimpan output scraping:  
  - `data_halaman/` → CSV hasil scraping halaman Kemendikbud.  
  - `data_profil/` → JSON hasil scraping profil sekolah.  
- **notebooks/** → notebook untuk scraping.  
- **dummy/** → file HTML contoh untuk **testing fungsi scraping**.  

- **gambar/** → gambar ilustrasi dari fungsi-fungsi scraping, membantu dokumentasi dan penjelasan alur.

### 🤝 Kolaborasi

Proyek ini dikerjakan secara kolaboratif sebagai bagian dari inisiatif **SKYLEARN**.  

**Kontributor:**  
- 🌟 **Algae Desma Fridasary** — *Ketua Tim & Visioner Utama*  
  Pemilik ide, penggerak utama proyek, berfokus pada penulisan artikel ilmiah dan deployment sistem.  

- 🎓 **Sabrina Aziz Aulia** — *Mentor & Spesialis Komputasi*  
  Memberikan arahan strategis serta pendampingan teknis, terutama pada aspek komputasi dan pemodelan data.

Kontribusi tambahan sangat terbuka!  
Silakan buat *issue* atau *pull request* jika ingin berpartisipasi.
