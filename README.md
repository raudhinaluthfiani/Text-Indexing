# Text-Indexing

1. Persiapan konfigurasi Swish-e untuk indexing
- install swish-e di computer 
$ sudo apt-get install –y swish-e
![Uploading 1.png…]()
$ sudo apt-get install swish-e


2. Konfigurasi Swish-e
membuat file konfigurasi swish-e untuk indexing
$ touch crawling.conf


menulis file konfigurasi yang telah dibuat sebelumnya
$ pico crawling.conf


menjalankan swish-e
$ swish-e –c crawling.conf







search word
$ swish-e –f hasil_index.swish-e –w abstrak


