# Bijak Sampah — Website Edukasi SDGs

Website Bijak Sampah
SDG 11 (Kota dan Permukiman Berkelanjutan) dan SDG 12 (Konsumsi dan Produksi yang Bertanggung Jawab).

## Anggota Kelompok
1. Nazma Rahmadhani - 2515091028 - Membuat halaman Tentang (tentang.html)
2. Ni Made Ira Perlina - 2515091031 - Membuat halaman Panduan dan Artikel (panduan.html & artikel.html)
3. Ni Luh Putu Terry Maharani Putri -2515091034 - Membuat halaman Kategori (kategori.html)
4. Putu Githa Kusuma Wardani - 2515091110 - Membuat halaman Beranda (beranda.html)

## Deskripsi Website

### Tujuan
Menyediakan informasi tentang pengelolaan sampah rumah tangga yang mudah dipahami dan dapat diterapkan dalam kehidupan sehari-hari.

### Manfaat
- Membantu pengunjung mengenali jenis-jenis sampah.
- Memberikan panduan sederhana untuk mengurangi dan memilah sampah.
- Meningkatkan kesadaran tentang pentingnya pengelolaan sampah.
- Mengajak masyarakat membangun kebiasaan yang lebih ramah lingkungan.

### Sasaran Pengguna
Website ini ditujukan untuk masyarakat umum, khususnya pelajar, mahasiswa, dan keluarga yang ingin mempelajari pengelolaan sampah rumah tangga.

## Halaman Website

Website ini terdiri dari lima halaman HTML yang saling terhubung melalui navigasi.
1. Beranda: `index.html`, Memperkenalkan website dan mengarahkan pengunjung ke materi utama.
2. Kategori: `Kategori.html`, Menjelaskan jenis sampah: organik, anorganik, B3, dan residu.
3. Panduan: `panduan.html`, Memberikan panduan Reduce, Reuse, Recycle, serta kebiasaan pengelolaan sampah di rumah.
4. Artikel: `artikel.html`, Menyajikan inspirasi untuk mengurangi sampah makanan, penggunaan plastik, dan membiasakan pemilahan sampah. 
5. Tentang: `tentang.html`, Memuat informasi tentang website, anggota kelompok, dan referensi.

## Teknologi

- HTML5: Membuat struktur dan isi setiap halaman website.
- CSS3: Mengatur tampilan, warna, tipografi, jarak, dan komponen website.
- CSS Grid: Mengatur tata letak kartu dan bagian konten dalam beberapa kolom.
- Flexbox: Membantu menyusun elemen agar rapi dan mudah disesuaikan.
- Media Queries: Menyesuaikan tampilan website pada desktop, tablet, dan smartphone.
- Google Fonts dan Unsplash: Menyediakan font dan foto dekoratif yang dimuat melalui internet.

## Penjelasan Implementasi

### Struktur HTML

HTML digunakan untuk menyusun konten setiap halaman. Website menggunakan elemen semantik seperti `header`, `nav`, `main`, `section`, `article`, dan `footer` agar struktur halaman lebih terorganisasi.

Contoh:

```html
<header class="site-header">
    <nav class="nav">
        <a href="index.html">Beranda</a>
        <a href="edukasi.html">Edukasi</a>
        <a href="panduan.html">Panduan</a>
        <a href="artikel.html">Artikel</a>
        <a href="tentang.html">Tentang</a>
    </nav>
</header>
```

Kode tersebut membuat navigasi yang menghubungkan lima halaman website.

### CSS Eksternal

Seluruh halaman menggunakan file CSS eksternal yang berada di `css/style.css`.

```html
<link rel="stylesheet" href="css/style.css">
```

Kode tersebut menghubungkan dokumen HTML dengan stylesheet sehingga tampilan halaman dapat diatur melalui satu file CSS.

### CSS Grid dan Flexbox

CSS Grid digunakan untuk mengatur tata letak kartu dan konten dalam beberapa kolom. Flexbox digunakan untuk membantu menyusun elemen secara horizontal atau vertikal sesuai kebutuhan desain.

Contoh penggunaan Grid berikut merupakan ilustrasi. 
```css
.category-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 24px;
}
```

Kode tersebut menyusun kartu kategori menjadi empat kolom pada layar yang cukup lebar.

### Media Queries

Media queries digunakan untuk menyesuaikan tata letak berdasarkan ukuran layar.

Contoh berikut merupakan ilustrasi penyesuaian menjadi dua kolom pada layar yang lebih kecil. 
```css
@media (max-width: 1000px) {
    .category-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}
```

Dengan desain responsif, tata letak dapat disesuaikan agar konten lebih nyaman dibaca pada perangkat yang berbeda.

### Navigasi Antarahalaman

Setiap halaman menyediakan tautan menuju halaman lainnya. Navigasi ini membantu pengunjung berpindah dari Beranda ke Edukasi, Panduan, Artikel, atau Tentang.


## Struktur Folder

Struktur folder proyek dirancang sebagai berikut:

```text
Bijak_Sampah_Professional/
├── index.html
├── kategori.html
├── panduan.html
├── artikel.html
├── tentang.html
├── css/
│   └── style.css
└── README.md
```

## Website dan Repository

- URL GitHub Repository: https://github.com/githaceo/Bijak-Sampah/
- URL GitHub Pages: https://githaceo.github.io/Bijak-Sampah/index.html
  
## Referensi 

1. Kementerian Lingkungan Hidup dan Kehutanan. Sistem Informasi Pengelolaan Sampah Nasional. https://sipsn.menlhk.go.id/sipsn/
2. United Nations. Sustainable Development Goal 11: Sustainable Cities and Communities. https://sdgs.un.org/goals/goal11
3. United Nations. Sustainable Development Goal 12: Responsible Consumption and Production. https://sdgs.un.org/goals/goal12
4. United Nations Environment Programme. https://www.unep.org/

## Sumber Gambar
1. https://qr.ptsuparmatbk.com/blog/wp-content/uploads/2025/05/sampah-organik.png 
2. https://www.circularonline.co.uk/wp-content/uploads/2019/09/Screenshot-2019-09-12-at-07.45.34-1.png
3. https://axil-is.com/wp-content/uploads/2022/08/5-Hazardous-Waste-Examples-Image-1-768x512.jpeg
4. https://media.istockphoto.com/id/1132033248/id/foto/sampah-tisu-gambar-pilek-pilek-demam-jerami-dll-atau-setelah-make-up.jpg?s=170667a&w=0&k=20&c=FabDx9YqFQ-JrdfQFjIn9Yg8PFrlHk4-Jzkjyu6JUug=
5. https://dlhk.mamujukab.go.id/foto_berita/75food_waste_reduce.jpg
6. https://cdn.vectorstock.com/i/500p/38/45/plastic-or-textile-bags-plastics-rubbish-vector-24613845.jpg
7. https://thumbs.dreamstime.com/b/hand-putting-single-use-plastic-bottle-recycling-bin-hand-putting-single-use-plastic-bottle-recycling-bin-person-163286509.jpg
