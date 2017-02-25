# Nginx PHP Phalcon

Phalcon（[官方网站](https://phalconphp.com)）是一个C编写的轻量级PHP框架，实现了MVC、ORM等核心功能。详细内容请参阅[官方文档](https://docs.phalconphp.com/en/latest/index.html)。Github在[这里](https://github.com/phalcon/cphalcon)可以找到。

本Docker镜像基于richarvey/nginx-php-fpm（[镜像地址](https://hub.docker.com/r/richarvey/nginx-php-fpm/)）的PHP5版本内容，Github在[这里](https://github.com/ngineered/nginx-php-fpm)可以找到。

Docker镜像中关于Nginx、PHP等各种配置方法，请参考[richarvey/nginx-php-fpm](https://hub.docker.com/r/richarvey/nginx-php-fpm/)在[Github](https://github.com/ngineered/nginx-php-fpm)上的说明。

## 版本信息
| Tag | Nginx | PHP | Phalcon | Alpine |
|-----|-------|-----|---------|--------|
| php5 | 1.11.5 | 5.6.29 | 3.0.2 | 3.4 |
| php5.6 | 1.11.5 | 5.6.29 | 3.0.2 | 3.4 |
| release-php5-20170225 | 1.11.5 | 5.6.29 | 3.0.2 | 3.4 |

## 使用方法

在本镜像中，站点路径被定义在```/data/webroot/```，将站点文件加入到该文件夹下即可正常访问。增加了一个默认首页，输出```phpinfo();```的内容。


