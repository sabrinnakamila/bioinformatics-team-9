# 🌸 STUDI IN SILICO ANALISIS FILOGENETIK ANGGREK *Vanda* spp. MENGGUNAKAN GEN matK, rbcL, DAN trnL

> Studi kekerabatan molekuler pada anggrek genus *Vanda* berbasis sekuens DNA dengan perangkat lunak MEGA (Molecular Evolutionary Genetics Analysis)

---

## 📖 Pendahuluan

### *Vanda* spp.

blablabla

### Filogenetik dengan MEGA

**Filogenetik** adalah ilmu yang mempelajari hubungan evolusioner antar organisme. Analisis filogenetik molekuler dilakukan dengan membandingkan sekuens DNA (seperti **ITS, matK, rbcL**) dari berbagai spesies untuk membangun **pohon filogenetik** (*phylogenetic tree*).

**MEGA** (*Molecular Evolutionary Genetics Analysis*) adalah perangkat lunak bioinformatika yang digunakan secara luas untuk:
- Penyelarasan sekuens (*multiple sequence alignment*)
- Rekonstruksi pohon filogenetik (Neighbor-Joining, Maximum Likelihood, UPGMA)
- Analisis jarak genetik antar takson
- Uji statistik bootstrap untuk mengevaluasi keandalan topologi pohon

Analisis ini bertujuan mengungkap hubungan kekerabatan antar spesies *Vanda* dan posisinya dalam konteks evolusi Orchidaceae secara lebih luas.

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

---

### Langkah 1 — Persiapan Sekuens

1. Buka NCBI (https://www.ncbi.nlm.nih.gov/) atau EBI (https://www.ebi.ac.uk/)
2. Cari sekuens gen _matK, rbcL_, dan _trnL_ untuk 10 spesies _Vanda_ + outgroup _Phalaenopsis deliciosa_
3. Unduh semua sekuens dalam format FASTA

---

### Langkah 2 — Multiple Sequence Alignment

1. Buka MEGA 12 → File → Open a File/Session
2. Import file FASTA > Align
3. Jalankan alignment: Alignment > Align by ClustalW
4. Trimming_ bagian awal dan akhir sekuens untuk menyeragamkan panjang basa
5. Ekspor hasil: Data > Export Alignment > MEGA Format (.meg)

---

### Langkah 3 — Rekonstruksi Pohon Filogenetik

1. Dari menu utama MEGA 12, klik Phylogeny > Construct/Test Neighbor-Joining Tree
2. Pilih file .meg hasil alignment
3. Atur parameter:
   - Model: Kimura 2-Parameter
   - Bootstrap replications: 1000
4. Klik Compute dan tunggu proses selesai

---

### Langkah 4 — Visualisasi dan Ekspor Pohon

1. Pohon tampil di Tree Explorer
2. File > Export Current Tree → simpan sebagai PNG

---

## 📈🌳 Hasil Analisis

### Pohon Filogenetik *Vanda* spp. - Marker matK
![Pohon filogenetik matK](PhyloTree/Pohon%20filogeni%20matK.png)
**Gambar 1. Pohon filogenetik _Vanda_ spp. berdasarkan sekuens matK**

### Pohon Filogenetik *Vanda* spp. - Marker rbcL
![Pohon filogenetik matK](PhyloTree/Pohon%20filogeni%20rbcL.png)
**Gambar 2. Pohon filogenetik _Vanda_ spp. berdasarkan sekuens rbcL**

### Pohon Filogenetik *Vanda* spp. - Marker trnL
![Pohon filogenetik matK](PhyloTree/Pohon%20filogeni%20rbcL.png)
**Gambar 3. Pohon filogenetik _Vanda_ spp. berdasarkan sekuens trnL**

---

## 📄 Dokumen

| Dokumen | Format | Unduh |
|---------|--------|-------|
| 📃 Makalah — Analisis Filogenetik *Vanda* spp. | PDF | [📥 Unduh Makalah](dokumen/makalah_filogenetik_vanda.pdf) |
| 🖼️ Poster Ilmiah | PDF | [📥 Unduh Poster](dokumen/poster_filogenetik_vanda.pdf) |

---

## 🔬 Referensi

- Kumar, S., Stecher, G., Li, M., Knyaz, C., & Tamura, K. (2018). MEGA X: Molecular Evolutionary Genetics Analysis across computing platforms. *Molecular Biology and Evolution*, 35(6), 1547–1549.
- Christenson, E. A. (1994). *Vanda* Miss Joaquim — is it a natural hybrid? *American Orchid Society Bulletin*, 63, 1030–1038.
- NCBI GenBank. (2024). *National Center for Biotechnology Information*. https://www.ncbi.nlm.nih.gov
- Chase, M. W., et al. (2015). An updated classification of Orchidaceae. *Botanical Journal of the Linnean Society*, 177(2), 151–174.

---
