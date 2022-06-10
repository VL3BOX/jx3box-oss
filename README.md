# OSS  
不包含用户上传资源，此库为图片镜像。
头像：部署南京
## 存档
@部署：github master  
@备份：//oss/image|img (push自动推送)

## 访问
@源站：https://img.jx3box.com/  
@图片加速：https://console.cnyixun.com/

## Nginx
```
#跨域设置
    add_header Access-Control-Allow-Origin *;
    add_header Access-Control-Allow-Methods 'GET, POST, OPTIONS';
    add_header Access-Control-Allow-Headers 'DNT,X-Mx-ReqToken,Keep-Alive,User-Agent,X-Requested-With,If-Modified-Since,Cache-Control,Content-Type,Authorization';
    
    if ($request_method = 'OPTIONS') {
      return 204;
    }


    location /avatar/ {  
        alias /www/wwwroot/jx3box/img/img-avatar/;
    }
    location /emotion/ {  
        alias /www/wwwroot/jx3box/jx3-emotion/;
    }
    location /map/ {  
        alias /www/wwwroot/jx3box/jx3-map/;
    }
    location /pvx/ {  
        alias /www/wwwroot/jx3box/jx3-pvx/;
    }
    location /adventure/ {  
        alias /www/wwwroot/jx3box/img/img-adventure/;
    }
    location /pet/ {  
        alias /www/wwwroot/jx3box/img/img-pet/;
    }    
    location /homeland/ {  
        alias /www/wwwroot/jx3box/img/img-homeland/;
    }
    location /topic/ {  
        alias /www/wwwroot/jx3box/img/img-topic/;
    }
    
```
