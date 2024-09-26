<h2 align="center">Problem G</h2>
<h1 align="center">Mencari Penerbangan</h1>
<p align="center">Time limit: 1s</p>
<p align="center">Memory limit: 128mb</p>

#### **Deskripsi**
Vini merupakan seorang Software Engineer yang bekerja di negara Vinisia. Ia bertugas membuat program untuk mengendalikan sebuah robot ruang angkasa agar dapat melakukan perjalanan dengan aman.

Peta perjalanan robot luar angkasa ini dapat dinyatakan dalam koordinat dua dimensi. Mula - mula robot berada di titik (_$S_x$_, _$S_y$_) dan akan menuju titik (_$F_x$_, _$F_y$_). Di perjalanan, terdapat _N_ buah asteroid yang di nomori dari 1 hingga _N_. Setiap asteroid dapat digambarkan sebagai sebuah segmen garis yang memanjang dari titik _$A_i$_ menuju titik _$B_i$_.

Untuk menghemat biaya, Vini akan menerbangkan robot tersebut agar dapat menuju Venezia dengan
jarak seminimum mungkin tanpa menabrak asteroid apapun. Namun ternyata ia kesulitan dengan pekerjaan itu. Sebagai temannya yang baik, bantulah Vini untuk menentukan jarak minimum yang mungkin robot agar dapat mencapai tujuan dengan selamat! Catatan: Jarak antara 2 titik yang berbeda dinyatakan dalam jarak euclidean

#### Batasan
- 1 ≤ _$N$_ ≤ 200
- Semua titik pada koordinat kartesius akan memiliki komponen (_x_, _y_) dimana (1 ≤ _x_, _y_ ≤ _$10^8$_).
Dijamin nilai dari setiap pasangan (_x_, _y_) unik

#### Format Masukan
- Baris pertama berisi 4 bilangan bulat _$S_x$_, _$S_y$_, _$F_x$_, _$F_y$_ seperti pada soal
- Baris kedua berisi bilangan bulat _N_ yang menyatakan jumlah asteroid pada peta
- _N_ baris berikutnya merupakan bilangan bulat \(A_{ix}\), \(A_{iy}\), \(B_{ix}\), \(B_{iy}\) yang merupakan asteroid ke-_i_ merupakan segmen garis yang memanjang dari titik \(A_{ix}\) menuju titik \(B_{ix}\)

#### Format Keluaran
Jarak minimum yang dapat ditempuh robot Vini untuk mencapai tujuan dengan selamat. Keluarkan
jawaban dengan 2 angka di belakang koma. Jawaban akan dianggap benar apabila memiliki
perbedaan absolut dengan jawaban juri kurang dari \(10^{-3}\)

#### Contoh Masukan 1
```
0 0 22 0
2
12 -5 7 15
19 -20 18 3
```

#### Contoh Keluaran 1
```
28.00
```

#### Penjelasan Contoh 1
Berikut adalah contoh peta rintangan pada contoh masukan satu. Garis tebal merupakan contoh lintasan dengan jarak minimum pada peta.
<div style="text-align: center;">
    <img src=asset/G_image.png>
</div>

Maka jalur dengan jarak minimum yang tidak menabrak rintangan berturut - turut adalah jalur _S_, _$A_1$_, _$B_2$_, lalu _F_. Yaitu dengan jarak

= _S$A_1$_ + _$A_1$$B_2$_ + _$B_2$F_
= $\sqrt{(12 - 0)^2 + (-5 - 0)^2}$ + $\sqrt{(18 - 12)^2 + (3 - (-5))^2}$ + $\sqrt{(22 - 18)^2 + (0 - 3)^2}$
= $\sqrt{12^2 + 5^2}$ + $\sqrt{6^2 + 8^2}$ + $\sqrt{4^2 + 3^2}$
= 13 + 10 + 5
= 28.00

#### Contoh Masukan 2
```
2 2 6 3
1
4 0 4 4
```

#### Contoh Keluaran 2
```
5.06
```
