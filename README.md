# AppendCopy
复制拼接

<img src="https://github.com/xiaofei-dev/AppendCopy/blob/master/app/src/main/res/drawable/ic_launcher.png" width="15%" height="15%">

一个实现 非连续复制 的小工具。

安装包下载地址：[https://www.coolapk.com/apk/138511](https://www.coolapk.com/apk/138511)

本应用没有界面！！！打开后会自动转到后台运行并开始监听复制事件。
当发生复制事件时会在屏幕右侧弹出一个三秒自动消失的半透明图标。此时点击图标图标会变成绿色并且不会再自动消失，
此时应用将继续在后台监听复制事件，不同的是此时应用会在后台自动拼接接下来（包括初次）复制的文本（不限次数和地方），当感觉没有更多需要复制的内容之后，再点击绿色图标图标会自动消失，并在后台将拼接好的文本写入剪贴板。
