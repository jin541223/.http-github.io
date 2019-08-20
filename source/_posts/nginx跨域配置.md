---
title: nginx跨域配置
date: 2018-08-04 23:01:16
tags: nginx 跨域配置
---

更改/etc/nginx/nginx.conf
``` bash
add_header 'Access-Control-Allow-Origin' '*';
add_header 'Access-Control-Allow-Credentials' 'true';
add_header 'Access-Control-Allow-Methods' 'POST, GET, OPTIONS, PUT, PATCH, DELETE';
add_header 'Access-Control-Allow-Headers' 'Authorization, Content-Type, X-Auth-Token, Accept, Origin';
```