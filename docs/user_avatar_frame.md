# JX3BOX 头像框设计说明

一套头像需使用相同风格，提供 5 种尺寸。  
可以为圆形，也可以为方形，但一套尺寸样式必须统一（要么全方，要么全圆）。

## 图片路径

文件存放在 [jx3box-oss/image/avatar](https://gitee.com/JX3BOX/jx3box-oss/tree/master/image/avatar)  
按头像框主题（英文名）每个主题一个子文件夹，内附 5 张图，格式自拟（格式无需统一，即可以小图为 gif，大图为 png）。  

以默认为例，主题名 default

### default

| 文件名格式 | 头像尺寸 | 相框尺寸 | 展示           |
| ---------- | -------- | -------- | -------------- |
| default-xs | 48       | 60       | 评论           |
| default-s  | 68       | 84       | 文章单页侧边栏 |
| default-m  | 108      | 136      | 个人中心首页   |
| default-l  | 180      | 224      | 个人主页       |
| default-xl | 240      | 300      |

----------------------

## 数据信息

文件路径为 [jx3box-oss/data/user_avatar_frame](https://gitee.com/JX3BOX/jx3box-oss/tree/master/data/user_avatar_frame.json)

#### style可取值
+ square方形
+ circle圆形