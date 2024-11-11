# SEMANTIC-HTML
Latihan Praktikum 1 Semantic HTML

## Latihan 1 : Semantic HTML
1. **Menganalisis Kode index.html** <br>
  Semantic HTML adalah elemen-elemen di HTML yang dapat menggantikan fungsi div berserta atributnya, sehingga baris kode menjadi    lebih ringkas.
  a. **Revisi yang dilakukan dari modul** <br>
    Revisi yang dilakukan adalah pada struktur dasar HTML yaitu penambahan tag html, tag head berserta tag yang ada di dalamnya       seperti tag meta,title, link. Struktur dasar HTML adalah elemen yang harus ada didalam kode program HTML yang merupakan           pembentuk suatu dokumen atau website. Jika tidak lengkap maka website yang terbentuk juga tidak akan sesuai dengan yang           diharapkan. 
  b. **Penjelasan kode index.html** <br>
     => **Struktur dasar HTML** terdiri dari tag DOCTYPE, tag html, tag head dan tag body sebagai tempat konten seluruh isi web.
     => **tag header** yang mendefinisikan bagian pembuka atau kepala dari halaman yang dibuat. Di dalam tag header ada tag h1            sebagai judul utama dari halam yang dibuat.
     => **tag nav** yang berfungsi untuk mengelompokkan bagian navigasi di halaman web seperti Home, Pengertian, Kesimpulan. Isi          bagian navigasi ini di bungkus dengan tag ul untuk membentuk daftar menu navigasi tetapi dengan tidak terurut.
     => **tag section** yang mendefinisikan bagian utama konten halaman web.
     => **tag footer** yang menunjukkan bagian akhir atau penutup halaman web yang dibuat.
   
2. **Menganalisis Kode style_index.css**
   Revisi yang dilakukan adalah pada bagian atribut background yang dibuat menjadi lebih spesifik dengan background-color
   a. **Elemen nav** diberikan gaya yaitu warna latar belakang abu-abu muda dan tag nav akan berada di area grid yang diberi nama       "nav".
   b. **Elemen header** diberikan gaya yaitu warna latar belakang abu-abu lalu tag header akan berada di area grid yang diberi            nama "header" dan perataan teksnya adalah tengah.
   c. **Elemen section** diberikan gaya yaitu warna latar belakang abu-abu terang dan tag section akan berada di area grid yang         diberi nama "section".
   d. **Elemen footer** diberikan gaya yaitu warna latar belakang abu-abu, tag footer akan berada di area grid yang diberi              nama "footer", ukuran size teksnya kecil dan perataan teksnya adalah tengah.
   e. **Elemen body** diberikan gaya :
     => Tampilan tata letak yaitu grid yang lebih fleksibel dan terstruktur
     => Bagaimana tata letak ini diatur yaitu dengan grid-template-areas yang diberikan nama sesuai elemen yang diatur.
     => Ukuran tinggi setiap baris grid yaitu 80px untuk baris bertama, 1fr untuk baris kedua, 50px untuk baris ketiga.
     => Ukuran kolom-kolom pada grid yaitu 20% untuk kolom pertama, 1fr untuk kolom kedua, 18% untuk kolom ketiga.
     => Jarak antar elemen grid adalah 5px
     => Ukuran tinggi elemen pembungkusnya yaitu body adalah 100vh dengan marginnya 10px.
   f. Gaya keseluruhan pada elemen pembentuk halaman web yaitu padding 5px. 
