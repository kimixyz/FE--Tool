# FE--Tool
一些小工具

###browsersync
同步工具，手机和电脑上都可以刷新实时看到效果
[官网][1]
[1]: http://www.browsersync.io/#install
Browsersync + Gulp.js
[地址][2]
[2]:http://www.browsersync.io/docs/gulp/

###sublime text3增加右键用Sublime Text 打开功能
1.依次点击桌面左下角windows图标——>运行——>regedit，打开注册表。

2.依次找到HKEY_CLASSESS_ROOT->*->Shell，右键新建项，命名为Edit with Sublime Text3。

3.在项“Edit with Sublime Text”下新建字符串值，命名为Icon，值为“Z:\SublimeText\Sublime Text Build 3083\sublime_text.exe,0”,其中黑色地址为 Sublime Text程序文件地址。

4.在项“Edit with Sublime Text”下新建项，命名为Command，该Command项下默认值修改为“Z:\SublimeText\Sublime Text Build 3083\sublime_text.exe %1”。

5.设置完成后，无需重启电脑，就可以在右键菜单中，显示Edit with Sublime Text3。

[参考][1]
[1]: http://www.jianshu.com/p/1767b513a2c4
