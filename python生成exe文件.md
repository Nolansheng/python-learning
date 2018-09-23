# .py文件生成可执行exe文件

标签（空格分隔）： python类

---
#1.pip是一个现代的，通用的 Python 包管理工具。提供了对 Python 包的查找、下载、安装、卸载的功能。

#2.pycharm中可以很方便的安装包，左上角File-->settings-->Projetc:-->Project Interpreter 需要科学上网才能下载

#3.在windows上用命令行的方式用pip，下载python的时候会有pip一起下载，然后把pip文件地址加到系统变量

#4.把一个.py文件放到一个文件夹中，点中文件夹按住shift然后右击，会有一个PowerShell窗口选项，然后在命令行中输入命令 pyinstaller -Fw xxx.py

#5.pyinstaller 的参数 
参数名|描述|说明
-|-|
-D|生成one-folder的程序（默认）|生产结果是一个目录，各种第三方依赖，资源，exe同时存储在该目录
-F|生成one-file的程序|生成结果是exe文件，所有第三方依赖，资源，代码均被打包在exe内
-specpaht|指定.spec文件的存储目录|默认当前目录
-w|不显示命令行窗口|编写GUI程序时使用该参数有用
