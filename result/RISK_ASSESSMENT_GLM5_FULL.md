# Laporan Penilaian Risiko & Rekomendasi Strategis (Exhaustive Edition)
## Strategic Plan 2027–2029 — AXA Financial Indonesia

**Tanggal:** 27 Maret 2026  
**Perspektif:** Chief Actuary & Head of Enterprise Risk Management (ERM)  
**Klasifikasi:** CONFIDENTIAL / BOARD-LEVEL  

---

## 1. Ringkasan Eksekutif

Strategic Plan (SP) 2027–2029 AXA Financial Indonesia (AFI) menargetkan pertumbuhan masif dengan APE CAGR +22% dan GWP CAGR +14%. Rencana ini sangat bergantung pada strategi "Super Sekali" melalui ekspansi besar-besaran jalur keagenan (Agency), penjualan produk *Whole Life*, restrukturisasi harga asuransi kesehatan (GLM Repricing), dan proyek investasi AI senilai Rp 118 Miliar.

Meskipun secara kasat mata menjanjikan pertumbuhan *top-line*, analisis aktuaria mendalam dan pemodelan risiko ERM menyingkap **16 risiko material** yang saling beririsan (krisis makroekonomi, kelemahan marjin NBV, tekanan klaim kesehatan, dan pendarahan modal dari *spin-off* syariah). Laporan ini menyajikan *Risk Heatmap* komprehensif beserta mitigasi kuantitatif untuk melindungi solvabilitas dan *IFRS 17 Operating Earnings* perusahaan.

---

## 2. Risk Heatmap: 16 Risiko Material Teridentifikasi

| No. | Kategori | Risiko | Severity | Probability | Rating |
|-----|----------|--------|----------|-------------|--------|
| 1 | Insurance/Pricing | **NBV Margin Erosion (Whole Life Drag)** | **CRITICAL** | High | 🔴 |
| 2 | Insurance/Morbidity | **Health Claims Inflation & Anti-Selection** | **CRITICAL** | High | 🔴 |
| 3 | Financial/Capital | **Sharia Spin-Off (ASLI) Capital Bleed** | **CRITICAL** | High | 🔴 |
| 4 | Geopolitical/Macro | **Konflik Timur Tengah & Kelangkaan BBM (Inflasi)** | **HIGH** | Medium-High | 🔴 |
| 5 | Strategic/Distribution| **Agency Channel Concentration Risk** | **HIGH** | High | 🔴 |
| 6 | Accounting/IFRS 17 | **Onerous Contract Recognition (Loss Component)** | **HIGH** | High | 🔴 |
| 7 | Financial/FX | **Depresiasi IDR terhadap USD (Imported Inflation)** | **HIGH** | Medium-High | 🟠 |
| 8 | Financial/ALM | **Interest Rate & Duration Mismatch (Yield Curve)** | **HIGH** | Medium | 🟠 |
| 9 | Insurance/Lapse | **Persistency Drop & Mass Lapse Scenario** | **HIGH** | Medium | 🟠 |
| 10 | Strategic/Execution | **AI / Tech Investment ROI Failure (Cost Overrun)** | **MEDIUM** | Medium-High | 🟡 |
| 11 | Expense/Inflation | **Non-Commission Expense (NCE) Inflation Exceeds Assumptions** | **MEDIUM** | High | 🟡 |
| 12 | Strategic/HR | **Recruitment Target & Agent Quality Deterioration** | **MEDIUM** | Medium | 🟡 |
| 13 | Investment/Market | **Investment Return Volatility (Equities & Bonds)** | **MEDIUM** | Medium | 🟡 |
| 14 | Regulatory | **Perubahan Regulasi OJK & Minimum Solvency Margin** | **MEDIUM** | Medium | 🟡 |
| 15 | Operational/Cyber | **Cyber Security Breach pada Legacy System** | **MEDIUM** | Low-Medium | 🟡 |
| 16 | Mortality/Catastrophe| **Pandemic & Catastrophe Mortality Shock** | **LOW** | Low | 🟢 |

---

## 3. Deep-Dive Analysis (16 Risiko Material)

### RISIKO 1: NBV Margin Erosion (Whole Life Drag) 🔴
- **Deskripsi:** Rencana SP secara terbuka menjadikan produk *Whole Life* Tradisional sebagai *loss-leader* (rugi) untuk mempertahankan agen dan meningkatkan omset APE. Akibatnya, marjin NBV tergerus parah.
- **Analisis Kuantitatif:** Formula *Value of New Business* (VNB): $VNB = PV(Premiums) - PV(Claims \& Expenses) - Cost of Capital$. Dengan NBV Margin target hanya 2.8% ($\frac{129}{4667}$ di 2029), penambahan modal (CoC) sekecil apa pun akan membuat produk ini menjadi negatif dan menghancurkan nilai perusahaan.
- **Dampak pada SP:** *Business Mix impact* menekan NBV roll-forward (-11.5M di 2028, -17.2M di 2029).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 1.1 | Quota Cap Limit | Q1 2026 | Terapkan batas kuota produksi harian maksimal 15% dari total portofolio agen untuk produk *Whole Life* negatif ini. |
  | 1.2 | Bundling Rider CI | Q2 2026 | Wajibkan penyertaan *Critical Illness* Rider yang ber-NBV tinggi saat menjual polis *Whole Life* dasar. |

### RISIKO 2: Health Claims Inflation & Anti-Selection 🔴
- **Deskripsi:** Merespons kenaikan klaim industri (11%), SP mengandalkan GLM repricing di atas inflasi medis. Ini memicu *death spiral* (nasabah sehat kabur karena mahal, yang sakit tetap bertahan).
- **Analisis Kuantitatif:** Dalam SII framework, *morbidity shock* memukul BEL (*Best Estimate Liability*). $\Delta BEL = BEL_{base} \times (1 + \text{Morbidity Trend})$. Kenaikan loss ratio 1% pada Rp 1.7T GWP berarti bocor Rp 17 Miliar per tahun.
- **Dampak pada SP:** *Actuarial assumption* (-4.5M di SP27) pada NBV Health mencerminkan memburuknya asumsi morbiditas.
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 2.1 | Migration to Co-Pay | 2026-2027 | Paksakan skema *co-payment* (urun biaya) 10-20% untuk menekan moral hazard alih-alih sekadar menaikkan premi buta. |
  | 2.2 | Stop-Loss Treaty | 2026 | Negosiasikan *reinsurance stop-loss treaty* dengan *trigger* rasio klaim 85%. |

### RISIKO 3: Sharia Spin-Off (ASLI) Capital Bleed 🔴
- **Deskripsi:** *Spin-off* syariah (ASLI) diproyeksikan mencatat kerugian OE hingga Rp 56 Miliar di 2027 dengan *Expense Ratio* absurd (200% di 2026).
- **Analisis Kuantitatif:** OJK mewajibkan Modal Disetor minimum Rp 100 Miliar. Jika proyeksi kerugian kumulatif ASLI (2026-2029) mencapai minus Rp 194 Miliar, modal akan habis dalam 2 tahun pertama dan membutuhkan *bailout* dari induk konvensional.
- **Dampak pada SP:** Menggerus total IFRS 17 Operating Earnings perusahaan secara material (dari 119M turun jadi 68M secara grup).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 3.1 | Capital Ring-fencing | Q1 2026 | Segregasi penuh neraca ASLI dengan modal awal Rp 150 Miliar untuk memastikan operasional 3 tahun tanpa menyedot RBC konvensional. |
  | 3.2 | Shared Service Model | 2026-2028 | Penyatuan 100% *back-office* (IT, Aktuaria, Klaim) ke induk; ASLI hanya beroperasi dengan struktur penjualan dan dewan syariah. |

### RISIKO 4: Konflik Timur Tengah & Kelangkaan BBM (Inflasi) 🔴
- **Deskripsi:** Indonesia adalah *net oil importer*. Perang yang membatasi pasokan minyak (Selat Hormuz) akan memicu inflasi domestik ganda: inflasi energi dan inflasi obat-obatan logistik.
- **Analisis Kuantitatif:** $CPI_{new} = CPI_{base} + \alpha(\Delta Oil Price)$. Kenaikan biaya logistik RS otomatis mengerek *medical inflation* menjadi >15% p.a.
- **Dampak pada SP:** Target NCE yang membaik ke 19.9% di 2029 akan hancur karena beban gaji (staff cost) dan inflasi vendor akan meleset dari asumsi dasar (6%).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 4.1 | Inflation Stress Test | Immediate | Masukkan skenario harga minyak $120/bbl dalam ORSA untuk uji ketahanan solvabilitas. |

### RISIKO 5: Agency Channel Concentration Risk 🔴
- **Deskripsi:** Kontribusi produk bersumber dari 98% Agency di 2029, sementara channel kemitraan menurun tajam (-17%).
- **Analisis Kuantitatif:** Paparan *Mass Lapse Scenario* (SII: 30% *immediate lapse*) menjadi sangat asimetris dan terkonsentrasi. Kehilangan 1 Top Agency Leader berarti kehilangan 20% total premi baru.
- **Dampak pada SP:** Target agresif APE CAGR 22% rapuh terhadap gejolak internal keagenan atau intervensi bajak-agen oleh pemain dominan (Prudential/Allianz).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 5.1 | Bancassurance Revival | 2026-2028 | Re-alokasi dana untuk mengakuisisi minimal 2 mitra perbankan regional (BPD) guna menyeimbangkan bauran distribusi. |

### RISIKO 6: Onerous Contract Recognition (Loss Component) 🔴
- **Deskripsi:** Berbeda dengan aturan lama, IFRS 17 (PSAK 74) melarang penundaan kerugian. Produk *Whole Life* yang berdarah akan langsung memukul Laporan Laba Rugi di tahun pertama.
- **Analisis Kuantitatif:** $\text{Fulfillment Cash Flows (FCF)} > 0 \Rightarrow \text{Onerous}$. CSM menjadi Nol, dan total FCF dicatat sebagai *Loss Component* (misal: -IDR 10.7 Miliar di 2028).
- **Dampak pada SP:** Terbukti di tabel UE Roll-forward, baris *Onerous NB* menyedot profit secara masif dari 2027 hingga 2029.
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 6.1 | Portfolio Grouping | 2026 | Rekayasa pengelompokan (*grouping*) kontrak IFRS 17 dengan mencampur produk rugi dan sangat untung pada kohort penerbitan yang sama. |

### RISIKO 7: Depresiasi IDR terhadap USD (Imported Inflation) 🟠
- **Deskripsi:** *Capital outflow* dan pelemahan nilai tukar Rupiah menghantam beban operasional lintas-negara dan inflasi obat impor.
- **Analisis Kuantitatif:** *Net Open Position* (NOP) pada premi reasuradur ($) dan tagihan AXA Group Rebilling ($) akan membengkak. $\Delta Cost = Exposure_{USD} \times \Delta IDR/USD$.
- **Dampak pada SP:** Net Group Rebillings naik konstan 6% hingga Rp 98.4 M di 2029. Pelemahan IDR 15% akan merusak *budget NCE*.
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 7.1 | FX Hedging Program | 2026 | Terapkan proteksi nilai tukar (*Forward / Swap*) untuk 70% dari tagihan premi reasuransi luar negeri dan AXA GO Rebillings. |

### RISIKO 8: Interest Rate & Duration Mismatch 🟠
- **Deskripsi:** Kenaikan BI Rate memicu kerugian nilai wajar obligasi (SBN) saat ini, sekaligus menciptakan *mismatch* aset-liabilitas (ALM) pada portofolio asuransi tradisional jangka panjang (*Whole life/Endowment*).
- **Analisis Kuantitatif:** $\Delta Equity = -(\text{Duration}_{Asset} - \text{Duration}_{Liab}) \times Equity \times \Delta Yield$. *Whole life* memiliki durasi ~15 tahun, sedangkan SBN panjang di pasar sangat langka.
- **Dampak pada SP:** Volatilitas *Investment Margin* pada IFRS 17 OE (naik/turun dari -8.9 Miliar hingga +4.3 Miliar).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 8.1 | Barbell Strategy | Q2 2026 | Gunakan portofolio *barbell* (SPN jangka sangat pendek + SUN FR jangka 20 tahun) untuk mencocokkan konveksitas durasi. |

### RISIKO 9: Persistency Drop & Mass Lapse Scenario 🟠
- **Deskripsi:** Asumsi *lapse rate* statis 10% di SP sangat optimis. Tekanan daya beli akibat ekonomi makro memicu pembatalan polis asuransi secara massal, khususnya polis unit-link lawas.
- **Analisis Kuantitatif:** Hilangnya polis masa depan merusak pemulihan CSM. $PV(\text{Future Profit}) \rightarrow 0$ pada polis yang batal.
- **Dampak pada SP:** Penurunan GWP *renewal* (yang diharapkan mendongkrak APE) berpotensi meleset jauh.
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 9.1 | Premium Holiday | 2026 | Aktifkan fitur *Premium Holiday* selama 3-6 bulan alih-alih membiarkan nasabah melakukan *surrender* (batal polis) penuh saat ekonomi sulit. |

### RISIKO 10: AI / Tech Investment ROI Failure 🟡
- **Deskripsi:** SP menganggarkan Rp 118 Miliar untuk modernisasi inti (*Gen AI*, Sistem Klaim *Cashless*). Asumsinya: ini akan menekan biaya operasi NCE menjadi 19.9%. Kegagalan implementasi adalah risiko IT klasik.
- **Analisis Kuantitatif:** Bila utilisasi AI meleset, *Non-IT operational expense* yang tumbuh 6% p.a. akan terus menggerus *Operating Earnings* tanpa ada bantalan efisiensi dari *software*.
- **Dampak pada SP:** Belanja modal IT hilang tanpa *return* berupa penghematan staf (yang tetap naik 6%).
- **Rekomendasi Mitigasi:**
  | # | Strategi | Timeline | Detail |
  |---|----------|----------|--------|
  | 10.1| Vendor Penalty Clause| 2026 | Buat kontrak SLA keras dengan vendor IT; penundaan serah terima dikenakan penalti untuk melindungi proyeksi beban perusahaan. |

### RISIKO 11: Non-Commission Expense (NCE) Inflation Exceeds Assumptions 🟡
- **Deskripsi:** SP mematok asumsi pertumbuhan biaya operasi (gaji, fasilitas, marketing) sebesar rata-rata datar 6% setiap tahun. Ini tidak realistis di negara berkembang bersuhu inflasi dinamis seperti Indonesia.
- **Analisis Kuantitatif:** $NCE Ratio = NCE / GWP$. Jika *top-line* GWP gagal tercapai tetapi NCE tetap membengkak mengikuti inflasi riil 8-10%, rasio NCE perusahaan tidak akan pernah turun ke angka 19.9%.
- **Dampak pada SP:** Keuntungan tergerus secara eksponensial di pos "Operational Expenses".
- **Rekomendasi Mitigasi:** Penghematan berbasis performa ketat (SLA) untuk staf pendukung (back-office) dan digitalisasi penuh tanpa merekrut staf operasional baru.

### RISIKO 12: Recruitment Target & Agent Quality Deterioration 🟡
- **Deskripsi:** Lonjakan target dari 1.000 menjadi 1.800 *Active Agents* berisiko memicu kanibalisme kualitas agen (merekrut agen kutu loncat atau minim literasi asuransi).
- **Analisis Kuantitatif:** *Case size* diasumsikan naik moderat dari IDR 23.6M ke 25.0M. Agen miskin kualitas cenderung melakukan *mis-selling* yang melonjakkan komplain dan pembatalan (lapse) tahun pertama.
- **Dampak pada SP:** Memicu *Sunk Cost* masif untuk ongkos pelatihan, lisensi AAJI, dan bonus sirkulasi.
- **Rekomendasi Mitigasi:** Pengetatan validasi AI *screening* (Agentic AI) khusus untuk mengevaluasi skor kredit dan riwayat penjualan calon agen sebelum disetujui.

### RISIKO 13: Investment Return Volatility (Equities & Bonds) 🟡
- **Deskripsi:** Tekanan pasar modal akan mengganggu dana investasi Unit-link dan mengurangi pendapatan asuransi melalui porsi FMC (*Fund Management Charge*).
- **Analisis Kuantitatif:** IHSG turun 25% → *Asset Under Management* (AUM) anjlok → *Fee Income* turun drastis, memukul *investment margin*.
- **Dampak pada SP:** Menghancurkan target keuntungan investasi sebesar IDR 4.3 Miliar di 2029.
- **Rekomendasi Mitigasi:** *De-risking* portofolio *proprietary* menuju instrumen pendapatan tetap terproteksi inflasi dan *cash-equivalent*.

### RISIKO 14: Perubahan Regulasi OJK & Minimum Solvency Margin 🟡
- **Deskripsi:** OJK secara aktif merevisi SEOJK (seperti SEOJK PAYDI) yang semakin memperketat kebebasan memungut biaya di awal (front-loading fee).
- **Analisis Kuantitatif:** Pengetatan ini menunda pengakuan laba dan menekan nilai tunai awal. Jika target *Solvency* (RBC) sewaktu-waktu direvisi minimum >150%, perusahaan bisa langsung diaudit.
- **Dampak pada SP:** Memaksa perubahan seketika pada rancangan komisi keagenan, mencederai strategi rekrutmen.
- **Rekomendasi Mitigasi:** Membangun cadangan solvabilitas internal (RBC internal limit 200%) agar kebal terhadap turbulensi regulasi.

### RISIKO 15: Cyber Security Breach pada Legacy System 🟡
- **Deskripsi:** Modernisasi arsitektur menuju sistem "Claim Cashless" yang terintegrasi (IDR 17.2 Miliar) membuka celah serangan peretas, khususnya *Ransomware* atau pencurian data medis nasabah.
- **Analisis Kuantitatif:** Denda denda pelanggaran UU PDP (Perlindungan Data Pribadi) dapat mencapai 2% dari pendapatan tahunan (Total GWP IDR 3T = denda hingga IDR 60 Miliar).
- **Dampak pada SP:** Menghapus seketika laba yang dicita-citakan di tahun terjadinya pelanggaran.
- **Rekomendasi Mitigasi:** Mewajibkan asuransi *Cyber Liability* internal dan uji penetrasi berkala setiap 6 bulan pada "Emma" dan platform klaim otomatis.

### RISIKO 16: Pandemic & Catastrophe Mortality Shock 🟢
- **Deskripsi:** Risiko *tail-end* terjadinya lonjakan tingkat kematian (Mortality Shock) akibat pandemi baru atau bencana alam mematikan massal.
- **Analisis Kuantitatif:** $\Delta BEL_{Mort} = BEL \times 0.15 \text{ (shock 15%)}$.
- **Dampak pada SP:** Berpengaruh secara sekunder karena produk yang dibeli lebih condong ke elemen tabungan jangka panjang alih-alih perlindungan risiko kematian murni tinggi (Sum Assured).
- **Rekomendasi Mitigasi:** Mengamankan proteksi reasuransi *Catastrophe Excess of Loss* secara ketat.

---
*Laporan Analisis Risiko Aktuaria Komprehensif Selesai.*