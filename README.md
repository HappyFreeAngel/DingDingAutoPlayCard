# DingDingAutoPlayCard
钉钉自动上下班打卡辅助，基于windows10 ,Python3.6，adb，安卓手机实现。需要安装adb 和python运行环境。
## 效果展示：
![daka1](https://github.com/1414044032/imgs/blob/master/daka1.png)
![daka2](https://github.com/1414044032/imgs/blob/master/daka2.png)
## 1.安装 ADB：
windows版本adb下载地址:
[https://adb.clockworkmod.com/](https://adb.clockworkmod.com/)
### 安装完成后，把adb.exe所在文件夹路径加入环境变量Path中。
![1.添加adb到path](https://github.com/1414044032/imgs/blob/master/adbinstall.png)
![2.添加adb到path](https://github.com/1414044032/imgs/blob/master/adbpath.png)
![3.添加adb到path](https://github.com/1414044032/imgs/blob/master/path1.png)
### 手机需要打开开发者选项，通过USB数据线连接电脑。
### 打开CMD命令行，输入“adb devices”,能成功显示手机信息即可。
![cmdshow](https://github.com/1414044032/imgs/blob/master/adbcmd.png)

## 2.安装Python3.6
![pythonshow](https://github.com/1414044032/imgs/blob/master/python.png)

## 3.获取屏幕尺寸，设置模拟点击位置：
### 滑动解锁手机。如果手机屏幕自动点亮后不需要解锁。可以在文件中删除滑动解锁的部分。
![screen1](https://github.com/1414044032/imgs/blob/master/screen1.png)
### 像素点的获取：
![screen2](https://github.com/1414044032/imgs/blob/master/screen2.png)
### 画图工具打开保存到电脑的设备截图：
![screen3](https://github.com/1414044032/imgs/blob/master/screen3.png)
![screen4](https://github.com/1414044032/imgs/blob/master/screen4.png)
![screen5](https://github.com/1414044032/imgs/blob/master/screen5.png)

## 4.修改文件参数：
![screen6](https://github.com/1414044032/imgs/blob/master/screen6.png)

## 5.运行：
### 定位到文件所在目录。然后执行命令“python DingDing_Secend.py”
![screen7](https://github.com/1414044032/imgs/blob/master/screen7.png)

## 6.参考资料：
[https://github.com/Skyexu/TopSup](https://github.com/Skyexu/TopSup)
[https://github.com/mzlogin/awesome-adb](https://github.com/mzlogin/awesome-adb)