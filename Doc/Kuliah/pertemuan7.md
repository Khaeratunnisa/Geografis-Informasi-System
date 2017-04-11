

**Tutorial Menjalankan Map Server dan Map Proxy**


**Pembukaan**
Latar Belakang
Google map merupakan aplikasi dari google berbasis _geographic information system_ dimana fungsinya untuk mencari lokasi dimuka bumi ini. Pada pembahasan kali ini akan dibahas mengenai map server dan map proxy.

**Isi**

Cara untuk menjalankan map proxy dan map server adalah sebagi berikut :

1. Meload data geospasial, mendownload data geospasial di situs   [http://www.halaman.download/](http://www.halaman.download/) kemudian pilih &quot;Producer&quot; dan klik &quot;Indonesia Mapproxy&quot;.
2. Setelah itu ekstak file, lalu path-nya akan digunakan untuk edit file yang di direktoru yang telah diektrak.
3. Terdapat file infomap,lalu mapproxy dan akan terdapat tiga file kemudian buka file agm.yaml.
4. Lalu pada file agm.yaml tersebut edit beberapa baris sesuai dengan direktori penyimpanan file tersebut:

- Baris :

binary: /usr/libexec/mapserver

**ubah menjadi**

binary: /usr/lib/cgi-bin/mapserv

- Baris

map: var/mapdata/mapfile/indo.map

**ubah menjadi**

map: /home/hera/Downloads/indomap/mapfile/indo.map

- Kemudian direktori baru dengan nama tmp pada direktori indomap ubah baris

working\_dir: /var/mapdata/tmp

**menjadi**

/home/hera/Downloads/indomap/tmp

**Kemudian Save**

1. Kemudian pada direktori mapproxy(di terminal/cmd), gunakan perintah :

vi mapproxy.ini

edit baris

chdir = /var/mymapproxy/

menjadi

chdir = /home/hera/Downloads/indomap/mapproxy

Kemudian Save

1. edit file config.py pada direktori mapproxy

ubah

application = make\_wsgi\_app(r&#39;/var/mymapproxy/agm.yaml&#39;)

**menjadi**

application = make\_wsgi\_app(r&#39;/home/hera/Downloads/indomap/mapproxy/agm.yaml&#39;)

1. Untuk menjalankan programnya gunakan perintah uwsgi mapproxy.ini
2. Untuk mengecek apakah mapproxy sudah terinsall atau belum, buka browser kemudian ketik localhost:8080
3. Klik demo atau ketik localhost:8080/demo
4. Pada bagian WMTS klik di bawah Image Format yaitu png
5. Tunggu beberapa saat karna datanya sedang di load.
6. Map Peta akan muncul

**Penutup :**

**Kesimpulan :**

Setelah menjalan tutorial diatas,dapat diketahui cara menjalankan map server dan juga map proxy pada Ubuntu.

**Saran :**

Sebaiknya sebelum menjalankan map server map proxy sebaiknya mengatahui terlebih dahulu cara menjalankan Ubuntu agar tidak kesulitan dalam menjalankan praktikum.

Link Github : [https://github.com/Khaeratunnisa/Geografis-Informasi-System](https://github.com/Khaeratunnisa/Geografis-Informasi-System)

NAMA        :KHAERATUNNISA
NPM                : 1144044

KELAS        : D4TI3A

KAMPUS        : POLITEKNIK POS INDONESIA

Link Mata Kuliah :   [Sistem Informasi Geografis](http://www.awangga.net/)

Referensi                 : http://www.wikipedial.com /

Scan Plagiarisme :

[https://drive.google.com/open?id=0B2tnHz81APcBRkkyNFZHQVMyUkE](https://drive.google.com/open?id=0B2tnHz81APcBRkkyNFZHQVMyUkE)

[https://drive.google.com/open?id=0B2tnHz81APcBNFU5TzBVRG5zT0U](https://drive.google.com/open?id=0B2tnHz81APcBNFU5TzBVRG5zT0U)

