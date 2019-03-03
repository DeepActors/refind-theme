## refind 主题
[refind](http://www.rodsbooks.com/refind/) 是一个用于管理操作系统启动入口的跨平台工具。
这是一个简单的refind的主题。该示例在MacBook双系统（macOS + linux）上运行良好。

![refind 主题示例](https://github.com/connorgame/res/raw/master/pic/refind-theme-readhat.png)

### 使用方法

1.复刻本仓库至任意目录。

2.CD至refind安装目录。refind安装目录一般是`/boot/efi/EFI/refind`，这取决于实际安装目录。

3.备份该目录下原始的refind.conf文件。重命名它或异动至别处。建议重命名它。

4.复制本仓库中的refind.conf文件和theme文件夹至refind安装目录。


### 关于背景不生效

可能原因是图片尺寸和你的屏幕尺寸不一致。可以修改theme/bg/bg-redhat1.png这张图片的尺寸
和你的屏幕分辨率一致，或者选择一副自己喜欢的图片放到`theme/bg/`目录下，并修改refind.conf
中的`banner theme/bg/bg-redhat1.png`使它与你的采用的图片一致，再修改refind.conf中的
`resolution 2560 1600`，使它与你的屏幕分辨率一致。

## refind-theme

[refind](http://www.rodsbooks.com/refind/) is an easy to use boot manager for UEFI based 
systems. This is a simple refind theme.

![refind sample](https://github.com/connorgame/res/raw/master/pic/refind-theme-readhat.png)

### Usage

 1. Clone this repository into any directory you like.

 2. Locate your refind directory. This is commonly `/boot/efi/EFI/refind`
    though it will depend on where refind is installed.

 2. Backup origin refind.conf(rename it(recommend this way) or remove it).

 3. Copy refind.conf and theme folder(in repository directory) to refind directory.

### Background size

If you find the background not go into effect it may be due to the included wallpaper
being an incorrect resolution for your monitor. You can choose another background or 
your own and resize it as appropriate, and put it to theme/bg folder, and modify the line
`banner theme/bg/bg-redhat1.png` and the line `resolution 2560 1600` in refind.conf.
