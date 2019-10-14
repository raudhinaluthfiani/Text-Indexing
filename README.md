# Text-Indexing
1.	Persiapan konfigurasi Swish-e untuk indexing  
-	install swish-e di computer  
$ sudo apt-get install –y swish-e  
$ sudo apt-get install swish-e  

<img width="530" alt="1" src="https://user-images.githubusercontent.com/49057899/66782126-3ed92480-eeff-11e9-9ef4-8be7fab49512.png">
<img width="500" alt="2" src="https://user-images.githubusercontent.com/49057899/66782161-4ef10400-eeff-11e9-8e79-09a39dc5761f.png">

2.	Konfigurasi Swish-e  
-	membuat file konfigurasi swish-e untuk indexing  
$ touch crawling.conf  
<img width="511" alt="3" src="https://user-images.githubusercontent.com/49057899/66782200-5ca68980-eeff-11e9-80f3-b686d4778dfb.png">

-	menulis file konfigurasi yang telah dibuat sebelumnya  
$ pico crawling.conf  
<img width="528" alt="4" src="https://user-images.githubusercontent.com/49057899/66782222-68924b80-eeff-11e9-90a1-6d364be1a928.png">


-	menjalankan swish-e  
$ swish-e –c crawling.conf  
<img width="512" alt="5" src="https://user-images.githubusercontent.com/49057899/66782279-88297400-eeff-11e9-9129-fc9391c96a67.png">






-	search word  
$ swish-e –f hasil_index.swish-e –w abstrak  
<img width="492" alt="6" src="https://user-images.githubusercontent.com/49057899/66782260-7a73ee80-eeff-11e9-8740-8e5bb2f76173.PNG">


