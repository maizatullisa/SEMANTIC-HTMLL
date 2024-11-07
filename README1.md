# SEMANTIC-HTMLL
2205101042

PENJELASAN TAG HTML :

1. <!DOCTYPE html> : Deklarasi tipe dokumen HTML5, yang memberi tahu browser bahwa dokumen ini menggunakan standar HTML5.

2. <html lang="en"> : Tag pembuka elemen HTML. Atribut `lang="en"` menunjukkan bahwa bahasa utama dokumen ini adalah bahasa Inggris.

3.  <head> : Bagian ini berisi metadata dokumen, seperti judul, karakter yang digunakan, stylesheet yang dihubungkan, dan informasi yang tidak akan terlihat langsung di halaman web.

4. <meta charset="UTF-8"> : Menentukan bahwa karakter yang digunakan di halaman ini adalah UTF-8, yang mendukung berbagai macam karakter internasional.

5. <meta name="viewport" content="width=device-width, initial-scale=1.0">: Mengatur tampilan agar sesuai dengan ukuran layar perangkat, khususnya untuk membuat halaman responsif pada perangkat seluler.

6. <title>HTML5 SEMANTIC</title>: Menentukan judul halaman yang akan muncul di tab browser atau bookmark.

7. <link rel="stylesheet" href="./Assets/style/style.css">: Menghubungkan file CSS eksternal yang bernama `style.css` untuk menambahkan gaya pada halaman ini.

8. <body>: Bagian utama yang berisi semua konten yang akan ditampilkan di halaman web.

9. <header>: Menandakan bagian header dari halaman, biasanya berisi judul atau elemen navigasi utama. Dalam hal ini, header berisi judul "HTML5 SEMANTIC".

10. <h1>HTML5 SEMANTIC</h1>: Elemen heading utama yang menampilkan judul halaman dengan ukuran terbesar.

11. <nav>: Bagian navigasi dari halaman, biasanya berisi tautan untuk berpindah ke bagian lain di halaman atau ke halaman lain.

12. <ul>: Elemen list yang tidak berurutan (unordered list) yang berisi beberapa item navigasi.

13. <li><a href="#home">Home</a></li>: Setiap `<li>` adalah item daftar, dan `<a href="#home">Home</a>` adalah tautan ke bagian dengan id "home" dalam halaman ini.

14. <section>: Digunakan untuk menandakan bagian konten utama dari halaman. Di sini, tertulis teks "Konten" yang dapat diisi dengan konten lebih lanjut.

15. <footer> : Bagian footer halaman, yang biasanya berisi informasi hak cipta, tautan tambahan, atau informasi kontak. Di sini hanya tertulis "Copyright".

PENJELASAN TAG STYLE CSS :

Berikut adalah penjelasan dari masing-masing tag dan properti CSS di dalam kode tersebut:

1. **`<body>`**: 
   - Elemen ini merupakan bagian utama dari halaman web, yang berisi semua konten yang akan ditampilkan pada halaman.
   - Dalam kode ini, `body` menggunakan CSS Grid untuk mengatur tata letak halaman menjadi beberapa area (header, nav, section, footer).

2. **`<header>`**:
   - Bagian atas dari halaman web, sering digunakan untuk menampilkan judul, logo, atau navigasi utama.
   - Diatur dalam grid area bernama "header" dengan latar belakang abu-abu (#707070) dan teks ditengah (centered).

3. **`<nav>`**:
   - Bagian navigasi yang berisi tautan atau menu untuk berpindah antar halaman.
   - Ditempatkan di sebelah kiri (area grid "nav") dan memiliki latar belakang warna abu-abu (#C9BFBF).

4. **`<section>`**:
   - Bagian utama dari halaman yang berisi konten.
   - Diatur pada area grid "section" dan memiliki latar belakang abu-abu muda (#ABABAB).

5. **`<footer>`**:
   - Bagian bawah dari halaman, biasanya menampilkan informasi hak cipta atau informasi tambahan lainnya.
   - Terletak di area grid "footer", dengan latar belakang abu-abu (#707070), ukuran font kecil, dan teks ditengah.

### Properti CSS:
1. **`display: grid`**:
   - Mengaktifkan CSS Grid Layout pada elemen `<body>`, memungkinkan pembuatan tata letak berbasis grid.

2. **`grid-template-areas`**:
   - Menentukan tata letak grid dengan menamai area, yaitu:
     - `header` menempati tiga kolom di atas.
     - `nav` berada di kolom pertama baris kedua.
     - `section` berada di dua kolom terakhir di baris kedua.
     - `footer` menempati seluruh baris ketiga.

3. **`grid-template-rows`** dan **`grid-template-columns`**:
   - Menentukan ukuran dari setiap baris dan kolom grid.
   - `grid-template-rows: 80px 1fr 50px`:
     - Baris pertama setinggi 80px.
     - Baris kedua memiliki ukuran fleksibel (`1fr`) yang mengisi ruang yang tersisa.
     - Baris ketiga setinggi 50px.
   - `grid-template-columns: 20% 1fr 18%`:
     - Kolom pertama adalah 20% dari lebar halaman.
     - Kolom kedua adalah 1fr (fleksibel, mengisi ruang tersisa).
     - Kolom ketiga adalah 18% dari lebar halaman.

4. **`grid-gap: 5px`**:
   - Menambahkan jarak 5px di antara elemen grid.

5. **`height: 100vh`**:
   - Mengatur tinggi dari `body` agar mencakup seluruh tinggi viewport.

6. **`background`**:
   - Menentukan warna latar belakang untuk setiap area (`nav`, `header`, `section`, `footer`).

7. **`padding: 5px`**:
   - Memberikan jarak dalam (padding) sebesar 5px di dalam setiap elemen grid agar konten tidak terlalu dekat dengan batas elemen.

8. **`text-align: center`**:
   - Mengatur teks dalam elemen `<header>` dan `<footer>` agar berada di tengah.

9. **`font-size: small`**:
   - Mengatur ukuran font di `<footer>` menjadi kecil.
