BlackLight 新浪微博客户端
---
![Logo](https://raw.githubusercontent.com/PaperAirplane-Dev-Team/BlackLight/master/art/logo.png)  
[![Build Status](https://travis-ci.org/PaperAirplane-Dev-Team/BlackLight.svg?branch=master)](https://travis-ci.org/PaperAirplane-Dev-Team/BlackLight)  

详细介绍以及Changelog请见Play商店 <https://play.google.com/store/apps/details?id=us.shandian.blacklight>  
源代码在GPLv3协议下发布

由于新浪微博已经不再接受新的第三方客户端申请，因此BlackLight使用“黑魔法”的方式登录微博。要登录，您需要一个可用的微博App Key，这里有一个：<https://gist.github.com/PeterCxy/3085799055f63c63c911>  
个人娱乐之作，勿用于任何盈利性用途。  

如果你有意加入本项目，你可以阅读我们的Wiki以及下面的内容来获得有关指导。  

使用Android Studio导入
---
1. `git clone` 本项目到本地
2. 在`Android Studio` 中执行 `Import` 并耐心等待……等待……再等待
3. 编译时请选择`app`模块，`app_snapshot`仅供自动发布之用
4. Enjoy it!

使用AIDE导入
---
1. 安装 `AIDE` 到你的手机上
2. 在其中直接clone本项目并打开即可

编译非调试版本
---
如果您想编译非调试版本，即 `Release` 版本，请在项目根目录创建 `signing.properties`

```
STORE_FILE=/path/to/your/publish/keystore
STORE_PASSWORD=your_passwd
KEY_ALIAS=your_alias
KEY_PASSWORD=your_passwd
```

然后即可使用 `gradle :app:assembleRelease`


感谢
---
四次元(@qii)  
碎星iKe(@IssacWong)


主要开发者
---
@PeterCxy  
@Harry-Chen  
@fython  
@xavieryao

纸飞机开发团队 @PaperAirplane-Dev-Team 出品
