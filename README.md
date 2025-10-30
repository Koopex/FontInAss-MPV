# FontInAss-MPV

在MPV播放器中请求 [FontInAss](https://github.com/RiderLty/fontInAss) 子集化处理字幕。

# 主要功能

[FontInAss](https://github.com/RiderLty/fontInAss): 实时将字体子集化后嵌入ass的小工具，用于在未安装对应字体的系统上正确显示字幕。

把外挂的ass字幕发送给 FontInAss 处理，提示缺少的字体和字形。

不需要 emby 也能使用 FontInAss 实时处理字幕。

使用 [embyToLocalPlayer](https://github.com/kjtsune/embyToLocalPlayer) 的"读取硬盘模式"也能用 FontInAss。

# 使用方法

保存`font_in_ass.lua`到mpv配置目录的`scripts`文件夹

编辑`font_in_ass.lua`：填写fontinass的服务地址等

可选的快捷键设置: `#	script-binding font_in_ass/openLog	#! 打开字体缺失日志`

# 感谢!
- [FontInAss](https://github.com/RiderLty/fontInAss)
- [mpv](https://github.com/mpv-player/mpv)
- [uosc](https://github.com/tomasklaen/uosc)
- [embyToLocalPlayer](https://github.com/kjtsune/embyToLocalPlayer)
