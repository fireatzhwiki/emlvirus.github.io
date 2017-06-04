## [萨满喵喵 ヽ(￣ω￣(￣ω￣〃)](https://emlvirus.github.io/)

<h2 align="center">Rainmeter 教程基础版</h2>

<p align="center"> <img src="images/82c5b5a7gw1ei04sza147j206z02s0t2.jpg"/> </p>

<p align="center">
本教程适用环境
</p>
<p align="center">
OS Windows 7/8.1/10
</p>
<p align="center">
Rainmeter版本 4.x
</p>
<p align="center">
本教程会随着Rainmeter版本号更新而更新，请在阅读前认真核对教程适用环境
</p>

<h2 align="center">FAQs 常见问题</h2>

Q1：Rainmeter对系统资源占用如何（使用Rainmeter会卡电脑吗）？

A1：CPU占用率取决于Rainmeter已激活皮肤的数量及已激活皮肤的刷新频率，一般而言，类似于频谱、舞蹈人物等实时刷新皮肤若刷新率较高且数量较多，CPU占用将明显偏高（稍后将详细讲解降低占用的办法，见于调整皮肤刷新率部分）；

RAM占用一般极少，可忽略不计，对于大部分用户这个数值不多于70M；

此外，正常情况下不出现明显磁盘读取、I/O读取等占用。

（一句题外话，运行中完全不占用系统资源的软件目前理论上不存在。）

Q2：我需要怎样的知识水平才能使用Rainmeter（Rainmeter上手难度高吗）？

A2：如果你只用下载并安装在互联网上分享的皮肤、插件等，那么是不需要任何专业知识的；但是自行制作皮肤、插件等将要求一定开发知识。

~~（连基本电脑操作基础都不懂的话请无视）~~

Q3：Rainmeter 4.x系统兼容如何？

A3：Windows 7及更新 不支持XP 不支持XP 不支持XP

（题外话：停止支持的OS还是放弃吧。习惯？怀旧？嗯 ~~反正主流开发者们觉得这就是\*\*的扯淡）

此外若使用Windows 7时无法安装，那么安装如下系统补丁

[https://www.microsoft.com/zh-CN/download/details.aspx?id=36805](https://www.microsoft.com/zh-CN/download/details.aspx?id=36805)

<h2 align="center">Concepts 概念解释</h2>

皮肤skin：Rainmeter显示于桌面的可视化组件，文件格式为ini；
例如播放器皮肤可以在绑定的播放器运行时控制播放器

插件plugin：赋予Rainmeter一定功能的动态链接库文件，文件格式为dll；
例如nowplaying.dll插件为雨滴提供运行的播放器播放的音频信息

主题layout：当前的皮肤激活情况、皮肤布局（可以包括壁纸）的组合方案

<h2 align="center">Install Skins安装皮肤</h2>

在软件初次安装时会连带安装激活一些内置皮肤（仅英文），如不需要右键关闭即可

#### 安装rmskin皮肤包

1.安装rmskin皮肤包时，若已经安装Rainmeter，那么双击该皮肤包文件，点击Install按钮（如下图）

![](/assets/1.png)

2.此时在Rainmeter管理视窗中即可看到安装的皮肤，并且一般情况下，皮肤包内所有皮肤都会被激活（使用自定义主题时另作别论）

_注意：当安装Rainmeter如果选择便携安装，上述操作将无法执行（未写入注册表信息），此时若希望安装此类皮肤请重新运行安装程序并选择标准安装_

#### 安装rar压缩包皮肤

1.首先找到Rainmeter皮肤安装路径：右键单击Rainmeter托盘图标，点击关于 ，在 版本 选项卡中的 SkinPath 后描述的路径即为皮肤安装路径（如下图）
![](/assets/23.png)

2.然后将rar压缩包中的皮肤解压到皮肤安装路径

3.右键单击Rainmeter托盘图标，点击_刷新全部_

4.此时在Rainmeter管理视窗中即可看到相应皮肤，双击一个ini皮肤即可激活，或选中后点击右侧的 加载 按钮 （如下图）
![](/assets/3.png)
