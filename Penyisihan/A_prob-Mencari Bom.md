<h2 align="center">Problem A</h2>
<h1 align="center">Mencari Bom</h1>
<p align="center">Time limit: 1s</p>
<p align="center">Memory limit: 128mb</p>

#### **Deskripsi**
Vini si penjinak bom sedang mendapatkan tugas untuk menjinakkan beberapa bom di Yogyakarta. Kota Yogyakarta tempat Vini bertugas terdiri dari _N_ daerah yang terhubung oleh _N - 1_ jalan. Untuk setiap jalan ke-_i_ dimana 1 ≤ _i_ ≤ _N - 1_ dapat ditempuh dalam waktu _W_. Selain itu, terdapat tepat _K_ daerah di Yogyakarta yang telah diberi bom. Pada mulanya, Vini berada di kota-1. Untuk menjinakkan bom di kota ke-_j_ , Vini harus bergerak menuju ke kota-_k_ melalui jalan - jalan pada kota yang ada.

Vini tahu bahwa seluruh bom akan meledak dalam satuan waktu. Oleh karena itu, bisa saja ia tidak mampu untuk menjinakkan seluruh bom yang ada karena keterbatasan waktu. Vini pun bertanya, apabila waktu untuk menjinakkan sebuah bom apabila Vini sudah sampai di daerah bom adalah satuan waktu, berapakah banyak bom maksimal yang dapat Vini jinakkan sebelum ia kehabisan waktu?

#### Format Masukan

- Baris pertama berisi 3 bilangan bulat _N_, _K_ dan _T_ dimana (1 ≤ _N_ ≤ 5000), (0 ≤ _K_ ≤ 100), dan (0 ≤ _T_ ≤ $10^9$)
- Baris kedua berisi _K_ bilangan bulat yang menunjukkan nomor daerah yang diberi bom. Untuk setiap daerah _$D_j$_ dimana (1 ≤ _j_ ≤ _K_) memenuhi (1 ≤ _$D_j$_ ≤ _N_)
- _N - 1_ baris berikutnya berisi _$U_i$_, _$V_i$_, dan _$W_i$_ dimana (1 ≤ _i_ ≤ _N − 1_), (1 ≤ _$U_i$_ ≤ _N_), (1 ≤ _$V_i$_ ≤ _N_), dan (0 ≤ _$W_i$_ ≤ $10^5$) menunjukkan bahwa kota _$U_i$_ dan _$V_i$_ terhubung oleh jalan sepanjang _$W_i$_

#### Format Keluaran
- Sebuah baris berisi bilangan bulat yang menyatakan berapa banyak bom maksimal yang dapat Vini
jinakkan sebelum ia kehabisan waktu

#### Contoh Masukan 1
```
4 2 4
2 4
1 3 1
3 4 1
3 2 1
```

#### Contoh Keluaran 1
```
2
```

#### Penjelasan Contoh 1
Berikut adalah illustrasi mengenai jalur yang dapat Vini ambil. Daerah yang diberi tanda silang adalah daerah yang diberi bom. Rute yang dilakukan Vini adalah 1 → 3 → 2 → 3 → 4 dengan total waktu perjalanan 1 + 1 + 1 + 1 = 4. Sehingga Vini hanya dapat memadamkan bom di daerah 2 dan 4.

<div style="text-align: center;">
    <img src=asset/A_image.png>
</div>

#### Contoh Masukan 2
```
4 2 4
2 4
1 3 1
3 4 2
3 2 1
```

#### Contoh Keluaran 2
```
1
```

#### Penjelasan Contoh 2
Pada contoh 2, Vini dapat mengambil 1 → 3 → 2 → 3 dengan total waktu perjalanan 1 + 1 + 1 = 3. Sehingga Vini hanya dapat memadamkan bom di daerah 2 saja.

<div style="text-align: center;">
    <img src=asset/A_image-1.png>
</div>
