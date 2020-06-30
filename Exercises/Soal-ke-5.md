#### 1.characterMapping

Buatlah sebuah fungsi untuk menentukan pemetaan karakter unik pada sebuah String, dimana yang nantinya akan mengembalikan pemetaan karakter dari masing-masing setiap karakter tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
characterMapping("babbcb") ➞ [0, 1, 0, 0, 2, 0]
characterMapping("aaabb") ➞ [0, 0, 0, 1, 1]
characterMapping("fluffy") ➞ [0, 1, 2, 0, 0, 3]
characterMapping("buttery") ➞ [0, 1, 2, 2, 3, 4, 5]
characterMapping("canine") ➞ [0, 1, 2, 3, 2, 4]
```

#### 2.charCount

Buatlah sebuah fungsi untuk menghitung instans dari setiap karakter dalam sebuah String, yang dimana argumentnya memiliki dua buah String, yang harus anda lakukan hanyalah menghitung berapa banyak String pertama itu muncul, didalam karakter String yang kedua, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output**
```javascript
charCount('b', 'big fat bubble') ➞ 4
charCount('c', 'Chamber of secrets') ➞ 1
charCount('f', 'frank and his friends have offered five foxes for sale') ➞ 7
charCount('x', 'edabit') ➞ 0
charCount('a', 'Adam and Eve bit the apple and found a snake') ➞ 6
charCount('7', '10795426697') ➞ 2
```

#### 3.doubleChar

Buatlah sebuah fungsi untuk menentukan sebuah karakter yang berulang, yang dimana setiap karakternya itu nanti akan diulang sebanyak satukali, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
doubleChar("String") ➞ "SSttrriinngg"
doubleChar("Hello World!") ➞ "HHeelllloo  WWoorrlldd!!"
doubleChar("1234!_ ") ➞ "11223344!!__  "
doubleChar("##^&%%*&%%$#@@!") ➞ "####^^&&%%%%**&&%%%%$$##@@@@!!"
doubleChar(" ") ➞ "  "
doubleChar("_______") ➞ "______________"
```

#### 4.factorChain

Buatlah sebuah fungsi untuk menentukan Faktor Rantai dari sebuah bilangan bulat yang berada didalam sebuah Array, yang dimana setiap element sebelumnya adalah faktor dari element berikutnya secara berturut - turut, Berikut ini adalah contoh rantai faktor dari [3, 6, 12, 36]

3 adalah faktor dari 6
6 adalah faktor dari 12
12 adalah faktor dari 36

jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
factorChain([1, 2, 4, 8, 16, 32]) ➞ true
factorChain([2, 4, 6, 7, 12]) ➞ false
factorChain([1, 1, 1, 1, 1, 1]) ➞ true
factorChain([10, 1]) ➞ false
factorChain([10, 20, 30, 40]) ➞ false
factorChain([10, 20, 40]) ➞ true
```

#### 5.caesarCipher

Buatlah sebuah fungsi apakah Julius Caesar melindungi informasi rahasianya dengan mengenkripsi informasi tersebut menggunakan sandi, yang dimana setiap sandinya dibuat dengan menggeser setiap huruf dengan sejumlah huruf Alfabetnya, jika pergeseran membawa anda melewati akhir Alfabet maka cukup putar kembali ke awal Alfabet, dalam contoh kasus ini rotasi diputar sebanyak tiga kali dengan huruf Alfabet sebagai berikut "wxyz" maka akan menjadi seperti ini "zabc", yang harus anda lakukan hanyalah memutar rotasi Alfabet tersebut sebanyak digit angka yang diberikan, kemudian semua outpunya harus berupa String ASCII yang valid, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
caesarCipher("middle-Outz", 2) ➞ "okffng-Qwvb"
caesarCipher("Always-Look-on-the-Bright-Side-of-Life", 5) ➞ "Fqbfdx-Qttp-ts-ymj-Gwnlmy-Xnij-tk-Qnkj"
caesarCipher("A friend in need is a friend indeed", 20) ➞ "U zlcyhx ch hyyx cm u zlcyhx chxyyx"
caesarCipher("A Fool and His Money Are Soon Parted.", 27) ➞ "B Gppm boe Ijt Npofz Bsf Tppo Qbsufe."
```

#### 6.harshadNumber

Buatlah sebuah fungsi untuk menentukan sebuah bilangan Harshad, angka Harshad / Niven adalah angka positif yang dapat dibagi dengan jumlah digit mereka, semua angka satu digit termasuk dalam angka Harshad misalnya 27, karena 2 + 7 = 9 dan 9 adalah pembagi 27, angka Harshad dapat muncul dalam kelompok yang berurutan mulai dari angka 1 hingga 10 adalah angka Harshad, angka 132 dan 133 keduanya juga termasuk angka Harshad, jadi tugas anda hanyalah mengambil yang termasuk angka Harshad, kemudian kembalikan Array dua element yang dimana element pertamamya adalah panjang cluster Harshad, yang kedua adalah urutannya di cluster angka Harshad tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Outputnya:**
```javascript
harshadNumber(5) ➞ [10,5]
harshadNumber(133) ➞ [2,2]
harshadNumber(82) ➞ [0,0]
harshadNumber(72) ➞ [1,1]
harshadNumber(7384) ➞ [0,0]
harshadNumber(2584) ➞ [1,1]
```

#### 7.replaceVowel

Buatlah sebuah fungsi untuk menganti setiap karakter Alfabet yang ada dengan karakter yang lainnya, yang dimana setiap karakternya cocok dengan karakter Vowels berikut ini

a = 1
e = 2
i = 3
o = 4
u = 5

jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
replaceVowel("karachi") ➞ "k1r1ch3"
replaceVowel("dang") ➞ "d1ng"
replaceVowel("aen") ➞ "12n"
replaceVowel("chembur") ➞ "ch2mb5r"
replaceVowel("khandbari") ➞"kh1ndb1r3"
replaceVowel("thamel") ➞ "th1m2l"
```

#### 8.anagram

Buatlah sebuah fungsi untuk menghasilkan kata - kata dari sebuah nama yang telah disediakan, kembalikan nilai true jika nama yang diberikan dapat menghasilkan sebuah kata - kata seperti yang berada didalam sebuah Array, jika nama nya tidak sama dengan kata - kata yang berada didalam sebuah Array maka kembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
anagram("Justin Bieber", ["injures", "ebb", "it"]) ➞ true
anagram("Natalie Portman", ["ornamental", "pita"]) ➞ true
anagram("Emma Watson", ["mows", "meant", "a"]) ➞ true
anagram("Daniel Radcliffe", ["clarified", "elf", "and"]) ➞ true
anagram("Chris Pratt", ["chirps", "rat"]) ➞ false
anagram("Jeff Goldblum", ["jog", "meld", "bluffs"]) ➞ false
anagram("Taylor Swift", ["stratify", "ow"]), ➞ false
anagram("Adam Levine", ["medieval", "man"]), ➞ false
```

#### 9.minSwaps

Buatlah sebuah fungsi untuk mengkonversi satu String Biner ke String Biner yang lainnya, yang dimana nilainya harus mengembalikan jumlah minimum swap untuk mengkonversi String Biner pertama agar menjadi String Biner yang kedua, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
minSwaps("1001", "1001") ➞ 0
minSwaps("1100", "1001") ➞ 1
minSwaps("110011", "010111") ➞ 1
minSwaps("1100", "0011") ➞ 2
minSwaps("110011", "001111") ➞ 2
minSwaps("10011001", "01100101") ➞ 3
minSwaps("11111000001100", "10110010100110") ➞ 3
minSwaps("10011001", "01100110") ➞ 4
```

#### 10.balancedWords

Buatlah sebuah fungsi untuk menentukan kata - kata yang seimbang, kita dapat menetapkan nilai untuk setiap karakter dalam sebuah kata berdasarkan posisi mereka dalam Alfabet (a = 1, b = 2, ..., z = 26), sebuah kata yang dikatakan seimbang adalah salah satu dimana jumlah nilai disisi kiri dari kata sama dengan jumlah dari nilai - nilai dari disisi kanan, semua kata akan menjadi huruf kecil dan memiliki minimal 2 karakter, kata - kata yang termasuk Palindrom akan selalu seimbang, jika karakternya termasuk dalam kata - kata yang seimbang maka kembalikan nilai true dan jika tidak termasuk dalam kata - kata yang tidak seimbang maka kembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Outputnya:**
```javascript
balancedWords('at') ➞ false
balancedWords('forgetful') ➞ false
balancedWords('vegetation') ➞ true
balancedWords('disillusioned') ➞ false
balancedWords('abstract') ➞ true
balancedWords('clever') ➞ false
balancedWords('conditionalities') ➞ true
```