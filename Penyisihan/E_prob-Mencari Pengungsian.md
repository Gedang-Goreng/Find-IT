<h2 align="center">Problem E</h2>
<h1 align="center">Mencari Pengungsian</h1>
<p align="center">Time limit: 1s</p>
<p align="center">Memory limit: 128mb</p>

#### **Deskripsi**
Negara Api sedang menyerang! Vini yang merupakan Raja Negara Vinisia harus menyiapkan strategi untuk menghadapi serangan tersebut. Namun sebelum memikirkan strategi untuk menghadapi Negara Api, ia juga harus memikirkan cara untuk mengungsikan warganya.

Kerajaan Vinisia dapat digambarkan sebagai sebuah jalan yang besar. Kerajaan ini memiliki _N_ warga yang harus diselamatkan. Pada mulanya, setiap warga kerajaan berada pada titik _X_ pada jalan (karena mereka tinggal disitu). Kemudian Vini akan membangun sebuah benteng pertahanan yang memanjang dari titik _L_ hingga _R_ pada jalan dan meminta seluruh warga kerajaan (yang belum berada di dalam benteng) untuk pergi ke situ. Seorang warga-_i_ dikatakan sudah berada di dalam benteng apabila memenuhi L ≤ _$X_i$_ ≤ _R_. Kemudian, waktu yang dibutuhkan seorang warga untuk pergi ke benteng tersebut adalah selisih terdekat posisi benteng dengan posisi warga itu mula - mula. Vini pun bertanya, apabila ia memiliki rencana pengungsian _L_ dan _R_, berapakah **total** waktu yang diperlukan seluruh warganya untuk
dapat mencapai benteng tersebut?

#### Format Masukan
- Baris pertama berisi bilangan bulat _N_ dan _Q_ (1 ≤ _N_,_Q_ ≤ 2 ≤ _$10^5$_) yang menyatakan jumlah warga kerjaan dan banyaknya pertanyaan Vini.
- Baris kedua berisi _N_ bilangan bulat _$X_i$_ untuk setiap (1 ≤ _$X_i$_ ≤ _$10^9$_) yang menyatakan posisi mula - mula setiap warga negara. Dijamin _$X_i$_ memiliki nilai yang unik.
- _Q_ baris berikutnya berisi bilangan bulat _L_ dan _R_ (1 ≤ _L_ ≤ _R_ ≤ _$10^9$_) yang menyatakan rencana pengungsian Vini.

#### Format Keluaran
- Untuk setiap pertanyaan Vini, keluarkan satu baris berisi bilangan bulat yang menyatakan waktu **total** yang dibutuhkan seluruh warga negara untuk mengungsi ke benteng yang Vini bangun. Perhatikan bahwa setiap pertanyaan bersifat independent yang berarti tidak saling memengaruhi satu sama lain.

#### Contoh Masukan 1
```
4 2
1 3 5 7
3 5
4 4
```

#### Contoh Keluaran 1
```
4
8
```

#### Penjelasan Contoh 1
Pada pertanyan pertama (_L_ = 3, _R_ = 5)

- Warga pertama memerlukan waktu | 3 - 1 | = 2 satuan waktu untuk pergi ke benteng
- Warga kedua dan ketiga sudah berada di dalam benteng, sehingga memerlukan 0 satuan waktu
- Warga keempat memerlukan waktu | 5 - 7 | = 2 satuan waktu untuk pergi ke benteng

Sehingga total waktu yang dibutuhkan Vini adalah 2 + 0 + 0 + 2 = 4 satuan waktu

Pada pertanyaan kedua (_L_ = 4,  _R_ = 4)

- Warga pertama memerlukan waktu | 4 - 1 | = 3 satuan waktu untuk pergi ke benteng
- Warga kedua memperlukan waktu | 4 - 3 | = 1 satuan waktu untuk pergi ke benteng
- Warga ketiga memerlukan waktu | 4 - 5 | = 1 satuan waktu untuk pergi ke benteng
- Warga keempat memerlukan waktu | 4 - 7 | = 3 satuan waktu untuk pergi ke benteng

Sehingga total waktu yang dibutuhkan Vini adalah 3 + 1 + 1 + 3 = 8 satuan Waktu
