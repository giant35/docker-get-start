# Docker 是什么？能干嘛？

## 是什么
Docker 是一种容器技术。能把一个应用及其关联都打包好，方便在其他机器上再次运行。这样不会环境互相干扰。可以把Docker想象成只能运行一个进程的虚拟机
## 能干嘛

## 核心概念
* image : 镜像, 是 container 的基础。image 是静态的，container 是动态的
* container：容器，以image 为基础是进程执行的环境


## 应用场景
* 比如一台服务器上a 应用依赖 python2.x ，b 应用依赖 python3.x 。使用Docker 打包后，各自没有任何影响
