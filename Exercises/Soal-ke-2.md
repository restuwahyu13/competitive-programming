#### 1.isFibonacci

1.Buatlah sebuah fungsi untuk merubah angka bilangan bulat menggunakan perhitungan matematik Fibonacci seperti output dibawah ini, Fibonacci sangat identik dengan penjumlahan digit angka dari nilai sebelumnya, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
isFibonacci(3) ➞ [1, 2]
isFibonacci(8) ➞ [1, 2, 3, 5, 8, 13, 21]
```

#### 2.isBubleSort

Buatlah sebuah fungsi Array dengan nilai acak seperti dibawah ini, yang dimana nanti Array tersebut harus diurutkan nilainya sesuai dengan urutan angkanya menggunakan algorithm BubleShort, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
isBubleSort([303, 6, 90, 21, 33, 80, 212]) ➞ [6, 21, 33, 80, 90, 212, 303]
isBubleSort([101, 1002, 0, 212, 12, 4, 10]) ➞ [0, 4, 10, 12, 101, 212, 1002]
```

#### 3.calcDeterminant

Buatlah sebuah fungsi untuk menghitung kalkulasi determinant matrix berikut, yang dimana nilai tersebut akan dihitung dengan metode menyilang seperti huruf X seperti berikut AD - BC, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
calcDeterminant([[1, 2], [3, 4]]) ➞ -2
calcDeterminant([[5, 3], [3, 1]]) ➞ -4
calcDeterminant([[1, 1], [1, 1]]) ➞ 0
```

#### 4.middleEarth

Buatlah sebuah fungsi untuk memeriksa sebuah String apakah Ari dan Danang itu posisinya saling berdekatan, jika mereka posisinya saling berdekatan didalam sebuah Array, jika benar anda harus megembalikan nilai true dan jika salah maka anda harus megembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
middleEarth(['Ari', 'Danang', 'Jamal']) ➞ true
middleEarth(['Susi', 'Ari', 'Danang', 'Jono']) ➞ true
middleEarth(['Okta', 'Ari', 'Beben', 'Danang']) ➞ false
middleEarth(['Ruben', 'Ari', 'Restu', 'Danang', 'Arif']) ➞ false
```

#### 5.firstAndLast

Buatlah sebuah fungsi untuk menentukan karakter String dibawah ini menggunakan cara Leksikografis, Leksikografis adalah cabang ilmu bahasa yang mempelajari tentang teknik penyusunan kamus berdasarkan huruf pertama Alfabet, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
firstAndLast("another") ➞ ["aehnort", "tronhea"]
firstAndLast("welcome") ➞ ["ceelmow", "womleec"]
firstAndLast("anonymous") ➞ ["amnnoosuy", "yusoonnma"]
```

#### 6.uniqueStyles

Buatlah sebuah fungsi ada berapa banyak karakter unik pada genre musik berikut ini yang ada didalam sebuah Array, yang harus anda lakukan hanyalah mengambil beberapa karakter unik yang tidak memiliki duplicate, kemudian kembalikan jumlah panjang karakter yang berada didalam sebuah Array tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
uniqueStyles(["Dangdut, Rock", "Keroncong, Heavy Metal", "Techno, Rege", "Pop, Disco", "Arimbi, Techno, Metal"]) ➞ 10
uniqueStyles(["Rege", "Rap, Funk", "Grunge, Dangdut, Hip Hop, Rap", "Keroncong","Rege"]) ➞ 7
uniqueStyles(["Arimbi", "Arimbi", "Arimbi"]) ➞ 1
```

#### 7.lookAndSay

Buatlah sebuah fungsi untuk mengandakan sebuah angka, dimana nantinya angka akan dikelompokan menjadi dua type bagian yaitu Odd dan Even, jika angkanya termasuk type Odd maka akan mengembalikan nilai "salah" dan jika angkanya termasuk type Even maka akan mengembalikan nilai baru, untuk setiap group akan memiliki 2 digit angka kemudian gabungkan digit angka terakhir yang sama jumlah nya dengan digit angka yang pertama, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Outputnya:**
```javascript
lookAndSay(95) ➞ 555555555
lookAndSay(1213141516171819) ➞ 23456789
lookAndSay(786497) ➞ 8888888444444777777777
lookAndSay(231) ➞ "salah"
```

#### 8.sumDigProd

Buatlah sebuah fungsi yang mengambil digit angka sebagai argumentnya, kemudian ubahlah nilai tersebut menjadi sebuah bilangan bulat, kemudian ambil sub-nilai terkecil dari nilai bilangan bulat tersebut hingga nilainya tersisa 1 digit angka, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output**
```javascript
sumDigProd(16, 28) ➞ 6
sumDigProd(167, 167, 167, 167, 167, 3) ➞ 8
sumDigProd(26, 497, 62, 841) ➞ 6
sumDigProd(98526, 54, 863, 156489, 45, 6156) ➞ 2
sumDigProd(123, -99) ➞ 8
```

#### 9.additiveInverse

Buatlah sebuah fungsi untuk menentukan profit dari penjualan sebuah Apartement, dimana harga biayanya itu dihitung dalam bentuk USD, mulai dari HARGA BIAYA, HARGA JUAL & MODAL, kemudian hasilkan total laba dari penjualan Apartement tersebut dan total labanya harus berupa bilangan bulat, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
profit({hargaBiaya: 32.67, hargaJual: 45.00, modal: 1200}) ➞ 14796
profit({hargaBiaya: 378.11, hargaJual: 990.00, modal: 99}) ➞ 60577
profit({hargaBiaya: 4.67, hargaJual: 5.00, modal: 78000}) ➞ 25740
profit({hargaBiaya: 19.87, hargaJual: 110.00, modal: 350}) ➞ 31546
```

#### 10.filterAddress

Buatlah sebuah fungsi untuk mengambil sebuah alamat pada sebuah String menggunakan Reguler Expression, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
filterAddress("jakarta selatan, blok m 122 jl.jendral sudirman, kebayoran baru") ➞ 122 jl.jendral sudirman
filterAddress("depok lama, pasar lama 112 jl.dewi sartika, pancoranmas") ➞ 112 jl.dewi sartika
```