## Mac 设置方法

打开一个可跨域的 chrome 窗口实现方法：

1.  打开终端
2.  输入下面的命令 (需要替换路径中的 yourname)

```
cd /Applications/Google\ Chrome.app/Contents\


mkdir myChromeDevData

open -n /Applications/Google\ Chrome.app/ --args --disable-web-security --user-data-dir=/Applications/Google\ Chrome.app/Contents/myChromeDevData/


```
