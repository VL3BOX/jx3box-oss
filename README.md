# OSS  
不包含用户上传资源，此库为图片镜像。

## 存档
@部署：github master  
@备份：//oss/image|img (push自动推送)

## 访问
@源站：https://cdn.jx3box.com/  
@图片加速：https://console.cnyixun.com/

## 本地开发环境
1. host:cdn.jx3box.com绑定根目录为
2. 配置跨域
```
location / {  
    add_header Access-Control-Allow-Origin *;
    add_header Access-Control-Allow-Methods 'GET, POST, OPTIONS';
    add_header Access-Control-Allow-Headers 'DNT,X-Mx-ReqToken,Keep-Alive,User-Agent,X-Requested-With,If-Modified-Since,Cache-Control,Content-Type,Authorization';

    if ($request_method = 'OPTIONS') {
        return 204;
    }
} 
``
