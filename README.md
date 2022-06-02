# Microservice Implementation - Book Library



## Introduction

Aplikasi ini merupakan aplikasi dengan Microservice arsitektur dengan tiga servis di dalamnya, yaitu:
1. book service
2. costumer service
3. lends service

Aplikasi ini mengginakan API gateway yang diimplementasikan sebagai Node servers menggunakan Express.

Tentunya, setiap servis dapat bekerja secara independen dan tidak mengetahui tentang keberadaan servis lain.


Use case pada aplikasi ini:
* Menambah costumer
* menambah buku
* meminjam buku
* mengembalikan buku


## Step by Step to Run Book Library Microservices

1. Download dan instal Docker melalui pranala berikut ini https://hub.docker.com/search/?type=edition&offering=community jika belum memiliki Docker

2. Buka Docker kemudian klik button Create untuk membuat New Dev Environment, kemudian clone branch github dengan link berikut: https://github.com/ElisaCT/book-library-microservices.git

3. Kemudian klik tombol continue dan tunggu beberapa saat hingga Docker selesai melakukan preparing.


4. Buka terminal pada lokasi project dan run:
'''bash 
> docker-compose up


5. Setelah docker selesai membuat semua service, copy link localhost pada terminal, sebagai contoh kunjungi: 
'''bash
localhost:3003

jika berhasil, hompage aplikasi book library akan ditampilkan
