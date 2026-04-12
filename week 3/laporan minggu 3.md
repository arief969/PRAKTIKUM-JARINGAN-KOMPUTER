# Laporan Praktikum Jarkom

# Langkah Percobaan
1. 3.2
2. 3.2.1
3. 3.3
4. 3.4
5. 3.5

# Lampiran


# 3.2 Basic HTTP GET/response interaction
# Membuka aplikasi Wireshark dan memilih interface Wi-Fi yang sedang aktif.
![Hasil Percobaan](../assets/3.2.no1.png)
# Menerapkan display filter http untuk membatasi paket yang tertangkap
![Hasil Percobaan](../assets/3.2.no2.png)
# Mengakses URL http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file1.html melalui Chrome.
![Hasil Percobaan](../assets/3.2.no3.png)
#  Menganalisis GET (No. 3384)
![Hasil Percobaan](../assets/3.2.no4.png)

# 3.2.1 HTTP CONDITIONAL GET/response interaction
#  Bersihkan cache browser
![Hasil Percobaan](../assets/3.2.1.no1.png)
# Jalankan Wireshark dengan filter http
![Hasil Percobaan](../assets/3.2.1.no2.png)
#  Mengakses URL http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file2.htmlmelalui browser Chrome dan Tekan tombol Refresh pada browser untuk memicupengambilan data bersyarat
![Hasil Percobaan](../assets/3.2.1.no3.png)
#  Menganalisis 1336 dan 1364 (Akses Pertama) serta 1389 dan 1401. (Akses Kedua).1336
![Hasil Percobaan](../assets/3.2.1.no4.png)
# 1364
![Hasil Percobaan](../assets/3.2.1.no5.png)
# 1389
![Hasil Percobaan](../assets/3.2.1.no6.png)
# 1401
![Hasil Percobaan](../assets/3.2.1.no7.png)


# 3.3 Retrieving Long Documents
# Menghapus cache browser
![Hasil Percobaan](../assets/3.3.1.png)
# Jalankan Wireshark dengan filter http
![Hasil Percobaan](../assets/3.3.2.png)
# Mengakses URL http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file3.html.
![Hasil Percobaan](../assets/3.3.3.png)
# Menghapus display filter http
![Hasil Percobaan](../assets/3.3.4.png)
# Mengamati paket TCP (No. 3175) dan TCP (No. 3177)
# TCP (No. 3175)
![Hasil Percobaan](../assets/3.3.5.png)
# TCP (No. 3177)
![Hasil Percobaan](../assets/3.3.6.png)
# Menganalisis HTTP 200 OK (No. 3178)
![Hasil Percobaan](../assets/3.3.7.png)

# 3.4 HTML Documents dengan Embedded Objects
# Menghapus cache browser pada menu Settings
![Hasil Percobaan](../assets/3.4.1.png)
# Menjalankan Wireshark dengan display filter http
![Hasil Percobaan](../assets/3.4.2.png)
# Mengakses URL http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file4.html.
![Hasil Percobaan](../assets/3.4.3.png)
# Mengamati munculnya halaman HTML yang berisi teks serta dua buah gambar (LogoPearson dan Cover Buku).
# 1056 (pearson.png)
![Hasil Percobaan](../assets/3.4.4.png)
# 1166 (8E_cover_small.jpg)
![Hasil Percobaan](../assets/3.4.5.png)
# Menganalisis paket GET (No. 1015)
![Hasil Percobaan](../assets/3.4.6.png)


# 3.5  HTTP Authentication
# Menghapus cache browser melalui menu Settings
![Hasil Percobaan](../assets/3.5.1.png)
# Menjalankan Wireshark dan menerapkan display filter http

![Hasil Percobaan](../assets/3.5.2.png)
#  Mengakses URL http://gaia.cs.umass.edu/wireshark-labs/protected_pages/HTTPwireshark-file5.html dan memasukkan username wireshark-students serta password network pada kotak dialog yang muncul.
![Hasil Percobaan](../assets/3.5.3.png)
# get (No. 301)
![Hasil Percobaan](../assets/3.5.4.png)
# 401 Unauthorized (No. 311)
![Hasil Percobaan](../assets/3.5.5.png)
# ET dengan Authorization (No. 1219)
![Hasil Percobaan](../assets/3.5.6.png)