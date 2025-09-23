# 📌 Proyek SCRAPING-DATA-SEKOLAH  

Proyek ini merupakan **bagian pertama** dari lima tahap utama inisiatif **SKYLEARN**:  

1. **SCRAPING-DATA-SEKOLAH**  
2. **SCRAPING-CITRA-SATELIT**  
3. **CLUSTERING-SEKOLAH**  
4. **KLASIFIKASI-SEKOLAH**  
5. **DEPLOYMENT**  

---

## 🎯 Tujuan  

Tujuan dari **SCRAPING-DATA-SEKOLAH** adalah menyiapkan **data sekolah Indonesia yang valid dan lengkap** dari website resmi Kemendikbud  
👉 [https://sekolah.data.kemendikdasmen.go.id/](https://sekolah.data.kemendikdasmen.go.id/)  

Data ini nantinya akan digunakan dalam proses lanjutan proyek **SKYLEARN**, seperti:  
- Scraping data pendukung (**Citra Satelit**) melalui Google Maps  
- Analisis clustering sekolah  
- Klasifikasi sekolah berbasis machine learning  
- Deployment model dan aplikasi  

---

## 📂 Struktur Folder  

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
│ └── gambar/                   # Dokumentasi gambar untuk notebook
```

---

## 📝 Keterangan  

- **data/** → berisi catatan mengenai **asal dan penggunaan data**.  
- **hasil/** → menyimpan output scraping:  
  - `data_halaman/` → hasil scraping halaman Kemendikbud (CSV).  
  - `data_profil/` → hasil scraping profil sekolah (JSON).  
- **notebooks/** → notebook utama untuk scraping.  
- **dummy/** → file HTML contoh untuk **pengujian fungsi scraping**.  
- **gambar/** → ilustrasi/dokumentasi yang mendukung penjelasan notebook.  

---

## 🤝 Kolaborasi  

Proyek ini dikerjakan secara kolaboratif dalam rangka inisiatif **SKYLEARN**.  

### 👥 Kontributor  
- 🌟 **Algae Desma Fridasary** — *Ketua Tim & Visioner Utama*  
  Pemilik ide dan penggerak utama proyek. Berfokus pada penulisan artikel ilmiah serta deployment sistem.  

- 🎓 **Sabrina Aziz Aulia** — *Mentor & Spesialis Komputasi*  
  Memberikan arahan strategis dan pendampingan teknis, terutama dalam aspek komputasi dan pemodelan data.  

---

## 📢 Kontribusi  

Kami sangat terbuka untuk kontribusi dari komunitas!  
- Buat **issue** untuk melaporkan bug atau memberikan ide.  
- Ajukan **pull request** jika ingin menambahkan fitur atau perbaikan.  

> Mari bersama-sama membangun ekosistem data sekolah Indonesia yang lebih terbuka, rapi, dan bermanfaat 🚀  


