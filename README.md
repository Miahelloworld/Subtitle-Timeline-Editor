## 产品名：时间轴小助手
[README in English](./README-in-English.md)

## 设计图 
![](./img/design.jpg)  
(使用 Sketch 设计)

## 当前状态：开发中
第一版预计完成时间：2020年下半年      

## 是个人还是公司作品？
个人, 开发出来解决自己的需求

## 解决什么问题？
做字幕时可以舒服一些，高效一些   

## 具体意思是：
1. 界面好看（也要有夜间模式）
2. 调整时间轴的效率高
	* 有快捷键
	* 背景有音频波形图，方便对齐

## 为什么做这个？
目前字幕编辑软件的体验很不好，   
因此做个新的，让做字幕的时候能舒服一些


## 设计的幕后

### 做了多个版本
![](./img/1.jpg)

### 缩放看全景是这样的: 
![](./img/2.jpg)

## 同类软件分析
可以做字幕的软件有：   
* Aegisub
* Arctime Pro
* 人人译视界

此列表不全，我忽略了不少小软件，  
那些软件只有 Windows 版，而且界面很难看（发布于 2000~2010 年间）

## Aegisub 的缺点
![](./img/aegisub.jpg)

* 2014年左右停止更新
* 界面不美观, 没有夜间模式，纯白界面看久了眼睛疼
* 快捷键的支持不够好，macOS 上不好用+容易崩溃
* 我从2013年用到现在2020年，忍够了

编程语言：根据开源代码，看起来是用 C/C++ 写的

## Arctime Pro 的缺点
![](./img/arctime.jpg)

* 界面难看 (以我个人的审美标准)
* macOS 上用起来不舒服
* 时间轴一样的字幕块会叠加到一起，不方便做双语字幕

优点:  
* Arctime 有音频波形图

## 人人译视界的缺点
![](./img/rr.jpg)

* 卡
* 难看
* 不好用

优点：
* 功能很齐全，各种小工具都有

他们有很多用户，软件用肯定能用，这是最基本的底线，    
我的问题是用起来不舒服，不爽      


## 功能路线图 (很粗略)
总体:
* Aegisub 大大小小的功能太多了，一时半会儿肯定替代不了 Aegisub，先不以这个为目标
* 先把调整时间轴，改字幕文本，增删字幕的整体操作做舒服了，其他的再说      

### 1.0 版
* 界面美观
* 调整时间轴方便
* 支持的格式有一个两个就行，不需要做太多兼容 (srt,ass,vtt)
* MVP 做出来就行
* 自用，可能暂不开源

### 1.5 版
* 做快捷键的设置和使用
* 其他待定   

### 2.0 版
* 加入机器翻译功能
* 加入视频压制功能
