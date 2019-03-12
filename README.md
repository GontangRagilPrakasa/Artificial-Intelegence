# Artificial-Intelegence
#1. Instalasi Package
Penambahan package ke dalam Python dapat dilakukan melalui perintah  pip install <nama package>. Apabila pip belum terinstal, lakukan langkah berikut:
•	Unduh get-pip.py melalui tautan berikut: https://bootstrap.pypa.io/get-pip.py. 
•	Jalankan perintah berikut untuk instalasi pip:
python get-pip.py
Apabila pip telah terinstal, package Python dapat diinstal menggunakan perintah sebagai berikut:
pip install <nama_package>
Package yang telah didaftarkan pada PyPI (repository resmi untuk package python) dapat diinstal secara langsung dengan memanggil nama packagenya. Contohnya jika ingin menginstal package numpy untuk komputasi numerik di Python, maka perintah berikut ini dapat dijalankan:
pip install numpy
#2.	Penggunaan Module di dalam Package Python
Module merupakan file berekstensi .py yang memuat kode Python dan berisi beberapa fungsi maupun Class. Module dapat disatukan dalam satu package supaya kumpulan module tersebut menjadi terstruktur dan dapat didistribusikan secara mudah. Pemanggilan module dapat dilakukan menggunakan “dot/titik”, contohnya apabila ingin menggunakan module core dalam numpy, maka dapat dilakukan dengan numpy.core
 Konten dari module dapat diakses dengan melakukan import. Ada tiga cara untuk melakukan import module: 
•	import <nama_module> 
contoh: 
import numpy.core
subtract(3,2)
•	from <nama_ module> import <nama_obyek>
contoh: from numpy.core import substract
subtract(3,2) 
•	from <nama_ module> import <nama_obyek> as <inisial>
contoh:  
from numpy.core import subtract as sub
sub(3, 2)
