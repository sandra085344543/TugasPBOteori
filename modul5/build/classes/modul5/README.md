## Modul5

Ini adalah program sederhana yang meminta pengguna memasukkan tiga kata dan kemudian mencetak kata-kata tersebut. Program ini ditulis dalam bahasa pemrograman Java.

### Penggunaan

1. Jalankan program ini di lingkungan pengembangan Java, seperti NetBeans atau Eclipse.
2. Saat program dijalankan, Anda akan melihat pesan "Enter word1: ".
3. Masukkan kata pertama yang Anda inginkan dan tekan Enter.
4. Anda akan melihat pesan "Enter word2: ".
5. Masukkan kata kedua yang Anda inginkan dan tekan Enter.
6. Anda akan melihat pesan "Enter word3: ".
7. Masukkan kata ketiga yang Anda inginkan dan tekan Enter.
8. Program akan mencetak kata-kata yang telah Anda masukkan.

Pastikan Anda telah mengatur lingkungan Java dengan benar sebelum menjalankan program ini.

### Contoh

```
Enter word1: Hello
Enter word2: World
Enter word3: !
Hello World !
```

### Catatan

- Program ini menggunakan `BufferedReader` untuk membaca input dari pengguna.
- Jika terjadi kesalahan saat membaca input, program akan mencetak pesan "Error reading input from user".

--------------------------------------------------------------------------------------------------------------------------------
## Modul5

Ini adalah program sederhana yang meminta pengguna memasukkan tiga kata menggunakan `JOptionPane` dan kemudian menampilkan kata-kata tersebut dalam dialog. Program ini ditulis dalam bahasa pemrograman Java.

### Penggunaan

1. Jalankan program ini di lingkungan pengembangan Java, seperti NetBeans atau Eclipse.
2. Saat program dijalankan, Anda akan melihat dialog dengan pesan "Enter word1:".
3. Masukkan kata pertama yang Anda inginkan dan klik OK.
4. Anda akan melihat dialog dengan pesan "Enter word2:".
5. Masukkan kata kedua yang Anda inginkan dan klik OK.
6. Anda akan melihat dialog dengan pesan "Enter word3:".
7. Masukkan kata ketiga yang Anda inginkan dan klik OK.
8. Program akan menampilkan dialog dengan teks yang berisi kata-kata yang telah Anda masukkan.

Pastikan Anda telah mengatur lingkungan Java dengan benar sebelum menjalankan program ini.

### Catatan

- Program ini menggunakan kelas `JOptionPane` dari pustaka Java Swing untuk membuat dialog input dan dialog pesan.
- Kata-kata yang dimasukkan oleh pengguna disimpan dalam variabel `word1`, `word2`, dan `word3`.
- Teks yang berisi kata-kata tersebut digabungkan menjadi satu string yang disimpan dalam variabel `output`.
- Program menggunakan `JOptionPane.showMessageDialog` untuk menampilkan dialog dengan teks `output`.