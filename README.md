Nama: Indi Warda Ramadhani
<br>NIM: 2341760026
<br>Kelas: SIB 3D
<br>Mata Kuliah: Pemrograman Mobile

Praktikum 1: Membuat Project Flutter Baru
<br> 1. Buka VS Code, tekan Ctrl + Shift + P, ketik Flutter, lalu pilih New Application Project.

![Screenshot hello_world](images/01.png)

<br> 2. Buat pada folder Pemograman Mobile, lalu pilih Select a folder to create the project in.

![Screenshot hello_world](images/02.png)

<br> 3. Ketik nama project hello_world, tekan Enter, lalu tunggu hingga proses selesai.

![Screenshot hello_world](images/03.png)

<br> 4. Jika proses selesai, akan muncul pesan **'Your Flutter Project is ready!'** sebagai tanda project baru berhasil dibuat.

![Screenshot hello_world](images/04.png)

<br>Praktikum 2: Menghubungkan Perangkat Android atau Emulator
Melanjutkan dari praktikum 1, Anda diminta untuk menjalankan aplikasi ke perangkat fisik (device Android atau iOS). Silakan ikuti langkah-langkah pada codelab tautan berikut ini.

https://developer.android.com/codelabs/basic-android-kotlin-compose-connect-device?hl=id#0

Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum

1. Buat repository baru dengan nama "flutter-fundamental-part1

![Screenshot hello_world](images/05.png)

2. Klik tombol Create repository , lalu akan muncul tampilan seperti gambar berikut.

![Screenshot hello_world](images/06.png)

3. Kembali ke VS Code pada project hello_world, buka Terminal > New Terminal, lalu ketik perintah untuk inisialisasi git.

![Screenshot hello_world](images/07.png)

4. Beri pesan commit "tambah gitignore" lalu klik Commit (✔)

![Screenshot hello_world](images/08.png)

5. Lakukan push dengan klik bagian menu titik tiga > Push

![Screenshot hello_world](images/09.png)

6. Salin tautan repository Anda dari browser ke bagian ini, lalu klik Add remote

![Screenshot hello_world](images/10.png)

8. Setelah berhasil, tulis remote name dengan "origin"

![Screenshot hello_world](images/11.png)

9. Commit juga pada README

![Screenshot hello_world](images/12.png)

10. Setelah itu berhasil tampil kedua file yang di push

![Screenshot hello_world](images/13.png)

11. Lakukan push juga untuk semua file lainnya dengan pilih Stage All Changes. Beri pesan commit "project hello_world". Maka akan tampil di repository GitHub seperti berikut.

![Screenshot hello_world](images/14.png)

12. Kembali ke VS Code, ubah platform di pojok kanan bawah ke emulator atau device atau bisa juga menggunakan browser Chrome. Lalu coba running project hello_world dengan tekan F5 atau Run > Start Debugging. Tunggu proses kompilasi hingga selesai, maka aplikasi flutter pertama akan tampil seperti berikut.

![Screenshot hello_world](images/15.png)

13. Silakan screenshot seperti pada Langkah 11, namun teks yang ditampilkan dalam aplikasi berupa nama lengkap Anda. Simpan file screenshot dengan nama 01.png pada folder images (buat folder baru jika belum ada) di project hello_world Anda. Lalu ubah isi README.md seperti berikut, sehingga tampil hasil screenshot pada file README.md. Kemudian push ke repository. 

![Screenshot hello_world](images/16.png)

Praktikum 4: Menerapkan Widget Dasar

1. Buat folder lib/basic_widgets, lalu file text_widget.dart. Salin kode berikut ke file tersebut pada project hello_world.

![Screenshot hello_world](images/17.png)

Import text_widget.dart ke main.dart, ganti bagian Text widget dengan kode tersebut. Jalankan project, screenshot hasilnya, lalu buat laporan di README.md.

![Screenshot hello_world](images/18.png)

2. Buat file image_widget.dart di folder lib/basic_widgets, lalu isi dengan kode berikut

![Screenshot hello_world](images/19.png)

Lakukan penyesuaian asset pada file pubspec.yaml dan tambahkan file logo Anda di folder assets project hello_world.

![Screenshot hello_world](images/20.png)

Jangan lupa sesuaikan kode dan import di file main.dart kemudian akan tampil gambar seperti berikut.

![Screenshot hello_world](images/21.png)

Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino

1. Buat file loading_cupertino.dart di basic_widgets, import `material` dan `cupertino`, lalu isi `build` dengan kode berikut:

![Screenshot hello_world](images/22.png)

![Screenshot hello_world](images/23.png)

2. Buat file fab_widget.dart di basic_widgets, import `material`, lalu isi `build` dengan kode untuk tombol FloatingActionButton.

![Screenshot hello_world](images/24.png)

3. Ubah isi main.dart dengan kode berikut untuk menggunakan Scaffold sesuai Material Design:

![Screenshot hello_world](images/25.png)

4. Ubah isi main.dart dengan kode berikut untuk menampilkan AlertDialog dan SimpleDialog:

![Screenshot hello_world](images/26.png)

5. Flutter menyediakan widget input seperti Checkbox, Date/Time Picker, Radio, Slider, Switch, dan TextField. Contoh penggunaan TextField:

![Screenshot hello_world](images/27.png)

6. Date dan Time Pickers termasuk widget input & selection. Contoh penggunaannya:

![Screenshot hello_world](images/28.png)

![Screenshot hello_world](images/29.png)










