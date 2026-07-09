# Pengolahan Data Kuantitatif

**Sumber:** Materi presentasi — Ratna Sri Widyastuti (Program Wartawan Specialist 2026), Jakarta, 17 Juni 2026  
**File sumber:** `04_Pengolahan_Data_Kuantitatif_Ratna_Sri_W---d72a4b8e-d40b-44f6-8551-1d8af2481ffb.pdf`  
**Tanggal di-wiki:** 17 Juni 2026  
**Update:** 9 Juli 2026 — tambah 5 pertanyaan konteks, framework Menemukan Pola (ranking/gap/tren/korelasi), & 5 jenis visualisasi data

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

## 5 Pertanyaan Sebelum Percaya Angka

Setiap angka butuh konteks. Sebelum menulis, tanyakan:

1. **Dibandingkan dengan apa?** — 100 kasus itu banyak atau sedikit? Harus dibandingkan dengan sesuatu supaya "bunyi".
2. **Dibandingkan dengan kapan?** — 100 kasus tahun ini, tahun lalu berapa?
3. **Dibandingkan dengan di mana?** — 100 kasus di Kota A, kota/daerah lain berapa? Seperti apa?
4. **Dalam proporsi berapa?** — 100 kasus dari 1.000 orang vs 100 kasus dari 1 juta orang → artinya sangat berbeda.
5. **Apakah masuk akal?** — Misalnya pengangguran turun dari 10% menjadi 0% → aneh, perlu dicek.

> Angka tunggal jarang bercerita. Kekuatan angka ada pada perbandingannya.

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

## Menemukan Pola dalam Data

Statistik dalam jurnalisme bukan terutama soal menghitung angka. **Statistik adalah cara menemukan pola yang layak menjadi cerita.**

Dari satu set data (misal: jumlah kasus DBD per provinsi), ajukan 4 pertanyaan pola:

### 1. Ranking — Siapa tertinggi & terendah?
Provinsi mana yang kasusnya paling tinggi, dan mana yang paling rendah?

### 2. Gap — Seberapa besar perbedaannya?
Contoh: kemiskinan di provinsi A lima kali lebih banyak dibanding provinsi B.

### 3. Tren — Ada perubahan kecenderungan?
Angka yang terus naik/turun dalam periode tertentu. Apakah ada perubahan tren yang berarti?

### 4. Korelasi — Dua hal bergerak bersama?
Korelasi muncul ketika dua fenomena terlihat meningkat/turun pada waktu yang sama. **Korelasi menunjukkan hubungan, tetapi belum tentu sebab-akibat.**

> Statistik dalam jurnalisme bukan terutama soal menghitung angka. Statistik adalah cara menemukan pola yang layak menjadi cerita.

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

Bukan sekadar mempercantik — ada fungsi lainnya. Biasanya ada 5 kemungkinan visualisasi tergantung apa yang mau dijelaskan:

| Jenis | Untuk apa | Catatan |
|---|---|---|
| **Grafik Batang (Bar Chart)** | Ranking & perbandingan (termasuk antar kategori) | Paling aman untuk banyak kategori |
| **Grafik Garis (Line Chart)** | Perubahan dari waktu ke waktu; juga untuk korelasi | Cocok memverifikasi asumsi tren |
| **Grafik Pie** | Proporsi (total 100%) | Hanya untuk kategori sedikit (≤5). Lebih dari 5 kategori, pakai bar chart |
| **Scatter Plot** | Hubungan dua variabel (mis. pendapatan vs pendidikan) | Sangat berguna untuk investigasi & analisis |
| **Peta (di luar 5 di atas)** | Menampilkan data spasial/geografis | Jenis yang sering muncul di luar kategori di atas |

**Fungsi visualisasi:**
- **Menemukan cerita** — pola tak terlihat di tabel (mis. korban kecelakaan naik tajam setelah pandemi) bisa langsung kelihatan.
- **Memverifikasi asumsi** — mis. "masyarakat makin banyak pakai transportasi umum", benarkah? Grafik tren bisa membuktikan atau membantah.
- **Menjelaskan isu kompleks** — stunting, perubahan iklim, APBN, kriminalitas, penyakit menular.

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
