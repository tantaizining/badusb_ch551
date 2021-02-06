# badusb_ch551

#### 介绍
基于ch551/ch552单片机制作的可以使电脑关机的badusb整蛊小工具。

#### 软件架构



#### 安装教程

1.  下载badusb文件夹，以及烧录工具
2.  打开烧录工具，在功能中添加ch55x到keil
3.  打开keil工程文件，编译，输出hex
4.  根据gerber文件（压缩包）打样pcb
5.  焊接完成后，打开烧录软件，短接D+与D++，插入电脑
6.  选择对应hex文件即可烧录完成
7.  拔掉，断开D+与D++，重新插入电脑，即可在5s后实现关机

#### 使用说明

1.  本仓库中既有keil工程文件、pcb文件，也有hex文件、gerber文件
2.  不追求过程，可直接下载hex、gerber文件和烧录软件
3.  hex文件在badusb文件夹中object中
4.  gerber文件为压缩包，可直接发给板厂打样
5.  元件采用sop16封装的ch551/ch552，LED不要焊接，LED旁边的电阻推荐4.7k-10k，剩余两个0805封装是104电容，仅需四个元件即可组成最小系统

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
