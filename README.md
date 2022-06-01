# Microservice Example - Library



## Introduction

This is a small example for a Microservice architecture. It consists of three services (book service, customer service, lend service) and an API gateway implemented as Node servers using Express.

The API Gateway also serves as the host for a minimalistic web frontend.

All services handle their use cases independently and don't know about the existence of other services.

The master branch of this repository contains only the services and frontend while the `camunda` branch adds an additional orchestration layer implemented by the camunda process engine.

Implemented use cases:

* Create a customer
* Create a book
* Borrow a book
* Return a book


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
