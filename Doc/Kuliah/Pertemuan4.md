**Retrive Data Geospasial**
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict1.PNG">
</p>
**Pembukaan**

Meretrive Data Vektor,dimana data shape.shp,operasi retrieve data menggunakan library python yang bernama py.shp.

Shapefile : Standar file vector geospasial dikeluarkan oleh ESRI.

**Isi**

Shapefile terbagi atas dua,yaitu

1. Shp merupakan data geometri.
2. Dbf merupakan table basis data.

Geomtri :

Data kordinat yang membentuk bangundatar/ruang diantaranya

1. Point/titik (shape type [1] )
2. Line/garis (shape type[2] )
3. Poligon (shape type [3] )

Operasi pengambilan Data

Library pysh class shapefile

1. Buka/ baca

Sf = shapefile – Reader (&#39;namafile.shp)

                Variable       class      method      inputfile.shp

              Penampung

1. Shp

Method : shapes() ,shape(n)

Bbox,parts,point,shape type

2. Dbf

Method : Fields (nama field) ,record (n) baris ke n, records() baris ke semua.

3. Python

Import shapefile

Sf = shapefile.Reader (&#39;folder&#39;)

Die() =&gt; Untuk Melihat

Untuk Menampilkan Parameter :

1. BBox(Boading box merupakan  batas view peta
2. Parts ( Bagian dari record lainnya/ pecahan ).
3. Points ( Kordinat Pembentukan peta ).
4. Shape type ( Jenis geometri dari points ).

Menampilkan jumlah record melalui terminal
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict2.PNG">
</p>

Menampilkan jumlah recorc dehan main.py
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict3.PNG">
</p>
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict4.png">
</p>

TUGAS PRAKTEK :

1. Membuat class geospasial editor

<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict5.PNG">
</p>

<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict6.PNG">
</p>
2. Membuat Select,where Negara

<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/pict7.PNG">
</p>

**Penutup**

1. **Kesimpulan**

Pada tugas ini, kita telah mempeljari cara membuat Class dan select method pada retrieve data.

2. **Saran**

Sebaiknya dalam melakukan praktek ini harus mengetahui apa itu retrieve data,select,method pada retrieve data.

NAMA        :KHAERATUNNISA
NPM                : 1144044

KELAS        : D4TI3A

KAMPUS        : POLITEKNIK POS INDONESIA

Referensi : [http://www.naturalearthdata.com/downloads/](http://www.naturalearthdata.com/downloads/)

Scan Plagiarisme :

[https://drive.google.com/open?id=0B2tnHz81APcBOUs2dHQzcjRJQ2s](https://drive.google.com/open?id=0B2tnHz81APcBOUs2dHQzcjRJQ2s)

[https://drive.google.com/open?id=0B2tnHz81APcBSlRhREVEYnFMSnM](https://drive.google.com/open?id=0B2tnHz81APcBSlRhREVEYnFMSnM)
