# Pengantar Jurnalisme Data

**Sumber:** Presentasi Haris Firdaus (Jurnalis Harian Kompas)  
**Tanggal ekstrak:** 6 Juli 2026  
**File:** Pengantar_Jurnalisme_Data.pdf

## Definisi Jurnalisme Data

Menurut **Giannina Segnini** (Columbia University):  
> “Data journalism is using data as a tool to find relevant stories. Data is the service of journalism and not the other way around.”

**Definisi lain:**  
Jurnalisme Data adalah proses jurnalistik yang **digerakkan oleh data** atau menggunakan data sebagai bagian **utama/penting** dalam proses jurnalistik.

### Perbedaan Tingkat Penggunaan Data

| Tipe | Keterangan | Contoh Alur |
|------|----------|-----------|
| **Data sebagai Cerita Utama** | Data menjadi pengarah/penggerak utama liputan. Jurnalis sering mulai dari data, lalu menemukan cerita. | Mencari data → menemukan ide liputan |
| **Data sebagai Pelengkap Cerita** | Data digunakan untuk memperkaya atau mendukung temuan reportase. | Ide liputan dulu → cari data pendukung |

## Alur Kerja Jurnalisme Data

### Alur 1 (Data-driven)
1. Mencari Data
2. Menganalisis Data
3. Menemukan Ide Liputan
4. Melakukan Reportase & Wawancara
5. Menulis Laporan + Visualisasi Data

### Alur 2 (Story-driven)
1. Menentukan Ide Liputan
2. Mencari Data yang Relevan
3. Menganalisis Data
4. Melakukan Reportase & Wawancara
5. Menulis Laporan + Visualisasi Data

## Cara Mencari Data

1. **Google Searching** dengan teknik advanced:
   - Gunakan tanda kutip (`""`) untuk frase persis
   - Gunakan `-` untuk exclude kata
   - Gunakan `site:` untuk batasi website tertentu
   - Gunakan `filetype:` untuk format tertentu (pdf, xlsx, csv, dll)

2. **Download dari sumber resmi**:
   - Website BPS
   - Website Covid-19
   - Website LSM nasional & internasional

3. **Web Scraping**  
   Teknik mengambil data secara otomatis dari website. Tools: Dataminer.io, Scrapy, Octoparse, ImportHTML di Google Sheets.

**Contoh ImportHTML Google Sheets:**
``` 
=IMPORTHTML("https://id.wikipedia.org/wiki/Daftar_rumah_sakit_di_Kota_Semarang", "table", 1)
```

## Pembersihan & Analisis Data

Tools paling umum & sederhana:
- Microsoft Excel
- Google Sheets

Tools lain:
- OpenRefine (cleaning)
- Tableau
- Microsoft Power BI (analisis kompleks)

## Visualisasi Data

Gunakan tools **no-code** untuk membuat visualisasi interaktif yang mudah dipahami pembaca:
- **Flourish**
- **Datawrapper**

Tujuan: Membantu pembaca memahami data dengan lebih baik.

---

**Catatan:** Ini adalah materi pengantar yang sangat baik untuk jurnalis pemula. Fokus utamanya adalah menempatkan **data sebagai alat bantu jurnalisme**, bukan tujuan akhir.

Mau aku tambahkan contoh kasus nyata, template alur kerja, atau buat versi yang lebih pendek untuk wiki?