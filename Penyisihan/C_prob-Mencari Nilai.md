<h2 align="center">Problem C</h2>
<h1 align="center">Mencari Nilai</h1>
<p align="center">Time limit: 1s</p>
<p align="center">Memory limit: 64mb</p>

#### **Deskripsi**
Vini merupakan seorang mahasiswa yang sedang mengikuti Ujian Tengah Semester di kampusnya. Pada saat ujian, Vini melihat bahwa ada _N_ soal yang diberikan. Soal - soal tersebut dinomori dari 1 hingga _N_. Masing - masing soal memiliki bobot sebesar _$B_i$_ untuk (1 ≤ _i_ ≤ _N_) dengan total poin keseluruhan soal sebanyak _K_.

Setelah selesai ujian, untuk setiap soal _i_ dimana (1 ≤ _i_ ≤ _N_) Vini hanya bisa mengerjakan _$X_i$_ bagian dari soal ke-_i_ tersebut. Vini tahu bahwa nilai yang ia didapatkan dari mengerjakan _$X_i$_ bagian dari soal ke-_i_ adalah _$B_i$_ x _$X_i$_ %.  Selain itu, ia juga tahu bahwa nilai minimal yang ia perlukan untuk lulus pada ujian tersebut adalah _R_. Vini yang panik pun bertanya kepada Anda, apakah Vini akan lulus dengan nilai yang ia
miliki?

#### Format Masukan
- Baris pertama berisi 3 bilangan bulat _N_, _R_ dan _K_ dimana (1 ≤ _N_ ≤ _$10^3$_) dan (1 ≤ _R_ ≤ _K_ ≤ _$10^7$_) yang menunjukkan banyak soal ujian, nilai minimum agar dapat lulus di ujian itu, nilai maksimum dari keseluruhan soal.
- Baris kedua berisi _N_ bilangan bulat _$B_i$_ untuk setiap (1 ≤ _i_ ≤ _N_) dimana (1 ≤ _$B_i$_ ≤ _$10^4$_) yang menyatakan bobot dari soal - soal yang diberikan. Dijamin _$B_i$_ merupakan kelipatan 100.
- Baris berikutnya berisi _N_ bilangan bulat _$X_i$_ untuk setiap (1 ≤ _i_ ≤ _N_) dimana  (1 ≤ _$X_i$_ ≤ 100) yang menyatakan besar bagian dari soal-_i_
yang berhasil Vini selesaikan.

#### Format Keluaran
- Sebuah string yang menyatakan apakah Vini lulus pada ujian itu atau tidak. Apabila lulus, keluarkan ```PASS``` dan ```NOT PASS``` jika tidak.

#### Contoh Masukan 1
```
4 200 1000
100 200 300 400
40 30 20 10
```

#### Contoh Keluaran 1
```
PASS
```

#### Penjelasan Contoh 1
Pada kasus ini, Vini mendapatkan 40 + 60 + 60 + 40 = 200. Karena nilai Vini ≥ _R_ , maka ia lulus pada ujian itu.

#### Contoh Masukan 2
```
4 200 1000
100 200 300 400
10 30 20 10
```

#### Contoh Keluaran 2
```
NOT PASS
```

#### Penjelasan Contoh 2
Pada kasus ini, Vini mendapatkan 10 + 60 + 60 + 40 = 170. Karena nilai Vini < _R_ , maka ia tidak lulus pada ujian itu.
