# Warning: Not secure!
# Upozorenje: Nije sigurno!

[dispet: IP adresa](ip-adresa)
Za odrediti lokaciju sa koje stizu zahtjevi moze se koristiti https://geolocation.com
```bash
[dado@dispet html]$ sudo python -m http.server 80
Serving HTTP on 0.0.0.0 port 80 (http://0.0.0.0:80/) ...
n 80.66.76.121 - - [07/Sep/2024 21:06:30] code 400, message Bad HTTP/0.9 request type ('\\x03\\x00\\x00/*à\\x00\\x00\\x00\\x00\\x00Cookie:')
80.66.76.121 - - [07/Sep/2024 21:06:30] "\x03\x00\x00/*à\x00\x00\x00\x00\x00Cookie: mstshash=Administr" 400 -
[149.50.103.48 - - [07/Sep/2024 21:18:44] "GET / HTTP/1.1" 200 -
87.236.176.17 - - [07/Sep/2024 21:19:55] "GET / HTTP/1.1" 200 -
45.148.10.242 - - [07/Sep/2024 21:21:43] code 404, message File not found
45.148.10.242 - - [07/Sep/2024 21:21:43] "GET /cgi-bin/luci/;stok=/locale HTTP/1.1" 404 -
[178.211.139.188 - - [07/Sep/2024 21:24:21] "GET / HTTP/1.1" 200 -
183.239.186.30 - - [07/Sep/2024 21:25:46] code 404, message File not found
183.239.186.30 - - [07/Sep/2024 21:25:46] "GET /manager/html HTTP/1.1" 404 -
k205.210.31.40 - - [07/Sep/2024 21:32:19] "GET / HTTP/1.0" 200 -
83.97.73.245 - - [07/Sep/2024 21:37:27] code 404, message File not found
83.97.73.245 - - [07/Sep/2024 21:37:27] "GET /vendor/phpunit/phpunit/src/Util/PHP/eval-stdin.php HTTP/1.1" 404 -
83.97.73.245 - - [07/Sep/2024 21:40:12] code 404, message File not found
83.97.73.245 - - [07/Sep/2024 21:40:12] "GET /solr/admin/info/system?wt=json HTTP/1.1" 404 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET / HTTP/1.1" 200 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/pygments.css?v=d1102ebc HTTP/1.1" 200 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/basic.css?v=c058f7c8 HTTP/1.1" 200 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/alabaster.css?v=27fed22d HTTP/1.1" 200 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/documentation_options.js?v=5128caf1 HTTP/1.1" 200 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/doctools.js?v=9a2dae69 HTTP/1.1" 304 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/sphinx_highlight.js?v=dc90522c HTTP/1.1" 304 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/translations.js?v=81a5e6b8 HTTP/1.1" 304 -
84.138.105.208 - - [07/Sep/2024 21:46:24] "GET /_static/custom.css HTTP/1.1" 304 -
45.148.10.242 - - [07/Sep/2024 21:50:10] code 404, message File not found
45.148.10.242 - - [07/Sep/2024 21:50:10] "GET /cgi-bin/luci/;stok=/locale HTTP/1.1" 404 -
95.214.55.138 - - [07/Sep/2024 21:51:50] "GET / HTTP/1.1" 200 -
5.42.104.64 - - [07/Sep/2024 22:03:55] "GET / HTTP/1.0" 200 -
185.224.128.83 - - [07/Sep/2024 22:08:55] code 404, message File not found
185.224.128.83 - - [07/Sep/2024 22:08:55] "GET /cgi-bin/luci/;stok=/locale HTTP/1.1" 404 -
83.97.73.245 - - [07/Sep/2024 22:09:40] "GET /?XDEBUG_SESSION_START=phpstorm HTTP/1.1" 200 -
93.174.93.12 - - [07/Sep/2024 22:17:20] "GET / HTTP/1.0" 200
83.97.73.245 - - [07/Sep/2024 22:09:40] "GET /?XDEBUG_SESSION_START=phpstorm HTTP/1.1" 200 -
93.174.93.12 - - [07/Sep/2024 22:17:20] "GET / HTTP/1.0" 200 -
141.98.11.48 - - [07/Sep/2024 22:25:40] code 501, message Unsupported method ('POST')
141.98.11.48 - - [07/Sep/2024 22:25:40] "POST /boaform/admin/formLogin HTTP/1.1" 501 -
47.252.21.165 - - [07/Sep/2024 22:29:25] code 404, message File not found
47.252.21.165 - - [07/Sep/2024 22:29:25] "GET http://www.google.com/ HTTP/1.0" 404 -
185.224.128.59 - - [07/Sep/2024 22:31:49] code 404, message File not found
185.224.128.59 - - [07/Sep/2024 22:31:49] "GET /cgi-bin/luci/;stok=/locale HTTP/1.1" 404
149.50.103.48 - - [07/Sep/2024 22:42:25] "GET / HTTP/1.1" 200 -
185.191.126.213 - - [07/Sep/2024 22:42:53] "GET / HTTP/1.1" 200 -
