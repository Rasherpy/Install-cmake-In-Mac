# Install-cmake-In-Mac
Mac 上安装cmake
## 什么是cmake
[百度百科](http://baike.baidu.com/link?url=osQ0qBOk4pwgGkjQDqzC__DMMyU2K2aIZrbyD3scFKGmDAuWAiJ2J2jbEjVytbE8uIMcrMSRNaSpWizvEh8_6a)
## 下载cmake
[下载网址](https://cmake.org/download/)
## 安装(以3.8.0为例)
* 1.解压：tar xvf cmake-3.8.0.tar
* 2.进入解压目录：cd cmake-3.8.0

进行如下操作:(选择适合自己的操作步骤)如果还没有安装CMake，源码树中提供了一个 bootstrap 脚本：
* 1. ./bootstrap
* 2. make
* 3. make install
## cmake 运行
运行cmake with GUI，如果系统中有curses库，cmake将生成一个可执行文件ccmake，它是一个基于文本程序的终端，有点类似windows GUI。在源码目录中运行ccmake .，生成的二进制文件存放在源码目录下，当然也可以在其他目录下运行cmake，只是要指定你想编译的源码的路径
## cmake的使用
当我们在源码目录下运行ccmake.时，终端将显示如下：
* 1 键入c时，ccmake将编译
* 2 键入方向键时，可以选择cache entry
* 3 键入enter时，可以编辑cache entry
* 4 键入g时，将生成Makefile，然后退出
* 5 键入h时，将弹出帮助文档
* 6 键入q时，将退出ccmake
* 7 键入t时，可以打开或关闭advanced cache entry
