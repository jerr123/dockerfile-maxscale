# dockerfile-maxscale

这里用了mariadb 官方提供的源构建的镜像,由于国内网络原因，尝试过不同操作系统(e.g debian8 debian9) 最后只有ubuntu的系统 mariadb 官方源才可用。所以就有了这个它。

> 由于存在不可预知的网络问题，有特意做了份从源码build的方式来构建镜像

# usage

`docker build -t maxscale:latest .`

# blog

这里是相关的blog
