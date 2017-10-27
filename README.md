# OSboy 源豆卡片机资源和游戏
欢迎使用源豆卡片机,让我们一起生命不息，鼓捣不止。源豆卡片机是开源游戏机Arduboy的分支项目，与源豆卡片机的各种代码更新都在github.com/osbeancom/OSboy/

## 源豆卡片机主创人员：
------------------------
* *产品策划和工业设计：杨锴
* 电路设计：任刚 Lester
* AtbotDude开发：双源电子
* 库文件优化和开发：任刚*

## 目录结构如下：
-----------------------
* lib/  8个文件打包
* rom/  编译好的游戏文件
* src/  游戏源代码
* tools/  AtbotDude游戏烧录工具等

## 游戏机使用方法：
-----------------------
#### 1.	开始游戏
拨动卡片机左上部的拨动开关，启动后会自动进入默认游戏，然后根据游戏提示按动按钮，就可以开始游戏啦。
#### 2.	充电
源豆卡片机自带210MAH锂电池，你用5V0.5A-1A的充电器连接MicroUSB口即可。充满电后LED1会亮起。

#### 3.	更换游戏
#### 3.1.	游戏的获取
在源豆科技官网www.osbean.com会不定期的更新游戏内容，github.com/osbeancom/OSboy/这里也有不少游戏，你可以选择喜欢的游戏下载到本地。另外，www.arduboy.com上面大多数的游戏在源豆卡片机上都可以使用。

#### 3.2.	需要的环境
#### 3.2.1.	入门方式
感谢双源电子提供的傻瓜式烧录游戏工具AntbotDude。这个工具在github.com/osbeancom/OSboy/tools/中可下载。
AntbotDude运行在windows环境中，烧录前，首先要确认游戏机电源是关闭状态，然后通过USB线将游戏机连接到电脑。双击运行“AntbotDude.exe”，
#### 3.2.2.	开发者方式

#### 3.2.2.1.	下载Arduino IDE

#### 3.2.2.2.	安装 Arduboy 库文件
Arduboy库文件目前已经包括了8个库，统一打包下载地址是：https://github.com/osbeancom/OSboy/lib/
压缩包中包含8个库文件，其中Arduboy和Arduboy2我们在官方库的基础上做了优化和修改，其他的6个就是官方的库。
*	Arduboy   
*	Arduboy2  
*	ArduboyTones   https://github.com/MLXXXp/ArduboyTones
*	ArduboyPlaytune  https://github.com/Arduboy/ArduboyPlaytune
*	ArdBitmap  https://github.com/igvina/ArdBitmap
*	ArdVoice  https://github.com/igvina/ArdVoice
*	ATMlib  https://github.com/TEAMarg/ATMlib
*	Arduboy-TinyFont  https://github.com/yinkou/Arduboy-TinyFont

把库文件下载到本地，在Arduino IDE中加载： Sketch > Include Library > Manage Libraries 依次选择本地的几个Arduboy 库，选择install 完成安装。
