
# snaillove-sharing-weekly
This is the weekly sharing in the company.

***
### #20 2016-05-28(Sat)

@木昜景页

1.[交互产品中的音效设计](https://zhuanlan.zhihu.com/p/20957023?refer=uxcoffee)

有没有听说过音效设计师？

2.[各种 XX Designer 到底有什么区别？](https://zhuanlan.zhihu.com/p/20797703?refer=lycheeorange)

想要知道各种 Designer 的区别么？

***
### #19 2016-05-21(Sat)

@木昜景页

1.[UX Coffee](http://ux.coffee)

UX Coffee 是一个专注于 UX 的交流分享的平台，现在有 Podcast 节目。

***

[@ifeegoo](https://github.com/ifeegoo)

1.[日本的传统颜色](http://www.nipponcolors.com)

第一次听说这个的是从李如一的播客中听说的，学设计的同学可以关注下，可以去找找颜色灵感。

2.关于灯泡的创意用途。

最近发现有人用灯泡做饮料瓶（果汁，奶茶），还有用作植物栽培的，比较有创意。

3.[创意T恤](https://mp.weixin.qq.com/s?__biz=MjM5ODE4ODMzMQ==&mid=2652762708&idx=2&sn=86dcc5eb44e44a7079c4725a2f23cef3&scene=1&srcid=0518ZeNRnfn8HsBSyezVDI7f&key=f5c31ae61525f82eebbb59dd063fd1262af2e8243f1d5f941c1e265d035269fe09571d08a595feb79964f0f063e891a0&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=KisPoK3MhgkLL%2BJpIUpUuHYuXvKjH5Nh9%2Fo%2BeptzTrlUY3Xu3Yv0BIeN59uVuL07)

去国外旅游，免不了语言不通，如何更好的表达自己的想法，我们可以看看这个创意T恤。

4.[QQ空间点赞的那些事](https://isux.tencent.com/qzone-infographic-video.html)

我们平时基本上都会用QQ空间，有兴趣看看背后点赞的那些事情否？

***

### #18 2016-04-16(Sat)


***
[@misparking](https://github.com/misparking)

1.[little big shots](http://www.nbc.com/little-big-shots)

***

[@JackWaiting](https://github.com/JackWaiting)

1.[向“黑曼巴”致敬！](http://sports.qq.com/a/20160414/039870.htm)

***
[@ifeegoo](https://github.com/ifeegoo)

1.[向用户征询iOS授权的五种常见设计模式](http://beforweb.com/node/766)

2.程序员将来的道路应该如何发展》

[程序员，向左或向右](http://ryantang.me/blog/2016/02/25/left-or-right/)  
[涅槃重生:我的技术转管理之路](http://blog.devtang.com/2015/12/18/from-dev-to-manager/)

***

### #17 2016-04-9(Sat)
***
[@misparking](https://github.com/misparking)

1.[你的思考真的用上大脑了吗？](http://www.360doc.com/content/16/0404/10/20284327_547722773.shtml)  
大脑是用来思考的，从小我们都被如此教育，以至于这条准则近乎于常识。然而，一旦脱离教育体系，无人指导，需要靠自己去甄别信息、学习知识的时候，这种常识却成为了思维底层最大的盲区。

2.[几个帮程序员减压放松的网站](http://www.techug.com/website-make-you-relax)  
[Calm](http://www.calm.com/)属于同类型中比较火的网站了，站如其名，「平和」，通过自然的图像（阳光下的暖流、淙淙的小溪等）与缓缓的音乐，帮你在短时间内放松下来，并且有手机客户端可以下载。
***
### #16 2016-03-26(Sat)

@木易景页

### Quartz Composer & Origami 调查分析

#### 1.什么是Quartz Composer？

Apple自己的定义：

Quartz Composer is a development tool for processing and rendering graphical data. Its visual programming environment lets you develop graphic processing modules, called compositions, without writing a single line of code. Quartz Composer is also a framework that lets you programmatically access, manage, and manipulate compositions created with the development tool. This document, however, is a guide to the Quartz Composer development tool supplied in OS X v10.5. By reading this guide, you’ll get an introduction to using the Quartz Composer editor and find out how to use it to create a composition. You’ll also see how to use compositions as screen savers and in QuickTime movies.

WiKi上的定义：

Quartz Composer is a node-based visual programming language provided as part of the Xcode development environment in Mac OS X for processing and rendering graphical data.

QC designer社区总结：

It is an Apple product used by designers & animators to create animations and prototypes. It also has wide use by VJs for live visualizations, among other uses. It has been around for a number of years but has recently had a resurgence in the software world following news of its role as a prototyping tool at industry giants Apple and Facebook.
 
To create a composition, a user uses the Editor to connect a number of patches with “noodles” that sends a signal from one patch to another. The end result is displayed in the Viewer. Changes you make in the Editor immediately appear in the Viewer, which makes QC particularly well-suited for creating interactive prototypes.


#### 2.Quartz Composer的实现模式？

简单来说可以把 Quartz Composer 想象成图形化的 jQuery，我们只需把封装好的代码模块（patch）组装起来，设好参数，便能生成各种动态效果。由于是个编程工具，入门 Quartz Composer 需要点编程基础，最好会写 JavaScript 方便实现复杂的逻辑（初期对各种 patch 不熟悉更常会用到）。
Quartz Composer 的基本原理就是把各种封装好的代码模块拼接起来。

自定义patch的特性导致了插件的存在。
Quartz Composer Custom Patch Programming Guide provides instructions on creating your own patches that you can then use in the Quartz Composer development tool.


#### 3.什么是Origami？

JQC and Origami are frameworks for QC that make it easier to use for interaction design. jQC is an open source framework that was built with help from this community and first released here, on this site. Origami is a framework developed by Facebook that includes many helpful bugfixes for QC as well as a number of patches. Both frameworks can be installed at the same time, and are complimentary to each other.

Origami 和JQC都是QC的插件。


facebook自己的解釋定义：


Origami is a free tool for designing modern user interfaces. Quickly put together a prototype, run it on your iPhone or iPad, iterate on it, and export code snippets your engineers can use. 

We created Origami to help us design and build many of our products at Facebook, including Instagram, Paper, Messenger, Slingshot, Rooms, and Groups. We’re excited to see what people make with it.


#### 4.Origami＋Quartz Composer作为交互软件与同类型相比有何优势 ？

优缺点比较：

https://www.zhihu.com/question/24134539

https://www.zhihu.com/question/26881294

网友机灵比较：

https://www.zhihu.com/question/26717124


#### 5.Origami的不足？

Origami可以导出iOS、Android、Web端的动效代码，然而基本上不能直接调用。 
在关于逻辑、ui布局方面上还是需要手工编码。

参考链接：
https://www.zhihu.com/question/33407844

导出代码并不是为了提高设计师与工程师之间的沟通效率，Facebook自己也表示这只是为了让动效在不同平台上达到统一。

参考链接：
https://medium.com/facebook-design/introducing-origami-live-and-origami-2-0-a68116294e65#.vt83dshh1


#### 6.Origami如何运用在生产流程？

Axure 搭建App整体框架，Origami＋Quartz Composer表现个别动效。


#### 7.综合总结评价

通过综合比较1.可呈现效果、2.开发效率、3.入门学习成本这三点，QC＋Origami的组合还是挺适合初级阶段的。
但随着追求的效果逐步升高，学会编码是必须的。当对编码上手之后，同时追求更好的交互效果，不妨可以尝试使用Framer 之类的编程交互设计软件。


#### 8.相关链接

资源：

Quartz Composer：在苹果的开发者网站下找到 Graphics Tools for Xcode。
Origami：http://www.facebookorigami.cn/

论坛：

知乎：https://www.zhihu.com/question/20956344

QC designer社区：http://qcdesigners.com/index.php/forums/topic/2/new-to-quartz-composer-start-he


### #15 2016-03-12(Sat)

***
[@misparking](https://github.com/misparking)

1.可见光无线通信  
可见光无线通信又称“光保真技术”，英文名LightFidelity（简称LiFi）是一种利用可见光波谱(如灯泡发出的光)进行数据传输的全新无线传输技术，由英国爱丁堡大学电子通信学院移动通信系主席、德国物理学家HaraldHass（哈拉尔德·哈斯)教授发明。
LiFi是运用已铺设好的设备(无处不在的LED灯)，通过在灯泡上植入一个微小的芯片形成类似于AP(WiFi热点)的设备，使终端随时能接入网络。该技术通过改变房间照明光线的闪烁频率进行数据传输，只要在室内开启电灯，无需WiFi也便可接入互联网。  
TED视频：[Li-Fi网络传输技术-详细介绍](http://v.qq.com/boke/page/f/0/9/f0186kxf2y9.html)

2.[怎样用互联网思维追到女神？](http://www.niaogebiji.com/article-9961-1.html)  
结合互联网思维，择偶模式就像做产品，一个黄金公式通用，即G=M*R*T。

3.[揭秘阿里巴巴人力资源体系：牛逼的团队是如何建立的？](http://www.admin5.com/article/20160309/650762.shtml)  
1、阿里巴巴是怎么面试的? 2、阿里巴巴闻味官是怎么回事?  3、阿里巴巴职级怎么设置?...

***

[@ifeegoo](http://github.com/ifeegoo)

1.关于跑步

在跑步机上跑步推荐用运动耳机，同时可以听听音乐，但是音乐要注意把握节奏，可以参考的节奏：[推荐的几首歌曲](https://mp.weixin.qq.com/s?__biz=MjM5NzM0NjcwMQ==&mid=402649922&idx=4&sn=e3f841d29810e7d216f32f0aa282877e&scene=1&srcid=0105U0eyAsJ64Ow4UKwQb4Ql&key=710a5d99946419d9c15492e8eeb45724d96e952bcfe43d4b790b4cb805e550f90eab6c829416756d718e86afc2f47bc8&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=uQ6KYW%2F0E0e29kr%2F4M1UvxbBt4uzCbVSkzIZi78Ri3%2F5Tw93XjBvXVXPzYvNq6UZ)，另外我们可以关注一个公众账号：running_guide。

2.[这10个英文句子太魔性了，简直要上天啊！](https://mp.weixin.qq.com/s?__biz=MjM5Njk5NTE2Mg==&mid=406310389&idx=1&sn=a4e8f060bcbc1e59a07f6bd4918d5990&scene=1&srcid=0217jqyj0SJs8b5pJVBXz1gD&key=710a5d99946419d939297e0e17a1a7b74a09e78acc839d21cbe6933b50afeb56003160b94f59a8bc803cdca68ff78ab5&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=R78ZO8Dg%2BnwLU%2Fz7iuOWY4c0ja0VIlOFzh%2FJxUrD80WPThgY9PmWJDG9F%2BBa%2Ba9Y)

Can you can a can like a canner cans a can?

3.[亲戚问每月多少工资时，程序猿该如何回答？](https://mp.weixin.qq.com/s?__biz=MzA3NzM0NzkxMQ==&mid=404060683&idx=1&sn=0008cd1284bca41b457879037a72efff&scene=1&srcid=0312InCjZbQLAd0Pr1GTRRCK&key=710a5d99946419d9f017d79806bb9f8ba7fdfb11c9def472bfad80e75265310cf5ec8d4d8a3728a9f31cc33473555c66&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=R78ZO8Dg%2BnwLU%2Fz7iuOWY4c0ja0VIlOFzh%2FJxUrD80WPThgY9PmWJDG9F%2BBa%2Ba9Y)

在回答别人问题的时候。不一定要告诉他真实的答案。很多时候，告诉他一个符合他想象的答案，可能效果更好。因为不是每一个人，都有勇气去接受他不懂的东西，愿意去理解他未知的领域。对绝大多数人来说，更倾向用已有的想法，去解释看到的一切。这些人极度自负。固有的观念，在他心中围成了牢不可破的城堡。

4.[想和你一起在这样的童话小镇，只闻花香，不谈喜悲](http://zixun.html5.qq.com/wechathot/article?ch=060000&tabId=wxtab1&tagId=MttWXSource&docId=2784510137&sourceType=&showAttach=true&clientWidth=320&video_ch=003902&sc_id=NIEw8fA)

美到炸的通话小镇，开来一睹芳容！

***
[@chenyunxuan](http://github.com/chenyunxuan)

1.[最新免费帆樯神器：灯笼Lantern下载及使用教程](http://www.iyaxi.com/2015-11-17/732.html)

众所周知，在天朝有一个伟大的GFW（防火长城）保护着我们的网络环境，如果你想看看墙那边的风景，就必须想办法翻过去，然而一批批造福网民的软件倒下了，帆樯变得越来越难，然而最近却传来了一个好消息，一款免费强大的帆樯软件——Lantern横空出世。（2016.1.5新增Windows、Mac、Linux、Android四个版本的Lantern蓝灯）

2.[纸飞机](http://www.ishadowsocks.com)

另一款翻墙软件。

3.[Google Map + VR游戏：Ingress](http://www.godeyes.cn/html/2014/12/15/google_earth_15914.html)

想象一下利用街道作为游戏场景？

***

[@JackWaiting](http://github.com/jackwaiting)

1.[除了AlphaGo，谷歌还有这10个黑科技让你震惊](http://mt.sohu.com/20160311/n440109629.shtml)

Google X Lab 各种炸天的项目。

***

@shuyao

1.[吓傻了！这家德国公司的仿生黑科技，即将颠覆自然！](https://mp.weixin.qq.com/s?__biz=MzA5NjIzNjgxNw==&mid=404059437&idx=4&sn=244cf1645a783a8ea809b1cd9544d502&scene=0&key=710a5d99946419d9094f21d0dc15befa7e39eba592eecc6785e4338c34f21c0b2f3e6fe6b9379923dd55efdef770b484&ascene=0&uin=OTg2NTM0ODYx&devicetype=iMac14%2C3+OSX+OSX+10.10.5+build(14F1605)&version=11020201&pass_ticket=2tsPMJs5foOA2T0qqFFim0x2UD2T8%2BJ9WlO6%2FHx3C5CFP8XHzJWoJpybh1jpcSzc)

德国著名气动公司FESTO，各种叼炸天的仿生黑科技。

2.[【学摄影】摄影中的前构图和后构图](https://mp.weixin.qq.com/s?__biz=MzA5NjIzNjgxNw==&mid=404059437&idx=2&sn=3ab9cb25799eaf22db72f37001184161&scene=0&key=710a5d99946419d9d82bbe87d7b0e9f7e6e926a5b5f9019f6ea5948b0780971d319c6f5e1a243bfa98236195c45203a5&ascene=0&uin=OTg2NTM0ODYx&devicetype=iMac14%2C3+OSX+OSX+10.10.5+build(14F1605)&version=11020201&pass_ticket=2tsPMJs5foOA2T0qqFFim0x2UD2T8%2BJ9WlO6%2FHx3C5CFP8XHzJWoJpybh1jpcSzc)

想要拍摄有逼格的照片吗？

***

### #14 2016-03-05(Sat)

***
[@misparking](http://github.com/misparking)

1.[GIPHY](http://giphy.com/)

关于动态图片的搜索引擎，哪些喜欢发动态图的同学们，有福了！

***
[@ifeegoo](http://www.ifeegoo.com)

1.[哪些令人印象深刻的特殊的艺术品或艺术形式？](https://www.zhihu.com/question/29635624/answer/88511044)

可爱的卡通食物，盐画，剪纸服饰，绘鱼，理发画，海底兵马俑，要不要一窥究竟？

2.[Color Run](http://www.thecolorrun.com.cn/)

彩色跑，要不要搞一把？

3.[TIFO](https://www.youtube.com/watch?v=cXIBYpqvdsw)

喜欢看足球的同学，一定看过球场上巨大的横幅，这有一个专门的名字，叫做TIFO。

4.[泰国的感人广告](https://www.zhihu.com/question/19869078)

泰国的广告，尤其是感人的广告，这些年来比较火。大家可以关注下。

[实例1](http://mp.weixin.qq.com/s?__biz=MzIwMzE0ODMwMA==&mid=401528821&idx=3&sn=6552348cd4d79bb4ab19182d6d5791d9&scene=0#wechat_redirect)

[实例2](https://mp.weixin.qq.com/s?__biz=MzA5OTM0MzU5Mg==&mid=402847629&idx=4&sn=7e3d0621e836b722964731b7071044e4&scene=1&srcid=0304l483r2JfMl4B8Gv19sD6&key=710a5d99946419d9b799a4a74121d6c2707584b253a6ccf3bf15ea0031877d8b47b6d578a0bd413be6bf4a8363ebb9dd&ascene=0&)

***

[@chenyunxuan](http://github.com/chenyunxuan)

1.[泡泡跑](http://www.bubblerun.com/)

在满是泡泡的路上跑步是怎样的一种感觉？

***

### #13 2016-02-27(Sat)

***
@[ifeegoo](http://github.com/ifeegoo)

1.[懒人癌的福音之椅子](https://mp.weixin.qq.com/s?__biz=MzA5NjM2MTEzNw==&mid=402673978&idx=1&sn=bdab3d18462221658f652a0a30ef4c44&scene=0&key=710a5d99946419d9a6833e20da47f282cb9f08d0bbd30e4b3a4a4797a57ae3e9a4afd7e9a41b30770ec29d256804f529&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=50TQcgJf4akWNofh6tTNJ8O68KeRv9ks1fEsXS4BvGPrsr51fZiNT%2Bn36WDLsGYm)

开完会之后，你是否有手动将椅子归还到原处？

2.[电气行业的"强迫症"](https://mp.weixin.qq.com/s?__biz=MzA5NTgwNzkxMQ==&mid=485113704&idx=4&sn=487cdc66ba36ebde10f1b0c510ab07b1&scene=2&srcid=0222MZhVQbdHDD1rfpFHfrVY&key=710a5d99946419d9f07c82e7ff69e56f1346212bce29aee3ff84069502d6b8c504867db3a41724544c4006b842b0339d&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=50TQcgJf4akWNofh6tTNJ8O68KeRv9ks1fEsXS4BvGPrsr51fZiNT%2Bn36WDLsGYm)

你看过这么美的布线吗？

3.[如何挣脱电缆扎带？](http://v.youku.com/v_show/id_XNzA0NjQ2MzA0.html?from=s1.8-1-1.2)

有没有看到那些电影或者现实中用来捆绑人手脚的扎带？这个就是电气行业常用的电缆扎带。

4.[德国小人国](https://mp.weixin.qq.com/s?__biz=MjM5NjAwMjEwMA==&mid=405460706&idx=1&sn=a103fb604021de02781182a43f8e181d&scene=0&key=710a5d99946419d990448906a65e877a8b33ee9c650f802eaa37ae9a64dd6cabfc9a1473dbb8083917bb59aa7c48af9d&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=50TQcgJf4akWNofh6tTNJ8O68KeRv9ks1fEsXS4BvGPrsr51fZiNT%2Bn36WDLsGYm)

一对德国的双胞胎花了15年2000万人民币打造的这样一个“小人国”，赶紧去看看！

5.[从87.5kg故意吃成122kg，再减回86.3kg…美国网红告诉你减肥真的很难！](https://mp.weixin.qq.com/s?__biz=MjM5OTY1MDMxMg==&mid=401798221&idx=1&sn=5f3551d27f33862e14a7ecdfa97bbc74&scene=0&key=710a5d99946419d978099268c5b636c73046644248821a3b3e7c95e0ea8a0c210cc222fa8ef4d1bdc299450ff15fdd7f&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=50TQcgJf4akWNofh6tTNJ8O68KeRv9ks1fEsXS4BvGPrsr51fZiNT%2Bn36WDLsGYm)

你要不要试一试？

6.[世界历史动态地图](http://h5.qzone.qq.com/ugc/share?ticket=&subtype=0&srctype=&sk=&blog_photo=0&appid=311&ciphertext=43699A39C08B8F009730A2D67C08473528DB07E502BD43DD7E500100E8AA8AECEED06847ACA974C0D356595A28D5792C47AE3D5BC546868F52A9A3A09B9D6E2A&g_f=&_wv=1&from=timeline&isappinstalled=0)

这个视频，一定会震撼到你！

7.[华为发布首款笔记本电脑MateBook](https://mp.weixin.qq.com/s?__biz=MTQzMjE1NjQwMQ==&mid=405805928&idx=1&sn=798c770573f8411e358f6b9609333c95&scene=0&key=710a5d99946419d92b826dedd2fb9c670114bfd1820adb323193904ec83bc789b2cd8ac851c48446bc090f5ff41d6b07&ascene=0&uin=ODA0NTUxMDAw&devicetype=iMac+MacBookPro11%2C3+OSX+OSX+10.11+build(15A284)&version=11020201&pass_ticket=50TQcgJf4akWNofh6tTNJ8O68KeRv9ks1fEsXS4BvGPrsr51fZiNT%2Bn36WDLsGYm)

华为已经开始进军笔记本行业了。

8.[新型混合运动：足球高尔夫](http://jandan.net/2013/04/26/footgolf.html)

足球和高尔夫的结合。

9.[新型混合运动：乒乓足球](http://v.youku.com/v_show/id_XMTQ2NDAzMzY1Mg==.html?from=s1.8-1-1.2)

像打乒乓球一样打足球。
***

### #13 2016-02-27(Sat)

***

1.[@ifeegoo](http://github.com/ifeegoo)

1.[iOS设备的系统时间bug](http://www.pingwest.com/fools-guide-to-iphone-1970-brick-bug/)

将iOS设备设置成1970之前的时间，就会变砖。

2.[天气太冷！ iPhone 手机就这样默默地自动关机了](http://www.pingwest.com/apple-iphone-winter-shutdown/)

为什么天气太冷，iOS 设备为什么电池有问题？

3.[移动 App 有哪些优秀的、令人难忘的引导页设计？](https://www.zhihu.com/question/25684387)

引导页对于一个APP来说，可有，可无。

4.[微软幻想中的 NFL，和现实中 NFL 之间的区别……](http://www.pingwest.com/microsoft-nfl-hololens-surface/)

又一款看起来叼炸天的虚拟现实应用场景。

5.[我们的精神角落](http://v.youku.com/v_show/id_XMTQ3MTc2MTg2MA==.html)

豆瓣首支广告。

***

### #11 2016-01-23(Sat)

***
@Holson

1.[有哪些相貌平凡的人穿出衣服品味的例子？](https://www.zhihu.com/question/27936753/answer/81327730)

真的是人靠衣装，美靠靓妆。程序猿们一定要好好学习了！
***

[@arrfu](http://github.com/arrfu)

1.[2015牛人完美瞬间大合集](http://url.cn/2FDtyu0)

2015年牛人行为大放送！看得人手心直冒汗！

***

[@ifeegoo](http://github.com/ifeegoo)

1.[博客思听中文有声书摘](http://www.bookast.com/)

换一种方式看书，真的很不错！

2.[2015华语电影泪奔混剪《十字路口》](http://mp.weixin.qq.com/s?__biz=MzIyNzA2MjcyOQ==&mid=401679600&idx=3&sn=141bd3190dbb1eae1e2d28d7157db03e&scene=2&srcid=0117V8A48A80haDT3a1mKAa6#wechat_redirect)

非常不错混剪，电影的片段重新组合成了一个完整的故事，关于爱情，关于家庭，关于理想，关于每一次选择。

3.[心灵魔术师 Derren Brown](https://www.zhihu.com/question/39408533/answer/81594114)

现场直播俄罗斯轮盘赌，彩票预测中奖！

4.[徒手攀岩大师 Alex Honnold](https://www.zhihu.com/question/39408533/answer/82907604)

Free Solo Climbing：无辅助、无保护、单人徒手攀岩。被称为十大极限运动之首，死亡率超过50%！

***

### #10 2016-01-16(Sat)

***
[@chenyunxuan](http://github.com/chenyunxuan)

1.[让你的每个屏幕上都有一颗美丽的地球 | 馒头地球 & Earth Live](http://www.tuicool.com/articles/riYJRfA)

想不想在你的手机、平板、电脑上实时查看地球的状态？赶紧来试试吧。

2.[了不起的挑战：啥？让我穿裙子！](http://www.wandoujia.com/eyepetizer/detail.html?vid=4816)

这只是一个广告，但是你看出来了这是个什么广告吗？

***

@Holson 

1.[怎样快速有效地分辨出值得追和果断弃的日剧？](https://www.zhihu.com/question/39414582/answer/81687774)

大家关注美剧比较多，但是有了解过日剧吗？这篇让你进一步了解日剧。

***

[@arrfu](http://github.com/arrfu)

1.[搞笑剪辑：神人居然这样演绎“仙剑奇侠传我彻底醉了”](http://url.cn/ds80WU)

你懂的。

2.[推荐二十七部近让你憋着尿看完的电影](http://url.cn/YqDycS)

值得你细细品味的电影！

### #9 2015-12-19(Sat)

***
[@ifeegoo](http://github.com/ifeegoo)

1.[《人生七年》](http://www.douban.com/search?q=%E4%BA%BA%E7%94%9F%E4%B8%83%E5%B9%B4)

这是一个非常真实的纪录片，来看看英国的人的一生是怎么度过的。想知道最终有多少人改变了自己的人生，过上了更好的生活吗？

2.[叔丁基锂](http://baike.baidu.com/view/6480644.htm)

最近清华大学实验室发生了一起爆炸，很多人在知乎上讨论[https://www.zhihu.com/question/38641134](https://www.zhihu.com/question/38641134)，大部分人都认为是“叔丁基锂”惹的祸，快来看看这个是什么吧。

3.[致幻剂](http://baike.baidu.com/view/654039.htm)

澳大利亚电视节目《60分钟》报道，2013年，16岁的澳大利亚少年Preston Bridge服用了合成致幻剂后出现飞翔的幻觉，跳楼身亡。他的父亲布里奇（Rod Bridge）为了追查致幻剂的来源，来到中国合肥，以澳洲黑帮的身份卧底一家致幻剂制造商，称要采购毒品。并在电视台制片人的帮助下，全程偷拍。节目称，在中国，这些合成致幻剂打着“研究用药”的旗号，因此从严格意义上来说并不算非法。而一旦一种致幻剂被法律禁止，就会马上改变化学成分，制造出新的致幻剂逃避法律。实际上，在中国严格的毒品控制之下，“所有只要是用于中枢、产生中枢性变化的、非医疗性的用途的药，不管它的化学结构是什么东西，都是违法的”。然而，更现实的问题是，近两年，“在我国每年新发现的吸毒人员大概有60%至70%左右都是吸食新型毒品”。北京安定医院医务科主任、中国合成毒品防治专家委员会委员盛利霞告诉新浪《新闻极客》，合成致幻剂最大的危害就是出现幻觉，导致跳楼、暴力等行为。

[http://news.sina.com.cn/c/zg/2015-09-16/doc-ifxhytwu5660750.shtml](http://news.sina.com.cn/c/zg/2015-09-16/doc-ifxhytwu5660750.shtml)

***

[@misparking](http://github.com/misparking)

1.[智能迷你花园](http://www.leikeji.com/article/4090)

能想象下，在家里房间中整一个迷你花园，这是一种怎样的感觉？

2.[高逸峰《从头再来》](http://v.youku.com/v_show/id_XNDM1MTA2Njky.html?from=y1.2-1-86.3.3-2.1-1-1-2-0)

只不过是从头再来，如果是你，有这样的豪迈气质否？

***

[@chenyunxuan](http://github.com/chenyunxuan)

1.[超强执行力](http://www.wandoujia.com/eyepetizer/detail.html?vid=1806)

你的执行力强吗？有他强吗？

2.[强迫症的理想归属](http://www.wandoujia.com/eyepetizer/detail.html?vid=1860)

现代社会，每个人或多或少的都有些强迫症，但是如果是一个严重的强迫症患者，该如何是好呢？

***
### #9 2015-12-05(Sat)

***

[@subvin](http://github.com/subvin)

苗族出身的帅小伙，分享你所不知道的一些关于苗族的奇闻异事。

***

@木昜景页

### 1.[如何实现一份设计稿支持多个尺寸并支持iPhone 6 / 6 plus](http://mp.weixin.qq.com/s?__biz=MzA4NDI5MjI5Nw==&mid=401149029&idx=1&sn=4734ca2ba3850bc0c8dbac48f4ce6da6&scene=0#wechat_redirect)

不管是Android，还是iOS，适配的确都是一个问题。

***

[@arrfu](http://github.com/arrfu)

### 1.[生活小技能](http://toutiao.com/i6211655782518653442/?tt_from=mobile_qq&utm_campaign=client_share&app=news_article&utm_source=mobile_qq&iid=3312691405&utm_medium=toutiao_android)

这里有你生活中没有留意到，可能让你眼前一亮的生活小技能。

### 2.[五个魔术般的火焰实验](http://url.cn/kSKNZ0)

还记得以前上化学课，做的实验吗？我们来看看更加诡异的火焰实验。

***

[@misparking](http://github.com/misparking)

### 1.[打造走心方案](http://www.meihua.info/a/65287)
广告大师奥格威看来，“创作成功的广告是一门手艺，一部分靠灵感，但是基本上是靠知识和勤奋。”这同样适用于一切文案工作，把玩文字需要天赋，但知识和技巧能弥补并拓宽一个人的创造才能。

### 2.[无针验血](http://tech2ipo.com/10021344)
最近，Google 公司提交了一款「无针验血」的专利申请。该申请为一种腕部佩戴或手持装置，可以在指尖和身体的其他部位抽血。

### 3.[上班神器-机械手臂](http://tech2ipo.com/10021312)
长期坐在办公室里对着电脑的你，不知不觉已经驼背了吧？你那颗沉重的脑袋在站立时本来会有整个身体来支撑，可是当你坐在电脑前，身体不由自主向前倾斜，支撑头的就只有你可怜的肩膀和脖子了。这就是为什么当你在电脑前面坐了一天之后，肩膀和脖子都会十分酸痛；明明什么体力劳动都没干，每天下班回到家里却觉得像是被人打了一顿一样。
***

### #8 2015-11-15(Sun)
***

[@misparking](http://github.com/misparking)

### 1.[大数据告诉你，电商会把假货发给谁？](http://tech.qianlong.com/2015/1112/87940.shtml)
内幕：你在网上买件大牌化妆品，在订单提交→发货之前，系统会查询分析你在全平台的购物数据(大数据内部共享)：购买均价，常购品牌，退货率。

### 2.[手机让人变得冷漠？](http://tech2ipo.com/10020545)
有人认为：技术发展，尤其是智能手机的出现，已经破坏了我们原有的社会交往方式，人们彼此不再紧密联系在一起，取而代之的是花费大量时间与我们的每一个电子设备互动。
可能以上文字讲出了你的心声，不过你所看到的不一定就是事实。

### 3.[全自动停车场](http://mt.sohu.com/20150427/n411971682.shtml)
[相关报道视频](http://www.iqiyi.com/w_19rs2zcgq5.html)
寻找停车位一直是现代都市人最头疼的事情，怎样做到既节省空间又能保证停车安全呢，德国朋友给我们做出了范例。

### 4.奥巴马的[Facebook](https://www.facebook.com/potus/?fref=ts)和[Twitter](https://twitter.com/WhiteHouse)
继2015年五月份开设了个人 Twitter 账号，奥巴马总统在11月份正式开通个人Facebook,他的 Facebook 时间线上记载了他的自传，上面有从 1992 年他与米歇尔夫人结婚直到他 2009 年成为第 44 位美国总统的宣誓仪式的照片。比起近期照片，老照片吸引了更多的赞和评论。

***
[@arrfu](https://github.com/arrfu)
### 1.[四轴飞行器灵活的运动性能](http://v.youku.com/v_show/id_XNzMyNjc2NjAw.html)
在TEDGlobal的机器人试验室里,拉菲洛·安德烈展示了如运动员一般思考的四轴飞行器,四轴飞行器能根据被输入的运算法则灵活解决...

***

### #7 2015-10-31(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

#### 1.一周智能硬件汇总

1° [Polaroid Socialmatic](http://www.leiphone.com/news/201510/Ui2jNJBL5pexgDKs.html)  
Polaroid Socialmatic：长得像Instagram Logo的相机。  
京东购买链接：[http://item.jd.com/1455434.html](http://item.jd.com/1455434.html)
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/5629f29754025.jpg)  
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/5629f35d519c9.jpg)  
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/5629f35db602d.jpg)

2° [Skarp](http://www.leiphone.com/news/201510/hyNQsndk8PGCANj8.html)  
Skarp：号称全球第一款激光剃须刀，而它引发的史上最大众筹撕逼大战。  
Indiegogo：[https://www.indiegogo.com/projects/the-skarp-laser-razor-21st-century-shaving](https://www.indiegogo.com/projects/the-skarp-laser-razor-21st-century-shaving)  
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/562a6e5f8b718.png)

3° [手指一指，灯泡亮起](http://www.leiphone.com/news/201510/ZQldKz8ZF5483fhL.html)  
用手势控制灯泡，像魔法一样神奇。其实你也可以做到，还不赶紧来看看是什么鬼？  
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/562d96ce776f4.gif)

4° [ZipChip](http://www.leiphone.com/news/201510/7Z8Rutxb55CLXK40.html)  
ZipChip：这是一款飞碟玩具，看起来还是很酷的。  
Kickstarter：[https://www.kickstarter.com/projects/214846388/zipchip-the-new-way-to-play](https://www.kickstarter.com/projects/214846388/zipchip-the-new-way-to-play)  
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201510/5625e9dd81313.png)

5° [NFC Ring](http://36kr.com/p/5038828.html)  
想不想拥有一个魔戒？  
![](http://img1.cache.netease.com/catchpic/6/68/683C1DE3F581999E4322A3540223E24D.jpg)

6° [Hoverboard](http://36kr.com/p/5038988.html)  
看过电影《回到未来》里面的高科技了吗？现在磁悬浮滑板已经问世了，还不赶紧来瞧瞧？  
Kickstarter：[https://www.kickstarter.com/projects/142464853/hendo-hoverboards-worlds-first-real-hoverboard](https://www.kickstarter.com/projects/142464853/hendo-hoverboards-worlds-first-real-hoverboard) 
![](https://ksr-ugc.imgix.net/projects/1415522/photo-original.jpg?v=1413688992&w=1536&h=1152&fit=crop&auto=format&q=92&s=1d25ba69864f0973bbc462bada38fcc7)

7° [OpenROV](http://36kr.com/p/5039113.html)  
OpenROV：帮你探索水下世界的机器人！  
Kickstarter：[https://www.kickstarter.com/projects/openrov/openrov-trident-an-underwater-drone-for-everyone](https://www.kickstarter.com/projects/openrov/openrov-trident-an-underwater-drone-for-everyone)
官网：[http://openrov.com/](http://openrov.com/)  
Github：[https://github.com/OpenROV](https://github.com/OpenROV)  
![](http://e.36krcnd.com/nil_class/05de983a-fbdf-4bc7-8be0-a32ef04bb97d/8105e5ee3abf271df36c1bddbdd43903_original.png!heading)

8° [magic Leap](http://www.ifanr.com/575230)  
magic leap：Google重金投资的MR公司，来看看他们将要做的令人惊讶的内容吧。
![](http://images.ifanr.cn/wp-content/uploads/2015/10/64f1122c5adb09a87d35f86cab7b18c1.gifheading.gif)

#### 2.[Splittable](http://36kr.com/p/5039085.html)  

如何更好的管理合租的费用支出，这是一个问题。

#### 3.[The quick brown fox jumps over the lazy dog](https://en.wikipedia.org/wiki/The_quick_brown_fox_jumps_over_the_lazy_dog)

看到上面这段话，是不是觉得这是一句简单的英文句子。但是它是最短的一句包含全部26个英文字母的有意义的句子。大家所能够见到的是在字体文件中。

![](https://upload.wikimedia.org/wikipedia/commons/6/65/Kfontview.png)

#### 4.密码管理问题

现在网络是非常的不安全，自己的各大网站的密码很有可能就被别人盗取。如果你所有的账号都用同一个邮件/ID注册的话，一旦你的一个网站的密码被别人盗取的话，其他的可能都会被别人盗取。大家可以在“社工库”网站上查询自己的曾经的密码是否有被泄漏。也推荐大家自己建立一套自己的密码管理系统。每一个网站的密码都是不一样的，但是你看到这个网站，你就会知道是哪个密码。  
社工库网站举例：[http://www.shunmay.cn](http://www.shunmay.cn)

#### 5.[64k Intro](http://blog.csdn.net/shifuwawa/article/details/4643689)

每年世界上会有64k Intro[64k大小的动画]的比赛。64k动画：只有64k大小的文件，播放出来的动画。有的狂拽酷炫，有的可以播放一两个小时。基本上是通过汇编语言操作显卡实时渲染出来的动画。
视频举例：[http://v.youku.com/v_show/id_XMTI2MDkyOTg0MA==.html](http://v.youku.com/v_show/id_XMTI2MDkyOTg0MA==.html)

***

[@misparking](http://github.com/misparking)

#### 1.[原来我们看到的地图错得离谱?](http://dy.qq.com/article.htm?id=20151028A0237R00)

世界地图我们都看过，但是我们有怀疑过他上面标注的尺寸是否靠谱吗？其实有些地方不是你想象的那样子的。  
[网上曝光常用世界地图“错得离谱” 专家反驳(图)](http://www.ahfeixi.com/article-179622-1.html)

#### 2.[坚果影视](http://www.jmgo.com/index.html)

想要一款背包里的电影院产品吗？来看看这个被任泉、李冰冰、黄晓明等明星投资的产品吧。

#### 3.无人驾驶技术现状
[视频](http://www.bilibili.com/video/av2525904/)
[图文](http://www.100tmt.com/news/news_3581.shtml)

无人驾驶技术一直被热捧，但是究竟什么时候，才能够“上线”呢？

***

@[chenyunxuan](http://github.com/chenyunxuan)

#### 1.[有道云笔记小技巧](http://note.youdao.com/web-clipper-chrome.html)

如何更好的保存网络书签，这是一个好的问题。看看有道云笔记如何帮助你。

#### 2.推荐两个微信公众账号。

名称：科技美学  
ID：kejimx  
说明：「科技美学」是移动端第一科技新媒体,那岩 每天用语音为你解读前沿科技。  
点评：独立公正的第三方科技测评。

名称：e袋洗  
ID：ewashing  
说明：专业、便捷、高性价比的的洗衣品牌，手机下单，取送到家。  
点评：对于想要洗鞋子的我来说，是一个不错的服务！

***

@木昜景页

#### 1.[枯燥无味的心理学](http://read.douban.com/reader/ebook/2190088/)

大家都喜欢谈论心理学，但是心理学是你想象的那么有趣，那么神奇吗？

#### 2.[汉尼拔](http://baike.baidu.com/subview/18508/10356387.htm)

《汉尼拔》（Hannibal）是由美国NBC电视台根据自托马斯·哈里斯经典小说《红龙》改编。由布莱恩·福勒主创，麦德斯·米科尔森、休·丹西主。
讲述了FBI特别探员威尔·格雷厄姆以及表面上是优雅心理医生，实际上是食人魔连环杀人犯的汉尼拔·莱科特博士的故事。他们的关系从一开始的亲近到后来的微妙、疏离，着实令人胆寒[1]  。

***

@shuyao

#### 1.[magic leap/ 3D纹身](http://mp.weixin.qq.com/s?__biz=MjM1ODIzNTU2MQ==&mid=401153834&idx=1&sn=ff8f0e9afb6248d347a78a8bd0304152&scene=1&srcid=1029j0wKK0SqJ57ZvNDytUFZ&from=singlemessage&isappinstalled=0#wechat_redirect)

本文中提到的 magic leap 的MR视频，在@ifeegoo本期分享的内容中也有这个。另外这个3D动态纹身是相当酷炫的，大家赶紧一睹为快！

***



### #6 2015-10-24(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

#### 1.[耐克自动系鞋带运动鞋](http://tech.qq.com/a/20151023/011762.htm)

想象一下，你的脚放入鞋中，鞋带自动的系上。是不是有点小酷，这样的鞋，要不要来一双？

#### 2.[跟着贝尔去冒险](http://www.iqiyi.com/w_19rtjbnlcx.html)

大家都知道贝爷吧，一个站在食物链顶端的男人。现在他要带领：张钧甯、谢天华、张丹峰、大张伟、吴倩、白敬亭、韩雪、刘语熙、荒野求生！想要看他们生吃活蚯蚓的样子吗？嘿嘿。

#### 3.[5.11 Tactical](http://www.511tactical.com/)

有没有注意到最近习大大打的那把伞？要不要搞一把？:smile:

![](http://y3.ifengimg.com/a/2015_43/5fc60f87cb757f4.jpg)

#### 4.[程序员节](http://baike.baidu.com/view/4367098.htm)

程序员节是什么鬼？现在越来越多的中国程序员呼吁10.24作为中国程序员的节日，你觉得如何？

#### 5.[Ada Lovelace](http://baike.baidu.com/view/10960576.htm)

知不知道这位美女？

![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Ada_Lovelace_portrait.jpg/220px-Ada_Lovelace_portrait.jpg)

美国花费十几年研究的适用于军方的计算机编程语言，就是以她的名字命名。号称世界上最强大的反编译软件，没有之一的IDA Pro，就是用她的头像做的Logo。她的父亲是英国的大诗人拜伦。怎么样？还不赶快了解一下她？

#### 6.[Hacker News](https://news.ycombinator.com/)

科技工作者需要关注的网站。

#### 7.[关于ID和URL的强迫症](http://blog.vrypan.net/2013/11/08/why-i-wont-use-a-gplus-custom-url/)

你有没有自己专属的网络ID，是不是一定要每一个网站的ID都保持一致，不能让你自定义ID，是不是就不舒服，是不是就不想用？看到这种URL：

https://plus.google.com/u/0/106649334741002817472

是不是觉得抓狂？恭喜你，你有ID和URL的强迫症，不用担心，你不是一个人！来看下这些人的说法：

[https://news.ycombinator.com/item?id=6698821](https://news.ycombinator.com/item?id=6698821)

***

### #5 2015-10-17(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

#### 1.[传闻小米和华为即将推出笔记本电脑产品](http://digi.163.com/15/1016/10/B61TF3DU00162Q5T_all.html)

很早之前就有小米笔记本的传闻了，但是也一直也没有见官方的动静，这次消息应该更加确切的。这样的话，小米在模仿苹果的上就更进一步了！华为已经注册 MateBook 商标，看来离华为笔记本出现也不远了！

#### 2.[苹果配件的升级：鼠标、键盘、触控板](http://tech.sina.com.cn/mobile/n/n/2015-10-14/doc-ifxirmpz8324383.shtml)

新款鼠标：Lightning 接口，快速充电：充电两分钟，可用九小时。

新款键盘：全新的外观设计。可充电。

新款触控板：全新的外观设备。支持 Force Touch。

#### 3.[苹果iMac全部配备Retina显示屏](http://tech.qq.com/a/20151013/069500.htm)

对于设计师来说，这是一个非常好的消息。

#### 4.暴力测试

有两个比较有名的针对电子产品的暴力测试团队：  
[Full Mag](http://revision3.com/fullmag/) 和 [RatedRR](http://revision3.com/ratedrr/)

#### 5.[Dribbble](https://dribbble.com/)

Dribbble：设计师界的 Github。当然也非常适合那些想要写那些酷炫的交互动画的程序员去寻找素材。  
备注：这个网站国内访问效果不太理想，搭梯子访问效果更加。国内有一个专门推荐Dribbble上面资源的网站：[追波中国](http://dribbble.cn/)

#### 6.[柔宇科技](http://www.royole.com/)

柔宇科技：这家科技公司很有可能成为下一个大疆。  
这家公司成立时间只有短短不到三年，却有着令人惊叹的发展历程：  
2012年5月，柔宇科技成立，在中国深圳、香港和美国硅谷同步运营  
2013年8月，发布世界最薄可量产柔性显示器背板(最薄可达0.03至0.1毫米)  
2014年8月，发布全球最薄彩色柔性显示器，厚度仅0.01毫米  
2014年9月，中央电视台《新闻联播》头条报道  
2014年11月，国务院副总理刘延东参观调研柔宇科技  
2015年4月，国务院副总理马凯参观调研柔宇科技  
2015年7月，柔宇科技世界首条超薄柔性显示模组及柔性触控量产线正式启动量产  
2015年8月，完成海内外共四轮风险投资，企业估值超10亿美金，跻升全球独角兽俱乐部

看看他们现在的产品：

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/royole.jpg)

[柔性屏幕概念视频：未来比想象美好！](http://v.qq.com/page/r/s/r/r0123iljgsr.html)

#### 7.[APP推荐：声色](http://36kr.com/p/5038381.html)

声色：这是一个关于生僻字为主题的APP，看看它搞的什么鬼？

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/app-shengse.jpg)

#### 8.《开司》

第一部是赌博默示录，第二部是赌博破戒录，第三部是赌博堕天录。 从1996年开始在《周刊Young Magazine》上连载《赌博默示录》、《赌博破戒录》、《赌博堕天录》统称《开司》系列。《开司》系列到2008年为止合计39卷，是卖出1000万本以上的大受欢迎之作，福本的人气稳如泰山。2005年《斗牌传说》、2007年《赌博默示录》均被TV动画化。《赌博默示录》动画名为《逆境无赖KAIJI～Ultimate Survivor～》。2009年《赌博默示录》电影，2011年《赌博默示录2》电影。

从动漫，到动画，再到电影。值得一看！

[《赌博默示录》预告片](http://v.youku.com/v_show/id_XMTI1MjY3NTI0.html)

[《赌博默示录2》预告片](http://v.youku.com/v_show/id_XMjcyMjU4MzE2.html)

***

[@misparking](http://github.com/misparking)

#### 1.劝读书

我家族中有个孩子曾一本正经地问我：“我一读书就头疼，怎么办？”我说：“读书好比弯腰捡拾钻石。你说是腰酸重要还是捡起钻石重要？”她说：“当然是捡起钻石重要了。”我说：“那你的头疼就可以忽略不计！”她继续抱怨：“我读了那么多书，感觉一点用都没有！”我问她：“10年前的今天，你吃了一顿怎样的午餐？”她说：“那我当然不记得了。”我说：“是不是不记得了就意味着那顿午餐没有用呢？想想看，你不就是被一顿顿不记得的午餐喂成了今天的你吗？而书籍喂养的，是一个精神的你，你今天的‘精神颜值’有多高，很大程度上取决于你读过的那些书——哪怕你已不记得它们。”

#### 2.[为什么圆是360度？](http://www.360doc.com/content/15/0304/17/20284327_452534325.shtml)

为什么圆是360度？嗯，这是个好问题！

#### 3.[尼古拉·特斯拉](http://baike.baidu.com/view/966246.htm)

这个人你可能不知道，但是你一定听说过特斯拉电动车，没错，就是为了纪念这个人而命名。可以听听《罗辑思维》关于特斯拉这期的节目，可以关注一下他和爱迪生之间的事情。

[中国达人秀：高压电激光特斯拉线圈演奏秀](http://tv.sohu.com/20110627/n311723707.shtml)

#### 4.[用一张图片去安慰一个人](http://www.360doc.com/content/15/0501/02/23114593_467178438.shtml)

有的时候，一段文字加上一张很配的图片，给人的感觉，远远超过仅仅一段文字给人的感觉。

#### 5.[壹心理](http://www.xinli001.com/)

壹心理：一个很棒的关于心理学的网站。同时他们还有自己的播客节目：

[心理FM](http://fm.xinli001.com/)：世界和我爱着你！


####

***

### #4 2015-10-10(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

####1.苹果两款产品入华：

[Apple Music](http://www.apple.com/cn/music)  
三个月的免费试用，个人会员每月 RMB 10，家庭会员每月只需 RMB 15。  
[iBooks](http://www.apple.com/support/ios/ibooks)  
苹果电子书。  
备注：另外请关注[微信读书](http://tech.qq.com/a/20150827/238620.htm)。

####2.播客节目：字谈字畅(Type Chat)

出品方：[Type is Beautiful](http://www.typeisbeautiful.com)。请在苹果设备的播客中搜索。第一台用华语制作的字体主题播客节目。微信公众号：[thetype]。

####3.屠呦呦获得诺贝尔生理医学奖

屠呦呦发现了青蒿素对疟疾的治疗作用，从而获得了诺贝尔生理医学奖，她说这是中药对世界的贡献。之前《罗辑思维》有一期节目讲的是"反对中医"的问题，其实他本质上是认同传统中医精华的部分。只是中医在很长的时间，没有确立类似于“大样本随机双盲试验”的理论。  
```
“大样本随机双盲试验”是现代医学判断疗效的“金标准”。  

大样本：试验选取的样本数要尽可能多。因为统计学的“大数原则”告诉我们，样本越大，统计结果越能稀释掉那些特例（例如某些人免疫系统特别强或特别弱），也就越能逼近真实情况。

随机：样本选取遵循随机原则。这样可以有效避免病人由于病情轻重而导致的痊愈效果阶段性差异。

双盲：医生和病人双方都不知道病人所属的对照组。

单盲：将样本病人随机分为以下三组，病人不清楚自己所属的组别，医生知道病人所属组别。

第一组是对照组，不做任何治疗，用来观察病人疾病在没有治疗情况下的自愈效果。

第二组是安慰剂组，给病人吃没有治疗成分的“假药”，用来观察病人的心理作用对疾病的影响。

第三组是治疗组，给病人吃真药，观察这种药物或疗法的真实治疗效果。

双盲：所有数据加密，连医生都不知道自己身处哪一组，而统计工作由第三方来进行。这样一来，就能很好屏蔽来自医生的主观意识影响，让实验更加客观公正。
```

####4.[微软「火力全开」，一口气发布了5款新品](http://www.geekpark.net/topics/213572)

+ Hololens:AR + VR  
+ Microsoft Band:二代，Microsoft Band 二代搭载了 GPS、UV 检测、气压计等多达 11 个不同类别传感器（上代为 10 个），可以全方位监测身体的各项指标。  
+ Surface Pro 4:我的对手是 Macbook Air」。售价 899 美金起（约 5708 元）。
+ Surface Book:「正统的」微软笔记本。
+ 新款 Lumia 手机:运行 Windows 10 mobile 操作系统。

####5.[Google](http://www.google.com) 上市主体正式更名为 [Alphabet](http://abc.xyz)

Alphabet:字母表的意思。新的Alphabet公司的业务如下：

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/Alphabet-company-composition.jpg)

备注：由于 www.alphabet.com 这个域名被宝马公司持有，Alphabet公司只能注册 abc.xyz域名为公司域名，另有消息称其还购买了 [www.abcdefghijklmnopqrstuvwxyz.com](www.abcdefghijklmnopqrstuvwxyz.com)作为备用。

####6.[Elon Musk](https://en.wikipedia.org/wiki/Elon_Musk)

Elon Musk:这个在IT界有着「钢铁侠」称号的男人，绝对是乔布斯之后最酷的一个人！来看看他做了些什么：

Words are cheap,show you the pictures!

1.[Zip2](http://www.citysearch.com/world)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/Citysearch.png)

2.[Paypal](https://www.paypal.com)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/PayPal.png)

3.[Solar City](http://www.solarcity.com)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/SolarCity.png)

4.[Tesla](http://www.Tesla.com)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/Tesla.png)

5.[Hyperloop](http://www.spacex.com/hyperloop)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/Hyperloop.png)

6.[SpaceX](http://www.spaceX.com)

![](https://raw.githubusercontent.com/SnailLove/snaillove-weekly-sharing/master/resources/pictures/spaceX.png)

另外相关的新闻：  
[Tesla Model X :全球首款鸥翼门SUV！](http://tech.qq.com/a/20151001/018374.htm)  
[谁将第一个登上火星？拉斯维加斯真的开了个赌局，他们最看好Space X!](http://www.pingwest.com/wholl-be-the-first-to-set-foot-on-mars/)  
Elon Musk 在 TED 上的演讲:[http://www.ted.com/talks/elon_musk_the_mind_behind_tesla_spacex_solarcity](http://www.ted.com/talks/elon_musk_the_mind_behind_tesla_spacex_solarcity) 

***

### #3 2015-09-19(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

####1.[iOS 9 有哪些新功能？](http://www.ifanr.com/563687)

iOS 9 带给用户最新的功能，个人觉得印象比较深刻的内容有：1.输入法大小写的问题。2.新的任务管理器UI动画。当然还有作为开发者所遇到的各种技术的坑。

####2.[XcodeGhost](http://blog.jobbole.com/91646)

最近闹的沸沸扬扬的XcodeGhost事件，自己也是捏了一把汗，前两天准备更新到最新版本的Xcode7，需要测试iOS9。发现在App Store中更新Xcode，根本没有反应。只能去找第三方来下载了。发现很多大公司都中招。自己赶紧去测试Xcode7的dmg文件的MD5,SHA1值。

Mac用户可以在Terminal中用"md5"和"shasum"命令分别查看相关文件的MD5和SHA1值。

``` 
ifeegoo:Downloads ifeegoo$ md5 Xcode_7.dmg
MD5 (Xcode_7.dmg) = 6be3e59a8a8d2ce40fb2076575d71c24
ifeegoo:Downloads ifeegoo$ shasum Xcode_7.dmg
4afc067e5fc9266413c157167a123c8cdfdfb15e  Xcode_7.dmg
```

Windows用户可以在Command里面用 "certutil -hashfile "文件" MD5" 和 "certutil -hashfile "文件" SHA1" 命令来获取文件的MD5和SHA1值。

```
C:\Users\ifeegoo\Downloads>certutil -hashfile Xcode_7.dmg MD5
MD5 哈希(文件 Xcode_7.dmg):
6b e3 e5 9a 8a 8d 2c e4 0f b2 07 65 75 d7 1c 24
CertUtil: -hashfile 命令成功完成。
C:\Users\ifeegoo\Downloads>certutil -hashfile Xcode_7.dmg SHA1
SHA1 哈希(文件 Xcode_7.dmg):
4a fc 06 7e 5f c9 26 64 13 c1 57 16 7a 12 3c 8c df df b1 5e
CertUtil: -hashfile 命令成功完成。
```


####3.[电信运营商数据缓存问题](http://ipn.li/kernelpanic/20/)

不同的电信运营商之间进行数据交换，他们会采取数据缓存。我之前在北京更新Android apk文件的时候，就发现此类的问题。更新了apk文件，但是发现还是下载到的是之前的数据，但是换了运营商网络，就不存在这个问题。但是由于运营商本身缓存的机制存在技术问题。导致文件更新不到，甚至出现串文件的情况。可以听听著名播客"内核恐慌"它们出现的问题，你就知道了这个问题的所在。

####4.[http://www.kat.ph](http://www.kat.ph)

[http://www.kat.ph](http://www.kat.ph)，这个网站是除了之前海盗湾之外，现在资源比较丰富的种子网站。尤其是一些好莱坞电影，基本上是可以第一时间可以找到的。

最近有一部电影，叫做[疯狂的麦克斯4 (Mad Max 4)](http://baike.baidu.com/subview/1624332/7832697.htm)，这是一部风格比较独特的电影，值得一看，推荐给大家。

***

[@chenyunxuan](https://github.com/chenyunxuan)

####1.[有趣网址之家](http://youquhome.com/)

这是一个收集了很多有趣网站的网站，很多有趣的内容，大家可以一探究竟。

####2.[推荐微信公众账号：唉生活VS爱生活]

微信ID：ashvsash

这个公众账号推荐各种不错的视频资源。

***

[@wangrui](https://github.com/CatchComing)

####1.[12分钟看完90万字科幻神作《三体》](http://www.acfun.tv/v/ac2167557)

刘慈欣的《三体》是近年来少有的很棒的中国科幻小说，2014年底小说第一部的英文版在美国上市，反响热烈，并于2015年获得美国科幻奇幻协会“星云奖”等五个奖项提名。2015年8月23日，《三体》获第73届世界科幻大会颁发的雨果奖最佳长篇小说奖，这是亚洲人首次获得雨果奖。
目前这部同名小说电影正在拍摄之中，导演是中国人，让我们拭目以待！

***

### #2 2015-09-05(Sat)

***
[@ifeegoo](http://github.com/ifeegoo)

####1.最近两家科技公司的Logo的变化：

Google:
![](http://7te8bu.com1.z0.glb.clouddn.com/uploads/new/article/740_740/201509/55e6792ca3eb9.jpg)


Meizu:  
![](http://img1.mydrivers.com/img/20141024/b3e50eeab0fb4a71ac38aaa63dc33544.gif)  
![](http://upload.techweb.com.cn/2015/0831/1441003468950.jpg)

Google Logo的变化：[Google过去17年Logo的变化](http://v.qq.com/boke/page/f/0/6/f0164rt8ra6.html)

相关科技公司Logo变化：[竟然越换越丑？你想不到的科技公司LOGO进化史](http://mt.sohu.com/20150905/n420421489.shtml)

####2.[让用户在输入密码时看到明文吧](http://beforweb.com/node/658)

以前在PC时代，输入密码的时候，我们都只能看到“园点”，“星号”，时间久了，我们理所当然，认为输入密码的时候，必然是这个样子，你有想过让用户输入密码的时候，让他们看到明文吗？让用户看到明文有什么好处呢？

####3.[别让用户觉得自己蠢](http://beforweb.com/node/753)

在移动应用时代，用户体验是一个非常重要的点。如果你的应用到处都弥漫着让用户觉得自己蠢的地方，那你的应用离被用户抛弃就不远了。

####4.[iphone手机翻墙](https://itunes.apple.com/cn/app/kuai-miao-jia-su-qivpn-gao/id1009096479)

给大家推荐一个非常好用的VPN软件：[快喵加速器](https://itunes.apple.com/cn/app/kuai-miao-jia-su-qivpn-gao/id1009096479):有初始的免费流量送，每天还可以签到获取免费流量，操作简单，只需要一次安装描述文件，然后一键控制，就可以轻松看世界了！对于只刷刷Facebook,Twitter的用户来说，绝对不错！

####5.[Mac系统上移除.DS_Store文件](http://asepsis.binaryage.com)

作为开发人员，默认开启影藏文件显示，是技术人员必备习惯。但是有些人又不想看到那个不舒服的.DS_Store文件，给大家推荐的一款Mac软件[Asepsis](http://asepsis.binaryage.com)，可以完美的解决问题。可以让你在开启影藏文件显示的时候，看不到.DS_Store文件。想要知道它在技术上如何实现的吗？赶紧去一窥究竟吧！  
[http://asepsis.binaryage.com](http://asepsis.binaryage.com)

***
[@misparking](http://github.com/misparking)

####1.[未来十年企业大趋势](http://read.haosou.com/article/?id=5ac615f9f4ffb81ec71bb45d7b5e82f0)
十五年前的思考和十五年的行动才铸就了今天。O2O本身是个伪命题，从线下经济往线上经济走。坦克装上翅膀未必是飞机，坦克就是坦克，只有飞机和坦克的完全结合才能有未来。 未来的机会，是我们共同的合作，共同的打造未来。互联网经济不是虚拟经济，互联网经济是把虚拟经济和实体经济联合起来，这才是赢家！

***

### #2 2015-08-29(Sat)

***
[@ifeegoo](http://github.com/ifeegoo)

####1.[苹果的字母"i"表示什么？](http://softu.cn/252)

很多人都在用苹果的产品，尤其是iPhone，你们都有想过为什么要用字母i吗？是不是就是指我的意思呢？我们来看看非官方和官方的解读，这个小的细节一定能够给你涨姿势！

####2.[如何一边跑步一边写代码？](http://www.zhihu.com/question/34985774)

这个是知乎上面一个程序员提出的一个比较怪异的问题。但是仔细一想，提出这样的问题也还算正常。我们都知道程序员一直缺乏运动，身体健康状况堪忧，但是如果你又想花大量的时间来提升自己的技术的话，你又不得不缺乏运动。为什么很多程序员“聪明绝顶”，这个是一个矛盾的东西。这说明提问者是想既要珍惜时间，又要爱惜身体。这个看起来是一个矛盾的东西，怎么破？我摘要了几个比较有意思的回答：

[李哲](http://www.zhihu.com/people/li-zhe-8-6)  

&emsp;&emsp;*我不想谴责现有的调侃性回答，因为它们确实也给我带来了欢乐。对那些谩骂性的回答，我只能说“燕雀安知鸿鹄之志”。
我确实能够理解提问者那份不想浪费生命中每一分钟，但又不想因为过分不重视身体健康而隐性地丢失掉未来的数年生命和可以用来尽情挥霍的健康体魄的心。*  
&emsp;&emsp;*我认为，这样的生命是值得珍惜的，也值得花些时间来帮忙想一下如何珍惜。*  
&emsp;&emsp;*实际上，我也思考过同样的问题。类似的还有，如何在通勤时间写东西（不仅限于代码），如何躺在床上写东西而不需要被低效的手机输入法折磨，甚至如何在洗澡的时候写东西……*
&emsp;&emsp;*然而，不幸的是，我没有找到一个完美的解决方案，只能说说目前采取的折中方案。*  
&emsp;&emsp;*在跑的时候，不要去思考具体的代码，而是转入软件设计模式，去考虑整个系统如何实现、如何设计：框架如何分层、应该有哪些主要模块、界面应该有哪些主要的控件。当有一个大概成型的思路的时候，稍事休息，找张纸画下来。* 
&emsp;&emsp;*既然你是在室内用跑步机，可以找一张大一些的纸，画好之后贴在面前的墙上，然后盯着墙上的初步设计图，继续跑，然后针对其中一个个模块进行进一步设计。设计差不多了，再画下来，顺便喝口水、喘口气。*  
&emsp;&emsp;*如此递归下去，细化到代码层面的时候，差不多你也完成那一天的健身任务了吧。*  
&emsp;&emsp;*然后，像很多人说的那样，乖乖坐到桌子前面写代码。*  
&emsp;&emsp;*实际上，我的情况比你的艰难很多。因为我倾向于在野外跑或者骑自行车，没有纸，只能用手机之类的记下来然后继续在脑子里空想。但落实到写代码的时候，还是得回到桌子前面。*  
&emsp;&emsp;*另外，记下来的不仅仅是设计图，还有需要上网查资料确认的问题点。*  
&emsp;&emsp;*如果还没跑完，一个设计已经完成了。你可以考虑先放下，换下一个系统继续设计。*  
&emsp;&emsp;*我本人除了写代码，还喜欢写小说什么的，基本上腹稿都是在路上、厕所里或者临睡前完成的。正应了欧阳修的“枕上马上厕上之三上”。*
&emsp;&emsp;*其实，关于写小说，我还得益于不坐在桌子前。因为我自知自己的描写能力很差，尤其是景物、人物外貌等描写，所以，我会在走路的时候刻意地去观察身边的景色，然后在头脑中去想应该如何遣词造句来描写这样的景色。遇到人也一样。 * 
&emsp;&emsp;*另一方面，学习外语，要想提高口语和听力，自言自语是一种不错的练习方法。这也可以在跑步、走路、骑车等健身时间很好地完成。不过，在公共场合要控制一下音量或者调整到脑内默读的静音模式（只要静音就好了，请不要开启振动）。 * 
&emsp;&emsp;*当然，如果今后技术提高了，我认为可以考虑开发一个追踪瞳孔运动的输入法。*  
&emsp;&emsp;*在类似Google眼镜的穿戴设备上，显示一个键盘，监视瞳孔移动，然后敲出相应的字母。按照目前的手机滑动输入法的推测准确率，配合上IDE的自动完成功能，我觉得还是能够满足基本的编码需求的。*  
&emsp;&emsp;*希望以上方法能给你带来启示。如果你找到了更好的解决方案，请不要忘记分享给同样珍惜生命中每一分钟的同伴们。*

[小小春](http://www.zhihu.com/people/xiao-xiao-chun-11)

&emsp;&emsp;*既然有人认真回答了，那么好吧。如果在室内，用跑步机的话，只需要一个大屏幕，至少看得清字符，加一个体感输入器，我相信大家应该玩过或者知道体感游戏。体感输入器把手势转化成键位，然后就可以一边跑步一边比划手势，假以时日我相信舞王非你莫属啦!*

[DavidPan](http://www.zhihu.com/people/davidPan)

&emsp;&emsp;*计算机的基本原理有0、1，人跑步的话会间隔对跑步机造成有限的压力。so，跑步机上做一个压力感应器，这样可以压力值来模拟0、1然后最基础的机器码计算器就做成了。*

[kubisoft](http://www.zhihu.com/people/kubisoft)

&emsp;&emsp;*不要用跑步机，用健身自行车坐着腿蹬蹬就可以了。*

[鹅蛋](http://www.zhihu.com/people/eegg)

![](http://pic1.zhimg.com/ac66c8e68490018e0f2cacd7d70ead74_b.jpg "")

[苏云](http://www.zhihu.com/people/suyun)

&emsp;&emsp;*向李阳学习，一边跑，一边大声的把代码喊出来，最好是咆哮式的：*  
&emsp;&emsp;*int！嘿！*  
&emsp;&emsp;*int hour！嘿！哈！*  
&emsp;&emsp;*int hour = 1.5！嘿！吼！*  
&emsp;&emsp;*我已经跑了一个半点啦！嘿哈！*  
&emsp;&emsp;*while！do while！do do do do it！哼哈！*  
&emsp;&emsp;*break还是continue？真是纠结！*  
&emsp;&emsp;*不如goto吧！go！go！go！*  

&emsp;&emsp;*别忘了还要配合跑步的节奏。这样一来，跑步也有节奏了，写代码也有音效了，绝对跑得爽，记得牢！*

####3.[半路学编程，可以成为大牛吗？](http://www.zhihu.com/question/34101611)

&emsp;&emsp;这个是比较好的问题。回答这个问题之前，我们需要了解一下当前IT行业的大背景：很多科班出生的，可能最后留下来编程的不多，转行做测试或者其他行业。而大量非科班出身的人都涌入到IT行业。所以会有所说的半路学编程的问题。  
&emsp;&emsp;半路学编程，你是带着什么目的半路学编程的，是为了混口饭吃，觉得这个行业工资高？还是说自己真心的兴趣？这两者是有很大的区别的。如果你是为了混口饭吃，觉得这个行业工资高，然后半路学编程的话，那么你成为大牛的概率就比较小，而且随着时间的变长，你会发现，外人看来的工资高，只是虚高，你付出的同样的多，这个行业的节奏，这个行业的压力，这个行业的更新换代，这些东西会极大的考验你对这个工作的热情还有坚持！如果你是真心的兴趣，你不想把生命浪费在其他的事情上去，你就认为编程是美好的，那么你成为大牛的概率就大一些。  
&emsp;&emsp;除了那些天赋异禀的人，没有人是不通过刻苦努力结合有效的方法来提升自己的能力的。我们那些很多开起来很牛的人，都是通过点点滴滴，一步一个脚印走过来的。他们或许离我们很远，我们也不必一下子达到他们那样的高度，因为这样也不可能。我们首先需要向比我们更加优秀的一层人学习，超越他们之后，然后继续向更高层的人学习，这样我们就会离大牛越来越近！

####4.[谁让APP工程师产生了泡沫!](http://www.cnblogs.com/yinrq/p/4745784.html)

现在的APP开发实在太火了，你不得不承认，现在Android/iOS工程师十分抢手。每年各种培训班大量的输出学生，依然是供不应求。这样就会导致Android/iOS开始人员的工资虚高，对于企业来说，虚高这个问题，是他们必须面对的。但是对于我们个人来说，这是一个严峻的问题。这个现象会对自己产生比较严重的影响。我们不是企业，企业倒了，可以重来，但是我们自己不能重来，我们的时间浪费了，却没有成长，这个才是最要命的。

如果你在这个虚高工资的行业里面，过于看中工资的话，你会迷失自己，这种迷失很有可能对你将来的发展造成重大打击。IT行业，是一个更新迭代非常快的行业，现在Android/iOS是很热，但是你能保证3-5年之后，还是很火热吗？你在职业发展过程中，过于看中工资的话，你会失去很多锻炼成长的机会，个人能力的提升。如果说这个行业泡沫破裂，或者大量的从业者的涌入，你如何在供大于求的这个行业里面保持自己的竞争力，这是一个问题！

***

@XiaoPan

####1.[音乐要素](https://github.com/SnailLove/snaillove-weekly-sharing/tree/master/No-2-2015-08-29-Sat)

音乐乐理、乐谱、乐器。

***

### #1 2015-08-22(Sat)

***

[@ifeegoo](http://github.com/ifeegoo)

####1.IPN:Intelligent Podcast Network

##### 什么是 IPN？

IPN (Intelligent Podcast Network) 是《IT 公论》主播不鸟万如一和不鸟万 Rio 创办的播客网络。目前它旗下有十档节目：  
[《IT 公论》](https://ipn.li/itgonglun/)（周一播出）  
[《味之道》](https://ipn.li/weizhidao/)（周三播出）  
[《太医来了》](https://ipn.li/taiyilaile/)（周二播出）  
[《内核恐慌》](https://ipn.li/kernelpanic/)（隔周周日播出）  
[《流行通信》](https://ipn.li/popdispatch/)（周四播出）  
[《(Hi)story》](https://ipn.li/history/)（休眠中）  
[《無次元》](https://ipn.li/wuciyuan/)（不定期播出）  
[《硬影像》](https://ipn.li/hardimage/)（不定期播出）  
[《博物志》](https://ipn.li/bowuzhi/)（周五播出）  
[《选·美》](https://ipn.li/xuanmei/)（周六播出）  
虽然主题各有不同，但它们都具备不接地气、不反智和湿货多这三个特点。

##### 什么是「播客网络」？

假如你做了一档播客，你就有了一个播客；假如你做了两档播客，或是自己做了一档播客的同时帮朋友管理另外一档播客，你就有了一个播客网络。IPN 同时也是旗下播客节目的制作方，它和各节目的关系有点像 [Alphabet](http://abc.xyz) 和 Google 的关系。

##### 如何订阅 IPN 出品的播客？

首先你需要一个泛用型（或称通用型）播客客户端软件。在 iOS 上我们第一推荐的是 [Castro](http://castro.fm)。若您暂时不打算为播客客户端付费，也可以用苹果自家出的那个紫色图标的 Podcasts，它是免费的，并已预装在了 iOS 8 上。在九月即将推出的 iOS 9 里，Podcasts 会全面更新。

在安卓上我们推荐 [Pocket Casts](http://www.shiftyjelly.com/pocketcasts)，但很遗憾国内安卓市场上的 Pocket Casts 均为盗版。若您无法[在 Google Play 购买 Pocket Casts](https://play.google.com/store/apps/details?id=au.com.shiftyjelly.pocketcasts)，我们推荐开源且免费的 [AntennaPod](http://www.wandoujia.com/apps/de.danoeh.antennapod)。

在 Windows Phone 上您可能需要直接输入 IPN 每档节目的订阅地址，具体见下。

在 Mac 和 Windows 上用 iTunes 就好。当然，您也可以随时在浏览器里访问各档节目的网站收听。

订阅方法：

*   IT 公论：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id747497890)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/itgonglun/feed)。
*   味之道：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id921775561)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/weizhidao/feed)。
*   太医来了：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id921829208)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/taiyilaile/feed)。
*   内核恐慌：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id928916244)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/kernelpanic/feed)。
*   流行通信：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/cn/podcast/id940780392)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/popdispatch/feed)。
*   (Hi)story：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/cn/podcast/id971922240)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/history/feed)。
*   無次元：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/wu-ci-yuan/id946742064)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/wuciyuan/feed)。
*   硬影像：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id982865614)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/hardimage/feed)。
*   博物志：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id1030448996)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/bowuzhi/feed)。
*   选·美：iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/xuan-mei/id1030831931)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/xuanmei/feed)。

如果您想一次性订阅 IPN 旗下的所有播客（谢谢！），iPhone 和 iPad 用户[请点这里](https://itunes.apple.com/podcast/id922715611)，安卓和 Windows Phone 用户[请点这里](https://ipn.li/feed)。

##### 在哪里可以关注你们？

*   IPN: [@IPNpodcast](https://twitter.com/ipnpodcast) on Twitter, [@IPN播客](http://weibo.com/ipnpodcast) on 新浪微博
*   IT 公论：[@itgonglun](https://twitter.com/itgonglun) on Twitter, [@IT公论](http://weibo.com/itgonglun) on 新浪微博，[@itgonglun](http://instagram.com/itgonglun) at Instagram, itgonglun at 微信公众账号
*   味之道：[@weizhidao](https://twitter.com/weizhidao) on Twitter, [@味之道播客](http://weibo.com/weizhidaopodcast) on 新浪微博
*   太医来了：[@taiyilaile](https://twitter.com/taiyilaile) on Twitter, [@太医来了](http://weibo.com/taiyilaile) on 新浪微博
*   内核恐慌：[@KernelPanicFM](https://twitter.com/kernelpanicfm) on Twitter, [@内核恐慌](http://weibo.com/kernelpanicfm) on 新浪微博
*   流行通信：[@PopDispatch](https://twitter.com/popdispatch) on Twitter, [@流行通信PopDispatch](http://weibo.com/popdispatch) on 新浪微博, [@PopDispatch](http://instagram.com/popdispatch) at Instagram。
*   (Hi)story：[@HistoryCheap](https://twitter.com/historycheap) on Twitter, [@HistoryCheap](http://weibo.com/historycheap) on 新浪微博。
*   無次元：[@wuciyuan](https://twitter.com/wuciyuan) on Twitter, [@無次元播客](http://weibo.com/wcypodcast) at 新浪微博。
*   硬影像：[@hard_image](https://twitter.com/hard_image) on Twitter, [@硬影像](http://weibo.com/hardimage) on 新浪微博。
*   博物志：[@bowuzhi](https://twitter.com/bowuzhi) on Twitter, [@博物志播客](http://weibo.com/bowuzhifm) on 新浪微博。
*   选·美：[@XuanmeiUS](https://twitter.com/xuanmeius) on Twitter, [@选美IAmElection](http://weibo.com/xuanmeifm) on 新浪微博。

##### 能否在荔枝 FM / 喜马拉雅 / 蜻蜓 FM / [某某播客平台]上线？

有可能，但我们不保证什么。无论用什么设备，你总是可以在[我们的网站](https://ipn.li)上在线收听或下载 IPN 出品的节目，也可以用本 FAQ 第三问中提到的通用型播客客户端订阅。

##### 为什么要听播客？

首先是可以在健身、坐地铁/公车、走路、驾驶时打发时间，其次可以减少面对屏幕和低头的时间。事实上，如果你为了腾出听播客的时间而开始运动，我们会认为自己做了善事。[然后还有这个](http://www.zhihu.com/question/24513480/answer/28112529)。

##### 如何联系你们？

*   [hi@ipn.li](mailto:hi@ipn.li)（不鸟万如一和不鸟万 Rio 都会收到）
*   [lawrence@ipn.li](mailto:lawrence@ipn.li)（不鸟万如一）
*   [rio@ipn.li](mailto:rio@ipn.li)（不鸟万 Rio）

各档节目的联络电邮可在其网站上找到。

##### 哪些节目有会员计划？

目前以下节目有会员计划：

*   [《IT 公论》会员计划](http://itgonglun.com/member)
*   [《味之道》会员计划](http://weizhidao.fm/member)
*   [《無次元》会员计划](http://wcy.wtf/member)
*   [《博物志》会员计划](http://bowuzhi.fm/member)

会员权益以及价格均可在上述链接看到。

此外，《内核恐慌》有[捐助计划](http://kernelpanic.fm/donate)。

##### 为什么我经常收不到会员通讯？

请留意您的 spam 文件夹或垃圾箱，群发的电邮有时会被误归入那里。另外，请考虑把会员通讯的发件人邮箱地址加入您的通讯录，这样可以提高电邮的送达率。我们推荐您使用 Gmail 或 iCloud 等国外邮箱。

##### 我现在是月付会员，想转成年付可以吗？

当然可以。请写信到各节目的客服邮箱说明，我们会直接在后台帮您操作。系统会自动处理差价。

####2.[Type is beautiful](http://www.typeisbeautiful.com/)

Type is Beautiful 是一个关于文字设计和视觉文化的网站。我们关注的话题包括字体、排版、平面设计、公共设计、技术和视觉文化。

####3.[Apple for us](http://www.apple4us.com/)

关于 Apple 产品的一个不错的网站。

####4.[好奇心日报](http://www.qdaily.com/)

好奇心日报是一个基于新闻和商业报道的生活方式媒体，包括智能、娱乐和城市三个板块，还有一个生活研究所供你吐槽。

***

[@ZhangGang](http://github.com/Jackwaiting)

####1.[Pngyu](http://nukesaq88.github.io/Pngyu/)

[Pngyu](http://nukesaq88.github.io/Pngyu/) 是一个简单的PNG文件压缩工具，采用的是[pngquant](http://pngquant.org/)压缩引擎。   
备注：特别适合做移动APP开发者压缩图片，减少安装包的大小。

***

@honeypapa

####1.[为什么英文比中文显得高大上？设计师必看！](http://www.uisdc.com/english-chinese-font-design)

>为什么大多数人会觉得衣服或车上印英文比印中文好看？严格意义上来说，这是一个无法放在一起做比较的两个属性。根据以上的几个案例。我们会发现，其实我们是在将文字的“实际表达含义”在与图形的“视觉形式美感”进行比较。

>这本来就是不严谨的类比方式。图形从视觉诱目度上来说，自然会更胜一筹。外国人看待我们的中文字，大脑也是会将其第一时间进行图形化或符号话处理。

>这就是为很多外国人喜欢纹中文纹身的原因，不是他们喜欢中文，而是中文字体他们是当作图形来理解，而中文字的方块形式，又正好与他们本国的纤细文字有着巨大的反差。

>造成这样感受的，其最本质的原因就在于我们大脑的反应速度。反应速度越慢，我们会觉得图形越好看。

>欧美地区人群，在看到英文时，其实是和我们看到中文时的心理活动一致的，他们也会第一时间去解读单词的直接含义。

>在设计中的中文也好，英文也罢，如需显得高端，必须保证第一时间不被解读出来。这也就是为什么，国内一些品牌喜欢在取名时，傍英文的目的。

***

@木昜景页

####1.[《设计面面观》](http://v.youku.com/v_show/id_XMTMxMDQwNTQ0.html)

由独立制片人导演Gary Hustwit执导拍摄的[《设计面面观》](http://v.youku.com/v_show/id_XMTMxMDQwNTQ0.html)是一部以工业设计为主题的长篇独立纪录片。  
影片详尽地展示了创造工业产品流程的实录片断，并记录了与世界顶尖设计师们的交谈与讨论。导演Gary Hustwit用洞察深切的镜头记录了这些在我们身边随处可见的工业设计产品，看似稀松平常的设计背后，却是设计师们倾尽全力的良苦用心。
***

