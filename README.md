Petunjuk File
JUDUL SKRIPSI: Attention-Driven Hybrid Model untuk Klasifikasi Jaringan Kolorektal


01. File tulisan skripsi (.pdf) dan presentasi pendadaran (.pptx)
02. Dataset original berupa citra histopatologi jaringan kolorektal yang terdiri dari 8 kategori dengan 01_TUMOR sebagai
    citra positif kanker dan 06_TUMOR sebagai citra sel normal dari struktur utama (negatif kanker). Dataset original
    dapat diakses pada Zenodo (https://zenodo.org/records/53169)
03. Citra hasil image enhancement menggunakan metode stain normalization Vahadane dan penjasaman unsharp masking.
04. Implementasi utama yang dilakukan pada skripsi dengan file "01_Main Implementation" adalah metode deep learning dan
    "02_Visualisasi Occlusion-new" adalah metode visualisasi area yang paling berpengaruh sebelum final layer klasifikasi.
    File 03 adalah model dengan best result dan file 04 adalah confusion matrix-nya.
05. Implementasi seperti folder 04 tetapi menyesuaikan splitting data seperti paper yang ingin di-compare karena adanya
    data untuk testing.
