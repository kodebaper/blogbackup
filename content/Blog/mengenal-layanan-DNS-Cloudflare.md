---
title: "Mengenal Layanan DNS Cloudflare"
date: 2020-08-21T00:46:17+07:00
draft: false
tags:  ["Static site"]
Categories: ["Cloud"]
description: "Mengenal Layanan DNS Cloudflare"
---

<center>
<img src="/images/cloudflarekbaper.png">
</center>

# Mengenal Layanan DNS Cloudflare

Mengenal apa itu Cloudflare dan untuk apa sebenarnya Cloudflare itu sendiiri.
Saya sendiri saat ini menggunakan layanan dari Cloudflare baru sebatas penggunaan dengan memanfaatkan layanan gratis untuk setting DNS blog saya ini, adapun di lain kesempatan saya akan membahas cara setting DNS di Cloudflare dari Github page untuk blog static site Hugo.

Berawal dari blog ini mendeploy ke GitHub page lalu memesan Domain **dot com** dari Domainesia, waktu itu setup custom domain di Cloudflare berlangsung. Di tengah perjalanan terkendala pada Proses pemanggilan domain dari semula **mazzempong.github.io**menjadi **kodebaper.com** karena hasilnya tidak sampai di custom domain di GitHub saja, namun ada setup lanjutan di Cloudflare. Dari sinilah saya mulai belajar dan mengenal apa itu Cloudflare.

*Jadi, apa itu Cloudflare ?*

Cloudflare adalah sebuah jasa jaringan penyalur konten, pencegahan keamanan Internet dan 'Peladen' domain terdistribusi. Produk Cloudflare adalah perantara pengunjung web, dan penyedia hosting pengguna Cloudflare [Penjelasan versi Wikipedia].
Penjelasan ini saya dapat dari wikipedia, tapi bagi saya sendiri memahami Cloudflare merupakan sebuah CDN (Content Delivery Network) dimana Cloudflare sendiri berada di antara nama domain dan web hosting yang memiliki kemampuan untuk mem-filter trafik dan mempercapat akses website. Adapun untuk keamanan tambahan yang di sedikan oleh Cloudflare salah satunya yaitu keamanan dari serangan DDoS dan lain sebagainya. 

Saya baru mengenal Clodflare kurang lebih sekitar 6 bulan lalu dan mulai familiar dengan beberapa fitur yang ada di dalamnya, saya memanfaatkan Cloudflare sebagai bagian dari rangkaian Setup saat saya melakukan custom domain di GitHub page dengan domain **dot com**. Menarik bukan menggunakan Hugo ? semakin di selami kita jadi tau banyak ilmu salah satu contohnya jadi mengenal apa itu layanan yang di sediakan oleh Cloudflare, kemudian untuk keuntungan lain diantaranya karena kita tidak hanya sekedar ngeblog biasa namun jadi ada tambahan ilmu lain yang kita pelajari dengan ngeblog melalui satic site generator menggunakan Hugo.

semoga artikel ini bermanfaat, selamat belajar !