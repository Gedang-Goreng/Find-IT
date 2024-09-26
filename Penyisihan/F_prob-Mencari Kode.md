<h2 align="center">Problem F</h2>
<h1 align="center">Mencari Kode</h1>
<p align="center">Time limit: 1s</p>
<p align="center">Memory limit: 256mb</p>

#### **Deskripsi**
Vina (pacar Vini) merupakan seorang petualang. Pada suatu hari ia mendatangi kuil kuno di Vinisia, dan setelah melalui segala jebakan dan rintangan di dalam kuil ia sampai pada sebuah pintu yang besar sekali. Pintu tersebut sulit untuk dibuka. Kebetulan sekali, di bawah pintu tersebut Vina menemukan sebuah gulungan pintu besar berisi sebuah kata yang memiliki panjang _N_. Vina tahu, bahwa terdapat sebuah substring dari kata tersebut yang merupakan kunci dari pintu tersebut.

Vina menyadari bahwa pintu besar di depannya merupakan pintu yang simetris. Sehingga substring yang menjadi kunci dari pintu tersebut juga harus simetris (apabila dibaca dari kiri ke kanan maupun sebaliknya akan menghasilkan kata yang sama).

Vina yang menyadari informasi tersebut pun segera ingin mengetahui kata tersebut. Namun karena ia terburu - buru, ia hanya ingin mengetahui panjang kunci terpanjang yang mungkin dari pintu tersebut.
Bantulah ia!

Catatan: Sebuah string _x_ dapat dikatakan sebagai substring dari _y_ apabila _x_ bisa didapatkan dengan menghapus beberapa (boleh 0) huruf terdepan dan terbelakang _y_. Sebagai contoh ```BEB```, ```BE```, dan ```EBE```
merupakan substring dari ```BEBEK``` sementara ```KEB``` dan ```YEY``` bukan.

#### Format Masukan
- Baris pertama berisi sebuah bilangan bulat _N_ (1 ≤ N ≤ 2 ≤ \(10^{6}\)) yang menyatakan panjang kata pada gulungan.
- Baris kedua berisi string _S_ yang menyatakan kata yang dimaksud

#### Format Keluaran
- Keluarkan sebuah bilangan bulat yang menyatakan panjang kunci yang mungkin

#### Contoh Masukan 1
```
6
aabbaa
```

#### Contoh Keluaran 1
```
6
```

#### Contoh Masukan 2
```
5
abcbe
```

#### Contoh Keluaran 2
```
3
```
