# Pengolahan Data Kuantitatif

**Sumber:** Materi presentasi — Ratna, Workshop Jurnalistik Data  
**Tanggal di-wiki:** 17 Juni 2026

---

## Mengapa Wartawan Perlu Statistik?

Dua judul berita bisa menghasilkan cerita berbeda dari data yang sama:

- "Kasus Demam Berdarah Naik 50 Persen" ( jumlah kasus naik )
- "Tingkat Demam Berdarah Turun" ( persentase penduduk turun: 1% → 0,75% )

**Pelajaran:** Jumlah dan persentase bisa menghasilkan cerita yang berbeda. Jangan langsung percaya data — kenali dulu sumbernya.

---

## Jenis Data

### Data Primer
Data yang dikumpulkan langsung dari sumber pertama (responden, objek, atau peristiwa yang diteliti) untuk tujuan tertentu.

**Contoh:**
- Survei kuesioner kepada 500 pekerja tambang mengenai kekhawatiran PHK
- Wawancara 20 korban banjir untuk mengetahui kerugian
- Observasi lapangan: menghitung kendaraan yang melintas selama satu jam
- Eksperimen: menguji efektivitas metode pembelajaran baru

### Data Sekunder
Data yang telah dikumpulkan oleh pihak lain dan digunakan kembali untuk analisis yang berbeda.

**Contoh:** Data BPS, data kementerian

---

## Populasi vs Sampel

### Populasi
Seluruh kelompok yang ingin diketahui.  
Contoh: seluruh pemilih Indonesia ≈ 205 juta orang

### Sampel
Sebagian kecil yang mewakili populasi.  
Contoh: 1.200 responden survei

**Analogi sendok sup:**  
Untuk mengecek rasa satu panci besar (populasi), kita hanya butuh 1 sendok teh (sampel). Jika diambil dengan benar, bisa memperkirakan rasa seluruh panci. Jika diambil sembarangan — sebelum diaduk, dll — hasilnya bisa menyesatkan.

**Contoh:** Survei 1.200 responden di 38 provinsi, margin of error ±2,8% → bisa menggambarkan Indonesia, **jika sampel dipilih dengan benar.**

### Tanda Sampel Bermasalah
- ❌ Sampel terlalu kecil
- ❌ Tidak jelas cara memilih responden
- ❌ Hanya berasal dari satu kelompok tertentu
- ❌ Tidak ada penjelasan metodologi

**Kunci:** Bukan jumlah responden yang paling penting, tapi apakah sampel bisa mewakili populasi.

---

## Bias Data (Siapa yang Tidak Terlihat?)

| Sumber Data | Siapa yang Ketinggalan |
|---|---|
| Survei online | Lansia, orang tanpa internet, masyarakat daerah terpencil |
| Media sosial | Orang yang tidak aktif bermedia sosial, kelompok usia tertentu |
| Pencarian Google | Orang yang tidak menggunakan Google, kelompok akses internet terbatas |

**Pelajaran:** Siapa yang tidak masuk data justru bisa menjadi cerita unik dan melengkapi data.

---

## Sebelum Mengutip Data, Baca Metodologinya

Pertanyaan yang harus dijawab:
1. Siapa yang mengumpulkan data?
2. Kapan data dikumpulkan?
3. Berapa jumlah sampelnya?
4. Bagaimana cara mengumpulkannya?

**Contoh:** "70% masyarakat mendukung kebijakan X" → Survei siapa? Kapan? Berapa responden? Wawancara tatap muka atau online?

---

## Jenis Data (Level Pengukuran)

| Jenis | Keterangan | Contoh |
|---|---|---|
| **Nominal** | Kategori tanpa urutan | Provinsi, jenis kelamin, agama |
| **Ordinal** | Kategori dengan tingkatan | Sangat puas → Puas → Netral → Tidak puas |
| **Interval** | Urutan + jarak sama | Suhu Celsius |
| **Rasio** | Bisa diolah operasi matematika | Pendapatan, jumlah penduduk, jumlah kasus, anggaran |

**Data rasio** adalah jenis paling "fleksibel" untuk dianalisis — bisa dihitung, dibandingkan, dicari rata-ratanya, dan diukur pertumbuhannya.

---

## 5 Statistik Dasar untuk Jurnalis

### 1. Mean (Rata-rata)
Jumlah seluruh nilai dibagi banyaknya data.  
**Catatan:** Rata-rata bisa menyesatkan jika ada outlier (nilai sangat tinggi/rendah).  
**Contoh:** Rata-rata pendapatan daerah Rp 10 juta/bulan — belum tentu sebagian besar berpenghasilan Rp 10 juta.  
**Excel:** `=AVERAGE(...)`

### 2. Median (Nilai Tengah)
Nilai di tengah setelah data diurutkan. Lebih mewakili mayoritas dibanding mean.  
**Contoh:** Median pendapatan Rp 4 juta → separuh di bawah, separuh di atas.  
**Excel:** `=MEDIAN(...)`

### 3. Persentase/Proporsi
Proporsi bagian dari keseluruhan. Membantu membandingkan kelompok berbeda ukuran.  
**Contoh:** 100 kasus di kota 10.000 orang vs 100 kasus di kota 1 juta orang — berbeda maknanya.  
**Rumus:** Angka bagian ÷ total

### 4. Growth (Pertumbuhan)
Seberapa besar perubahan angka dibanding periode sebelumnya.  
**Contoh:** Wisatawan naik dari 1 juta → 1,2 juta = pertumbuhan 20%.  
**Rumus:** `(X₁ - X₀) × 100 / X₀`

### 5. Outlier (Nilai Ekstrem)
Data yang jauh berbeda dari sebagian besar data lainnya. Sering jadi petunjuk awal masalah atau anomali menarik.  
**Contoh:** Sebagian besar kabupaten naik 5–10%, tapi satu kabupaten lonjak 200% → layak ditelusuri.

**Ketika melihat data, tanyakan:**
- Apa yang berubah paling cepat?
- Siapa/apa yang paling berbeda?
- Adakah angka yang tidak biasa?
- Mengapa hal itu terjadi?

> "Sering kali, cerita terbaik justru tersembunyi di balik angka yang paling menyimpang dari pola."

---

## Margin of Error (MOE)

Tingkat ketidakpastian dalam hasil survei akibat hanya mewawancarai sebagian kecil populasi.

**Contoh:**  
- A = 48%, B = 50%, MOE = ±3%
- A bisa 45–51%, B bisa 47–53%
- Selisih 2 poin < MOE ±3 → **belum bisa disimpulkan siapa unggul**

**Patokan MOE:**
- ±5% — Presisi rendah
- ±3% — Umum digunakan survei nasional
- ±2% — Presisi cukup tinggi
- ±1% — Sangat presisi, butuh sampel besar

**Kesimpulan:** MOE bukan menunjukkan survei benar/salah, tapi seberapa jauh hasil mungkin berbeda dari kondisi sebenarnya.

---

## Pivot Table — Mesin Pencari Cerita dalam Data

Pivot table adalah fitur Excel untuk "memutar" sudut pandang data — data yang sama bisa dilihat dari berbagai sisi.

**Empat area utama:**
- **Rows (baris):** Apa yang ingin dikelompokkan
- **Values (nilai):** Apa yang ingin dihitung
- **Columns (kolom):** Membandingkan kategori
- **Filters (penyaring):** Menampilkan data tertentu

**Contoh:**  
Rows = Provinsi, Values = Sum of Jumlah Kasus, Columns = Jenis Penyakit  
→ Langsung terlihat provinsi mana yang kasusnya tertinggi/terendah

---

## Visualisasi Data

Bukan sekadar mempercantik — ada fungsi lainnya. Biasanya ada 5 kemungkinan visualisasi tergantung apa yang mau dijelaskan.

**Yang harus dihindari:**
- Grafik yang menyesatkan (skala tidak konsisten, axis dipotong)
- Terlalu banyak warna/format yang membingungkan

**Cek grafik Anda:**
- Apakah representasi data sudah akurat?
- Apakah mudah dipahami pembaca?

---

## Kesimpulan

> "Data adalah bahan baku. Statistik membantu kita memahaminya. Jurnalisme membuatnya bermakna."

> "Statistik bukan untuk menghitung lebih banyak angka, melainkan menghasilkan cerita yang lebih akurat, lebih adil, dan lebih bermakna."
