<h1 align="center">Muhammad Daffa Atha Rizq</h1>
<h3 align="center">Data Science & Machine Learning Specialist<br>Menuju AI Engineer & AI Agent Developer</h3>

<p align="center">
  <img src="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/raw/main/assets/img/foto-profil.jpg" width="150" alt="Foto Daffa" style="border-radius:50%">
</p>

<p align="center">
  <a href="https://daffaatha03.github.io/Portofolio-Daffa-Atha/">🌐 Portofolio</a> ·
  <a href="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/cv.pdf">📄 CV (ID)</a> ·
  <a href="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/cv-en.pdf">📄 CV (EN)</a> ·
  Email: daffathr3@gmail.com
</p>

<p align="center">
  📍 Bekasi, Jawa Barat &nbsp;|&nbsp; 🟢 Terbuka untuk peluang kerja, magang, dan kolaborasi proyek data & AI
</p>

---

## 👋 Tentang Saya

Lulusan S1 Informatika dari **Universitas Gunadarma** (IPK 3.61). Memiliki keahlian kuat dalam membangun *end-to-end* Machine Learning pipeline berbasis kerangka **CRISP-DM**, pengolahan dataset skala besar (>2,9 juta transaksi), dan pembuatan aplikasi web interaktif.

Saya memadukan riset teknis AI dengan pengalaman praktis di lapangan: administrasi logistik, manajemen basis data, dan pengelolaan armada (*fleet management*).

Arah saya berikutnya adalah **AI Engineer & AI Agent Developer**: membangun sistem AI yang tidak hanya pintar, tetapi aman, bisa diaudit, dan tetap dikendalikan manusia.

| IPK | Baris transaksi diolah | Grafik dashboard bisnis | R² model terbaik |
|:---:|:---:|:---:|:---:|
| **3.61 / 4.00** | **2.900.000+** | **18** | **0.63** |

### Yang saya bawa

- **End-to-End ML Pipeline**: dari persiapan data, *feature engineering*, modeling, hingga evaluasi.
- **Data skala besar**: terbiasa mengolah dataset dengan jutaan baris transaksi secara efisien.
- **Siap lapangan & operasional**: pengalaman nyata menangani administrasi logistik, kontrak, dan krisis armada.
- **Pola pikir Human-in-the-Loop**: AI mengerjakan bagian teknis yang berulang, manusia memverifikasi dan bertanggung jawab.

---

## 🚀 Proyek

### 1. Prediksi Permintaan E-Commerce
*Machine Learning & Data Analytics*

Model yang memperkirakan permintaan produk setiap bulan, dibangun di atas lebih dari 2,9 juta baris data transaksi Kaggle, lengkap dengan dashboard analitik interaktif.

- **Masalah:** memprediksi permintaan bulanan secara akurat sulit pada data transaksi berskala besar yang penuh *noise*; kesalahan prediksi berdampak langsung pada perencanaan stok.
- **Metode:** persiapan data dan *feature engineering* berbasis CRISP-DM, lalu membandingkan **XGBoost Regressor**, Stacking Ensemble, dan Random Forest.
- **Hasil:** XGBoost menjadi model terbaik dengan **RMSE 0.626 · MAE 0.293 · R² 0.63**.
- **Dampak:** dashboard dengan 18 grafik bisnis membantu membaca tren permintaan secara berbasis data, bukan asumsi.
- **Stack:** `Python` `XGBoost` `Scikit-Learn` `Pandas` `Seaborn`

🔗 [Repositori](https://github.com/DaffaAtha03/ANALISIS-PERBANDINGAN-MODEL-MACHINE-LEARNING-UNTUK-PREDIKSI-PERMINTAAN-PRODUK-PADA-E-COMMERCE) · 📄 [Dokumentasi dashboard (PDF)](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/dokumentasi/proyek-1-analisis-penjualan.pdf)

<details>
<summary><b>Temuan utama dari analisis penjualan</b></summary>

- **Musiman akhir tahun:** penjualan memuncak menjelang pergantian tahun.
- **Volume menurun:** setelah puncak bulan ke-23, penjualan turun dari sekitar 170 ribu ke sekitar 65 ribu unit per bulan.
- **Terkonsentrasi:** tiga kategori teratas menyumbang 63,6% dari tujuh kategori teratas.
- **Produk punya siklus:** produk baru rilis melonjak lalu cepat turun, produk pendukung relatif stabil.

<img src="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/raw/main/assets/dokumentasi/p1-tren-bulanan.webp" width="600" alt="Tren penjualan bulanan">

</details>

---

### 2. CineMatch AI: Rekomendasi Film
*AI System & Web Application*

Aplikasi rekomendasi film *hybrid* yang dirancang untuk mendongkrak visibilitas **film lokal Indonesia**.

- **Masalah:** film lokal kerap kalah visibilitas pada sistem rekomendasi konvensional yang bias terhadap judul populer atau mancanegara.
- **Metode:** menggabungkan **TruncatedSVD, Sentence-BERT, dan Multinomial Naive Bayes**, dilengkapi *Strict Mode* dan alokasi kuota proporsional agar film lokal tetap terwakili.
- **Hasil:** dievaluasi dengan Precision/Recall, serta diuji lewat Blackbox Testing dan User Acceptance Testing (UAT).
- **Dampak:** representasi film lokal pada hasil rekomendasi meningkat.
- **Stack:** `Python` `Streamlit` `SBERT` `TruncatedSVD` `Naive Bayes`

📄 [Dokumentasi (PDF)](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/dokumentasi/proyek-2-cinematch-ai.pdf)

<details>
<summary><b>Tampilan aplikasi</b></summary>

<img src="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/raw/main/assets/dokumentasi/p2-halaman-utama.webp" width="600" alt="Halaman utama CineMatch AI">

</details>

---

### 3. PrivateAI: AI Agent Lokal & Offline `MVP · v1.8`
*AI Agent Engineering*

AI agent yang berjalan sepenuhnya di laptop sendiri tanpa internet. Pengguna mengetik tugas biasa, agent membuat dan menjalankan kodenya dengan aman, lalu **menunggu persetujuan manusia** sebelum hasilnya dianggap final.

- **Masalah:** model bahasa kecil yang berjalan lokal mudah salah (mengarang kolom data, menghasilkan kode berbahaya), sementara data sensitif tidak boleh dikirim ke cloud.
- **Prinsip:** **"Small LLM + Strong Engineering"**. LLM hanya memahami maksud dan menulis kode; keamanan, izin, validasi, dan audit dikerjakan kode biasa yang bisa diuji.
- **Fitur:** Task Contract, pemeriksaan AST, eksekusi terbatas folder workspace, perbaikan otomatis (maks. 3×), persetujuan manusia, dan audit log, tersusun dalam tujuh lapisan pertahanan.
- **Hasil:** GUI Gradio, memori SQLite, audit log JSON Lines, dan 13 tugas benchmark. **141 test lulus**, 22 file test, 3.226 baris kode aplikasi.
- **Stack:** `Python` `Ollama` `Qwen2.5 1.5B` `Gradio` `SQLite` `Pandas` `Pytest`

> **Catatan kejujuran:** ini MVP untuk pemakaian pribadi, bukan produk siap produksi. Eksekusi kode dibatasi workspace, *bukan* sandbox tingkat OS. Tes memakai LLM tiruan (mock), dan angka benchmark untuk model sungguhan sengaja belum diisi.

🔗 [Repositori](https://github.com/DaffaAtha03/private-ai-) · 📄 [Dokumentasi (PDF)](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/dokumentasi/proyek-3-privateai.pdf)

<details>
<summary><b>Arsitektur agent</b></summary>

Task Analyzer → Task Contract → Data/File Inspector → Context Compressor → Agent Orchestrator → **Permission Layer** → Tool Selection → LLM → Code Proposal → **Safety Gate** → **Syntax Validator** → **Workspace Isolation** → Executor → Error Analyzer (retry ≤ 3×) → **Validator** → **Human Approval** → Artifact → **Audit Log**

Prioritas desain: *Security > Correctness > Reliability > Testability > Upgradeability > Intelligence.*

<img src="https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/raw/main/assets/dokumentasi/p3-arsitektur-lapisan.webp" width="600" alt="Arsitektur PrivateAI">

</details>

---

## 🎯 Arah Karier: AI Engineer & AI Agent Developer

Statusnya saya tulis jujur: fondasi sudah ada, satu agent lokal (PrivateAI) sudah dibangun sebagai MVP, dan sisanya masih dipelajari.

| Fondasi yang sudah ada | Teknologi |
|---|---|
| Pemodelan ML & Deep Learning | XGBoost, TruncatedSVD, Naive Bayes, Deep Learning |
| Embedding semantik | Sentence-BERT |
| Evaluasi model | RMSE, MAE, R², Precision/Recall, UAT |
| Alur data berbasis CRISP-DM | CRISP-DM, Pandas, Feature Engineering |
| Aplikasi AI | Streamlit, Flask, Gradio |
| AI agent lokal (PrivateAI) | Ollama, Qwen2.5 1.5B, Safety gate, Self-healing loop, Audit log |

**Sedang dipelajari:**
- RAG & vector database (ChromaDB / Qdrant)
- Model lokal yang lebih besar (upgrade GPU)
- Isolasi tingkat OS: container / VM untuk eksekusi kode

**Prinsip kerja: Human-in-the-Loop.** AI mengerjakan bagian teknis yang berulang; manusia memverifikasi dan bertanggung jawab.

<details>
<summary><b>Catatan belajar: membangun PrivateAI</b></summary>

1. **Model kecil pasti salah, jadi buktinya harus diperiksa.** Schema file asli dibaca lebih dulu, sehingga kolom fiktif yang dikarang LLM ditolak sebelum kode dijalankan.
2. **LLM bukan lapisan keamanan.** Semua keputusan allow/deny dibuat kode Python yang bisa diuji, bukan bergantung pada kebaikan prompt.
3. **Mengaudit karya sendiri itu menyakitkan, dan berguna.** Sebelum perbaikan, 13 pola serangan terhadap safety gate semuanya lolos. Semuanya ditutup dan dikunci dengan test.
4. **Jangan mengarang angka.** Angka benchmark model sungguhan sengaja belum diisi sampai dijalankan beberapa kali di mesin sendiri.
5. **Batasan perangkat membentuk desain.** Dengan Ryzen 3, RAM 8 GB, tanpa GPU, konteks harus dipangkas sebelum dikirim ke LLM.
6. **Manusia memegang keputusan akhir.** Hasil baru disimpan setelah pengguna menekan Approve, dan setiap langkah masuk ke audit log.

</details>

---

## 🛠️ Keahlian & Tools

| Bidang | Keahlian |
|---|---|
| **Machine Learning & AI** | XGBoost · Scikit-Learn · Sentence-BERT · TruncatedSVD · Multinomial Naive Bayes · Deep Learning · Feature Engineering · Time-Series Forecasting |
| **Data Analytics & Viz** | Pandas · NumPy · Matplotlib · Seaborn · CRISP-DM · EDA · Data Entry |
| **Programming & Web** | Python · SQL · JavaScript · HTML5 · CSS3 · Streamlit · Flask · Bootstrap |
| **Tools & Database** | MySQL · phpMyAdmin · Git · GitHub · Google Colab |
| **Operational & Admin** | Fleet Management · Financial & Contract Reporting · Crisis Management |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## 💼 Pengalaman Kerja

**Admin Perusahaan Vendor Logistik** · CV Barokah Bersama Logistik, Cibitung, Kab. Bekasi
*Okt 2025 – Jul 2026 · Part Time*
- Mengelola basis data operasional dan *data entry* perusahaan secara akurat.
- Menyusun dan menganalisis laporan keuangan operasional dan kontrak kerja sama.
- Mengatur logistik, penjadwalan, dan koordinasi harian unit kendaraan (Fleet Management).
- Menangani manajemen krisis darurat armada di lapangan secara responsif.

**Contract Logistics Data & Billing Staff** · PT Sinar Sosro (via Shipper.id)
*Jun 2026 · Project-Based*
- Mengelola pencatatan data transaksi pengiriman.
- Menerbitkan Proforma Invoice dan Surat Jalan (Delivery Notes).
- Melakukan perhitungan pajak *gross-up* penagihan.

---

## 🎓 Pendidikan

| Jenjang | Institusi | Periode |
|---|---|---|
| **S1 Informatika (S.Kom.)**, IPK 3.61 / 4.00 | Universitas Gunadarma | 2022 – 2026 |
| SMA | SMAN 9 Tambun Selatan | 2019 – 2022 |
| SMP | SMPN 12 Tambun Selatan | 2016 – 2019 |
| SD | Putradarma | 2010 – 2016 |

**Tugas Akhir / Skripsi:** Implementasi Machine Learning & Deep Learning pada Sistem Rekomendasi CineMatch AI & Prediksi Permintaan E-Commerce.

---

## 📜 Sertifikasi & Pelatihan

Sertifikat keikutsertaan pelatihan, sebagian besar dari Universitas Gunadarma. Klik judul untuk membuka PDF-nya.

<details>
<summary><b>Basis Data (5)</b></summary>

- [Sistem Basisdata Lanjut](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2026-06-sistem-basisdata-lanjut.pdf), 25 Mei – 6 Jun 2026
- [Dasar-Dasar Sistem Basisdata](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2025-09-dasar-dasar-sistem-basisdata.pdf), 22 – 27 Sep 2025
- [Oracle untuk Tingkat Menengah](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2025-08-oracle-menengah.pdf), Agu 2025
- [Oracle untuk Tingkat Pemula](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2024-08-oracle-pemula.pdf), Agu 2024
- [Dasar Sistem Manajemen Basis Data](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2023-08-dasar-sistem-manajemen-basis-data.pdf), Agu 2023

</details>

<details>
<summary><b>Web & Pemrograman (4)</b></summary>

- [Pemrograman Go untuk Tingkat Menengah](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2025-02-go-menengah.pdf), Feb 2025
- [Membangun Website Menggunakan HTML 5](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2025-01-membangun-website-html5.pdf), 21 Jan 2025
- [Pemrograman Go untuk Tingkat Pemula](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2024-02-go-pemula.pdf), Feb 2024
- [Dasar Pemrograman Berbasis Web](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2023-02-dasar-pemrograman-web.pdf), Feb 2023

</details>

<details>
<summary><b>Lainnya (2)</b></summary>

- [Aptitude Test](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2026-07-aptitude-test.pdf), 18 Jul 2026
- [Info Session GDSC Universitas Gunadarma](https://github.com/DaffaAtha03/Portofolio-Daffa-Atha/blob/main/assets/sertifikat/2022-gdsc-gunadarma-info-session.pdf), 2022 (Google Developer Student Clubs Gunadarma)

</details>

---

## 📫 Mari Terhubung

Terbuka untuk peluang kerja, magang, maupun kolaborasi proyek data & AI.

- 🌐 Portofolio: https://daffaatha03.github.io/Portofolio-Daffa-Atha/
- ✉️ Email: daffathr3@gmail.com
- 📍 Bekasi, Jawa Barat
