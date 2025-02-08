# nukitashi_ns_port
## 简介

个人基于komome(久岛鸥)大佬的移植思路完善的NUKITASHI NS移植运行端口，运行程序和nsp壳是基于0100076015D4E000改动制作，Title ID和Icon借用了komome的移植nsp(因为我不太擅长nsp的ui一类信息的改动所以就借用了emm求原谅)。

## 如何安装

#### NUKITASHI 1

**下载链接：**[v1.0 点此下载](https://cloud.189.cn/web/share?code=qqqQrizyIrIn)(访问码：s5jn)

确保你的ns拥有Atmosphere OS，通过任意工具安装0100272018d1a000.nsp，并建立对应的大气层补丁文件夹0100272018D1A000。

确保你有steam原版的NUKITASHI 1、并已经打上了Shiravune的v2.0.2的patch(如果不知道如何安装patch可以在[Shiravune官网顶部的 Patches](https://shiravune.com/)中找到)。将游戏文件夹下的NUKITAHI.pfs、NUKITASHI.pfs.0xx文件全部重命名为类似root.pfs、root.pfs.0xx的样式，将所有重命名后的pfs文件放入ns中刚建好的0100272018D1A000补丁文件夹中。即可开始游玩。

（可选）root.pfs.023为素材优化修复补丁，推荐一块使用

#### NUKITASHI 2

WIP 正在制作中

## 按键

个人临时定义修改了一些按键功能

十字键 上：调出回想  下：确认/故事前进  左：快速保存  右：快速读取
A：确认/故事前进  B：隐藏文本  X：调出回想  Y：显示设置菜单
肩键 L：自动模式  R：跳过文本  ZL：显示保存菜单  ZR：显示读取菜单
— 按键：回到主界面  + 按键：隐藏/显示侧边菜单栏
屏幕左滑：隐藏文本  屏幕右滑：跳过文本  屏幕上滑：调出回想  屏幕下滑：显示菜单

## 更新记录

#### NUKITASHI 1

v1.0
用clip的方法替代了maskface蒙版无法正常使用的效果，调整了文字框和回想框文本的文字大小，修复了班长的两句语音

v0.5
fg立绘中face所用的cg/frame/maskface蒙版无法正常显示，临时将face立绘缩小至frame-waku框内；用ResourceHanRoundedCN-Bold替代了原先的resourcehanroundedcn-medium以使字体更饱满；新增了部分按键设置。

#### NUKITASHI 2

WIP 正在制作中

## 已知问题

1、游戏依旧会在某个时刻崩溃退出，例如开场“冷泉问答”中充气人偶出现后，推荐经常使用快速保存保存游玩进度。
2、游戏虽然可以快进，但快进的内容太多可能会导致开启回想时发生崩溃，也请快进后经常保存当前游玩进度。
3、exit按钮并不能完全退出关闭游戏，而在第一次游玩时选择语言设置后并不会第一时间保存全局设置，你可以通过进行一次exit来保存游戏当前的全局设置。
4、目前游戏的移植仍然处于测试阶段，可能会存在部分演出\图像\语音异常，你可以随时提出issue告诉我具体的章节位置和异常情况。