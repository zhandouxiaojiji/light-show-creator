<h1 align="center"/>Light Show Creator 使用手册</h1>
<p align="center">
	<a href="./README.md">English</a>
	/
    <a href="./README-zh.md">简体中文</a>
</p>

自定义灯光秀是特斯拉汽车的一项很酷的功能。 LightShowCreator是一款可以快速轻松制作灯光秀的APP。 如果你对它感兴趣，你也可以尝试用它来定制你自己的节目。
+ [AppStore](https://apps.apple.com/us/app/light-show-creator/id6446385602)
+ [Google Play](https://play.google.com/store/apps/details?id=com.coding1024.tslshow)
+ [Microsoft Store](https://www.microsoft.com/store/productId/9PL28B7M856D)

![](Images/preview.gif)

# U盘要求
+ 必须包含一个名为“LightShow”的基本文件夹（解压从该项目下载的 LightShow.zip）
+ 必须格式化为 exFAT、FAT 32（适用于 Windows）、MS-DOS FAT（适用于 Mac）、ext3 或 ext4。 当前不支持 NTFS。
+ 根目录不得包含的 TeslaCam 文件夹。

特斯拉官方指南: https://github.com/teslamotors/light-show

# 如何创建新项目
打开“项目”页面，点击“新建项目”按钮，输入项目名称
![](Images/new-project.png)

# 如何导入音乐
## Android
如果您的系统是Android，您可直接从文件系统里选择一首不超于5分钟的mp3或者wav文件来导入。

## IOS
如果您的系统是IOS，您需要从第三方APP里导入音乐，如iCloud, OneDrive, GoogleDrive, Dropbox。任意支持文件共享的APP都可以，以下OneDrive为例：
![](Images/import01.png)

# 自动模式如何使用
![](Images/auto.png)
自动模式的使用非常简单，只需要点亮“自动”按钮，车灯就会根据音乐的节奏自动亮起。点击播放按钮开始录制灯光秀，直到音乐播放结束，灯光秀就制作完成啦。

在录制的过程中，您可以调节一些参数：
+ 步进时间：就是每帧的时长， 越大越省内存
+ 节奏敏感度：对音乐节奏的敏感度，理论上越小越省内存
+ 节拍时长：每次车灯亮起的最大时长，越大越省内存
+ 雾灯开关（标续的Model 3和Model Y是没有前雾灯的，把这个选项关掉效果更加）

# 手动模式如何使用
手动模式可以进行更加个性化的编辑，就像是弹钢琴一样，非常简单。两个对称的车灯作为一组，黑键是同时亮起，白键是音边亮起。
![](Images/manual01.png)

在手动录制的同时，也可以激活自动模式，只需要自己控制关键的几个车灯即可。
![](Images/manual02.png)

# 如何导出灯光秀文件
导出灯光秀与导入音乐的原理一样，也是通过分享功能向第三方app发送，下面还是以OneDrive为例:
![](Images/export01.png)
![](Images/export02.png)
![](Images/export03.png)


# 如何使用xLights进行更加精细的编辑
目前我们的APP还不支持渐变效果和门窗的控制，如果您有这方面的需求，您可以把lightshow.wav/mp3，lightshow.fseq，lightshow.xsq，三个文件放到PC设备的同一个目录，然后用xLights打开即可。

# Q&A
### 手动模式下，如果音乐的节奏太快，跟不上节拍怎么办
您可以在设置页面，设置音乐的播放速度

### 为什么Window版本不支持手动模式
近期windows还没有更新计划，因为windows不支持触屏，与手机版本差异比较大。

### 有什么好办法做多车联动表演
我们后续的版本计划里有规划这项功能，目前有个建议，您可以把您的音乐切分成多个音轨，然后新建多个项目，使用自动模式的功能，这样可以快速的制作多辆车的灯光秀

# 这里分享一些LightShowCreator制作的demo
### Scenes
|Songs|Preview|Download|
|---|---|---|
|Halloween Kills(Main Title Theme)|[Youtube](https://youtu.be/EEkjOqiCXso)|[fseq](Downloads/HalloweenKills.fseq) [mp3](Downloads/HalloweenKills.mp3) [xsq](Downloads/HalloweenKills.xsq)|
|Thriller - Michael Jackson|[Youtube](https://youtu.be/DHbQ05eTug8)|[fseq](Downloads/Thriller.fseq) [mp3](Downloads/Thriller.mp3) [xsq](Downloads/Thriller.xsq)|
|Wedding March (The bride debut)|[Youtube](https://youtu.be/iakQSEtRHS8)|[fseq](Downloads/Wedding1.fseq) [mp3](Downloads/Wedding1.mp3) [xsq](Downloads/Wedding1.xsq)|
|Wedding March (The bride leaves)|[Youtube](https://youtu.be/Gn86WnPEw6o)|[fseq](Downloads/Wedding2.fseq) [mp3](Downloads/Wedding2.mp3) [xsq](Downloads/Wedding2.xsq)|
|Happy Birthday|[Youtube](https://youtu.be/c4l5BWJmnm8)|[fseq](Downloads/HappyBirthday.fseq) [mp3](Downloads/HappyBirthday.mp3) [xsq](Downloads/HappyBirthday.xsq)|
|Merry Christmas|[Youtube](https://youtu.be/pC14N6Z2QZY)|[fseq](Downloads/MerryChristmas.fseq) [mp3](Downloads/MerryChristmas.mp3) [xsq](Downloads/MerryChristmas.xsq)|

### Funny & BGM
|Songs|Preview|Download|
|---|---|---|
|Auf Und Auf Voll Lebenslust|[Youtube](https://youtu.be/QG7xRLSWCg0)|[fseq](Downloads/AufUndAufVollLebenslust.fseq) [mp3](Downloads/AufUndAufVollLebenslust.mp3) [xsq](Downloads/AufUndAufVollLebenslust.xsq)|
|AxelF|[Youtube](https://youtu.be/2tdLb02Y96o)|[fseq](Downloads/AxelF.fseq) [mp3](Downloads/AxelF.mp3) [xsq](Downloads/AxelF.xsq)|
|BettyBoop|[Youtube](https://youtu.be/H2x7Mawssjo)|[fseq](Downloads/BettyBoop.fseq) [mp3](Downloads/BettyBoop.mp3) [xsq](Downloads/BettyBoop.xsq)|
|JingleBell(LaughingAllTheWay)|[Youtube](https://youtu.be/J-K50W4beiU)|[fseq](Downloads/JingleBell(LaughingAllTheWay).fseq) [mp3](Downloads/JingleBell(LaughingAllTheWay).mp3) [xsq](Downloads/JingleBell(LaughingAllTheWay).xsq)|
|KillBill|[Youtube](https://youtu.be/6oPdOL5JQ6g)|[fseq](Downloads/KillBill.fseq) [mp3](Downloads/KillBill.mp3) [xsq](Downloads/KillBill.xsq)|
|Nijamena|[Youtube](https://youtu.be/3vFTLrvxN0A)|[fseq](Downloads/Nijamena.fseq) [mp3](Downloads/Nijamena.mp3) [xsq](Downloads/Nijamena.xsq)|
|Seafights|[Youtube](https://youtu.be/5yDf8Ge_mEE)|[fseq](Downloads/Seafights.fseq) [mp3](Downloads/Seafights.mp3) [xsq](Downloads/Seafights.xsq)|
|The Hampster Dance Song|[Youtube](https://youtu.be/Nl9QJFfxf2Y)|[fseq](Downloads/TheHampsterDanceSong.fseq) [mp3](Downloads/TheHampsterDanceSong.mp3) [xsq](Downloads/TheHampsterDanceSong.xsq)|
|Victory - Two Step From Hell| [Youtube](https://youtu.be/JfHDj0td7Y8)|[fseq](Downloads/Vectory.fseq) [mp3](Downloads/Vectory.mp3) [xsq](Downloads/Vectory.xsq)|
|Chinese Suona (耍猴儿)| [Youtube](https://youtu.be/PHS2iNy9a-Y)|[fseq](Downloads/MonkeySuona.fseq) [mp3](Downloads/MonkeySuona.mp3) [xsq](Downloads/MonkeySuona.xsq)|
|Astronomia Remix| [Youtube](https://youtu.be/4dl7x454HOI)|[fseq](Downloads/AstronomiaRemix.fseq) [mp3](Downloads/AstronomiaRemix.mp3) [xsq](Downloads/AstronomiaRemix.xsq)|
|Night Fireflies and You - Aniface| [Youtube](https://youtu.be/06apHQdidiQ)|[fseq](Downloads/NightFirefliesAndYou.fseq) [mp3](Downloads/NightFirefliesAndYou.mp3) [xsq](Downloads/NightFirefliesAndYou.xsq)|

### Popular
|Songs|Preview|Download|
|---|---|---|
|Tuesday|[Youtube](https://youtu.be/dwjc0wLnCfQ)|[fseq](Downloads/Tuesday.fseq) [mp3](Downloads/Tuesday.mp3) [xsq](Downloads/Tuesday.xsq)|
|DEAJ VU|[Youtube](https://youtu.be/dvio49U2RhE)|[fseq](Downloads/DEJAVU.fseq) [mp3](Downloads/DEJAVU.mp3) [xsq](Downloads/DEJAVU.xsq)|
|Pump It Up|[Youtube](https://youtu.be/G-VYmN47iyo)|[fseq](Downloads/PumpItUp.fseq) [mp3](Downloads/PumpItUp.mp3) [xsq](Downloads/PumpItUp.xsq)|
|Ankaranin baglari|[Youtube](https://youtu.be/8BakNXETqkA)|[fseq](Downloads/ANKARANIN.fseq) [mp3](Downloads/ANKARANIN.mp3) [xsq](Downloads/ANKARANIN.xsq)|

### For Kids
|Songs|Preview|Download|
|---|---|---|
|Schnappi|[Youtube](https://youtu.be/b-RGHncYe1Q)|[fseq](Downloads/Schnappi.fseq) [mp3](Downloads/Schnappi.mp3) [xsq](Downloads/Schnappi.xsq)|

### World Cup
|Songs|Preview|Download|
|---|---|---|
|Hayya Hayya (2022)|[Youtube](https://youtu.be/RpJeS3fIH1s)|[fseq](Downloads/HayyaHayya.fseq) [mp3](Downloads/HayyaHayya.mp3) [xsq](Downloads/HayyaHayya.xsq)|
|The Cup of Life (1998)|[Youtube](https://youtu.be/cqOPomTxMpo)|[fseq](Downloads/TheCupOfLife.fseq) [mp3](Downloads/TheCupOfLife.mp3) [xsq](Downloads/TheCupOfLife.xsq)|
|We Will Rock You (1994)|[Youtube](https://youtu.be/zCorVvQh99k)|[fseq](Downloads/WeWillRockYou.fseq) [mp3](Downloads/WeWillRockYou.mp3) [xsq](Downloads/WeWillRockYou.xsq)|
