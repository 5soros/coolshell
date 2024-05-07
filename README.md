# 运行该程序

很多人都是用windows系统，写下怎么在windows系统运行该程序

1.安装WSL（默认ubuntu系统）

2.打开一个资源浏览器（比如双击某个盘符），左下角，把下载到的coolshell文件复制到root或者其他文件夹

3.打开WSL（BASH界面），进入coolshell文件所在文件夹

4.将coolshell.elf文件赋予权限（输入：chmod +x coolshell 回车）

5.查看WSL的内网IP（输入：ip addr show eth0 | grep -oP '(?<=inet\s)\d+(\.\d+){3}' 回车）

6.绑定IP，端口到该程序（输入：./coolshell -b 上面查到的ip:8080）

7.执行完上一步，coolshell程序已经运行

8.宿主机浏览器访问上面查到的ip:8080就可以看文章了。

9.如果关机或者退出可能需要重新绑定IP



<https://coolshell.org>

740 篇文章列表： https://coolshell.org/articles/

## In Memoriam of haoel@

https://giantchen.wordpress.com/2023/05/18/haoel/

Dennis M. Ritchie 逝世十多年后，他的个人主页仍然能原址访问 <https://www.bell-labs.com/usr/dmr/www/>。

W. Richard Stevens 已经逝世二十余年，他的个人主页还保持着 1999 年的样子 <http://www.kohala.com/start/>。

希望借助 GitHub，让**陈皓**的文字能长久流传下去。

* Convert (most) links to local

```shell
$ ./links_to_local.sh `find . -type f -name '*.html'`
```

## Other sites

* <https://github.com/ghostincoolshell/haoel-articles> 包括 tweets 和微博
* <https://github.com/soulteary/forever-coolshell> 单机下载版

