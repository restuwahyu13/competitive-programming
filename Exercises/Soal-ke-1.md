#### 1.growUpNumber

Buatlah sebuah fungsi untuk perhitungan mundur dari sebuah angka yang diambil dari parameternya, outputnya harus berupa angka yang menghitung mundur sesuai dengan digit angka yang diberikan sampai dengan index ke 0, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
growUpNumber(5) ➞ [5, 4, 3, 2, 1, 0]
growUpNumber(3) ➞ [3, 2, 1, 0]
growUpNumber(0) ➞ []
```

#### 2.isMatchIdentity

Buatlah sebuah fungsi untuk mengecek setiap huruf yang menggunakan huruf Vowels, apakah ada sebuah String yang mengandung karakter yang identik sama, jika ada maka buatlah sebuah fungsi yang hanya megembalikan karakter yang identik sama, jika karakternya identik sama maka akan mengembalikan nilai true dan jika karakternya tidak identik sama maka akan mengembalikan nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
isMatchIdentity("aaaaaa") ➞ true
isMatchIdentity("aabbbaaa") ➞ false
isMatchIdentity("ccccc") ➞ true
```

#### 3.alphabetCharacter

Buatlah sebuah fungsi untuk mengurutkan masing - masing huruf sesuai dengan urutan sebuah Alfabet pada umumnya yaitu dari A-Z, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
alphabetCharacter("lamborgini") ➞ "abgiilmnor"
alphabetCharacter("hacker") ➞ "acehkr"
```

#### 4.existsHigherNumber

Buatlah sebuah fungsi apakah ada digit angka yang lebih besar didalam sebuah Array jika ada maka, buatlah sebuah fungsi yang mengembalikan true atau false, jika ada salah satu digit angka dari sebuah Array yang lebih besar dari N atau yang sama dengan N, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
existsHigherNumber([8, 4, 20, 32, 1], 10) ➞ true
existsHigherNumber([1, 3, 7, 4, 6], 8) ➞ false
existsHigherNumber([], 1) ➞ false
```

#### 5.howManyAlphabet

Buatlah sebuah fungsi yang mengambil sebuah bilangan bulat, yang dimana bilangan bulatnya dialokasikan menjadi panjang huruf dari sebuah Alfabet yaitu huruf A dari kata LAMBORGINI, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
howManyAlphabet(7) ➞ "Laaaaaaamborgini"
howManyAlphabet(2) ➞ "Laamborgini"
howManyAlphabet(10) ➞ "Laaaaaaaaaaborgini"
```

#### 6.isPalidrome

Buatlah sebuah fungsi untuk menentukan Palindrome seperti kata-kata berikut dibawah ini, Palidrome identik dengan penulisan karakter huruf yang maju mundur, jika huruf Palidromenya cocok maka akan mengembalikan sebuah nilai true dan jika huruf Palidromenya tidak cocok maka akan mengembalikan sebuah nilai false, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
isPalidrome("kakak") ➞ true
isPalidrome("adik") ➞ false
isPalidrome("sos") ➞ true
isPalidrome("lawak") ➞ false
```

#### 7.removeCaracter

Buatlah sebuah fungsi apakah ada sebuah Array String dengan kata-kata acak, yang dimana program anda tidak mau menerima kata-kata tersebut yang dimulai dengan awalan huruf "C" kapital, anda harus menghapus kata-kata tersebut yang memliki awalan huruf "C" kapital, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
removeCaracter(["Kambing", "Chapung",  "Kalong"]) ➞ ["Kambing", "Kalong"]
removeCaracter(["ayam", "kuda", "badak"] ➞ ["ayam", "kuda", "badak"]
removeCaracter(["Cacing", "Bebek", "Cicak", "Beruang"]) ➞ ["Beruang", "Bebek"]
```

#### 8.matchDictonary

Buatlah sebuah fungsi apakah ada beberapa kata - kata didalam sebuah Array yang cocok dengan inisialnya, jika ada maka anda harus mengembalikan nilai tersebut yang kata - katanya cocok dengan inisialnya yang berada didalam sebuah Array tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
matchDictonary("ku", ["kuda", "kurus", "kece", "kucel"]) ➞ ["kuda", "kurus"]
matchDictonary("di", ["diman", "dih", "debora", "deh", 'die']) ➞ ["diman", "dih", "die"]
matchDictonary("ci", ["ayam", "kampus", "memang", "beda"]) ➞ []
```

#### 9.additiveInverse

Buatlah sebuah fungsi untuk menghitung matematik dengan mengunakan pola Additive Inverse seperti angka berikut dibawah ini, Additive Inverse sangat identik dengan pertukaran angka dari Plus ke Mines begitu juga sebaliknya, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
additiveInverse([12, -7, -1, 3, 5]) ➞ [-12, 7, 1, -3, -5]
additiveInverse([0, -3, 4, 1, 2]) ➞ [0, 3, -4, -1, -2]
additiveInverse([-5, -25, 35]) ➞ [5, 25, -35]
```

#### 10.reverseBool

Buatlah sebuah fungsi untuk menentukan sebuah nilai apakah type datanya itu sebuah Boolean atau bukan, jika type datanya Boolean dan bernilai true maka anda harus mengembalikan nilai false begitu juga sebaliknya, atau jika type datanya bukan sebuah Boolean maka anda harus mengembalikan nilai "bukan boolean", jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String | Boolean seperti dibawah ini.

**Output:**
```javascript
reverseBool(true) ➞ false
reverseBool(false) ➞ true
reverseBool({}) ➞ "bukan boolean"
reverseBool(null) ➞ "bukan boolean"
```