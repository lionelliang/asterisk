# asterisk
Asterisk configuration files

简介
Asterisk 是一个开放源代码的软件VoIP PBX系统，它是一个运行在Linux环境下的纯软件实施方案。这里配置文件在CenOS系系统搭建Astersik 11进行测试

核心应用
Asterisk 作为程控交换机PBX，Asterisk 可以被配置为一个 IP 或混合的 PBX 的核心：交换呼叫、管理路由、使能特性，以及通过 IP、模拟线路（POTS）、以及数字（T1/E1）的联系同外部呼叫链接在一起。
Asterisk 运行于众多的操作系统之上，诸如 Linux、Mac OS X、OpenBSD、FreeBSD 和 Sun Solaris。提供了一个 PBX 所能提供的所有功能甚至包括那些高级 PBX （也是昂贵的）的功能。
Asterisk 的构架是基于如下他点来设计：最大程度的灵活性、支持众多的 VoIP 协议、使用廉价的硬件便可融合到几乎所有的电话设备等。
Asterisk 作为网关 Gateway
Asterisk 用于呼叫中心，Asterisk 在全球范围范围内被呼叫中心采纳是基于其灵活性。呼叫中心和联系中心的开发者基于 Asterisk 构建了整套 ACD 系统。它也同时给现有的呼叫中心注入新鲜血液诸如：远程 IP 代理人功能、基于能力的高级路由、预测和海量呼叫等等。
Asterisk用于公共网络，互联网电话服务提供商（ITPS），区域电信业者(CLECS)以及甚至包括一线在职业者意识到使用 Asterisk 的开源通信的力量。基于 Asterisk 构建了功能服务器（Feature servers）、托管服务簇（hosted services clusters）、语音信箱系统（voicemail systems）、预付费呼叫解决方案（pre-paid calling solutions）等，这一切大大的降低费用并展现强大的灵活性。

Asterisk 如同使用拼装玩具或乐高套件来搭建通信应用。正因为如此它被称为“套件”或“开发平台”。Asterisk 包含所有的用于构建 PBX 系统、IVR 系统、可以说现实中的任何通信方案的构件。诸如如下：
1、各类 VoIP 协议的驱动。
2、各类 PSTN 接口卡和设备的驱动。
3、呼入路由和策略。
4、呼出生成和路由。
5、媒介管理功能（录音、播放、彩铃生成，等等）。
6、账号和账单的通话详单。
7、媒介转换（从一种媒介转换成另一种）。
8、协议转换（从一种协议转换成另一种）。
9、用于存取关系式数据库的信息的数据库集成。
10、使用标准互联网协议存取数据的网络服务集成。
11、存取公司目录系统的 LDAP 集成。
12、单方和多方呼叫桥接。
13、呼叫记录和侦测功能。
14、集成用于呼叫处理的 "Dialplan" 脚本语言。
15、基于 Asterisk 网关接口（AGI - Asterisk Gateway Interface） 的处理外部呼叫管理的程序或脚本的编程。
16、基于 Asterisk 管理接口（AMI - Asterisk Manager Interface ）的时间提醒和 CTI 集成。
17、第三方的各种语音和方言的语音合成（或者称“文本语音转换”）第三方的各种语音识别。
综合这些因素使得系统集成商或开发者能够快速生成一个语音使能系统。

Asterisk 系统集成者小可建造 IP PBX，大可构架大型媒体运营系统。
Asterisk具有硬件VOIP 的常用功能。
Asterisk能够支持多媒体，具有可编程功能。
Asterisk有友好的管理界面。
Asterisk需要的带宽，一般为：32KB/ 线路。也就是说每支持一条线路，只需要增32KB 的带宽，但是需要网络质量良好。
Asterisk可支持成千的 客户端。（需要板卡与带宽支持）
