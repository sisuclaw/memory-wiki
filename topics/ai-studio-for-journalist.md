---
title: AI Studio untuk Jurnalis
type: topic
confidence: 0.95
lastUpdated: 2026-04-11
tags: [AI, google-ai-studio, journalism, prototyping, gemini, no-code, newsroom]
claims:
  - id: "ai-studio-free-no-code"
    text: "Google AI Studio gratis, berbasis browser, tanpa kode — cukup akun Google dan browser"
    status: confirmed
    confidence: 1.0
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 5"
        quote: "Free. No cost to use. Browser-based. No downloads, no installations. No code required."
  
  - id: "ai-studio-capabilities"
    text: "Google AI Studio bisa: upload & analisis dokumen, buat/edit gambar, generate suara/audio, cari web langsung, generate musik, buat chart, build aplikasi dari deskripsi, tambah database & autentikasi"
    status: confirmed
    confidence: 0.95
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 7"
        quote: "Upload & analyze documents. Create & edit images. Generate voice & audio. Add voice conversations. Search the live web. Generate music. Run calculations & make charts. Build full apps from a description. Add database & authentication."
  
  - id: "problem-first-mindset"
    text: "Workshop dimulai dari masalah, bukan dari tool. Pertanyaan yang benar: 'Masalah apa yang perlu diselesaikan newsroom saya?', bukan 'Apa yang bisa dilakukan AI?'"
    status: confirmed
    confidence: 1.0
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 4"
        quote: "Most AI workshops start with the tool. We start with the problem. Never 'what can AI do?' Always 'what problem does my newsroom need to solve?'"
  
  - id: "prototype-not-product"
    text: "Prototype bukan produk — prototype adalah tes ide, untuk menentukan apakah ide layak dikejar"
    status: confirmed
    confidence: 1.0
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 4"
        quote: "A prototype is not a product. It's a test of an idea. It tells you whether the idea is worth pursuing."
  
  - id: "four-features-for-journalists"
    text: "4 fitur utama AI Studio untuk jurnalis: (1) Upload dokumen & tanya jawab, (2) Koneksi data web live, (3) Format output konsisten untuk CMS, (4) Generate chart dari teks"
    status: confirmed
    confidence: 0.95
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 10"
  
  - id: "prompt-patterns-work"
    text: "4 pola prompt yang efektif: role assignment, source restriction, output template, iteration chain"
    status: confirmed
    confidence: 0.95
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 19"
        quote: "Role assignment: 'You are a [role] who specializes in [domain]...' Source restriction: 'Only answer from [uploaded doc]. Cite page numbers.' Output template: 'Format: Headline (max 10 words) + Lede + 3 paragraphs + Sources' Iteration chain: 'Now make it shorter / add data / change the angle to...'"
  
  - id: "latam-newsroom-prototypes"
    text: "14 newsroom di Argentina & Uruguay sudah membangun prototype dengan Google AI Studio: OrtiBot (cek guideline video), Búsqueda Dataviz (visualisasi data otomatis), Montevideo Portal (asisten media sosial), La Diaria (artikel peringatan cuaca)"
    status: confirmed
    confidence: 0.9
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 11-15"
  
  - id: "prototype-to-workflow-path"
    text: "Jalur dari prototype ke workflow: (1) Saved Prompt — simpan jika sudah bekerja, (2) Pilot — bagikan ke 2-3 rekan, test seminggu, (3) Implementation — integrasi ke workflow editorial secara sistematis (bulan 2-3)"
    status: confirmed
    confidence: 0.9
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 24"
  
  - id: "ai-studio-antigravity"
    text: "AI Studio mendukung full-stack vibe coding dengan Antigravity — bisa build production app lengkap dengan backend, database (Firestore), auth (Firebase Auth), dan deploy ke Cloud Run"
    status: confirmed
    confidence: 0.85
    evidence:
      - source: "Google_AI_Studio_for_Journalist_Workshop_JournalismAI_Claudi.pdf"
        section: "Slide 9"
        quote: "Full-stack vibe coding — powered by Antigravity. Full production apps. Turn a prompt into a working app with complex UI, backend, and deployment to Cloud Run."
---

# AI Studio untuk Jurnalis

## 📊 Overview

**Topik:** Google AI Studio untuk Prototyping di Newsroom  
**Confidence Level:** 0.95  
**Last Updated:** 2026-04-11  
**Source:** Workshop Claudia Báez — JournalismAI Connect, POLIS – London School of Economics, 31 Maret 2026  
**Pembicara:** Claudia Báez (@claudibaez) — Digital & AI Innovator, Senior Investigative/Data Journalist

---

## 🧠 Mindset yang Benar

### Mulai dari Masalah, Bukan dari Tool

> "Workshop AI kebanyakan mulai dari tool. Kami mulai dari masalah."

- **Pertanyaan yang salah:** "Apa yang bisa dilakukan AI?"
- **Pertanyaan yang benar:** "Masalah apa yang perlu diselesaikan newsroom saya?"

### Prototype ≠ Produk

- Prototype adalah **tes ide** — bukan produk jadi
- Tujuannya menentukan apakah ide layak dikejar
- Framework: **PROBLEM → PROMPT → PROTOTYPE → ITERATE**

---

## 💻 Apa Itu Google AI Studio?

- **Gratis** — tidak ada biaya
- **Berbasis browser** — tidak perlu download/install
- **Tanpa kode** — cukup deskripsikan dalam bahasa natural
- **Powered by Gemini** — model AI terbaru Google
- **Akses:** aistudio.google.com

### Yang Bisa Dilakukan

| Fitur | Keterangan |
|-------|------------|
| Upload & analisis dokumen | AI membaca sumber dokumenmu |
| Buat & edit gambar | Generate dan modifikasi visual |
| Generate suara & audio | Text-to-speech dan lainnya |
| Cari web langsung | Data real-time dengan sumber terverifikasi |
| Generate musik | Buat musik dari deskripsi |
| Buat chart | Dari angka ke visualisasi publikasi |
| Build aplikasi | Dari deskripsi ke app yang berjalan |
| Database & auth | Firestore, Firebase Auth |

### Yang Tidak Diperlukan

- ❌ Tidak perlu API key
- ❌ Tidak perlu coding
- ❌ Tidak perlu instalasi

---

## 🔧 4 Fitur Utama untuk Jurnalis

1. **Upload dokumen & tanya jawab** — AI membaca sumber dokumen Anda, bukan internet (Demo 1)
2. **Koneksi data web live** — dapatkan data terkini dengan sumber yang bisa diverifikasi (Demo 2)
3. **Format output konsisten** — setiap artikel formatnya sama, siap untuk CMS (Demo 2)
4. **Generate chart dari teks** — ubah angka di tengah narasi jadi visual siap publikasi (Demo 3)

---

## 🎯 3 Demo Langsung

### Demo 1: AI Policy Assistant (12 menit)
- **Masalah:** Jurnalis perlu mengecek apakah boleh upload dokumen ke AI sesuai kebijakan organisasi
- **Fitur:** File Upload + System Instructions
- **Langkah:** Upload PDF kebijakan AI → Instruksi "bertindak sebagai policy analyst" → Query pertanyaan → Iterasi minta kutip halaman
- **Pola prompt:** "You are a [role]. You only answer from [uploaded document]. Cite page numbers."

### Demo 2: Economic Evergreen Generator (12 menit)
- **Masalah:** Perlu artikel ekonomi rutin dengan data terkini
- **Fitur:** Grounding + Structured Output
- **Langkah:** Ground ke Google Search → Define schema (headline, lede, body, sources) → Generate → Iterasi (tone, konteks, atribusi sumber)
- **Pola prompt:** "Search for [topic]. Write in [format]. Always include [required fields]."

### Demo 3: Visual Story Finder + Data Viz (12 menit)
- **Masalah:** Reporter tidak punya skill teknis untuk visualisasi data
- **Fitur:** File Upload + Structured Output + Code Execution
- **Langkah:** Upload artikel → AI identifikasi paragraf yang bisa divisualisasi → AI sarankan tipe chart → Code Execution render chart Matplotlib
- **Pola prompt:** "Analyze this document. Find data that can be visualized. Generate charts."

---

## 📰 Studi Kasus: Newsroom di Latin America

**Google AI Prototyping Sprint** — Google News Initiative + Fathm, 14 newsroom di Argentina (ADEPA) & Uruguay (2025)

> "No programmers? No problem."

| Newsroom | Prototype | Masalah | Solusi |
|----------|-----------|---------|--------|
| **ADN Sur** (Patagonia) | OrtiBot | Video kontributor sering melanggar guideline platform | Upload script audiovisual → AI cek terhadap guideline → laporan risiko konten |
| **Búsqueda** (Montevideo) | Búsqueda Dataviz | Reporter tidak bisa bikin visualisasi data | Paste artikel → AI identifikasi data → generate chart + grafis |
| **Montevideo Portal** (Montevideo) | Social Media Posting Assistant | Distribusi medsos lambat & repetitif | AI generate copy multi-platform + cek nama/judul + edit gambar otomatis |
| **La Diaria** (Montevideo) | Weather Alert Assistant | Artikel cuaca memakan waktu saat peak workload | Upload PDF alert → AI draft artikel + generate peta |
| **Wips** (Bahía Blanca) | Interactive Memory Game | — | Game berbasis gesture camera untuk news gamification |

---

## 🛠️ Pola Prompt yang Efektif

| Pola | Contoh |
|------|--------|
| **Role Assignment** | "You are a [role] who specializes in [domain]..." |
| **Source Restriction** | "Only answer from [uploaded doc]. Cite page numbers." |
| **Output Template** | "Format: Headline (max 10 words) + Lede + 3 paragraphs + Sources" |
| **Iteration Chain** | "Now make it shorter / add data / change the angle to..." |

---

## 🚀 Dari Prototype ke Workflow

| Tahap | Aktivitas | Waktu |
|-------|-----------|-------|
| **1. Saved Prompt** | Sudah diuji, simpan di AI Studio | Hari ini |
| **2. Pilot** | Bagikan ke 2-3 rekan, test seminggu | Minggu depan |
| **3. Implementation** | Integrasikan ke workflow editorial secara sistematis | Bulan 2-3 |

---

## 📦 Jenis Prototype yang Bisa Dibangun

- **News apps & Gamification** — paste database + decision tree → AI generate elemen interaktif
- **Content-to-Audio Converter** — upload teks → AI generate script + audio summary
- **Data Visualization Generator** — upload dataset → AI identifikasi data → generate chart
- **Routine News Drafting Tool** — define style + kategori → AI generate draft → editor review
- **Video Script Creator** — paste artikel → AI tulis script + saran visual
- **Infographic/Diagram Creator** — upload laporan → AI identifikasi data → generate diagram

---

## 📚 Sumber Daya

**Template Siap Pakai di AI Studio:**
- **Ask the Docs** — Upload dokumen, chat dengan dokumen (seperti Demo 1)
- **RAG** — Retrieval-Augmented Generation untuk riset & investigasi
- **Video Analyzer** — Upload video, ekstrak claims + timestamp + identifikasi pembicara
- **Dictation** — Voice-to-text transcription

**Akses:** aistudio.google.com → Explore bundled apps

### Latihan Mandiri

1. **Video Analyzer untuk Konferensi Pers** — Upload YouTube konferensi pers/sidang, minta AI ekstrak klaim kunci, identifikasi kontradiksi, buat ringkasan dengan timestamp
2. **Investigation Starter Kit (Fact-Check)** — Upload dokumen publik (pengadilan, laporan keuangan), gunakan System Instructions sebagai asisten fact-checking, aktifkan Grounding untuk cross-reference

---

## 📚 Related Topics

- [[Literasi Digital]]
- [[Komunikasi Krisis]]
- [[AI Journalism]]
- [[Prompt Engineering]]

---

*Last compiled: 2026-04-11*
