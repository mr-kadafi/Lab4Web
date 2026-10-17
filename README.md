# Praktikum 4 — CSS Layout

## Identitas Praktikum

- **Nama:** Mu’ammar Kadafi
- **NIM:** 312510192
- **Program Studi/Semester:** Teknik Informatika / 3
- **Mata Kuliah:** Pemrograman Web
- **Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom.
- **Kelas:** I253C
- **Hari/Tanggal:** Sabtu, 17 Oktober 2026
- **Pertemuan:** 5 (Online)

## Langkah-Langkah Praktikum

### 1. Mempersiapkan Text Editor

Mempersiapkan text editor yang akan digunakan untuk menulis kode program, misalnya Visual Studio Code.

### 2. Membuat Folder Kerja

Membuat folder kerja dengan nama `Lab4Web` sebagai tempat menyimpan file praktikum.

### 3. Membuat File HTML

Membuat file baru dengan nama `lab4_box.html` di dalam folder kerja yang telah dibuat.

### 4. Menuliskan Kode HTML

Pada file `lab4_box.html`, masukkan kode berikut.

![Screenshot langkah 4](screenshots/4.1.png)

### 5. Membuat Box Element

Kemudian, tambahkan kode untuk membuat box element menggunakan tag `<div>` seperti berikut.

![Screenshot langkah 5](screenshots/5.1.png)

### 6. Menggunakan CSS Float Property

Selanjutnya, tambahkan deklarasi CSS pada bagian `<head>` untuk membuat elemen menggunakan properti `float`, seperti berikut.

![Screenshot langkah 6.1](screenshots/6.1.png)

Perubahan tampilannya akan terlihat seperti pada gambar berikut.

![Hasil langkah 6](screenshots/6.2.png)

### 7. Menambahkan Elemen Div

Tambahkan elemen `<div>` lainnya setelah elemen `div3` seperti berikut.

![Screenshot langkah 7](screenshots/7.1.png)

### 8. Mengatur Properti Clear pada CSS

Kemudian, atur properti `clear` pada CSS seperti berikut.

![Screenshot langkah 8.1](screenshots/8.1.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil langkah 8](screenshots/8.2.png)

### 9. Melakukan Eksperimen Properti Clear

Lakukan eksperimen terhadap penggunaan properti `clear` dengan nilai lainnya, yaitu `left`, `right`, `both`, dan `none`. Amati perubahan tampilan yang terjadi.

**a. Mengubah nilai `clear` menjadi `right`**

![Kode CSS clear right](screenshots/9.1.png)

Hasil: Elemen `Div 4` akan berpindah ke bawah elemen yang mengambang di sisi kanan. Tampilan akan terlihat seperti pada gambar berikut.

![Hasil clear right](screenshots/9.2.png)

**b. Mengubah nilai `clear` menjadi `both`**

![Kode CSS clear both](screenshots/9.3.png)

Hasil: Elemen `Div 4` akan berpindah ke bawah elemen yang mengambang di sisi kiri maupun kanan. Tampilan akan terlihat seperti pada gambar berikut.

![Hasil clear both](screenshots/9.4.png)

**c. Mengubah nilai `clear` menjadi `none`**

![Kode CSS clear none](screenshots/9.5.png)

Hasil: Elemen `Div 4` tidak diwajibkan berpindah ke bawah elemen yang menggunakan `float`. Karena `float: none` membuat `Div 4` mengikuti alur normal dokumen, elemen tersebut dapat berada di samping elemen-elemen sebelumnya jika masih tersedia ruang. Tampilan akan terlihat seperti pada gambar berikut.

![Hasil clear none](screenshots/9.6.png)

### 10. Membuat Folder dan File Layout

Buat folder baru dengan nama `lab4_layout`, kemudian buat file baru di dalamnya dengan nama `home.html` dan file CSS dengan nama `style.css`.

![Struktur folder dan file](screenshots/10.1.png)

### 11. Menuliskan Kode HTML Layout

Kemudian, tuliskan kode HTML berikut pada file `home.html`.

![Kode HTML layout](screenshots/11.1.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil HTML layout](screenshots/11.2.png)

### 12. Menambahkan CSS untuk Layout

Kemudian, tambahkan kode CSS untuk membuat layout halaman web.

![Kode CSS layout](screenshots/12.1.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil CSS layout](screenshots/12.2.png)

### 13. Mengatur Navigasi

Selanjutnya, atur bagian navigasi pada halaman web menggunakan kode berikut.

![Kode navigasi](screenshots/13.1.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil navigasi](screenshots/13.2.png)

### 14. Membuat Hero Panel

Selanjutnya, buat bagian hero panel dengan menambahkan kode HTML dan CSS seperti berikut.

![Kode HTML hero panel](screenshots/14.1.png)

![Kode CSS hero panel](screenshots/14.2.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil hero panel](screenshots/14.3.png)

### 15. Mengatur Main Content dan Sidebar

Selanjutnya, atur bagian main content dan sidebar dengan menambahkan CSS menggunakan properti `float`.

![Kode CSS main content dan sidebar](screenshots/15.1.png)

### 16. Menambahkan Elemen pada Sidebar

Selanjutnya, tambahkan elemen lainnya pada bagian sidebar.

![Kode HTML sidebar](screenshots/16.1.png)

Kemudian, tambahkan CSS untuk mengatur tampilan elemen sidebar tersebut.

![Kode CSS sidebar](screenshots/16.2.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil sidebar](screenshots/16.3.png)

### 17. Mengatur Tampilan Footer

Selanjutnya, atur tampilan footer dengan menambahkan kode CSS berikut.

![Kode CSS footer](screenshots/17.1.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil footer](screenshots/17.2.png)

### 18. Menambahkan Elemen pada Main Content

Tambahkan elemen lainnya pada bagian main content sesuai dengan kode berikut.

![Kode HTML elemen main content](screenshots/18.1.png)

Kemudian, tambahkan CSS untuk mengatur tampilan elemen tersebut.

![Kode CSS elemen main content](screenshots/18.2.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil main content](screenshots/18.3.png)

### 19. Membuat Konten Artikel

Selanjutnya, buat konten artikel dengan menambahkan kode HTML berikut pada bagian main content.

![Kode HTML konten artikel](screenshots/19.1.png)

Kemudian, tambahkan CSS untuk mengatur tampilan konten artikel.

![Kode CSS konten artikel](screenshots/19.2.png)

Tampilan akan terlihat seperti pada gambar berikut.

![Hasil konten artikel](screenshots/19.3.png)
