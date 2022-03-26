# OneNav

使用PHP + SQLite 3开发的书签管理器（导航），界面简洁，安装简单，使用方便。

![](https://i.bmp.ovh/imgs/2020/12/40f222b7da7a89c9.png)

![](https://i.bmp.ovh/imgs/2021/04/5c46f84f158d8d3a.png)

![](https://img.rss.ink/imgs/2022/03/cba9f1946776a8f0.png)

![](https://img.rss.ink/imgs/2022/03/4b1d6c95484e69bc.png)

![](https://i.bmp.ovh/imgs/2020/12/abba0af566f3c16a.png)

## 功能特色

* 支持后台管理
* 支持私有链接
* 支持Chrome/Firefox/Edge书签批量导入
* 支持多种主题风格
* 支持链接信息自动识别
* 支持API
* 支持Docker部署
* 支持uTools插件

## 安装

**常规安装：**

1. 需安装PHP环境，并确保支持SQLite3
2. 下载源码解压到站点根目录
3. 访问首页自动完成安装
4. 访问后台：`http://IP/index.php?c=login`

**Docker部署：**

```bash
docker run -itd --name="onenav" -p 80:80 \
    -e USER='xiaoz' -e PASSWORD='xiaoz.me' \
    -v /data/onenav:/data/wwwroot/default/data \
    helloz/onenav
```

* `USER`：设置用户名，上述设置为`xiaoz`
* `PASSWORD`：设置密码，上述设置为`xiaoz.me`
* `/data/onenav`：本机挂载目录，用于持久存储Onenav数据

> 更多说明，请参考帮助文档：https://dwz.ovh/onenav

## Demo

以下是OneNav部分用户演示站，排名不分先后。

* OneNav：[https://nav.rss.ink/](https://nav.rss.ink/)
* 千行书签：[http://www.52qx.club/](http://www.52qx.club/)
* 纽及书签：[http://www.1006788.com/](http://www.1006788.com/)

## 联系我

* Blog:https://www.xiaoz.me/
* QQ:337003006
* QQ群：147687134
* 社区支持：[https://dwz.ovh/vd0bw](https://dwz.ovh/vd0bw)

## 鸣谢

OneNav诞生离不开以下项目，在此表示感谢（排名不分先后）。

* [WebStackPage](https://github.com/WebStackPage/WebStackPage.github.io)
* [LayUI](https://github.com/sentsin/layui)
* [Medoo](https://github.com/catfan/Medoo)
* [MDUI](https://github.com/zdhxiong/mdui)
