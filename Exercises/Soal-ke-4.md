#### 1.mergeArray

Buatlah sebuah fungsi yang mengembalikan sebuah Array Tunggal dari setiap Array bertingkat, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
mergeArray([1, 2, 3], [4, 5], [6, 7]) ➞ [1, 2, 3, 4, 5, 6, 7]
mergeArray([1], [2], [3], [4], [5], [6] [7]) ➞ [1, 2, 3, 4, 5, 6, 7]
mergeArray([1, 2], [3, 4]) ➞ [1, 2, 3, 4]
mergeArray([4, 4, 4, 4, 4]) ➞ [4, 4, 4, 4, 4]
mergeArray(['a'], ['b', 'c']) ➞ ['a', 'b', 'c']
```

#### 2.factorGroup

Buatlah sebuah fungsi untuk menentukan jumlah faktor sebuah angka entah itu bilangan Genap atau Ganjil dari digit angka berikut ini, jika digit angkanya bilangan Genap maka akan mengembalikan "even" dan jika digit angkanya bilangan Ganjil maka akan mengembalikan "odd", jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
factorGroup(33) ➞ "even"
factorGroup(36) ➞ "odd"
factorGroup(7) ➞ "even"
factorGroup(1) ➞ "odd"
factorGroup(18) ➞ "even"
```


#### 3.isBetween

Buatlah sebuah fungsi yang menggembalikan tiga argument yaitu (first, last, word) dan kembalikan nilai true jika Word ditemukan diantara First dan Last, jika Word tidak ditemukan diantara First dan Last maka anda harus mengembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
isBetween("apple", "banana", "azure") ➞ true
isBetween("shrapnel", "tapenade", "tally") ➞ true
isBetween("oath", "ostrich", "osteoporosis") ➞ true
isBetween("tamer", "tanner", "timid") ➞ false
isBetween("rhino", "sorcerer", "quote") ➞ false
```

#### 4.isPositiveDominant

Buatlah sebuah fungsi yang menentukan sebuah nilai Positif itu lebih dominan dari nilai Negative, jika nilai Positif nya lebih banyak dari nilai Negative nya maka anda harus mengembalikan nilai true, jika tidak maka sebaliknya anda harus mengembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
isPositiveDominant([1, 1, 1, 1, -3, -4]) ➞ false
isPositiveDominant([5, 99, 832, -3, -4]) ➞ true
isPositiveDominant([0, -4, -1]) ➞ false
isPositiveDominant([1, 2, 3, -1]) ➞ true
isPositiveDominant([1, 0, 0, -1]) ➞ false
isPositiveDominant([5, 4, 3, 0, 0, -1, -1, -2, -2]) ➞ true
isPositiveDominant([52, 52, 52, -3, 2, 2, 2, -4]) ➞ false
```

#### 5.nextElement

Buatlah sebuah fungsi untuk menentukan Element berikutnya dalam urutan Aritmatika, jadi tugas anda hanyalah harus mengembalikan fungsi Element berikutnya sesuai dengan urutan Aritmatika, didalam urutan Aritmatika setiap Element dibentuk dengan menambahkan konstanta yang sama ke setiap Element sebelumnya, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
nextElement([3, 5, 7, 9]) ➞ 11
nextElement([-5, -6, -7]) ➞ -8
nextElement([2, 2, 2, 2, 2]) ➞ 2
```

#### 6.consecutiveCombo

Buatlah sebuah fungsi untuk menentukan urutan berturut gabungan, kembalikan nilai true jika dua Array ketika digabungkan membentuk sebuah digit angka yang berurutan, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
consecutiveCombo([1, 4, 5, 7], [2, 3, 6]) ➞ true
consecutiveCombo([1, 4, 5, 6], [2, 7, 8, 9]) ➞ false
consecutiveCombo([1, 4, 5, 6], [2, 3, 7, 8, 10]) ➞ false
consecutiveCombo([7, 5, 4, 1], [2, 3, 6, 8]) ➞ true
consecutiveCombo([33, 34, 40], [39, 38, 37, 36, 35, 32, 31, 30]) ➞ true
consecutiveCombo([1, 4, 5, 6], [2, 3, 7, 8, 10]) ➞ false
consecutiveCombo([4, 3, 1], [2, 5, 7, 6]) ➞ true
consecutiveCombo([4, 3, 1], [7, 6, 5]) ➞ false
```

#### 7.canConcatenate

Buatlah sebuah fungsi untuk menentukan sebuah Array untuk membentuk sebuah Array Target, yang mengembalikan nilai true jika Array yang lebih kecil dapat digabungkan untuk membentuk sebuah Array Target, kembalikan false jika nilainya tidak dapat membentuk sebuah Array Target, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
canConcatenate([[1, 2, 3, 4], [5, 6], [7]], [1, 2, 3, 4, 5, 6, 7]) ➞ true
canConcatenate([[2, 1, 3], [5, 4, 7, 6, 7]], [1, 2, 3, 4, 5, 6, 7]) ➞ false
canConcatenate([[2, 1, 3], [5, 4, 7]], [1, 2, 3, 4, 5, 6, 7]) ➞ false
canConcatenate([[1, 4], [3]], [1, 3, 4]), ➞ true
canConcatenate([[1, 4], [3]], [1, 2, 3, 4]) ➞ false
canConcatenate([[1, 4], [3]], [4, 3, 1]) ➞ true
```

#### 8.getDays

Buatlah sebuah fungsi untuk menentukan selisih berapa hari antara dua tanggal berikut ini, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
getDays(new Date("June 14, 2019"),  new Date("June 20, 2019")) ➞ 6
getDays(new Date("December 29, 2018"),  new Date("January 1, 2019")) ➞ 3
getDays(new Date("July 20, 2019"),  new Date("July 30, 2019")) ➞ 10
```

#### 9.combinations

Buatlah sebuah fungsi untuk mengkombinasikan setiap digit angka, yang mengambil jumlah angka masing - masing dari setiap grup item tersebut, kemudian kembalikan nilainya sebagai sebuah bilangan bulat, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
combinations(5, 6, 7) ➞ 210
combinations(5, 5, 5, 5) ➞ 625
combinations(3, 6, 9) ➞ 162
combinations(2, 3, 4, 5, 6, 7, 8, 9, 10) ➞ 3628800
combinations(4, 5, 6) ➞ 120
combinations(5, 6, 7, 8) ➞ 1680
combinations(6, 7, 0) ➞ 42
```

#### 10.reversedBinaryInteger

10.Buatlah sebuah fungsi untuk membalikkan sebuah String Biner yang mengambil nilai Integer N sebagai parameternya, tugas anda hanyalah harus membalikkan representasi bilangan Biner tersebut dari bilangan Integer, kemudian kembalikan sebuah nilai Integer baru dari bilangan Biner yang sudah dibalikan, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
reversedBinaryInteger(4) ➞ 1
reversedBinaryInteger(82) ➞ 37
reversedBinaryInteger(90) ➞ 45
reversedBinaryInteger(446) ➞ 251
reversedBinaryInteger(451) ➞ 391
reversedBinaryInteger(634) ➞ 377
reversedBinaryInteger(776) ➞ 67
reversedBinaryInteger(4096) ➞ 1
reversedBinaryInteger(547643) ➞ 904609
reversedBinaryInteger(612965) ➞ 681385
```
