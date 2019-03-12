# Artificial-Intelegence
# 1. Instalasi Package <br>
Penambahan package ke dalam Python dapat dilakukan melalui perintah  pip install <nama package>. Apabila pip belum terinstal, lakukan langkah berikut:
•	Unduh get-pip.py melalui tautan berikut: https://bootstrap.pypa.io/get-pip.py. 
•	Jalankan perintah berikut untuk instalasi pip:
python get-pip.py
Apabila pip telah terinstal, package Python dapat diinstal menggunakan perintah sebagai berikut:
pip install <nama_package>
Package yang telah didaftarkan pada PyPI (repository resmi untuk package python) dapat diinstal secara langsung dengan memanggil nama packagenya. Contohnya jika ingin menginstal package numpy untuk komputasi numerik di Python, maka perintah berikut ini dapat dijalankan:
pip install numpy <br>
# 2.	Penggunaan Module di dalam Package Python <br>
Module merupakan file berekstensi .py yang memuat kode Python dan berisi beberapa fungsi maupun Class. Module dapat disatukan dalam satu package supaya kumpulan module tersebut menjadi terstruktur dan dapat didistribusikan secara mudah. Pemanggilan module dapat dilakukan menggunakan “dot/titik”, contohnya apabila ingin menggunakan module core dalam numpy, maka dapat dilakukan dengan numpy.core
 Konten dari module dapat diakses dengan melakukan import. Ada tiga cara untuk melakukan import module: <br>
•	import <nama_module> <br> 
contoh: <br>
import numpy.core <br>
subtract(3,2) <br>
•	from <nama_ module> import <nama_obyek> <br>
contoh: from numpy.core import substract <br>
subtract(3,2) <br>
•	from <nama_ module> import <nama_obyek> as <inisial> <br>
contoh:  <br>
from numpy.core import subtract as sub <br>
sub(3, 2) <br>
