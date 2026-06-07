# Laporan Praktikum Jarkom

# Langkah Percobaan
1. 13.2
2. 133



# Lampiran
# 13.2 Menangkap dan menganalisis frame Ethernet
1. ketik http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-lab-file3.html
![Hasil Percobaan](../assets/13.2.1.png)
2. filter http untuk menemukan HTTP GET untuk http://gaia.cs.umass.edu/wireshark-labs/HTTPwireshark-file3.html
![Hasil Percobaan](../assets/13.2.2.png)
3. pilih Analyze -> Enabled Protocols. Kemudian hapus centang pada kotak IP dan pilih OK.
![Hasil Percobaan](../assets/13.2.3.png)
4. Tampilan Wireshark yang menampilkan detail frame Ethernet yang berisi permintaan HTTP GET
![Hasil Percobaan](../assets/13.2.4.png)
# 13.3 Address Resolution Protocol
1. ketik arp -d * di cmd Run as administrator
![Hasil Percobaan](../assets/13.3.1png)
2. ketik http://gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-lab-file3.html
![Hasil Percobaan](../assets/13.3.2.png)
3.  Permintaan ARP yang disiarkan dari salah satu komputer
![Hasil Percobaan](../assets/13.3.3.png)
