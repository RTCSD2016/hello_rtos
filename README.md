# hello_rtos
a simple xenomai application program

# 步骤:


- 在虚拟机HOME目录下建立一个工作目录如rtworks:

```
mkdir rtworks
cd rtworks
```
- 如果虚拟机尚未安装git软件包，安装该软件包：

```
sudo apt-get install git
```
- 在rtworks目录下通过git下载本示例程序：

```
git clone https://github.com/RTCSD2016/hello_rtos.git
```
下载成功后进入hello_rtos子目录，可以查看和编辑C程序：

```
gedit rtdemo.c
```

生成可执行文件：

```
make
```
运行可执行文件

```
./rtdemo
```
观看屏幕输出信息，运行Ctrl+C键退出程序。
