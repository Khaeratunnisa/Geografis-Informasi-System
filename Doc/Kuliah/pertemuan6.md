**SISTEM INFORMASI DAN GEOGRAFIS**

**MAP SERVER DAN MAP PROXY**

<p align="center">
	<img src="https://github.com/Khaeratunnisa/Geografis-Informasi-System/blob/master/img/Capture.PNG">
</p>


1. Latar Belakang

Seperti kita ketahui Map Server merupakan penyedia layanan web atau bisa disebut dengan web service peta. Map Proxy merupakan aplikasi penampung data sementara dari penyedia layanana web ( web service peta).

1. Pembahasan

1. Map Server

Map server merupakan sebuah lingkungan pengembang yang bersifat terbuka atau sering disebut dengan open source untuk pengembangan aplikasi aplikasi internet yang memungkinkan pengolahan data spasial. Map server ini bisa dijalankan sebagai program CGI.

1. Map Proxy

Map Proxy merupakan Sebuah aplikasi penampung data sementara dari penyedia layanan web (web service) peta yang berfungsi agar pengambilan data yang berulang-ulang lebih cepat tanpa meminta kembali ke map server.

1. Fitur Map Server

1. Mendukung format data standar industry dan database spasial.
2. Klasifikasi fiturnya on the fly.
3. Perlabelan canggih berdasarkan berbasis aturan.
4. On the fly untuk proyeksi kedua raster dan data vector.
5. Terigentrasi dan lingkungan frontend seperti ka Peta, MapBender dan Cartoweb.

1. Fitur Map Proxy

1. Server ubin (WMS-C, TMS, WMTS, KML)
2. Dilengkapi dengan API keamanan yang fleksibel.
3. Menghasilkan Cache ubin untuk kinerja yang lebih baik yang disebut seeding.
4. Menggunakan Map Proxy untuk upgrade SDI tanpa menyentuh server.

1. Cara menginstal Map server pada CentOS

- Instalasi Map Server melalui repository elgis

# rpm –Uvh [http://download.fedoraproject.org/pub/epel/6/x86\_64/epel-release-6-8.noarch.rpm](http://download.fedoraproject.org/pub/epel/6/x86_64/epel-release-6-8.noarch.rpm)

# rpm –Uvh [http://elgis.argeo.org/repos/6/elgis-release-6-6\_0.noarch.rpm](http://elgis.argeo.org/repos/6/elgis-release-6-6_0.noarch.rpm)

- Edit file epel.repo

# vi /etc/yum.repos.d/epel.repo

- Instalasi wget

# yum install wget

- Instalasi armadillo :

# wget http://elgis.argeo.org/repos/6/elgis/x86\_64/gdal-1.9.2-4.el6.x86\_64.rpm

# wget http://proj.badc.rl.ac.uk/cedaservices/raw-attachment/ticket/670/armadillo-3.800.2-1.el6.x86\_64.rpm

# yum install armadillo-3.800.2-1.el6.x86\_64.rpm

- Proses Instalasi :

# yum install gpsbabel

# yum install gdal

# yum install mapserver

# yum install glibc

# yum install libpng libpng-devel

# yum install gd gd-devel

# yum install giflib-devel

# yum install proj-epsg

1. Cara menginstal Map Proxy

# yum install python-pip python-devel

# pip install MapProxy

Kesimpulan :

Map Server ini merupakan sebuah aplikasi yang bersifat open source yang dapat membangun sebuah aplikasi pemaataan web sapsial. Sedangkan Map Proxy merupakan sebuah proxy yang open source untuk sebuah data geospasial yang berfungsi mempecepat dan dapat mengubah data dari layanan peta.

Saran :

Diharapkan sebelum melakukan instalasi agar memahami materi atau pemahaaman tentang Map Server dan juga Map Proxy agar proses instalasi tepat.

Link Github : [https://github.com/Khaeratunnisa/Geografis-Informasi-System](https://github.com/Khaeratunnisa/Geografis-Informasi-System)

NAMA        :KHAERATUNNISA
NPM        : 1144044

KELAS        : D4TI3A

KAMPUS        : POLITEKNIK POS INDONESIA

Link Mata Kuliah         :   [Sistem Informasi Geografis](http://www.awangga.net/)

Referensi                 : [https://id.wikipedia.org/wiki/MapServer](https://id.wikipedia.org/wiki/MapServer)

Scan Plagiarisme :

[https://drive.google.com/open?id=0B2tnHz81APcBU0prdFl3dUVhOUE](https://drive.google.com/open?id=0B2tnHz81APcBU0prdFl3dUVhOUE)

[https://drive.google.com/open?id=0B2tnHz81APcBYWhxUGJVTlU0SXM](https://drive.google.com/open?id=0B2tnHz81APcBYWhxUGJVTlU0SXM)