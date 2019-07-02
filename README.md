# EasyPlayer-RTMP播放器

EasyPlayer-RTMP播放器是一套RTMP专用的播放器，包括有：Windows、Android、iOS三个平台，是由[**青犀TSINGSEE开放平台**](http://open.tsingsee.com "青犀开放平台")开发和维护的区别于市面上大部分的通用播放器，EasyPlayer-RTMP系列始于成熟的商业项目，其底层模块[EasyRTMPClient项目](https://github.com/EasyDSS/EasyRTMPClient "EasyRTMPClient")经过多年迭代发展，上层模块复用[EasyPlayer-RTSP项目](https://github.com/EasyDSS/EasyPlayer-RTSP "EasyPlayer-RTSP")，均是站在巨人肩膀上的产品，目前得到了各行各业(尤其是安防行业)的广泛应用，EasyPlayer-RTMP更加精炼、更加专注，具备非常低的延时，非常高RTMP协议兼容性，编码数据解析等方面，都有非常大的优势，尤其是在有特殊参数/私有自定义字段的情况下，非常容易进行定制和兼容！

> 我们做过比较，EasyPlayer-RTMP各平台（Windows、Android、iOS）相比于同类型的功能的vlc、ffplay等等，其在打开速度、延时控制、兼容性等方面，都要优秀很多，即使是号称了秒开功能的ffmpeg based 播放器（通过设置probsize、AnalysisTime等参数）其打开速度和延时，还是会比EasyPlayer-RTMP要高，EasyPlayer-RTMP底层与上层全部自主开发，自主知识产权，可以说在RTMP播放器领域，目前最可靠、最可控的当属EasyPlayer-RTMP；


## EasyPlayer-RTMP系列项目说明 ##

- EasyPlayer-RTMP-Win

	RTMP Windows播放器：[https://github.com/EasyDSS/EasyPlayer-RTMP-Win](https://github.com/EasyDSS/EasyPlayer-RTMP-Win "EasyPlayer-RTMP-Win")

	最新版本下载：https://github.com/EasyDSS/EasyPlayer-RTMP-Win/releases

- EasyPlayer-RTMP-Android

	RTMP Android播放器：[https://github.com/EasyDSS/EasyPlayer-RTMP-Android](https://github.com/EasyDSS/EasyPlayer-RTMP-Android "EasyPlayer-RTMP-Android")

	最新版本下载：https://github.com/EasyDSS/EasyPlayer-RTMP-Android/releases

- EasyPlayer-RTMP-iOS

	RTMP iOS播放器：[https://github.com/EasyDSS/EasyPlayer-RTMP-iOS](https://github.com/EasyDSS/EasyPlayer-RTMP-iOS "EasyPlayer-RTMP-iOS")

	最新版本下载：https://github.com/EasyDSS/EasyPlayer-RTMP-iOS/releases



## 播放器效果 ##

![EasyPlayer Win](http://www.easydarwin.org/github/images/easyplayer20160908171027.png)

![EasyPlayer Android](https://raw.githubusercontent.com/EasyDarwin/EasyPlayer_Android/master/EasyPlayer/screenshot/single_video.jpg?raw=true)

![EasyPlayer iOS](http://www.easydarwin.org/github/images/easyplayeriosdemo20170310.jpg)


## EasyPlayer全套系列项目说明 ##

- EasyPlayer **RTSP播放器**（Windows / Android / iOS）

- EasyPlayer **RTMP播放器**（Windows / Android / iOS）

- EasyPlayerPro **全功能播放器**（Windows / Android / iOS）

### √ EasyPlayer-RTSP ###

**EasyPlayer-RTSP**是一套RTSP播放器项目，目前包括有Windows、Android、iOS多个分支，主要用于RTSP专用播放，比大部分通用播放器更加精炼，而且延时控制方面非常优秀：

- EasyPlayer-RTSP-Win：[https://github.com/EasyDSS/EasyPlayer-RTSP-Win](https://github.com/EasyDSS/EasyPlayer-RTSP-Win "EasyPlayer-RTSP-Win")

- EasyPlayer-RTSP-Android：[https://github.com/EasyDSS/EasyPlayer-RTSP-Android](https://github.com/EasyDSS/EasyPlayer-RTSP-Android "EasyPlayer-RTSP-Android")

- EasyPlayer-RTSP-iOS：[https://github.com/EasyDSS/EasyPlayer-RTSP-iOS](https://github.com/EasyDSS/EasyPlayer-RTSP-iOS "EasyPlayer-RTSP-iOS")


### √ EasyPlayer-RTMP ###

**EasyPlayer-RTMP**是一套RTMP播放器项目，目前包括有Windows、Android、iOS多个分支，主要用于RTMP专用播放，比大部分ffmpeg封装类型播放器更加精炼，而且延时控制方面非常优秀：

- EasyPlayer-RTMP-Win：[https://github.com/EasyDSS/EasyPlayer-RTMP-Win](https://github.com/EasyDSS/EasyPlayer-RTMP-Win "EasyPlayer-RTMP-Win")

- EasyPlayer-RTMP-Android：[https://github.com/EasyDSS/EasyPlayer-RTMP-Android](https://github.com/EasyDSS/EasyPlayer-RTMP-Android "EasyPlayer-RTMP-Android")

- EasyPlayer-RTMP-iOS：[https://github.com/EasyDSS/EasyPlayer-RTMP-iOS](https://github.com/EasyDSS/EasyPlayer-RTMP-iOS "EasyPlayer-RTMP-iOS")

### √ EasyPlayerPro ###

**EasyPlayerPro**是一款全功能的流媒体播放器，支持RTSP、RTMP、HTTP、HLS、UDP、RTP、File等多种流媒体协议播放、支持本地文件播放，支持本地抓拍、本地录像、播放旋转、多屏播放、倍数播放等多种功能特性，核心基于ffmpeg，稳定、高效、可靠、可控，支持Windows、Android、iOS三个平台，目前在多家教育、安防、行业型公司，都得到的应用，广受好评！

- EasyPlayerPro-Win：[https://github.com/EasyDSS/EasyPlayerPro-Win](https://github.com/EasyDSS/EasyPlayerPro-Win "EasyPlayerPro-Win")

- EasyPlayerPro-Android：[https://github.com/EasyDSS/EasyPlayerPro-Android](https://github.com/EasyDSS/EasyPlayerPro-Android "EasyPlayerPro-Android")

- EasyPlayerPro-iOS：[https://github.com/EasyDSS/EasyPlayerPro-iOS](https://github.com/EasyDSS/EasyPlayerPro-iOS "EasyPlayerPro-iOS")


### 有了EasyPlayerPro，为什么我们还要开发EasyPlayer-RTSP和EasyPlayer-RTMP？ ###

EasyPlayerPro虽然支持了几乎所有的流媒体协议，但是在很多场景和需求下面（例如：SDK包大小、自定义协议、数据加密），EasyPlayerPro的定制成本比较高，灵活程度没有EasyPlayer-RTSP和EasyPlayer-RTMP专用播放器的灵活程度高，EasyPlayerPro考虑的是通用性，而且专用播放器考虑的是定制性（例如EasyPlayer-RTMP将要定制H.265，这个是其他RTMP通用播放器都不能支持的），同样，在起播等方面，专用播放器更优！


## 技术支持 ##

- 邮件：[support@easydarwin.org](mailto:support@easydarwin.org) 

- QQ交流群：<a href="http://jq.qq.com/?_wv=1027&k=2IDkJId" target="_blank" title="EasyPlayer">**544917793**</a>

> EasyPlayer是一款非常稳定的全协议/全功能/全平台播放器，各平台版本需要经过授权才能商业使用，商业授权方案可以通过以上渠道进行更深入的技术与合作咨询；


## 获取更多信息 ##

**EasyDarwin**开源流媒体服务器：[www.EasyDarwin.org](http://www.easydarwin.org)

**EasyDSS**商用流媒体解决方案：[www.EasyDSS.com](http://www.easydss.com)

**EasyNVR**无插件直播方案：[www.EasyNVR.com](http://www.easynvr.com)

Copyright &copy; EasyDarwin Team 2012-2019

![EasyDarwin](http://www.easydarwin.org/skin/easydarwin/images/wx_qrcode.jpg)
