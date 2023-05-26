# Mencetak Argumen

Ini adalah contoh kode sederhana yang menerima argumen dari baris perintah dan mencetaknya ke layar. Program ini ditulis dalam bahasa Java.

## Penggunaan

Pastikan Anda memiliki perangkat lunak pengembangan Java (JDK) terpasang di komputer Anda sebelum menjalankan program ini.

1. Kompilasi program dengan menjalankan perintah berikut di terminal:

   ```
   javac mencetakArgumen.java
   ```

2. Jalankan program dengan memberikan argumen melalui baris perintah:

   ```
   java mencetakArgumen argumen1 argumen2 argumen3
   ```

   Ganti `argumen1`, `argumen2`, dan `argumen3` dengan argumen sesuai kebutuhan.

3. Program akan mencetak argumen yang diberikan ke layar.

## Contoh

Jalankan program dengan argumen berikut:

```
java mencetakArgumen Hello World! OpenAI
```

Output yang dihasilkan:

```
Hello
World!
OpenAI
```

Program akan mencetak setiap argumen ke layar dengan baris baru setiap kali mencetak.

## Catatan

- Argumen yang diberikan melalui baris perintah disimpan dalam array `args` di dalam metode `main`.
- Program ini menggunakan loop `for` untuk mengiterasi melalui setiap argumen dalam array `args`.
- Setiap argumen dicetak ke layar menggunakan `System.out.println()`.

**Catatan:** Pastikan Anda menyimpan file dengan nama `mencetakArgumen.java` agar sesuai dengan nama kelas yang diberikan di kode.
------------------------------------------------------------------------------------------------------------------------------------------------
# Operasi Aritmatik

Ini adalah contoh kode sederhana yang menerima dua argumen angka dari baris perintah, melakukan operasi aritmatika dasar, dan mencetak hasilnya ke layar. Program ini ditulis dalam bahasa Java.

## Penggunaan

Pastikan Anda memiliki perangkat lunak pengembangan Java (JDK) terpasang di komputer Anda sebelum menjalankan program ini.

1. Kompilasi program dengan menjalankan perintah berikut di terminal:

   ```
   javac operasiAritmatik.java
   ```

2. Jalankan program dengan memberikan dua argumen angka melalui baris perintah:

   ```
   java operasiAritmatik angka1 angka2
   ```

   Ganti `angka1` dan `angka2` dengan angka sesuai kebutuhan.

3. Program akan melakukan operasi aritmatika pada dua angka yang diberikan dan mencetak hasilnya ke layar.

## Contoh

Jalankan program dengan argumen berikut:

```
java operasiAritmatik 10 5
```

Output yang dihasilkan:

```
sum = 15
difference = 5
product = 50
quotient = 2
```

Program akan mencetak hasil operasi penjumlahan, pengurangan, perkalian, dan pembagian antara dua angka yang diberikan.

## Catatan

- Program ini memeriksa apakah jumlah argumen yang diberikan adalah 2. Jika tidak, program akan mencetak pesan error dan berhenti.
- Argumen yang diberikan melalui baris perintah dianggap sebagai string dan harus diubah menjadi bilangan bulat menggunakan `Integer.parseInt()`.
- Operasi aritmatika (penjumlahan, pengurangan, perkalian, dan pembagian) dilakukan pada dua bilangan tersebut.
- Hasil operasi aritmatika dicetak ke layar menggunakan `System.out.println()`.

**Catatan:** Pastikan Anda menyimpan file dengan nama `operasiAritmatik.java` agar sesuai dengan nama kelas yang diberikan di kode.
