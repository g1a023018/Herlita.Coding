# Herlita.Coding
# Tugas 1
Kode di atas adalah program Java sederhana yang mencetak angka dari 1 hingga 100 ke layar. Pada setiap iterasi perulangan `for`, program melakukan pemeriksaan kondisi dengan menggunakan pernyataan `if`. Jika nilai `i` (angka iterasi saat ini) kurang dari atau sama dengan 9, maka program akan mencetak angka itu sendiri. Namun, jika `i` lebih besar dari 9, maka program akan mencetak teks "Herlita" sebagai gantinya. Oleh karena itu, program ini akan mencetak angka dari 1 hingga 9, dan kemudian mencetak "Herlita" dari 10 hingga 100.

Ini hasil outputnya
![Screenshot (16)](https://github.com/g1a023018/Herlita.Coding/assets/149585321/584c01b0-c14a-4cbb-88c9-cd629f4cd457)

# Tugas 2
Kode di atas adalah program Java yang memungkinkan pengguna untuk memasukkan bilangan bulat dan kemudian menentukan apakah bilangan tersebut positif atau negatif. Program dimulai dengan mengimpor kelas `Scanner` untuk menerima input pengguna. Selanjutnya, program mendeklarasikan variabel `number` sebagai bilangan bulat yang akan digunakan untuk menyimpan input pengguna. Program kemudian meminta pengguna untuk memasukkan bilangan bulat dan membaca input tersebut dengan menggunakan `scanner.nextInt()`. 

Selanjutnya, program memasuki sebuah perulangan `while`, yang akan terus berjalan selama `number` tidak sama dengan 0, artinya pengguna masih ingin memasukkan bilangan. Di dalam perulangan, program menggunakan pernyataan `if` untuk memeriksa apakah `number` positif (lebih besar dari 0) atau negatif (kurang dari 0) dan mencetak pesan yang sesuai. Setelah itu, program meminta pengguna untuk memasukkan bilangan berikutnya atau 0 untuk keluar. Jika pengguna memasukkan 0, perulangan berakhir, dan program mencetak pesan "Program selesai" sebelum menutup objek `Scanner` dengan `scanner.close()`.

Dengan demikian, program ini memberikan pengguna kemampuan untuk menguji apakah bilangan bulat yang mereka masukkan adalah positif atau negatif, dan proses akan berlanjut hingga pengguna memutuskan untuk keluar dengan memasukkan 0.

Ini hasil outputnya
![Screenshot (17)](https://github.com/g1a023018/Herlita.Coding/assets/149585321/4374ea10-7300-4abe-ab17-8bcd7df1c048)

# Tugas 3
Kode di atas adalah program Java yang dirancang untuk membantu pengguna menentukan zodiak berdasarkan tanggal lahir yang mereka masukkan. Program ini dimulai dengan mengimpor kelas `Scanner` untuk menerima input dari pengguna. Selanjutnya, program meminta pengguna memasukkan tanggal dan bulan lahir mereka. Setelah menerima input ini, program memanggil fungsi `determineZodiacSign()`, yang secara modular memeriksa tanggal lahir dan mengembalikan zodiak yang sesuai. Jika tanggal lahir valid, program mencetak zodiak pengguna; jika tidak, program memberi tahu pengguna bahwa tanggal lahir tidak valid.

Fungsi `determineZodiacSign()` berisi aturan zodiak astrologi, yang memungkinkan program untuk mengidentifikasi zodiak berdasarkan bulan dan tanggal lahir yang dimasukkan. Jika tanggal lahir tidak memenuhi kriteria validasi, fungsi ini mengembalikan `null` untuk menunjukkan ketidakvalidan. Program kemudian memeriksa hasil yang dikembalikan oleh fungsi ini dan mencetak pesan yang sesuai, yaitu zodiak pengguna atau pesan kesalahan jika tanggal lahir tidak valid.

Akhirnya, program menutup objek `Scanner` untuk membersihkan sumber daya. Kode ini menggabungkan pemrosesan input dan output interaktif dengan penggunaan fungsi untuk membagi tugas-tugas program menjadi bagian yang lebih terstruktur.

Ini hasil outputnya
![Screenshot (18)](https://github.com/g1a023018/Herlita.Coding/assets/149585321/1937d2e8-baed-4336-b8eb-14170bd609bf)

# Tugas 4
Kode di atas adalah program Java yang menggambarkan cara bekerja dengan array bilangan bulat dan menggunakan perulangan `for` untuk menampilkan nilai-nilai dalam array tersebut. Pertama-tama, program mendeklarasikan sebuah array yang dinamai `numbers`, yang berisi sepuluh bilangan bulat mulai dari 1 hingga 10. Dalam array ini, setiap bilangan memiliki indeks yang dimulai dari 0, sehingga `numbers[0]` berisi 1, `numbers[1]` berisi 2, dan seterusnya hingga `numbers[9]` berisi 10.

Kemudian, program mencetak pesan "Nilai dalam variabel array:" ke layar, memberi tahu pengguna bahwa nilai-nilai dalam array akan ditampilkan. Program selanjutnya menggunakan perulangan `for` untuk mengakses setiap elemen dalam array. Perulangan ini diatur untuk mengulang sebanyak panjang array `numbers`, yaitu sebanyak sepuluh kali, dengan menggunakan variabel `i` sebagai indeks. Dalam setiap iterasi perulangan, nilai dari `numbers[i]` diambil, dan program mencetak nilai tersebut ke layar. Akibatnya, semua nilai dalam array, yaitu angka 1 hingga 10, akan ditampilkan secara berurutan di layar.

Dengan demikian, program ini memperlihatkan cara penggunaan array dalam Java dan bagaimana perulangan `for` dapat digunakan untuk mengakses dan menampilkan nilai-nilai dalam array secara berurutan.

Ini hasil outputnya
![Screenshot (19)](https://github.com/g1a023018/Herlita.Coding/assets/149585321/d7bfc26d-9730-48c9-a562-73e76f784b53)
