# OSS  
不包含用户上传资源，此库为图片&json等数据镜像。

## 环境
@部署：阿里云OSS  
@域名：https://cdn.jx3box.com/image|data  
@本地HOST：绑定根目录为cdn.jx3box.com

## 说明
推送后自动更新至oss

## 注意
本地环境需配置允许跨域
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