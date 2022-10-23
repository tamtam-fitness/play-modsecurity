$ sudo nginx -s reload
$ curl -D - http://localhost:8085 HTTP/1.1 200 OK
Server: nginx/1.11.10
Date: Wed, 3 May 2017 08:55:29 GMT Content-Type: text/plain
Content-Length: 27
Connection: keep-alive
Thank you for requesting /

----

# 注意
- DDosはNginxPlusでサポート
