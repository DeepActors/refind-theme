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
