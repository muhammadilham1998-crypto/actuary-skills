# Laporan Penilaian Risiko & Rekomendasi Strategis
## Strategic Plan 2027–2029 — AXA Financial Indonesia

**Tanggal:** 27 Maret 2026  
**Perspektif:** Chief Actuary (Pricing, Reserving, Financial Risk, & Macroeconomics)  
**Klasifikasi:** CONFIDENTIAL

---

## Ringkasan Eksekutif

Strategic Plan (SP) 2027–2029 AXA Financial Indonesia (AFI) menargetkan pertumbuhan yang sangat agresif (APE CAGR +22%, GWP CAGR +14%) di tengah stagnasi pasar asuransi jiwa nasional (-2% YoY). Strategi ini sangat bergantung pada ekspansi jalur keagenan ("Super Sekali"), penetrasi agresif pada produk Tradisional (khususnya *Whole Life*), dan pengguliran inisiatif otomatisasi berbasis AI.

Sebagai *Chief Actuary*, analisis mendalam terhadap dokumen SP ini menyingkap **10 risiko material** yang mengancam *solvency*, marjin profitabilitas, dan stabilitas IFRS 17 Operating Earnings perusahaan. Risiko paling kritis bersumber dari (1) erosi *New Business Value* (NBV) akibat penjualan produk *loss-leader*, (2) inflasi klaim kesehatan yang tidak terbendung oleh mitigasi operasional, dan (3) *capital strain* masif akibat operasional *spin-off* syariah (ASLI). 

Laporan ini merinci kerangka risiko secara kuantitatif dan kualitatif beserta rekomendasi mitigasi strategis.

---

## Daftar Risiko yang Teridentifikasi

| No. | Kategori | Risiko | Severity | Probability | Rating |
|-----|----------|--------|----------|-------------|--------|
| 1 | Insurance/Pricing | **NBV Margin Erosion (Whole Life Drag)** | **CRITICAL** | High | 🔴 |
| 2 | Insurance/Morbidity | **Health Claims Inflation & Anti-Selection** | **CRITICAL** | High | 🔴 |
| 3 | Financial/Capital | **Sharia Spin-Off (ASLI) Capital Bleed** | **HIGH** | High | 🔴 |
| 4 | Accounting/IFRS 17 | **Onerous Contract Recognition (Loss Component)** | **HIGH** | High | 🔴 |
| 5 | Strategic/Distribution| **Agency Channel Concentration Risk** | **HIGH** | Medium | 🟠 |
| 6 | Financial/ALM | **Interest Rate Risk on Long-Duration Liabilities** | **HIGH** | Medium | 🟠 |
| 7 | Operational/Execution| **AI / Tech Investment ROI Failure** | **MEDIUM** | Medium-High | 🟡 |
| 8 | Insurance/Lapse | **Persistency Drop / Mass Lapse Scenario** | **MEDIUM** | Medium | 🟡 |
| 9 | Macroeconomic/FX | **Depresiasi IDR & Imported Inflation** | **MEDIUM** | Medium | 🟡 |
| 10 | Reinsurance/Risk | **Catastrophe / Pandemic Tail Risk** | **LOW** | Low | 🟢 |

---

## Analisis Detail Per Risiko Material (Top 5)

---

### RISIKO 1: NBV Margin Erosion (Whole Life Drag) 🔴 CRITICAL

**Deskripsi:**  
SP secara eksplisit menyebutkan strategi untuk "menyeimbangkan ekspektasi marjin NBV negatif dari produk *whole life* sebagai bagian dari strategi untuk mempertahankan agen". Roll-forward NBV menunjukkan *business mix impact* yang makin memburuk:
- SP27 ke SP28: -IDR 11.5 miliar
- SP28 ke SP29: -IDR 17.2 miliar

**Analisis Kuantitatif:**
$$\\text{Target NBV Margin di SP2029} = \\frac{\\text{NBV (129M)}}{\\text{PVEP (4,667M)}} \\approx 2.76\\%$$
Marjin NBV di bawah 3% sangat berbahaya. *Baseline* industri asuransi jiwa yang sehat biasanya memiliki *VNB margin* di atas 15-20%. Menjual produk berdurasi sangat panjang dengan NBV negatif artinya perusahaan **mengunci kerugian (*locked-in loss*) dan beban modal di masa depan** hanya demi mengejar target rekrutmen 1.800 agen.

**Rekomendasi Mitigasi:**
| # | Strategi | Timeline | Detail |
|---|----------|----------|--------|
| 1.1 | **Quota System & Product Cap** | Immediate | Terapkan batas kuota produksi APE harian/bulanan untuk produk *Whole Life* ber-NBV negatif. Agen tidak boleh mendapat komisi penuh jika bauran produk (*mix*) bulanannya didominasi produk ini. |
| 1.2 | **Product Redesign & Repricing** | Q2 2026 | Lakukan repricing ulang. Turunkan nilai *guarantee* atau ubah asumsi diskonto. Tingkatkan porsi *riders* ber-NBV tinggi (seperti *Critical Illness*) sebagai keharusan (bundling) saat menjual polis *Whole Life*. |
| 1.3 | **Surplus Relief Reinsurance** | Q4 2026 | Susun perjanjian *quota-share reinsurance* dengan komisi reasuransi di depan (*ceding commission*) untuk menalangi *capital strain* produk ini. |

---

### RISIKO 2: Health Claims Inflation & Anti-Selection 🔴 CRITICAL

**Deskripsi:**  
Klaim kesehatan industri naik 11% YoY di 2025. Rencana mitigasi di SP bertumpu pada *Repricing* di atas inflasi medis menggunakan GLM dan pengendalian operasional (*Clinical Pathway*, *AI Fraud Detection*).

**Analisis Risiko (Spiral Anti-Seleksi):**
Menaikkan premi asuransi kesehatan *in-force* secara drastis (*above medical inflation*) sangat rentan terhadap **Death Spiral**. Nasabah yang masih sehat akan merasa premi terlalu mahal dan memilih *lapse* atau pindah ke kompetitor. Sebaliknya, nasabah dengan riwayat sakit/kronis akan tetap bertahan karena mereka tahu klaim mereka akan disetujui. Akibatnya, *pool* nasabah memburuk dan *Loss Ratio* justru meningkat pada siklus berikutnya.

**Rekomendasi Mitigasi:**
| # | Strategi | Timeline | Detail |
|---|----------|----------|--------|
| 2.1 | **Targeted Co-Pay Migration** | 2026-2027 | Jangan hanya menaikkan premi. Paksakan skema **Co-payment (Urun Biaya) 10-20%** kepada nasabah dengan riwayat utilisasi klaim tinggi. Ini adalah cara terampuh mengurangi *moral hazard*. |
| 2.2 | **Lapse-Morbidity Correlation Monitoring** | Monthly | Pantau rasio klaim dari kohort nasabah pasca-*repricing*. Jika tingkat *lapse* dari nasabah sehat melonjak di atas batas wajar (misal >15%), hentikan kenaikan premi dan alihkan ke negosiasi *provider* (Rumah Sakit). |
| 2.3 | **Stop-Loss Reinsurance** | 2026 | Amankan *Aggregate Excess of Loss* (XoL) treaty jika *Health Loss Ratio* portofolio melewati angka 85% untuk melindungi P&L. |

---

### RISIKO 3: Sharia Spin-Off (ASLI) Capital Bleed 🔴 HIGH

**Deskripsi:**  
Laporan proyeksi IFRS 17 Operating Earnings (OE) menunjukkan bahwa ASLI (Unit Syariah) akan menjadi "vampir" modal bagi konsolidasi AFI:
- OE ASLI SP 2026: (IDR 48 miliar)
- OE ASLI SP 2027: (IDR 56 miliar)
- NCE Ratio ASLI 2026: 200% (Sangat tidak efisien)

**Analisis Risiko:**
Sesuai aturan OJK (POJK 11/2023), modal minimum entitas asuransi baru (termasuk hasil *spin-off*) adalah **Rp 100 Miliar**. Mengingat ASLI diproyeksikan merugi total sekitar Rp 194 Miliar dalam 4 tahun ke depan, AFI harus secara terus-menerus menyuntikkan modal dasar agar ASLI tidak terkena intervensi pengawasan OJK karena RBC jeblok.

**Rekomendasi Mitigasi:**
| # | Strategi | Timeline | Detail |
|---|----------|----------|--------|
| 3.1 | **Capital Ring-Fencing** | Immediate | Pisahkan secara ketat *capital pool* AFI dan ASLI. Buat *buffer* modal Rp 150 Miliar spesifik untuk ASLI di hari pertama beroperasi untuk menahan laju kerugian 2 tahun ke depan tanpa mengganggu RBC konvensional. |
| 3.2 | **Aggressive Shared Services** | 2026-2028 | NCE Ratio 200% tidak masuk akal. Tekan rasio ini dengan menyatukan 100% sistem IT, *claims processing*, dan fungsi aktuaria dengan induk AFI. ASLI hanya boleh mempekerjakan *front-liner* dan *DPS* (Dewan Pengawas Syariah) sendiri. |

---

### RISIKO 4: Onerous Contract Recognition (IFRS 17) 🔴 HIGH

**Deskripsi:**  
Tabel *UE Roll-forward* membuktikan bahwa AFI knowingly menulis bisnis yang merugi. Item **"Onerous NB"** mencatat kerugian:
- SP28: -IDR 10.7 miliar
- SP29: -IDR 3.9 miliar

**Analisis Akuntansi & Aktuaria:**
Di bawah IFRS 17, produk yang *onerous* (Fulfillment Cash Flow > 0) tidak memiliki *Contractual Service Margin* (CSM) yang bisa ditunda sebagai keuntungn masa depan. Sebaliknya, seluruh kerugian (*Loss Component*) **langsung dicatat sebagai kerugian pada hari pertama polis diterbitkan**. Ini akan menyebabkan volatilitas masif pada pencapaian *Operating Earnings* (OE) dan bisa memicu turunnya dividen perusahaan induk.

**Rekomendasi Mitigasi:**
| # | Strategi | Timeline | Detail |
|---|----------|----------|--------|
| 4.1 | **Onerous Portfolio Grouping** | Q3 2026 | Rancang strategi agregasi IFRS 17 (*portfolio grouping*) yang agresif (tapi legal) untuk mencoba mencampur (*offset*) kontrak *Whole Life* yang merugi dengan kontrak/rider (misal CI) yang sangat menguntungkan di *cohort* yang sama untuk menghindari *loss component* di level grup. |
| 4.2 | **CFO-Level Gatekeeper** | Monthly | Wajibkan persetujuan CFO & Chief Actuary sebelum peluncuran produk apa pun yang hasil proyeksi *Onerous*-nya melebihi IDR 2 Miliar. |

---

### RISIKO 5: Agency Channel Concentration Risk 🟠 HIGH

**Deskripsi:**  
Proyeksi SP menunjukkan bahwa **98% dari total GWP di tahun 2029 akan berasal dari Jalur Keagenan (*Agency*)**, sedangkan jalur TM & *Partnership* mencatat CAGR negatif (-17%).

**Analisis Risiko Diversifikasi:**
Ketergantungan ekstrem pada satu *channel* membuat perusahaan rentan terhadap skenario diskontinuitas tunggal. Jika ada perubahan regulasi terkait komisi agen (OJK sedang getol memangkas *front-loading* komisi unit-link) atau agen elit di-bajak (*poached*) oleh dua pemain terbesar (Prudential/Allianz yang menguasai 50% pasar), maka seluruh proyeksi GWP AFI akan langsung ambruk.

**Rekomendasi Mitigasi:**
| # | Strategi | Timeline | Detail |
|---|----------|----------|--------|
| 5.1 | **Bancassurance Revival** | 2026-2027 | Hentikan penurunan jalur *Partnership*. Mulai rintis 1-2 kerjasama *bancassurance* eksklusif dengan bank pembangunan daerah (BPD) atau bank digital menengah untuk mendiversifikasi risiko distribusi. |
| 5.2 | **Digital D2C (Direct to Consumer)** | 2027-2029 | Alihkan sebagian kecil *budget* "Gen AI" (IDR 13.2 miliar) untuk merancang produk asuransi kecelakaan/penyakit tropis mikro yang dijual langsung via platform tanpa melalui perantara agen. |

---
*Laporan ini dihasilkan menggunakan pandangan lintas-disiplin aktuaria (Pricing, Reserving, Financial Risk, dan IFRS 17) sebagai landasan bagi pengambilan keputusan strategis tingkat C-Level.*