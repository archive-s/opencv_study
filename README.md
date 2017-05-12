# opencv_study

1. 直接编译，添加编译选项 `pkg-config --cflags --libs opencv`

2. 使用Makefile 编译opencv程序，包含的头文件路径名，库文件名，链接文件
   会因为安装环境的不同而有所不同，可使用下面命令进行查询：
		pkg-config --cflags --libs opencv
