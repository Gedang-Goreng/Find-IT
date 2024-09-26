<h2 align="center">Problem D</h2>
<h1 align="center">Mencari Batu</h1>
<p align="center">Time limit: 1.2s</p>
<p align="center">Memory limit: 512mb</p>

#### **Deskripsi**
Di sebuah desa terpencil di lereng gunung, terdapat seorang penduduk bernama Vidi yang gemar bermain dengan batu-batu kecil. Setiap harinya, ia mengumpulkan sejumlah batu dan menyusunnya dengan rapi dalam satu baris. Tiap batu memiliki nilai keunikan masing - masing yang direpresentasikan dalam bilangan bulat.

Suatu hari, datanglah seorang teman akrab Vini yang bernama Vidi. Mereka pun memutuskan untuk bermain sebuah permainan dengan batu-batu tersebut. Dalam setiap ronde, Vini harus membagi barisan batu tersebut menjadi dua baris tak kosong, yakni baris kiri dan baris kanan. Kemudian, tugas Vidi adalah menghitung jumlahan nilai dari batu - batu di kedua baris tersebut.

Namun, ada suatu aturan menarik yang harus diikuti. Di setiap ronde, Vidi harus membuang baris yang memiliki **nilai maksimum**. Kemudian, nilai dari baris yang tersisa akan ditambahkan ke nilai Vini. Namun, jika kedua baris tersebut memiliki nilai yang sama, maka Vidi memberi kesempatan kepada Vini untuk memilih baris mana yang akan dibuang. Dan permainan di ronde berikutnya akan dimulai dengan baris yang tersisa dari ronde sebelumnya. Permainan itu akan terus berjalan hingga nantinya tersisa satu batu saja pada permainan

Kini, tantangan mereka adalah menemukan strategi terbaik untuk memperoleh nilai maksimum dari permainan ini. Dan jawaban dari pertanyaan mereka adalah nilai maksimum yang dapat diperoleh Vini dari permainan tersebut.

#### Format Masukan
- Baris pertama berisi sebuah bilangan bulat _N_ dengan (1 ≤ _N_ ≤ 5000)
- Baris kedua berisi _N_ bilangan bulat _$  W_i$_ (1 ≤ _$W_i$_ ≤ _$10^9$_)

#### Format Keluaran
- Sebuah bilangan bulat yang menyatakan nilai maksimum yang mampu Vini dapatkan

#### Contoh Masukan 1
```
4
4 1 2 3
```

#### Contoh Keluaran 1
```
7
```

#### Penjelasan Contoh 1
Pada contoh pertama, Vini dan Vidi dapat melakukan langkah - langkah berikut

- Bagi barisan menjadi ```4 1```  dan ```2 3``` , kemudian buang baris ```4 1```. Nilai Vini sekarang adalah 2 + 3 = 5. Baris yang tersisa adalah ```2 3```
- Bagi barisan menjadi 2 dan 3 , kemudian buang baris 3. Nilai Vini sekarang adalah 5 + 2 = 7. Batu yang tersisa adalah 2
- Karena hanya tersisa satu batu saja di pertandingan, maka permainan berakhir. Nilai akhir Vini adalah 7. Tidak ada cara lain yang menghasilkan nilai lebih tinggi dari 7

#### Contoh Masukan 2
```
3
5 5 4
```

#### Contoh Keluaran 2
```
5
```
