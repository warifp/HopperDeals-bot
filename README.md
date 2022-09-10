Installation:

- Jika blm ada PHP (<https://www.apachefriends.org/download.html>) (Khusus Windows)

Legend :

- File socks5.txt : List socks5 atau proxy.
- File log/proxy_death.json : List Proxy yang mati.
- File log/proxy_live_used.json : List Proxy yang hidup, dan bisa dipakai, biasanya per 1 hari bisa dipake register lagi.
- File log/result.json : Hasil dari register.

Usage :

- composer install
- php hopper.php
  
Error Handling

- string(142) "<!doctype html><meta charset="utf-8"><meta name=viewport content="width=device-width, initial-scale=1"><title>429</title>429 Too Many Requests" : Ganti list paling atas pada file socks5.txt, karena socks5 atau proxynya jelek.
