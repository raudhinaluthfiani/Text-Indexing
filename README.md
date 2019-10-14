# Text-Indexing

1. Persiapan konfigurasi Swish-e untuk indexing
- install swish-e di computer 
 $ sudo apt-get install –y swish-e
![1](https://user-images.githubusercontent.com/49057899/66781218-e9037d00-eefc-11e9-953a-b4f8790f3ff2.png) 
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


