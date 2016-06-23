rem-unit
-------------
一个输入px可转为rem的Sublime Text 3自动完成插件。

##### 与CSSREM的区别
* 删除多余的小数 1.0rem -> 1rem
* 删除0px转换时多余的单位 0.0rem -> 0
* 增加 前导0的选择 0.25rem -> .25rem
* 增加 可在注释保留原始值 css使用块注释 其他语言行注释
* 增加默认支持文件类型.scss .styl
* TODO: 小数px起始替换位置不正确的bug 16.16px -> 16.1.01rem (should be 1.01rem)

#####插件效果：（CSSREM）
![效果演示图](cssrem.gif)

#### 安装(Package Control)
* Ctrl+Shift+P 输入 Package Control: Install Packag
* 搜索 rem-unit
* 重启 Sublime Text

#### 安装(github)
* Ctrl+Shift+P 输入 Package Control: Add Repository
* 添加git地址 https://github.com/fisker/rem-unit
* Ctrl+Shift+P 输入 Package Control: Install Package
* 搜索 rem-unit
* 重启 Sublime Text

##### 配置参数

参数配置文件：Sublime Text -> Preferences -> Package Settings -> rem-unit

* `fontsize` - html元素font-size值，默认为16。
* `precision` - px转rem的小数部分的最大长度，默认为8。
* `leadingzero` - 是否保留前导0，默认不保留。
* `exts` - 启用此插件的文件类型。默认为：[".css", ".scss", ".less", ".sass", ".styl"]。

#### 感谢
* CSSREM原作者 https://github.com/flashlizi/cssrem
* @马海星 对python脚本的帮助
