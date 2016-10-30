TUTORIAL QGIS
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/1.png">
</p>

Latar Belakang

Dalam mempelajari GIS mahasiswa harus mempunyai kemampuan membuat dan menanpilkan peta dengan elemen peta,skala,panah utara, dll. Dalam membuat dan menanmpilkan semua itu disediakan software GIS yaitu QGIS. QGIS berfungsi untuk menampilkan raster dan vector data.

Isi

QGIS berfungsi untuk mencakup semua fitur yang profesional spasial dan mampu mengimpor data dari berbagai sumber, digitalisasi, mengedit,analisis data, geoprocessing,konektivitas database dan pengelohan raser. Pada QGIS juga terdapat crud,dan retrieve data ini berfungsi untuk melihata isi data geospasial berupa data vector yaitu shape file ESRI dengan extensial.shp).

File dari shape File adalah

Shp : kordinat/titik
Dbf : Tabel / database
Shx : index data
Tutorial / langkah langkah praktikum QGIS :

Dwonload phyton terlebih dahulu
Download get pip
Install aplikasi GQIS
Buka browser -> Natural Eart -> lalu simpan ke file Misalnya directory ("E:\Coasline\coastline.shp")
Buka CMD:
ketikkan ->Python ->

import shapefile

sf = shapefile.Reader("E:\Coasline\coastline.shp")

shapes = sf.shapes()

print len(shapes)
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/2.png">
</p>

Setelah itu maka akan muncul isi recornya
Lalu masukkan dan panggil folder main.py pada directory yang sama lalu panggil kembali
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/3.png">
</p>
<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/4.png">
</p>

Buka Aplikasi QGIS yang telah diinstal->Browser panel -> Pilih directory folder nya-> buka database->database manager->dan akan menampilkan isi recordnya.

Penutup

Kesimpulan
Aplikasi QGIS ini berfungsi untuk menampilkan raster dan vector data,lalu python merupakan software pembantu untu menyimpan record.

Saran
Sebaiknya dalam melakukan praktikum sebaiknya mengambil data peta dari Natural eart karena semua data mengenai peta ada disana.

NAMA :KHAERATUNNISA
NPM : 1144044

KELAS : D4TI3A

KAMPUS : POLITEKNIK POS INDONESIA

Referensi : http://www.naturalearthdata.com/downloads/

Scan Plagiarisme :

https://drive.google.com/open?id=0B2tnHz81APcBTWZrRmZKc28wUTQ

https://drive.google.com/open?id=0B2tnHz81APcBQWxvbnNuc2VlbWM