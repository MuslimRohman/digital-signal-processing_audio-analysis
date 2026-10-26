# Analisis dan Pengenalan Sinyal Audio Menggunakan FFT dan MFCC

**Pengolahan Sinyal Digital | Audio Processing | Python**

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis pengaruh filtering sinyal audio terhadap karakteristik suara dan melakukan identifikasi pembicara berdasarkan pengucapan kata **"halo"**.

Analisis dilakukan menggunakan **Band-Pass Filter**, **Fast Fourier Transform (FFT)**, dan **Mel-Frequency Cepstral Coefficients (MFCC)** untuk membandingkan karakteristik sinyal sebelum dan sesudah filtering serta mengenali pembicara berdasarkan fitur suara.

## Tools & Libraries
- **Python** – Pengolahan dan analisis sinyal audio.
- **Librosa** – Pemrosesan audio dan ekstraksi fitur MFCC.
- **NumPy** – Perhitungan numerik dan FFT.
- **SciPy** – Penerapan Band-Pass Filter Butterworth.
- **Matplotlib** – Visualisasi spektrum frekuensi.
- **Jupyter Notebook** – Pengembangan dan dokumentasi analisis.

## Tahapan Proyek
1. **Data Collection:** Mengumpulkan 30 rekaman pengucapan kata "halo" dari tiga pembicara.
2. **Audio Filtering:** Menerapkan Band-Pass Filter dengan frekuensi cutoff 80–1100 Hz.
3. **Analisis Spektral:** Membandingkan spektrum frekuensi menggunakan FFT sebelum dan sesudah filtering.
4. **Feature Extraction:** Mengekstraksi 50 koefisien MFCC untuk merepresentasikan karakteristik suara.
5. **Speaker Identification:** Mengidentifikasi pembicara berdasarkan jarak Euclidean terdekat.

## Hasil Analisis
- Band-Pass Filter mampu meredam komponen frekuensi di luar rentang cutoff.
- Analisis FFT memperlihatkan perubahan distribusi spektrum sebelum dan sesudah filtering.
- Ekstraksi MFCC menghasilkan representasi numerik karakteristik suara setiap pembicara.
- Identifikasi pembicara berhasil dilakukan pada contoh pengujian menggunakan jarak Euclidean terkecil.

## Struktur Repository

- `Dataset/` — Dataset rekaman audio yang digunakan dalam proyek, dikelompokkan berdasarkan pembicara.
  - `Farel/` — Rekaman suara Farel.
  - `Kafka/` — Rekaman suara Kafka.
  - `Rama/` — Rekaman suara Rama.
- `Source Code/` — Folder berisi kode program pengolahan sinyal digital.
  - `PSD_Final_Kelompok_5.ipynb` — Notebook Python untuk filtering audio, analisis FFT, ekstraksi MFCC, dan identifikasi pembicara.
- `Laporan/` — Folder dokumentasi proyek.
  - `Laporan_PSD_Kelompok 5.pdf` — Laporan akhir proyek.
  - `PPT PSD Final_Kelompok 5.pdf` — Materi presentasi.
- `README.md` — Dokumentasi repository.

## Anggota Tim
- **Muslim Fazlur Rohman**
- **Muhammad Ramadhan Albaary Putra**
- **Kafka Praya Firmansyah**

**Program Studi Sains Data | Universitas Negeri Surabaya | 2025**
