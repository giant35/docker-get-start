# Docker 运行 Squid

centos7:

1. docker run -it centos /bin/bash
2. yum install -y squid
3. vi /etc/squid/squid.conf  
   增加
4. docker commit contianerId squid  
   containerId 通过 docker ps -l 获得
   
4. docker run -d -p 3128:3128 squid /usr/sbin/squid -N 
    启动 docker 运行squid
5. 