#### 1.uncensoredString

Buatlah sebuah fungsi apakah ada seseorang yang telah berusaha untuk menyensor komentar yang saya tulis, dengan mengganti setiap karakternya menjadi seperti ini l*k* th*s, untungnya saya dapat mengembalikan komentar yang telah disensor tersebut, tugas anda adalah harus mengembalikan sebuah komentar yang telah di sensor tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
uncensoredString('Wh*r* d*d my v*w*ls g*?', 'eeioeo') ➞ 'Where did my vowels go?'
uncensoredString('abcd', '') ➞ 'abcd'
uncensoredString('*PP*RC*S*', 'UEAE') ➞ 'UPPERCASE'
uncensoredString('*l*ph*nt', 'Eea') ➞ 'Elephant'
```

#### 2.happyNumber

Buatlah sebuah fungsi apakah Happy Numbers adalah sebuah angka bahagia, jika kita memberikan sebuah nomor apapun maka kita akan dapat membuat sebuah nomor baru dengan menambahkan jumlah kuadrat digit angka tersebut, misalnya diberikan angka 203 maka nomor barunya adalah 4 + 0 + 9 = 13, jika anda mengulangi proses ini maka anda akan mendapatkan urutan angka tersebut, kenapa dikatakan Happy Numbers dikarenakan angka tersebut sudah mencapat 1 atau final seperti contoh berikut

Berikut adalah angka bahagia 203 -> 13 -> 10 -> 1 -> 1
Berikut adalah angka tidak bahagia 11 -> 2 -> 4 -> 16 -> ...

jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Boolean seperti dibawah ini.

**Output:**
```javascript
happyNumber(203) ➞ true
happyNumber(11) ➞ false
happyNumber(107) ➞ false
```

#### 3.countIdenticalArrays

Buatlah sebuah fungsi untuk menghitung jumlah Array yang identik, yang menggunakan empat Array sebagai argumennya, kemudian kembalikan jumlah total digit angka Array yang identik tersebut, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
countIdenticalArrays([0, 0, 0], [0, 1, 2], [0, 0, 0], [2, 1, 0]) ➞ 2
countIdenticalArrays([0, 1, 0], [0, 1, 2], [0, 2, 0], [2, 1, 0]) ➞ 0
countIdenticalArrays([0, 1, 2], [0, 1, 2], [0, 1, 2], [2, 1, 0]) ➞ 3
```

#### 4.sevenBoom

Buatlah sebuah fungsi yang mengambil Array sebagai argumentnya dan kembalikan "Boom Exploded" jika angka 7 muncul dalam sebuah Array, jika tidak ada angka 7 didalam sebuah Array tersebut maka kembalikan "Boom Defused", jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
sevenBoom([1, 2, 3, 4, 5, 6, 7]) ➞ "Boom Exploded"
sevenBoom([8, 6, 33, 100]) ➞ "Boom Defused"
sevenBoom([2, 55, 60, 97, 86]) ➞ "Boom Exploded"
```

#### 5.numInStr

Buatlah sebuah fungsi untuk mengambil sebuah angka yang berada didalam sebuah Array, kembalikan String yang hanya memiliki sebuah angka didalamnya, jika tidak ada angka didalam sebuah String maka kembalikan sebuah Array kosong, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
numInStr(['abc', 'abc10']) ➞ ['abc10']
numInStr(['abc', 'ab10c',  'a10bc', 'bcd']) ➞ ['ab10c', 'a10bc']
numInStr(['1', 'a' , ' ' ,'b']) ➞ ['1']
numInStr(['rct', 'ABC', 'Test', 'xYz']) ➞ []
numInStr(['this IS','10xYZ', 'xy2K77', 'Z1K2W0', 'xYz']) ➞ ['10xYZ', 'xy2K77', 'Z1K2W0']
numInStr(['-/>', '10bc', 'abc ']) ➞ ['10bc']
```

#### 6.distanceToNearestVowel

Buatlah sebuah fungsi yang mengambil jarak antara karakter Alfabet terdekat, untuk setiap karakternya harus mengembalikan jarak ke Alfabet yang terdekat, jika karakternya Alfabet itu sendiri maka kembalikan 0, semua String input akan memiliki setidaknya satu karakter Alfabet, dalam kasus ini anda harus mengunakan huruf Vowels untuk mendapatkan nilainya, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
distanceToNearestVowel("aaaaa") ➞ [0, 0, 0, 0, 0]
distanceToNearestVowel("babbb") ➞ [1, 0, 1, 2, 3]
distanceToNearestVowel("abcdabcd") ➞ [0, 1, 2, 1, 0, 1, 2, 3]
distanceToNearestVowel("shopper") ➞ [2, 1, 0, 1, 1, 0, 1]
```

#### 7.getLength

Buatlah sebuah fungsi untuk menghitung berapa banyak jumlah element pada setiap Array bertingkat, anda harus mengembalikan total panjang karakter pada Array tersebut seperti contoh berikut ini [1, [2,3]] memeliki 2 element Array dan memiliki total panjang 3 karakter, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Number seperti dibawah ini.

**Output:**
```javascript
getLength([1, [2,3]]) ➞ 3
getLength([1, [2, [3, 4]]]) ➞ 4
getLength([1, [2, [3, [4, [5, 6]]]]]) ➞ 6
getLength([1, 7, 8]), ➞ 3
getLength([2]) ➞ 1
getLength([]) ➞ 0
```

#### 8.oddishOrEvenish

Buatlah sebuah fungsi Oddish vs Evenish, yang menentukan apakah suatu bilangan tersebut salah satu nilainya itu Oddish atau Evenish, jika digit angkanya bilangan ganjil maka anda harus mengembalikan "Oddish" dan jika digit angkanya bilangan genap maka anda harus mengembalikan "Evenish", jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah String seperti dibawah ini.

**Output:**
```javascript
oddishOrEvenish(43) ➞ "Oddish"
oddishOrEvenish(373) ➞ "Oddish"
oddishOrEvenish(55551) ➞ "Oddish"
oddishOrEvenish(694) ➞ "Oddish"
oddishOrEvenish(4433) ➞ "Evenish"
oddishOrEvenish(11) ➞ "Evenish"
oddishOrEvenish(211112) ➞ "Evenish"
```

#### 9.getHashTags

Buatlah sebuah fungsi untuk memberikan sebuah Hash Tag pada sebuah Judul surat kabar, ambilah 3 kata terpanjang teratas dari Judul surat kabar tersebut dan berikan tanda Hash Tag, jika beberapa kata memiliki panjang karakter yang sama maka ambillah kembali kata yang pertama kali muncul terlebih dahulu, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.

**Output:**
```javascript
getHashTags("How the Avocado Became the Fruit of the Global Trade") ➞ ["#avocado", "#became", "#global"]
getHashTags("Why You Will Probably Pay More for Your Christmas Tree This Year") ➞ ["#christmas", "#probably", "#will"]
getHashTags("Hey Parents, Surprise, Fruit Juice Is Not Fruit") ➞ ["#surprise", "#parents", "#fruit"]
getHashTags("Visualizing Science") ➞ ["#visualizing", "#science"]
getHashTags("Minecraft Stars on Youtube Share Secrets to Their Fame") ➞ ["#minecraft", "#youtube", "#secrets"]
getHashTags("Are You an Elite Entrepreneur?") ➞ ["#entrepreneur", "#elite", "#are"]
```

#### 10.sameVowelGroup

Buatlah sebuah fungsi untuk menentukan sebuah kata yang termasuk dalam keluarga Vowels, ambil semua kata yang memiliki semua Huruf Vowels yang sama, baik itu dalam urutan atau sebagai nomor, kemudian kata-kata hanya akan berisi huruf kecil dan mungkin akan berisi spasi putih juga, anda dapat memasukkan kata-kata dengan angka berapapun asalkan itu hanya berisi huruf o dan bukan Huruf Vowels lainnya, jadi buatlah sebuah fungsi untuk soal berikut ini dan outputnya harus mengembalikan sebuah Array seperti dibawah ini.


***Output:***
```javascript
sameVowelGroup(["hoops", "chuff", "bot", "bottom"]) ➞ ["hoops", "bot", "bottom"]
sameVowelGroup(["crop", "nomnom", "bolo", "yodeller"]) ➞ ["crop", "nomnom", "bolo"]
sameVowelGroup(["many", "carriage", "emit", "apricot", "animal"]) ➞ ["many"]
sameVowelGroup(["toe", "ocelot", "maniac"]) ➞ ["toe", "ocelot"]
sameVowelGroup(["a", "apple", "flat", "map", "shark"]) ➞ ["a", "flat", "map", "shark"]
sameVowelGroup(["a", "aa", "ab", "abc", "aaac", "abe"]) ➞ ["a", "aa", "ab", "abc", "aaac"]
```