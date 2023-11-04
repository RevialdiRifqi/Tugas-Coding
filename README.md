# TUGAS 1
1. public class task1 {: Ini adalah deklarasi kelas Java dengan nama task1. Dalam Java, nama kelas harus sama dengan nama file Java yang menyimpannya.

2. public static void main(String[] args) {: Ini adalah metode main, yang merupakan titik awal eksekusi program. Program Java akan mulai berjalan dari sini.

3. for (int i = 1; i <= 100; i++) {: Ini adalah pernyataan perulangan for. Ini akan melakukan iterasi dari i = 1 hingga i = 100. Setiap kali iterasi, nilai i akan bertambah satu.

4. if (i <= 9) {: Ini adalah pernyataan if yang menguji apakah nilai i kurang dari atau sama dengan 9.

5. System.out.println(i);: Jika nilai i kurang dari atau sama dengan 9, maka program akan mencetak nilai i ke layar.

6. } else {: Bagian else dari pernyataan if ini akan dijalankan jika nilai i lebih besar dari 9.

7. System.out.println("(Revialdi Rifqi Ramadhan Permana)");: Jika nilai i lebih besar dari 9, program akan mencetak teks "(Revialdi Rifqi Ramadhan Permana)" ke layar.

8. }: Ini menutup blok else dari pernyataan if.

9. }: Ini menutup blok for.

Jadi, program ini akan mencetak angka dari 1 hingga 9 dan kemudian mencetak teks "(Revialdi Rifqi Ramadhan Permana)" dari 10 hingga 100. Program ini akan mencetak output berdasarkan aturan yang telah dijelaskan di atas.
# TUGAS 2
1. import java.util.Scanner;: Ini adalah pernyataan impor yang mengimpor kelas Scanner dari paket java.util. Kelas Scanner digunakan untuk mengambil masukan dari pengguna melalui keyboard.

2. public class BilanganPrimaChecker {: Ini adalah deklarasi kelas Java dengan nama BilanganPrimaChecker.

3. public static void main(String[] args) {: Ini adalah metode main, yang merupakan titik awal eksekusi program. Program Java akan dimulai dari sini.

4. Scanner input = new Scanner(System.in);: Baris ini membuat objek Scanner dengan nama input yang akan digunakan untuk mengambil masukan dari pengguna melalui System.in (input dari keyboard).

5. Perulangan while (true) { ... } digunakan untuk membuat program berjalan terus menerus sampai pengguna memasukkan bilangan negatif atau nol (untuk keluar).

6. System.out.print("Masukkan bilangan bulat positif (atau 0/negatif untuk keluar): ");: Ini mencetak pesan permintaan masukan kepada pengguna.

7. int angka = input.nextInt();: Ini menggunakan objek input untuk membaca bilangan bulat yang dimasukkan oleh pengguna.

8. if (angka <= 0) { ... }: Ini adalah pernyataan if yang memeriksa apakah bilangan yang dimasukkan pengguna kurang dari atau sama dengan nol.

9. System.out.println("Terima kasih! Program keluar.");: Jika pengguna memasukkan bilangan negatif atau nol, program akan mencetak pesan terima kasih dan kemudian keluar dari perulangan menggunakan pernyataan break.

10. Pada baris-baris selanjutnya, program memanggil fungsi isPrima(angka) untuk menentukan apakah bilangan yang dimasukkan pengguna adalah bilangan prima atau bukan.

11. input.close();: Baris ini menutup objek Scanner setelah program selesai berjalan untuk memastikan bahwa sumber masukan (keyboard) dikembalikan dengan benar.

12. public static boolean isPrima(int angka) { ... }: Ini adalah fungsi yang digunakan untuk menentukan apakah suatu bilangan adalah bilangan prima atau bukan. Fungsi ini melakukan perhitungan dan mengembalikan true jika angka adalah bilangan prima, dan false jika bukan.

Dengan demikian, program ini meminta pengguna memasukkan bilangan bulat positif, kemudian menentukan apakah bilangan tersebut adalah bilangan prima atau bukan, dan akan terus berjalan hingga pengguna memasukkan bilangan negatif atau nol.
# TUGAS 3
1. import java.util.Scanner;: Ini adalah pernyataan impor yang mengimpor kelas Scanner dari paket java.util. Kelas Scanner digunakan untuk mengambil masukan dari pengguna melalui keyboard.

2. public class ZodiacSignChecker {: Ini adalah deklarasi kelas Java dengan nama ZodiacSignChecker.

3. public static void main(String[] args) {: Ini adalah metode main, yang merupakan titik awal eksekusi program. Program Java akan dimulai dari sini.

4. Scanner input = new Scanner(System.in);: Baris ini membuat objek Scanner dengan nama input yang akan digunakan untuk mengambil masukan dari pengguna melalui System.in (input dari keyboard).

5. Program kemudian mencetak pesan "Program Penentu Zodiak" dan meminta pengguna memasukkan tanggal lahir (hari dan bulan).

6. int day = input.nextInt();: Ini menggunakan objek input untuk membaca bilangan bulat yang merupakan tanggal lahir pengguna.

7. int month = input.nextInt();: Ini menggunakan objek input untuk membaca bilangan bulat yang merupakan bulan lahir pengguna.

8. Kemudian, program memanggil fungsi findZodiacSign(day, month) dengan tanggal dan bulan yang dimasukkan oleh pengguna sebagai argumen. Fungsi ini akan menentukan zodiak berdasarkan tanggal lahir.

9. String zodiacSign = findZodiacSign(day, month);: Hasil zodiak yang ditemukan disimpan dalam variabel zodiacSign.

10. Program menggunakan pernyataan if untuk memeriksa apakah hasil zodiak adalah null atau tidak. Jika hasilnya adalah null, artinya tanggal lahir tidak valid, dan program akan mencetak pesan "Tanggal lahir tidak valid." Jika hasilnya bukan null, program akan mencetak zodiak yang sesuai.

11. input.close();: Baris ini menutup objek Scanner setelah program selesai berjalan untuk memastikan bahwa sumber masukan (keyboard) dikembalikan dengan benar.

12. public static String findZodiacSign(int day, int month) { ... }: Ini adalah fungsi yang digunakan untuk menentukan zodiak berdasarkan tanggal lahir yang dimasukkan pengguna. Fungsi ini menggunakan beberapa pernyataan if-else untuk mengecek tanggal lahir dan mengembalikan nama zodiak yang sesuai.

Program ini meminta pengguna memasukkan tanggal lahir dan bulan, kemudian menentukan zodiak yang sesuai dengan tanggal lahir tersebut, dan akan memberikan pesan jika tanggal lahir tidak valid.
# TUGAS 4
1. public class ArrayExample {: Ini adalah deklarasi kelas Java dengan nama ArrayExample.

2. public static void main(String[] args) {: Ini adalah metode main, yang merupakan titik awal eksekusi program. Program Java akan dimulai dari sini.

3. int[] angka = {1, 2, 3, 4, 5};: Baris ini mendefinisikan sebuah array bernama angka yang berisi beberapa nilai bilangan bulat. Dalam hal ini, array angka berisi angka 1, 2, 3, 4, dan 5.

4. System.out.println("Nilai dalam array:");: Ini mencetak pesan "Nilai dalam array:" ke layar untuk memberi tahu pengguna bahwa program akan menampilkan nilai dalam array.

5. Perulangan for digunakan untuk mengakses setiap elemen dalam array angka dan mencetaknya ke layar.

- for (int i = 0; i < angka.length; i++) {: Ini adalah pernyataan perulangan for. Variabel i digunakan sebagai indeks untuk mengakses setiap elemen dalam array.

- System.out.println(angka[i]);: Dalam setiap iterasi perulangan, program akan mencetak nilai yang berada di indeks ke-i dalam array angka ke layar. Ini akan mencetak semua nilai dalam array satu per satu.

Dengan demikian, program ini akan mencetak semua nilai dalam array angka ke layar.
