### PENJELASAN HTML
- <!DOCTYPE html>  : Menentukan tipe dokumen sebagai HTML5.
- <html lang="en"> : Elemen utama yang menampung semua konten HTML, dengan atribut `lang="en"` menunjukkan bahwa bahasa                           dokumen adalah Inggris.
- <head>           : Bagian dari dokumen HTML yang berisi metadata seperti judul, karakter encoding, dan link ke stylesheet.
- <meta charset="UTF-8">: Menentukan karakter encoding sebagai UTF-8, yang mendukung berbagai karakter internasional.
- <meta name="viewport" content="width=device-width, initial-scale=1.0"> : Mengatur tampilan agar responsif pada perangkat yang berbeda.
- <title>HTML5 SEMANTIC</title> : Menentukan judul halaman yang akan ditampilkan di tab browser.
- <link rel="stylesheet" href="./Assets/style/style.css"> : Menghubungkan file CSS eksternal untuk menata tampilan halaman.

### TAG Di dalam <body> :
- <header>: Bagian header halaman, biasanya berisi judul dan elemen navigasi.
- <h1>HTML5 SEMANTIC</h1> : Elemen heading utama yang menampilkan judul besar "HTML5 SEMANTIC".
- <nav>: Elemen navigasi yang berisi daftar link atau menu navigasi.
- <ul> : Membuat daftar yang tidak berurutan (unordered list).
- <li> : Item di dalam daftar.
- <a href="#">Home</a> : Tautan yang mengarahkan pengguna ke bagian lain di halaman atau halaman lain.
- <section> : Digunakan untuk menandai bagian konten yang terstruktur.
- <footer> : Bagian footer halaman, biasanya berisi informasi seperti hak cipta atau kontak.

### PENJELASAN CSS
### CSS untuk <body>:

- display: grid; : Mengubah layout body menjadi grid.
- grid-template-areas : Mendefinisikan area grid yang diberi nama untuk mempermudah penataan elemen seperti `header`, `nav`, `section`, dan `footer`.
- "header header header" : Area `header` menempati seluruh kolom di baris pertama.
- "nav section section" : Area `nav` menempati kolom pertama di baris kedua, sedangkan `section` menempati dua kolom berikutnya.
- "footer footer footer" : Area `footer` menempati seluruh kolom di baris ketiga.
- grid-template-rows: 80px 1fr 50px; : Menetapkan tinggi setiap baris grid: 80px untuk header, `1fr` (fleksibel) untuk konten utama, dan 50px untuk footer.
- grid-template-columns: 20% 1fr 18%; : Menetapkan lebar setiap kolom grid: 20% untuk `nav`, `1fr` (fleksibel) untuk `section`, dan 18% untuk kolom tambahan (kosong).
- grid-gap: 5px; : Menambahkan jarak antar elemen grid sebesar 5px.
- height: 100vh; : Mengatur tinggi body agar sesuai dengan tinggi tampilan (viewport height).

### CSS untuk Setiap Elemen:
- header, nav, section, footer { padding: 5px; } : Memberikan padding 5px pada setiap elemen untuk menambahkan jarak di dalam elemen.

#### Styling Khusus untuk Setiap Elemen:
- nav : Background `#C9BFBF` dan ditempatkan di area nav.
- header: Background `#707070`, ditempatkan di area header , dan teks diatur rata tengah (`text-align: center;`).
- section : Background `#ABABAB` dan ditempatkan di area section.
- footer : Background `#707070`, ditempatkan di area footer, dengan font kecil (`font-size: small;`) dan teks rata tengah.

### PERBEDAAN 
### HTML
- **Struktur & Konten**: HTML digunakan untuk membuat struktur dan menyusun elemen-elemen pada halaman web. Tag HTML mendefinisikan berbagai bagian halaman seperti header, navigasi, konten, dan footer.
- **Elemen HTML**:
  - `<header>`: Menandai bagian header atau judul halaman.
  - `<nav>`: Bagian navigasi untuk menampilkan tautan.
  - `<section>`: Bagian utama untuk konten.
  - `<footer>`: Bagian footer untuk informasi tambahan.
  - `<h1>`, `<ul>`, `<li>`, `<a>`: Elemen-elemen yang mendefinisikan judul, daftar, dan tautan.
- **Peran**: HTML hanya memberikan *struktur* atau *layout* dari halaman web tanpa memberikan *gaya* atau *tampilan visual*.

### CSS
- **Tampilan & Desain**: CSS mengontrol tampilan, gaya, dan tata letak dari elemen-elemen HTML. Dalam kode di atas, CSS mengatur warna, posisi, ukuran, dan penataan dari setiap elemen yang telah didefinisikan dalam HTML.
- **Elemen CSS**:
  - `display: grid;`: Mengubah tata letak `body` menjadi grid.
  - `grid-template-areas`: Menetapkan area grid untuk elemen-elemen seperti `header`, `nav`, `section`, dan `footer`.
  - `grid-template-rows` dan `grid-template-columns`: Mengatur ukuran baris dan kolom dalam layout grid.
  - `background`: Mengatur warna latar belakang dari setiap elemen (`header`, `nav`, `section`, `footer`).
  - `padding`, `font-size`, `text-align`: Mengatur jarak dalam elemen, ukuran font, dan perataan teks.
- **Peran**: CSS hanya memberikan *gaya* atau *desain* tanpa mengubah struktur atau makna semantik dari elemen-elemen HTML.

### Perbedaan Utama
1. **Fungsi**:
   - HTML: Mengatur struktur dan isi halaman.
   - CSS: Mengatur tampilan visual dan tata letak halaman.

2. **Posisi dalam Dokumen**:
   - HTML ditulis dalam file `.html` (atau di bagian `<body>` halaman).
   - CSS ditulis dalam file `.css` terpisah atau di bagian `<style>` dalam `<head>` HTML.

3. **Efek pada Halaman**:
   - HTML: Menambah atau mengubah elemen atau bagian tertentu pada halaman.
   - CSS: Meningkatkan estetika halaman dengan warna, ukuran, spasi, dan tata letak.

Singkatnya, HTML membuat *kerangka* atau *struktur* halaman web, sedangkan CSS memberi halaman *gaya* dan *desain visual*.
