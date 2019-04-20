# 长延时点击

## 说明：

这个代码的功能是,

开机后，等按键按下。

按一次按键后，点击头从j1,j2,j3...j10,jok每个头点击一次一直循环点击。

再按一次后，所有头都会停止点击，直到再一次按下按键一次.


## 注意

这个代码使用了一个第三方的多线程SCoop库，这个库使用简单，使用这个库的主要原因是为了把按键实时检测和点击头延时停顿分开，以做到点击头点击的同时不影响程序对按键的检测（因为没有使用arduino的外部中断来处理按键）

使用的时候要把lib目录下的文件夹复制到arduio的库目录下。这个目录一般是在arduino的libraries目录下，这里放了所有的第三方arduino库.

## 点击头购买地址:

https://fengmm521.taobao.com

## SCoop多线程库地址：

https://github.com/fabriceo/SCoop

在这里查看SCoop库的使用方法，作者有放一个pdf教程在项目目录下