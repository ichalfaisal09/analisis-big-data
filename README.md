# Analisis Big Data - Case Study 1a

Analisis eksplorasi data **Seattle Cycle Share** (`trip.csv`, 236.065 trip, 13 Oktober 2014 - 31 Agustus 2016) dengan Python. Bahan: Bab 1 *Statistics and Probability* (Python Machine Learning Case Studies, D. Haroon).

## Isi repositori

| File | Keterangan |
|------|-----------|
| `2a_Listing_1-1_sd_1-14.ipynb` | Listing 1-1 s.d. 1-14 dari materi (disesuaikan ke Python 3), dijalankan dengan `trip.csv` |
| `2b_Soal_1a-1d_Multivariat.ipynb` | Distribusi jumlah trip per tahun, bulan, hari, dan harian, ditambah analisis multivariat |
| `2c_Analisis_Eksplorasi_Data.pdf` | Penjelasan analisis dari output tiap listing di 2a dan 2b |
| `trip.csv` | Dataset |

## Cara menjalankan

```
pip install notebook pandas matplotlib
jupyter notebook
```

Buka notebook, lalu pilih **Kernel > Restart Kernel and Run All Cells**. Letakkan `trip.csv` satu folder dengan notebook.

## Ringkasan temuan

- Member menyumbang 61,9% trip dan Short-Term Pass Holder 38,1%. Data gender dan tahun lahir hanya ada untuk Member.
- Jumlah trip sangat musiman: puncak Juli, terendah Desember.
- Member bersepeda terutama pada hari kerja dan jam sibuk (08:00 dan 17:00); Short-Term Pass Holder terutama pada akhir pekan.
- Pada periode Januari-Agustus, jumlah trip 2016 lebih rendah sekitar 28% daripada 2015.
