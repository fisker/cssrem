CSSREM
-------------

一个CSS的px值转rem值的Sublime Text 3自动完成插件。

插件效果如下：

![效果演示图](cssrem.gif)

#### 安装
* Ctrl+Shift+P 输入 Package Control: Add Repository
* 添加git地址 https://github.com/fisker/cssrem
* Ctrl+Shift+P 输入 Package Control: Install Package
* 搜索 cssrem
* 重启 Sublime Text

##### 配置参数

参数配置文件：Sublime Text -> Preferences -> Package Settings -> cssrem

* `fontsize` - px转rem的单位比例，默认为40。
* `precision` - px转rem的小数部分的最大长度。默认为6。
* `leadingzero` - 是否保留前导0。
* `exts` - 启用此插件的文件类型。默认为：[".css", ".less", ".sass"]。

#### thanks to
* original repo https://github.com/flashlizi/cssrem
* thanks to MA with help in python script
