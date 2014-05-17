## gvim 7 gvimext.dll for xqin


* 精简`gvim`向`Windows`的资源管理器(`explorer.exe`)注册的右键菜单项.
* 只保留 `Edit with Vim` 和 `Diff with Vim` 两项菜单(`Diff with Vim` 菜单项仅在选中的文件数大于1小于5时出现), 并给菜单项增加`vim`的图标.
* 默认使用右键编辑文件时的行为为:在现有的`gvim`中新开一个Tab来编辑文件(多个文件时使用多个Tab),在单击菜单项时,如果键盘上的`Shift`键是处于按下状态,则新开一个`gvim`来打开这些文件(此时在`gvim`在打开的文件是以`buffer`形式加载的).
* `restart_explorer.bat` 为快速关闭并重新启动`explorer.exe`的`bat`文件.
* 本代码仅在`Windows 7`下测试过,不保证其他`Windows`系列的操作系统同样适用.
* 编译时使用`vc++2010`编译通过, 具体编译方法请参见`<README.txt>`.
* 效果截图见`<screencast.png>`.
* `dll` 目录下的`x86`目录中的文件为`Windows` 32位的操作系统中使用的, `x64`中的为`Windows` 64位操作系统中使用的.
