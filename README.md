# README
Analisis ini menggunakan metode Product Affinity and Lift Analysis yang menggabungkan dua metrik statistik utama untuk akurasi maksimal. Berikut adalah variabel yang digunakan : 
  1. Confidence Score (C) : Mengukur tingkat kepastian, seberapa sering Produk B dibeli ketika konsumen membeli Produk A.
  2. Lift Score (L): Mengukur kekuatan hubungan, memastikan bahwa pembelian bersama tersebut bukanlah suatu kebetulan.
  3. ΣR-Rank (Sigma R-Rank) / Unique Rank: Penjumlahan dari peringkat Confidence (R.C) dan peringkat Lift (R.L)

Cara Membaca Analisa : 
  1. Confidence mengukur seberapa sering Produk B dibeli ketika seseorang membeli Produk A. Ini menunjukkan tingkat "populer" atau "pasti" dari sebuah pasangan produk di mata konsumen. (Jika Confidence Produk A -> Produk B adalah 20%, artinya dari 100 orang yang membeli Produk A, ada 20 orang yang juga memasukkan Produk B ke keranjang mereka.)
  3. Lift Score mengukur apakah hubungan antara dua produk tersebut memang nyata (berpola) atau hanya terjadi secara kebetulan.
     - Lift > 1 : Menunjukkan hubungan yang Sangat Kuat. Konsumen jauh lebih mungkin membeli Produk B karena mereka membeli Produk A.
     - Lift = 1 : Tidak ada hubungan khusus, pembelian terjadi secara acak
     - Lift < 1 : Hubungan lemah atau produk tersebut saling menggantikan (substitusi).




