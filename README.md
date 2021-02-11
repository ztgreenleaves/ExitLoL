# QuitLoLImmediately


快速退出英雄联盟游戏


本仓库包含以下内容：

1. 一个bat文件，用来直接退出lol客户端，返回重新连接界面等待队友结束游戏。
2. 将bat添加到任务栏，可以点击即退出游戏。


## 背景

在进行英雄联盟游戏时，经常遇到各种原因导致难以进行下去，就会想要快速退出游戏，避免被队友折磨。以往只需要按alt+F4,现在加了5秒冷静期，就让自己多被折磨5秒，感官上像是过了500秒，甚至会让你放弃退出的想法，继续被队友折磨。为了战胜队友，于是有了这个项目。

这个项目的目标是：

你折磨我，我就折磨你。

## 使用说明

方法一：直接双击运行bat文件。

方法二：按照如下安装方式创建快捷方式指向bat文件，并添加到任务栏。（推荐！！）
## 安装

下载项目，右键空白处新建快捷方式，输入：cmd/c 加上bat文件路径，如果路径中有空格，需要双引号引起来路径。
例如：
```sh
$ cmd /c  C:\Users\XXX\Desktop\快速退出lol.bat
```

