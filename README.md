# LAPORAN HASIL PRAKTIKUM
| Nama        | Fathur Rahman |
|--------------|------------|
| NIM        | 09030282327047 |
| Program Studi | Teknik Komputer |

## Judul Tugas
**Analisis Traffic Jaringan**

<div>
<br>Praktikum ini akan melakukan analisis Quality of Service (QoS) menggunakan wireshark.
<br>1. Pastikan terhubung pada internet

<br>2. Buka aplikasi wireshark, lalu pilih wifi <br>
<img src="https://github.com/user-attachments/assets/caf36c1a-92eb-4cd1-87fd-acd142e7afa7" width="300">

<br>3. Jalankan wireshark untuk capture packet

<img src="https://github.com/user-attachments/assets/6be627eb-665a-4f38-81f3-597b5f4d5c50" width="300">

<br>4. Selanjutnya melakukan kegiatan dilaptop seperti mendownload gambar dan menonton Youtube.
<br>5. Setelah selesai, mengklik ikon kotak merah untuk stop capturing paket <br>
<img src="https://github.com/user-attachments/assets/f4c16f29-43ba-46c2-bbfb-b8e0634c5e76" width="300">

<br>6. Selanjutnya tekan Statistics > Caputre File Properties, untuk melihat properties dari packet capture yg dilakukan
<img src="https://github.com/user-attachments/assets/2952a35e-3fa7-41c1-8c7d-b97128de9865" width="300">

<br>7. Melihat packet lost dengan mengetik tcp.analysis.lost_segment<br>
<img src="https://github.com/user-attachments/assets/14398434-5c85-4365-8700-ea17a0038ad7" width="300">

<br>8. Perhatikan bagian statics pada Properties untuk melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.
<img src="https://github.com/user-attachments/assets/ab6a0309-fb99-4a70-8957-fa46f809bba4" width="300">


<br>9. Perhitungan Throughput, Packet Loss, Delay, dan Jitter.<br>
<img src="https://github.com/user-attachments/assets/f28d0eed-6869-402b-b927-a49efec3aa87" width="300">

**Througput:**<br>
throughtput:<br>
jumlah byte : time span = hasil byte <br>
9067431 : 106.835 = 84,87322506669163 b x 8 = 678,985800533533 k<br><br>
**Packet Loss:**
**Packet dikirim Loss:**<br>
packet loss :<br>
(((paket dikirim - paket diterima ) : paket dikirim ) x 100)<br>
= ( 8579 - 8574 ) : 8579) x 100<br>
= ( 5 : 8579 ) x 100<br>
= 0,05 ( 0,1)<br><br>
**Delay:**
Total **Delay:**<br>
delay <br>
total delay :  106,834737 s<br>
rata rata delay : 0,012453052 s x 1000 =  12,453052 ms<br><br>
**Jitter:**
Total **Jitter:** <br>
jitter:<br>
total jitter  : -1,08761 s<br>
rata rata jitter : -0,000126776 s x 1000 = -0,126776 ms
<br><br>
<br>10. Setelah mendapatkan hasil perhitungan, selanjutnya ialah mengisi tabel indeks yang didapatkandari pengukuran QoS.
<img src="https://github.com/user-attachments/assets/279ff601-5e82-4fe8-9600-a49bef1d3488" Setelah width="300">
<br>
mendapatkan hasil perhitungan, selanjutnya ialah mengisi tabel indeks yang didapatkandari pengukuran QoS.
<br>
<img src="https://github.com/user-attachments/assets/f28d0eed-6869-402b-b927-a49efec3aa87" width="300">
<br> <br>**KESIMPULAN**
<br> Pada **KESIMPULAN** perhitungan QoS ini hasil Throughput, Packet Loss, dan Delay masuk kategori Sangat Bagus, yang menunjukkan jaringan cepat dan stabil dalam pengiriman data. Jitter masuk kategori Buruk, yang berarti ada variasi waktu antar paket yang sangat tinggi, berpotensi menyebabkan gangguan dalam komunikasi real-time. Jadi, jaringan ini sangat baik dalam kecepatan dan kestabilan latensi, tetapi jitter yang tinggi bisa menjadi masalah untuk aplikasi real-time.
<br> Pada perhitungan QoS ini hasil Throughput, Packet Loss, dan Delay masuk kategori Sangat Bagus, yang menunjukkan jaringan cepat dan stabil dalam pengiriman data. Jitter masuk kategori Buruk, yang berarti ada variasi waktu antar paket yang sangat tinggi, berpotensi menyebabkan gangguan dalam komunikasi real-time. Jadi, jaringan ini sangat baik dalam kecepatan dan kestabilan latensi, tetapi jitter yang tinggi bisa menjadi masalah untuk aplikasi real-time.
<br> </div>
</div>
