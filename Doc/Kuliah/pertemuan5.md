**SISTEM INFORMASI GEOGRAFIS**

**MEMBUAT DAN MENGEDIT DATA GEOSPASIAL**
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pic8.PNG">
</p>
**Latar Belakang :**

Untuk pembahasan kali ini akan membahas tentang manipulasi geospasila dan menjelaskan tentang bagaimana cara membuat dan mengedit data geospasial dengan menggunakan library pyshp.

**Pembahasan :**

1. **Untuk menambahkan data geospasial :**

Import Shapefile a = shapefile.writer()

- Untuk SHP file Geometri

a.point(x,y) a.poly{x,y],[x,y])

- Untuk DBF file Table

a.filed(&#39;namafolder&#39;,&#39;C&#39;,&#39;4&#39;).arecord(&#39;BDG&#39;)

- Untuk menyimpan,disimpan dengan method :

a.save(file.shp&#39;)

- Untuk menambahkan data Poin dan polygon :

1. Poin

a.poly([a,b],[c,d])

1. Polygon

a.field(&#39;kota&#39;,&#39;C&#39;,&#39;4&#39;)

- Untuk membuat Attribute :

a.field(&#39;Kota&#39;,&#39;C&#39;,&#39;4&#39;) a.record(&#39;Bandung&#39;)

- Untuk Menyimpan Shapefile :

a.save(&#39;namafile&#39;)

- Untuk Parameter Writer :

1. Shapefile Poin

a.point(&#39;10&#39;,&#39;12&#39;)

1. Shapefile Polygon

a.poly(ports = ([3.5], [5,5], [5,7] ))

1. Shapefile Polyline

a.ports([3,5], [5,5], [3,5], shapetype.shapefile.polyline).

1. **Untuk edit data geospasial**

Sf = shapefile.Writer(param)

Kemudian diganti dengan

Sf = shapefile.Editor(param) parameter disini adalah nama letak filenya.

**Penutup :**

1. **Kesimpulan**

Dalam membuat dan mengedit data geospasial menggunakan library pyshp langkah dan caranya hamper sama  hanya saja dalam membuat kita menggunakan _Write_ sedangkan untuk mengedit data geospasial kita menggunakan _Editor_.

1. **Saran**

Sebaiknya dalam melakukan prakter membuat dan mengedit harus mengetahui materi terlebih dahulu lalu melakukan prakter sehingga dapat memudahkan dalam mengedit dan membuat data geospasial.

Link Github : [https://github.com/Khaeratunnisa/Geografis-Informasi-System](https://github.com/Khaeratunnisa/Geografis-Informasi-System)

NAMA        :KHAERATUNNISA
NPM                : 1144044

KELAS        : D4TI3A

KAMPUS        : POLITEKNIK POS INDONESIA

Link Mata Kuliah :   [Sistem Informasi Geografis](http://www.awangga.net/)

Referensi                 : http://www.wikipedial.com /

Scan Plagiarisme :

[https://drive.google.com/open?id=0B2tnHz81APcBRVdpbmtXZWp1emc](https://drive.google.com/open?id=0B2tnHz81APcBRVdpbmtXZWp1emc)

[https://drive.google.com/open?id=0B2tnHz81APcBaDcyWU9oQzhsNFk](https://drive.google.com/open?id=0B2tnHz81APcBaDcyWU9oQzhsNFk)
