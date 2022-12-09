# Jarkom-Modul-5-ITA07-2022

## Laporan Hasil Praktikum Modul 5 Kelompok ITA07

Anggota kelompok: 

| Nama                           | NRP          | 
| -------------------------------| -------------| 
| Naftali Salsabila Kanaya Putri    | `5027201012` | 
| Ariel Daffansyah Aliski           | `5027201058` | 
| Anak Agung Bintang Krisnadewi     | `5027201060` |

**Soal Shift Modul 5 - Firewall**

Adapun untuk topologi jaringan yang harus dibuat adalah sebagai berikut

![topo_soal](topologi_soal.jpg)

Berikut adalah hasil topologi yang kami buat beserta pembagian subnetnya

![topo](topo.png)

Berikut adalah perhitungan untuk pembagian IPnya:

| Nama Subnet | Jumlah Host | Alokasi | Netmask | Subnet Mask | Network ID | Assignable IP Range | Broadcast Address |
| --- | --- | --- | --- | --- | --- | --- | --- |
| A2 | 701 | 1022 | /22 | 255.255.252.0 | 10.43.0.0 | 10.43.0.1 - 10.43.3.254 | 10.43.3.255 |
| A7 | 256 | 510 | /23 | 255.255.254.0 | 10.43.4.0 | 10.43.4.1 - 10.43.5.254 | 10.43.5.255 |
| A6 | 201 | 254 | /24 | 255.255.255.0 | 10.43.6.0 | 10.43.6.1 - 10.43.6.254 | 10.43.6.255 |
| A3 | 63 | 126 | /25 | 255.255.255.128 | 10.43.7.0 | 10.43.7.1 - 10.43.7.126 | 10.43.7.127 |
| A1 | 3 | 6 | /29 | 255.255.255.248 | 10.43.7.128 | 10.43.7.129 - 10.43.7.134 | 10.43.7.135 |
| A8 | 3 | 6 | /29 | 255.255.255.248 | 10.43.7.136 | 10.43.7.137 - 10.43.7.142 | 10.43.7.143 |
| A4 | 2 | 2 | /30 | 255.255.255.252 | 10.43.7.144 | 10.43.7.145 - 10.43.7.146 | 10.43.7.147 |
| A5 | 2 | 2 | /30 | 255.255.255.252 | 10.43.7.148 | 10.43.7.149 - 10.43.7.150 | 10.43.7.151 |
| Total | 1231 |  | /21 |  |  |  |  |
