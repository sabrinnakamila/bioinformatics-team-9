# 🌸 STUDI _IN SILICO_ ANALISIS FILOGENETIK ANGGREK *Vanda* spp. MENGGUNAKAN GEN matK, rbcL, DAN trnL

> Analisis ini bertujuan mengungkap potensi gen *matK*, *rbcL*, *trnL* sebagai penanda DNA barcode molekuler pada anggrek spesies *Vanda* beserta hubungan evolusinya dalam Orchidaceae secara *in silico*.

<sub>📌 **Referensi Utama:** Metodologi dan acuan dasar analisis filogenetik dalam studi ini mengacu pada [Sahadeva & Pertiwi (2023)](#-referensi-utama) dan studi barcoding Orchidaceae terkait. </sub>
---

## 📖 Pendahuluan
### Filogenetik dengan MEGA

**Filogenetik** adalah ilmu yang mempelajari hubungan evolusioner antar organisme. Analisis filogenetik molekuler dilakukan dengan membandingkan sekuens DNA (seperti **ITS, matK, rbcL**) dari berbagai spesies untuk membangun **pohon filogenetik** (*phylogenetic tree*).

**MEGA** (*Molecular Evolutionary Genetics Analysis*) adalah perangkat lunak bioinformatika yang digunakan secara luas untuk:
- Penyelarasan sekuens (*multiple sequence alignment*)
- Rekonstruksi pohon filogenetik (Neighbor-Joining, Maximum Likelihood, UPGMA, etc.)
- Analisis jarak genetik antar takson
- Uji statistik bootstrap untuk mengevaluasi keandalan topologi pohon

> Analisis ini bertujuan mengungkap potensi gen _matK, rbcL_, dan _trnL_ sebagai penanda DNA barcode molekuler pada anggrek spesies *Vanda* dan hubungan evolusinya dalam Orchidaceae secara lebih luas secara _in Silico_
---

## 👥 Anggota Kelompok

| No | Nama | NIM |
|----|------|-----|
| 1  | Kamila Tsamara Yofana | (23/514583/BI/11195)
| 2  | Intania Mustofa | (23/514735/BI/11204) 
| 3  | Nur Fatimah Ratna Handayani | (23/518359/BI/11286)
| 4  | Latifa Fitri Alviani | (23/521198/BI/11341)
| 5  | Kamila Miza Sabrina | (23/523324/BI/11385)

---

## 💻 Tata Cara Penggunaan Software MEGA

### Prasyarat
- Unduh dan instal **MEGA versi terbaru** dari [https://www.megasoftware.net](https://www.megasoftware.net)
- Sekuens DNA dalam format `.fasta`
- Akses internet untuk mengunduh sekuens dari NCBI dan EBI

### Langkah 1 — Persiapan Sekuens

1. Buka NCBI (https://www.ncbi.nlm.nih.gov/) atau EBI (https://www.ebi.ac.uk/)
2. Cari sekuens gen _matK, rbcL_, dan _trnL_ untuk 10 spesies _Vanda_ + outgroup _Phalaenopsis deliciosa_
3. Unduh semua sekuens dalam format FASTA

### Langkah 2 — Multiple Sequence Alignment

1. Buka MEGA 12 → File → Open a File/Session
2. Import file FASTA > Align
3. Jalankan alignment: Alignment > Align by ClustalW
4. Trimming bagian awal dan akhir sekuens untuk menyeragamkan panjang basa
5. Ekspor hasil: Data > Export Alignment > MEGA Format (`.meg`)

### Langkah 3 — Rekonstruksi Pohon Filogenetik

1. Dari menu utama MEGA 12, klik Phylogeny > Construct/Test Neighbor-Joining Tree
2. Pilih file .meg hasil alignment
3. Atur parameter:
   - Model: Kimura 2-Parameter
   - Bootstrap replications: 1000
4. Klik Compute dan tunggu proses selesai

### Langkah 4 — Visualisasi dan Ekspor Pohon

1. Pohon tampil di Tree Explorer
2. File > Export Current Tree → simpan sebagai PNG

---

## 📈🌳 Hasil Analisis

### Pohon Filogenetik *Vanda* spp. - Marker _matK_
![Pohon filogenetik matK](PhyloTree/Pohon%20filogeni%20matK.png)

### Pohon Filogenetik *Vanda* spp. - Marker _rbcL_
![Pohon filogenetik matK](PhyloTree/Pohon%20filogeni%20rbcL.png)

### Pohon Filogenetik *Vanda* spp. - Marker _trnL_
![Pohon filogenetik trnL](PhyloTree/Pohon%20filogeni%20trnL.jpeg)

## 📄 Dokumen Pendukung

| Dokumen | Format | Unduh |
|---------|--------|-------|
| 📃 Makalah | PDF | [Unduh Makalah](Files/Paper.pdf) |
| 🖼️ Presentation | PDF | [Unduh Presentasi](Files/Presentation.pdf) |
| 🖼️ Poster | PNG | [Unduh Poster](File/poster.png) |

---

## 🔬 Referensi

### 📌Referensi Utama
> Sahadeva, M.L. and Pertiwi, N.P.D. (2023). Konstruksi Pohon Filogenetik Spesies dalam Famili Orchidaceae Berdasarkan Marka Gen matK Kloroplas: Studi in Silico. _Wahana Matematika dan Sains: Jurnal Matematika, Sains, dan Pembelajarannya_, 17(3), pp.12-27. https://doi.org/10.23887/wms.v17i3.87986
### 📚Referensi Pendukung
- CBOL Plant Working Group. (2009). A DNA barcode for land plants. _Proceedings of the National Academy of Sciences of the United States of America_, 106(31), 12794–12797. https://doi.org/10.1073/pnas.0905845106
- Tamura, K., Stecher, G., & Kumar, S. (2021). MEGA11: Molecular Evolutionary Genetics Analysis Version 11. *Molecular Biology and Evolution*, 38(7), 3022-3027.

---
