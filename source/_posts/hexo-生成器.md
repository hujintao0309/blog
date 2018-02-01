---
title: hexo-生成器
date: 2018-01-31 20:18:39
categories: "Hexo官方文档"
tags:
     - hexo
---
使用 Hexo 生成静态文件快速而且简单。

``` bash
$ hexo generate
```

### 监视文件变动

Hexo 能够监视文件变动并立即重新生成静态文件，在生成时会比对文件的 SHA1 checksum，只有变动的文件才会写入。

``` bash
$ hexo generate --watch
```

### 完成后部署

您可执行下列的其中一个命令，让 Hexo 在生成完毕后自动部署网站，两个命令的作用是相同的。

``` bash
$ hexo generate --deploy
$ hexo deploy --generate
```
简写
上面两个命令可以简写为
$ hexo g -d
$ hexo d -g

