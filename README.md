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
<img src="https://github.com/user-attachments/assets/b2df0f6b-3d42-440e-b5ac-402aa2ee4ab4" width="300">

<br>3. Jalankan wireshark untuk capture packet

<img src="https://github.com/user-attachments/assets/825efd1d-056e-477d-b892-33e7dfc3a47b" width="300">

<br>4. Selanjutnya melakukan kegiatan dilaptop seperti mendownload gambar dan menonton Youtube.
<br>5. Setelah selesai, mengklik ikon kotak merah untuk stop capturing paket <br>
<img src="https://github.com/user-attachments/assets/f4c16f29-43ba-46c2-bbfb-b8e0634c5e76" width="300">

<br>6. Selanjutnya tekan Statistics > Caputre File Properties, untuk melihat properties dari packet capture yg dilakukan <br>
<img src="https://github.com/user-attachments/assets/2952a35e-3fa7-41c1-8c7d-b97128de9865" width="300">

<br>7. Melihat packet lost dengan mengetik tcp.analysis.lost_segment<br>
<img src="https://github.com/user-attachments/assets/fd4d7dc2-21f0-45e8-91e5-bff0a4bfe26f" width="300">

<br>8. Perhatikan bagian statics pada Properties untuk melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.<br>
<img src="https://github.com/user-attachments/assets/a87868f8-2175-4878-a8da-77c31f40c0d2" width="300">


<br>9. Perhitungan Throughput, Packet Loss, Delay, dan Jitter.<br>
<img src="https://github.com/user-attachments/assets/ddeb4788-6e8d-41d9-9f87-feb8d9aa7670" width="300">

**Througput:**<br>
throughtput:<br>
jumlah byte : time span = hasil byte <br>
143127 : 195.571 = 731.8416329619422 b x 8 = 5.854 <br><br>
**Packet Loss:**
**Packet dikirim Loss:**<br>
packet loss :<br>
(((paket dikirim - paket diterima ) : paket dikirim ) x 100)<br>
= ( 822 - 820 ) : 822) x 100<br>
= ( 2 : 822 ) x 100<br>
= 0,2 <br><br>
**Delay:**
Total **Delay:**<br>
delay <br>
total delay :  195,571234 s<br>
rata rata delay : 0,237921209 s x 1000 =  237,921209 ms<br><br>
**Jitter:**
Total **Jitter:** <br>
jitter:<br>
total jitter  : 2,058627 s<br>
rata rata jitter : 0,002504412 s x 1000 = 2,504412 ms
<br><br>
<br>10.
mendapatkan hasil perhitungan, selanjutnya ialah mengisi tabel yang didapatkan dari pengukuran QoS.
<br>
<img src="https://github.com/user-attachments/assets/ddeb4788-6e8d-41d9-9f87-feb8d9aa7670" width="300">
<br> <br>**KESIMPULAN**
<br> Pada **KESIMPULAN** perhitungan QoS ini hasil Throughput, Packet Loss, dan Delay masuk kategori Sangat Bagus, yang menunjukkan jaringan cepat dan stabil dalam pengiriman data. Jitter masuk kategori Buruk, yang berarti ada variasi waktu antar paket yang sangat tinggi, berpotensi menyebabkan gangguan dalam komunikasi real-time. Jadi, jaringan ini sangat baik dalam kecepatan dan kestabilan latensi, tetapi jitter yang tinggi bisa menjadi masalah untuk aplikasi real-time.
<br> Pada perhitungan QoS ini hasil Throughput, Packet Loss, dan Delay masuk kategori Sangat Bagus, yang menunjukkan jaringan cepat dan stabil dalam pengiriman data. Jitter masuk kategori Buruk, yang berarti ada variasi waktu antar paket yang sangat tinggi, berpotensi menyebabkan gangguan dalam komunikasi real-time. Jadi, jaringan ini sangat baik dalam kecepatan dan kestabilan latensi, tetapi jitter yang tinggi bisa menjadi masalah untuk aplikasi real-time.
<br> </div>
</div>
