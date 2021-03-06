# BCTF 2014

[官方网站] [BCTF]

[BCTF]:http://bctf.cn/

## 大赛简介

### 在线资格赛

比赛形式：在线解题形式

比赛时间：2014年3月8日08:00到10日08:00（48小时）

比赛平台：bctf.cn

每队人数：建议5-15人

比赛模拟场景：“重温世界头号黑客米特尼克冒险传奇”


### 现场决赛

比赛形式：网络攻防形式

比赛时间：暂定2014年5月2-4日

参赛战队数量：资格赛前8名的战队

每队人数：最多5名队员+1名领队

模拟场景：“决战江宁之巅峰”

## 大赛规则

* 本届BCTF大赛决赛仅面向中国本土战队（包括台湾、香港、澳门等地区），资格赛接受国外战队参加，并和中国本土战队分开排名。进入决赛的队伍必须在资格赛结束后的一段时间内提交解题报告，否则视为放弃决赛资格。
* 资格赛采用解题模式（Jeopardy）
* 资格赛每队建议5-15人，但是没有严格限制
* 资格赛赛题会根据参赛选手的解题进度由组委会逐渐开放
* 大部分flag为此形式：BCTF{可见字符串}，只需提交花括号内的可见字符串（大小写敏感）；如果flag为其他形式，题目中会单独说明。
* 资格赛每题分值为100-500分不等，每题优先解出的三支战队会分别获得额外30/20/10分的加分
* 战队积分相同时，先达到该分数的战队排名靠前
* 资格赛前8名的中国本土战队入围决赛，决赛每队限5名队员
* 公平起见，只有当没有队伍解出某题的时候，组委会才可能发放相关提示
* 如果参赛选手发现大赛平台或者赛题非预期漏洞，将会酌情给予一定加分奖励
* 使用网络扫描器（例如Nikto或者Nessus）不会对解题有帮助
* 大赛宝贝资格赛票选规则：战队队员解题之后将得到分值/10的选票，可以自由选择参赛大赛宝贝进行投票。大赛宝贝粉丝战队以战队队员投票数总和汇总排序显示。大赛宝贝初始以报名信息提交次序排序，之后以得票数进行排名，大赛宝贝票数相同时，先达到该票数的宝贝排名靠前(赛后统计)，资格赛选出8位票数最多的宝贝入选现场决赛，如不能到场，则名额顺延。
* 禁止队伍之间分享任何解题思路及flag，违规者一律取消参赛资格
* 禁止任何对比赛平台的暴力破解，违规者一律取消参赛资格
* 禁止对赛题以外的比赛平台发起攻击，违规者一律取消参赛资格
* 禁止一个人注册多个账号和参与多个队伍答题，违规者一律取消参赛资格
* 用户名、队伍等注册信息中，请勿出现暴力、色情、政治等相关表述，如发现将删除账号
* 如发现任何违规行为请向admin@mail.bctf.cn发邮件举报，查实后组委会将赠送礼物
* 关于比赛规则的最终解释权归大赛组委会所有
* **如果您对规则有疑问，请向admin@mail.bctf.cn发邮件询问。**

## FAQ

### 什么是CTF（Capture The Flag）？

CTF夺旗赛是计算机安全竞赛的一种形式，参赛选手往往需要组队参加。flag 指的是一串字符信息，它可能会被放在远程服务器上，也可能会被加密和隐藏在各种不容易访问到的媒介上，参赛选手通过使用逆向、解密、取证分析、渗透利用等技术来拿到 flag。CTF夺旗赛通常有两种形式，解题模式（Jeopardy）和攻防模式（Attack-Defense）。在解题模式的比赛中，主办方会提供一系列不同类型的赛题，比如上线一个有漏洞的服务、提供一段网络流量、给出一个加密后的数据或经过隐写后的文件等，他们将 flag 隐藏在这些赛题中，选手们通过比拼解题来一决高下；在攻防模式比赛中，主办方会事先编写一系列有漏洞的服务，并将它们安装在每个参赛队伍都相同的环境中，参赛队伍一方面需要修补自己服务的漏洞，同时也需要去攻击对手们的服务、拿到对手环境中的 flag 来得分，攻防模式的竞赛往往比解题模式的竞赛更接近真实环境，比赛过程也更加激烈。BCTF资格赛采用解题模式，决赛采用攻防模式。

### 为什么要举办CTF？

我们痴迷于计算机安全技术，然而计算机安全是一个很难进入的领域，并且那些对它十分感兴趣的人也很难合法地磨练自己的技能。因此，CTF提供一个了途径，让大家通过游戏竞技这种有趣的方式学习计算机攻防的技术，同时也能在比赛中结实志同道合的朋友。CTF参赛者不仅仅是学生队伍，也有来自行业中的专家，当然在竞赛中他们并不会对刚入门的参赛者手下留情。

### 什么是BCTF？

BCTF“百度杯”全国网络安全技术对抗赛，是由百度公司主办，清华和北大的安全技术专家提供技术支持，紫金江宁、南京赛宁承办，面向全国范围网络安全技术实战竞赛。大赛命题组主要成员来自于拥有丰富国际CTF大赛经验的蓝莲花战队。

### BCTF赛题有哪些类型？难度如何？
BCTF赛题涉及面较广，包含但不限于Web渗透、漏洞挖掘与利用、取证分析、隐写术、加密解密、基础编程这几个方面。

BCTF赛题难度差异很大，部分题目非常简单，绝大部分队伍应该都能做出，部分题目则会有一定的难度，但是不会太难。一方面，题目类型各异、设计角度、难度设置差别很大，另一方面，不同题目的考察侧重点不同，有的要求深厚的数学基础功底、有的需要较高的逆向技巧、有的需要对规范和协议有着深刻的理解。大家根据自己的特长和专项，每个人总能找到适合自己的题目。

我们希望这个比赛能真正体现黑客竞技的本质，成为一个真正的技术对抗赛，因此，通用的工具软件一般都无法直接解题，但是只要你理解相关技术的本质，往往只需要稍加变通，就能找到解题的关键思路。

### 我能参加BCTF吗？如何报名?

能！所有人都能组队报名参加BCTF。你只需要在这个网站注册账号，然后作为队长创建自己的战队并发动小伙伴们加入，或者加入已经创建的战队！

### 参加BCTF需要做什么准备？

不用惊慌！我们并不会要求你精通计算机安全技术，但是我们建议你能够了解一些计算机系统及编程方面的基础知识。无论你的基础如何，只要你对它感兴趣，你总会在其中享受到乐趣的，并且能够学习的新的知识。

网上有些练习资源可以参考，如果觉得这些练习太难，请不要沮丧。

* [Smash the Stack](http://smashthestack.org/)（漏洞利用）
* [Crackmes.de](http://crackmes.de/)（逆向工程）
* [Netforce.nl](http://netforce.nl/)（web渗透与密码学）

另外，BCTF赛题会与国际CTF比赛接轨，因此可以报名参加国际CTF比赛（详情参考[ctftime](http://ctftime.org/)）进行练手，也可以随时练习往届CTF赛题（[赛题集合](http://repo.shell-storm.org/CTF/)）。

### 能否介绍一下蓝莲花（blue-lotus）战队？

蓝莲花（blue-lotus）战队成立于清华大学网络与信息安全实验室，主要从事计算机安全攻防方面的研究。 多数主要成员为清华大学在读研究生，后吸纳包括来自浙江大学、上海交大、青岛理工、中国海洋大学、杭州电子科大等高校的多名学生， 以及若干绿盟、阿里巴巴等公司的年轻安全技术人员。在业余时间，团队组队参加多项国际知名CTF赛事， 曾作为中国的团队首次闯入全球顶级的DEFCON CTF总决赛。[这里](http://ctftime.org/team/1941/)可以看到blue-lotus在各项国际CTF赛事中取得的所有成绩。

## 组织单位

主办单位：百度公司

技术支持：清华大学、北京大学、蓝莲花网络安全技术战队

指导单位：网络安全应急技术国家工程实验室

承办单位：南京紫金（江宁）科技创业特别社区、南京赛宁信息技术有限公司

### 专家指导委员会 (排名不分先后)

姓名	单位名称	职位

陈文光	清华大学	教授

陈焰	美国西北大学、中国浙江大学	终身教授，特聘教授

程光	东南大学	教授

杜跃进	网络安全应急技术国家工程实验室	主任

段海新	清华大学	研究员

方兴	南京瀚海源信息技术有限公司	CEO

黄琰	百度公司软件研究院	技术总监

黄垠中	南京紫金（江宁）科技创业特别社区	副主任

金波	公安部第三研究所	研究员，所长助理

李康	美国乔治亚大学	终身教授

马杰	安全宝	CEO

万涛	IDF实验室	联合创始人

王清	北京子衿晨风科技有限公司	CEO

肖建国	北京大学	教授

肖新光	安天实验室	首席技术架构师

杨义先	北京邮电大学	教授

张玉清	中科院大学	教授

赵伟	北京知道创宇信息技术有限公司	总裁

郑全战	百度公司软件研究院	院长

### 工作组 (排名不分先后)

姓名	单位名称	职位

段海新	清华大学 网络与信息安全实验室	研究员，主任

诸葛建伟	清华大学 网络与信息安全实验室	副研究员

韩心慧	北京大学 计算机科学技术研究所	高级工程师

陈耀邦	南京紫金（江宁）科技创业特别社区	招商二局局长

江鹏	南京紫金（江宁）科技创业特别社区	项目经理

邸彦萌	百度公司软件研究院	高校合作高级经理

刘光翀	百度公司软件研究院	商务经理

田清	百度公司软件研究院	公关经理

谢峥	南京赛宁信息技术有限公司	总经理

杨坤	蓝莲花网络安全技术战队	队长

### 命题组

Blue-Lotus网络安全技术战队

Disket网络安全技术战队

Shellphish网络安全技术战队

## 背景

1994年，世界头号黑客米特尼克在美国逃亡期间，为了躲避FBI的追查，用假身份搭上了纽约飞往中国上海的国际航班，在飞机上遇到机组人员盘查时，忽然遭遇闪电恶劣天气，一道闪电通过飞机舷窗玻璃进入米特尼克的手臂，米特尼克晕了过去。米特尼克醒来之后已经要下飞机了，在机场米特尼克惊奇地发现自己穿越到了2014年，但一查FBI网站，郁闷地看到自己仍然在FBI的国际通缉名单上。于是米特尼克只能继续选择在中国逃亡......

由于米特尼克未能成功截获FBI与中国国际刑警的私密通信，3月10日上午，米特尼克在临时居所还在奋战BCTF，然而遭遇了中国国际刑警的突击抓捕行动，在国际刑警敲门之际，米特尼克用事先准备好的绳索打算从窗外逃离，却没料到从淘宝上买的绳索太坑爹断掉了，米特尼克一头栽倒地面，昏迷过去。在米特尼克苏醒后，发现自己又穿越回了20年前的航班上，只能无奈的被机组人员抓捕回国。

## MISC

### 初来乍到: 100

**描述**

米特尼克刚到中国人生地不熟，想要找到一些中国的黑客朋友帮助他，他知道Capture The Flag夺旗竞赛是黑客云集的地方，于是也报名参加了中国第一次全国性的CTF大赛 @BCTF百度杯网络安全技术对抗赛。而要进入BCTF圈交流，米特尼克需关注并@BCTF百度杯网络安全技术对抗赛，才能找到一个密语。

### 内网探险: 200

**描述**

为了收集更多参加 BCTF 大赛的中国黑客朋友的信息，米特尼克决定尝试渗透进入 BCTF 的内网以获取更多的信息。通过信息搜集和网络监听，他发现了进入内部数据库的一个入口代理，并且在代理入口处拿到了少量流量数据。正当他想继续收集更多信息的时候，他的行迹被发现并被踢出了网络。
[http://bctf.cn/files/downloads/misc200_23633b6b34ccf6f2769d35407f6b2665.pcap](http://bctf.cn/files/downloads/misc200_23633b6b34ccf6f2769d35407f6b2665.pcap) 入口代理：[218.2.197.236:12345](218.2.197.236:12345)

本地下载：[misc200_23633b6b34ccf6f2769d35407f6b2665.pcap](/attach/misc200_23633b6b34ccf6f2769d35407f6b2665.pcap)

**公告**

新提示：“特别报道，内网防护系统出现了漏洞，大家赶紧上阿！”

提示2:构造数据包

提示1:DNS

请不要使用脚本在服务器上暴力枚举。 违反规则的会酌情惩罚。

题目描述有更新。

### 诱捕陷阱: 300

**描述**

米特尼克从FBI探员凯瑟琳邮箱中发现了一位中国安全专家发给她的邮件，邮件内容如下： 我在THU高校部署了一些诱骗系统，捕获到了与米特尼克网络攻击行为相关的数据，见附件，我觉得你们有必要深入分析一下。当然如果你们没有能力分析的话，可以聘用我做技术顾问，不过我的咨询费用很高哦。

附件：[http://bctf.cn/files/downloads/dionaea.bistream.38930db22ae8cc6a2e589672ca39dca9](http://bctf.cn/files/downloads/dionaea.bistream.38930db22ae8cc6a2e589672ca39dca9)

米特尼克非常急迫地想知道这位中国安全专家到底发现了什么？

本地下载：[dionaea.bistream.38930db22ae8cc6a2e589672ca39dca9](/attach/dionaea.bistream.38930db22ae8cc6a2e589672ca39dca9)

**提示**

\[hint0\]: 也许蜜罐replay会帮助你:)

\[hint1\]: 好吧，再提示另一段蜜罐log，只能说这么多了.[http://bctf.cn/files/downloads/kippo.ttylog.692ce16db7d940cb9ec52a8419800423](http://bctf.cn/files/downloads/kippo.ttylog.692ce16db7d940cb9ec52a8419800423)

本地下载：[kippo.ttylog.692ce16db7d940cb9ec52a8419800423](/attach/kippo.ttylog.692ce16db7d940cb9ec52a8419800423)

### 海报探秘: 300

**描述**

米特尼克在探索专家的项目网站时发现了一张奇怪的海报。他敏锐地洞察到其中隐藏着一条秘密信息，并最终发现了它。

[http://bctf.cn/files/downloads/post_8140b05f5a77ec6c349ccda6deab07e9.png](http://bctf.cn/files/downloads/post_8140b05f5a77ec6c349ccda6deab07e9.png)

本地下载：[post_8140b05f5a77ec6c349ccda6deab07e9.png](/attach/post_8140b05f5a77ec6c349ccda6deab07e9.png)

### 秘密通信: 500

**描述**

通过对FBI与中国安全专家线上活动的跟踪，米特尼克已经感觉到危险临近，于是他入侵了专案组中国国际刑警的手机，并植入监控软件，dump出了手机数据。米特尼克从手机中发现了这位国际刑警和FBI探员凯瑟琳的短信通信记录，吓出一身冷汗，但还没有找到最重要的通信内容。危急关头，米特尼克必须静下心来分析每条可疑的线索，才有可能躲过这一劫！

[http://pan.baidu.com/s/1hCmfk](http://pan.baidu.com/s/1hCmfk) 提取码 `ofto`

本地下载：[memory.dmp_689497c5c864e7a047323d01ba3e1d3c.xz](/attach/memory.dmp_689497c5c864e7a047323d01ba3e1d3c.xz)

**提示**

提示0: 仔细读题

提示1: MISC题目有各种植入哦~

## PPC & CRYPTO

### 混沌密码锁: 100

**描述**

据传说，米特尼克进任何门都是不需要钥匙的，无论是金锁银锁还是密码锁。使用伪造身份在BAT安全部门工作的时候，有一扇带着密码锁的大门吸引了他的注意。门后面到底藏着什么呢？米特尼克决定一探究竟。

[http://bctf.cn/files/downloads/passcode_396331980c645d184ff793fdcbcb739b.py](http://bctf.cn/files/downloads/passcode_396331980c645d184ff793fdcbcb739b.py) 218.2.197.242:9991 218.2.197.243:9991

本地下载：[passcode_396331980c645d184ff793fdcbcb739b.py](/attach/passcode_396331980c645d184ff793fdcbcb739b.py)

**公告**

@BCTF百度杯网络安全技术对抗赛 组委会工作组发现存在多支战队存在作弊形式，请相关队伍在12点前通过IRC或者官方微博私信向组委会工作组进行解释，我们会根据情况进行处理，否则将直接取消发现作弊行为队伍的参赛资格。

FLAG 提交的时候是不需要带外部的 BCTF{} 标记的，只需要提交大括号之内的字符串即可，请大家注意！其它题目也是如此

请不要使用脚本在服务器上暴力枚举，大家可以在本地尝试。 违反规则的会酌情惩罚。

### 他乡遇故知: 200

**描述**

逃离到中国的米特尼克与以前的老朋友都失去了联系，这让他常常怀念逝去的时光。在一次潜入某著名外企尝试获取重要资料的行动中，米特尼克还没有拿到目标文件就不幸被保安发现了。在逃离的过程中，他闯进了一个办公室，结果惊奇地发现自己二十年前的老朋友 Tupper 就在眼前。更神奇的是，Tupper 知道米特尼克需要什么，给了他想要的东西并且帮助他成功脱逃。你知道米特尼克拿到的信息是什么吗？

[http://bctf.cn/files/downloads/meeting-tupper_baaa58809f2a0435cb5f282ce4249fdf.txt](http://bctf.cn/files/downloads/meeting-tupper_baaa58809f2a0435cb5f282ce4249fdf.txt)

本地下载：[meeting-tupper_baaa58809f2a0435cb5f282ce4249fdf.txt](/attach/meeting-tupper_baaa58809f2a0435cb5f282ce4249fdf.txt)

**提示**

1. 论文很重要

### 比特币钱包: 300

**描述**

来到中国后，米特尼克身无分文了，怎样赚一大笔钱以备不时之需呢？比特币的爆发引起了他的注意。FBI 从丝绸之路缴获的大量比特币成了他的目标，他也想借此机会嘲笑一下 FBI。不费吹灰之力，他就搞定了这笔比特币巨款。你知道他是怎么搞定的吗？

[http://bctf.cn/files/downloads/robotum_9332cfdb5e503889e24e757d962a7454.html](http://bctf.cn/files/downloads/robotum_9332cfdb5e503889e24e757d962a7454.html)

本地下载：[robotum_9332cfdb5e503889e24e757d962a7454.html](/attach/robotum_9332cfdb5e503889e24e757d962a7454.html)、[robotum_9332cfdb5e503889e24e757d962a7454.png](/attach/robotum_9332cfdb5e503889e24e757d962a7454)

**提示**

1. 机器人的眼睛是一个时钟，时钟是会走的阿，亲！

2. 要做出此题，请先研究清楚比特币地址签名机制和 warpwallet 的用途

3. 邮件发送格式说明，邮件内容那一行千万别写中文，verify 的部分不包含首尾的空格和回车(也就是 strip)，下面的 signature 是 base64 串，可以使用 bitcoin-qt 客户端进行 sign 和 verify message 来验证

**公告**

增加新提示

增加提示，此题背景知识要求较高，需要耐心研究

提示已出，密码题都有和密码学相关的工作要做，各位亲不要当做 web 随便猜呀，加油！

### 地铁难挤: 400

**描述**

米特尼克需要用社工办法拿到THU安全专家的磁盘镜像以了解更多信息，于是他收买了THU专家的博士生，来到BJ市需要与博士生当面联系。但是，来到BJ市之后遇到的第一个问题就是交通。BJ市人满为患，上下地铁时人们也不先下后上，而是互相挤。左边的人想挤到右边下车，右边的人也想挤到左边上车。你作为米特尼克在BJ的一位小伙伴，能否帮他和所有乘客设计一个尽量少移动次数的方案，使得需要上车的人都上车，需要下车的人都下车。

[218.2.197.242:6000](218.2.197.242:6000) or [218.2.197.243:6000](218.2.197.243:6000)

**提示**

此题是PPC

1. 地铁和车都是背景描述而已，和题目没关系，本题的目标就是让左边的人 L 都到 右边去，右边的人 R 都到左边来
 
2. 人的移动规则和游戏规则需要大家遍历出来，每次输入一个数字(20以内)

### 超级加解密: 500

**描述**

米特尼克感觉到 THU 安全专家掌握着大量的高价值信息，于是他开始捕捉安全专家的行动轨迹，然后安全专家不愧是安全专家，各种信息都使用了最先进的 RSA 算法来加密解密。米特尼克再次施展神技，动用了社会工程、漏洞利用、飞檐走壁、胸口碎石等毕身绝学之后终于偷到了半张宝贵的使用加密解密系统的截图。可是，怎么利用这半张截图来找回那丢失的秘密呢？

截图：[http://bctf.cn/files/downloads/adv-rsang_e213b3e09e2164c42b39a3eedb9be38c.png](http://bctf.cn/files/downloads/adv-rsang_e213b3e09e2164c42b39a3eedb9be38c.png)

服务：[218.2.197.242:1481](218.2.197.242:1481) or [218.2.197.243:1481](218.2.197.243:1481)

本地下载：[adv-rsang_e213b3e09e2164c42b39a3eedb9be38c.png](/attach/adv-rsang_e213b3e09e2164c42b39a3eedb9be38c.png)

**提示**

1. crypto 题目不会卡大家OCR的，建议大家OCR或者抄数字之前，先仔细看看图片内容

2. 请仔细看 [http://en.wikipedia.org/wiki/RSA_(algorithm)](http://en.wikipedia.org/wiki/RSA_(algorithm))

## PWN

###后门程序: 100

**描述**

米特尼克拿到了BAT数据中心的口令后，为了确保口令被更改后仍能登陆数据中心，他从一位小伙伴那拿到了一个后门程序植入进了服务器。这个后门程序没有任何说明，但是米特尼克迅速找到了使用方法。

后门程序：[http://bctf.cn/files/downloads/backdoor_844d899c6320ac74a471e3c0db5e902e](http://bctf.cn/files/downloads/backdoor_844d899c6320ac74a471e3c0db5e902e)

安装地址：[218.2.197.250:1337](218.2.197.250:1337)

安装地址2：[218.2.197.249:1337](218.2.197.249:1337)

本地下载：[backdoor_844d899c6320ac74a471e3c0db5e902e](/attach/backdoor_844d899c6320ac74a471e3c0db5e902e)

### 身无分文: 200

**描述**

米特尼克在BAT上班时，发现很多同事都在用新款Android手机，很是羡慕，他也想搞一部，来替换他那部用了“二十多年”的摩托罗拉手机。但是他在BAT公司还没拿到第一笔工资，用假身份申请的信用卡在租房与日常饮食上也快刷爆了，可以说是身无分文了。这却难不倒米特尼克，他发现了这个销售手机的在线商店。商店地址：[218.2.197.251:1234](218.2.197.251:1234)

[http://bctf.cn/files/downloads/mobile_shop_4d904f700ef95bae39936cd9c0829d31](http://bctf.cn/files/downloads/mobile_shop_4d904f700ef95bae39936cd9c0829d31)

本地下载：[mobile_shop_4d904f700ef95bae39936cd9c0829d31](/attach/mobile_shop_4d904f700ef95bae39936cd9c0829d31)

### 情报窃取: 300

**描述**

米特尼克在凯瑟琳手机中窃取到一些情报，成功逃脱了一次针对他的抓捕行动。然而在中国国际刑警的建议下，凯瑟琳在手机上安装了百度手机卫士，将米特尼克植入的木马应用检测并移除掉了。米特尼克必须找到另外的情报窃取渠道，他发现凯瑟琳经常使用一个专用的在线邮箱客户端，米特尼克必须侵入在线邮箱的服务器。

[218.2.197.244:2337](218.2.197.244:2337)

[http://bctf.cn/files/downloads/mailbox_177d7690bb16ccae7f7e6406a643ca05](http://bctf.cn/files/downloads/mailbox_177d7690bb16ccae7f7e6406a643ca05)

[http://bctf.cn/files/downloads/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a](http://bctf.cn/files/downloads/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a)

本地下载：[mailbox_177d7690bb16ccae7f7e6406a643ca05](/attach/mailbox_177d7690bb16ccae7f7e6406a643ca05)、[libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a](/attach/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a)

### 窃密木马: 300

**描述**

米特尼克得知追捕他的FBI探员凯瑟琳曾用过k9mail发邮件讨论一个对他的联合抓捕方案，他必须得知这个方案才能逃出生天。从对FBI的渗透获得的情报里，米特尼克了解到凯瑟琳和其他探员经常在一个在线应用市场上下载应用安装。米特尼克找到了市场的上传入口，该如何搞定？

市场上传入口：[http://218.2.197.252:5000](http://218.2.197.252:5000)

已知: 凯瑟琳很信任这个市场；凯瑟琳只会打开每个应用很短时间。

**提示**

hint1：凯瑟琳使用的手机系统版本并不新，无法兼容新版应用。

hint2：read the k9mail docs

hint3：no naive coding, no rooted environment

**公告**

有选手根据队名和提交时间，质疑前两个解出此题的队伍串通flag，经过组委会对二者解题方法的仔细审查，确认两队采用的是不同的正确解法，请大家消除疑虑。

再次上线。

抱歉，系统运行再次出了问题，我们在紧急修复中

系统已经重新上线，可以正常工作:-P

系统出了点问题，正在维护，请大家稍等，修复后会通知。

新提示放出。

代码中有个小笔误，已修改，对目前的解题没有影响

站点已升级，happy pwning:P

本题站点负载过大，下线维护，升级后上线

给了一个小小的提示。

### 黑客信息系统: 400

**描述**

逃亡中的米特尼克从来没有放弃过反击，每天攻击 FBI 的内部系统获取情报也是他的必修课。一天，他在 FBI 服务器中畅游的时候，无意中发现了一个黑客信息系统，而自己就列在其中，而且显示FBI已经和中国国际刑警联合建立了一个针对他的专案组。他非常紧张，必须马上搞定这个黑客信息系统，找到追查他的中国国际刑警信息。

系统地址：[218.2.197.245:31337](218.2.197.245:31337)

[http://bctf.cn/files/downloads/his_04668394b7e6e02feb0a25087de871f2](http://bctf.cn/files/downloads/his_04668394b7e6e02feb0a25087de871f2)

[http://bctf.cn/files/downloads/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a](http://bctf.cn/files/downloads/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a)

本地下载：[his_04668394b7e6e02feb0a25087de871f2](/attach/his_04668394b7e6e02feb0a25087de871f2)、[libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a](/attach/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a)

### 新型架构: 500

**描述**

米特尼克在BAT公司的工作任务之一就是对公司内部的各种系统做渗透测试，他几乎攻破了所有系统，除了一个在新型架构服务器上运行的服务——员工培训管理系统，他对这种架构一无所知，小伙伴们你们能帮助他吗？

系统地址：[218.2.197.248:4321](218.2.197.248:4321)

[http://bctf.cn/files/downloads/libc.so.6_43809daf20d1e9e364f097f2e9b9db2e](http://bctf.cn/files/downloads/libc.so.6_43809daf20d1e9e364f097f2e9b9db2e)

[http://bctf.cn/files/downloads/course_50b8451532469cf4def2a7103b13ba85](http://bctf.cn/files/downloads/course_50b8451532469cf4def2a7103b13ba85)

本地下载：[libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a](/attach/libc.so.6_6af07f67f3ea510adb71fb446e3b6e3a)、[course_50b8451532469cf4def2a7103b13ba85](/attach/course_50b8451532469cf4def2a7103b13ba85)

**公告**

资格赛最后一道题已经开放，keep on pwning:-P

## REVERSE

### 最难的题目: 100

**描述**

米特尼克路被各路大神追查痛苦饥渴难耐。顺手捡起身边一个水杯，打开瓶盖，居然写着one more，实在太神奇了。

[http://bctf.cn/files/downloads/re_100.8cd4820cbd1300bda951e694298f73a0](http://bctf.cn/files/downloads/re_100.8cd4820cbd1300bda951e694298f73a0)

本地下载：[re_100.8cd4820cbd1300bda951e694298f73a0](/attach/re_100.8cd4820cbd1300bda951e694298f73a0)

### 小菜一碟: 200

**描述**

米特尼克渐渐熟悉了现代的生活，并打算在中国开始新的生活，他用伪造身份进入了一个互联网公司BAT的安全部门工作，BAT庞大的数据中心对米特尼克来说无疑是一个巨大宝藏，但是以他的身份和资历，还没有权限查看这些数据。经过一番探查，米特尼克得到了进入数据中心的口令校验程序，要从中找到口令，这对米特尼克来说不是小菜一碟吗？ ［flag为输入的口令串］

[http://bctf.cn/files/downloads/divide.c3fcf65dd922249f6fb8a2fdf336d21](http://bctf.cn/files/downloads/divide.c3fcf65dd922249f6fb8a2fdf336d21)

本地下载：[divide.c3fcf65dd922249f6fb8a2fdf336d21](/attach/divide.c3fcf65dd922249f6fb8a2fdf336d21)

**提示**

\[hint 0\]: 什么？小学课本上的除法运算还需要暴力破解？

\[hint 1\]: google 0x66666667

**公告**

分值已升为200分

出新的提示了：google 0x66666667

题目描述给出提示了，小伙伴们快去看吧！！！

### 解锁密码: 300

**描述**

虽然米特尼克在中国被捕的可能性很小，但是谨慎的米特尼克从来不会放过蛛丝马迹的线索，中国的国际刑警很可能会配合FBI对其实施抓捕，这里的安全形势更加复杂。在成功控制了BAT数据中心后，米特尼克掌握了公司全体员工的个人信息，必须对公司高层的邮件和手机进行全面监控，以尽早发现对其相关的调查。米特尼克在试图向目标手机植入远控程序时，发现他们的手机都受到一种特殊程序的保护，需要一个解锁密码来关掉这个保护程序，但是米特尼克的年代还没有Android，他需要一个小伙伴来帮他找到这个解锁密码，你愿意帮助他吗？ [flag为输入的解锁码]

3.9 21:15分更新附件：

[http://bctf.cn/files/downloads/FindTheKey.81c9373ea9622ac0ccfb24f2eb72ce41](http://bctf.cn/files/downloads/FindTheKey.81c9373ea9622ac0ccfb24f2eb72ce41)

本地下载：[FindTheKey.81c9373ea9622ac0ccfb24f2eb72ce41](/attach/FindTheKey.81c9373ea9622ac0ccfb24f2eb72ce41)

**提示**

\[hint 0\]：或许不是每一个函数都用得到!

\[hint 1\]：flag是一句有趣的话

**公告**

刚才附件上传错误，请大家重新更新，耽误大家时间，非常抱歉！

附件更新，请大家重新下载，修正答案不唯一问题

由于我们失误，导致有效flag可能不唯一，题目描述已进行了一些补充

或许不是每一个函数都用得到!

提升为300分。

### 码海迷踪: 300

**描述**

米特尼克成功拿到了解锁码，并且开始监控BAT的高层员工，发现了一个被经常访问的文件，可是米特尼克打开后却什么都没发现，你能帮米特尼克找到文件中的秘密吗？ [flag不带BCTF前缀] 

[http://bctf.cn/files/downloads/vm.58d83ab038a31d6ac33e921076491301](http://bctf.cn/files/downloads/vm.58d83ab038a31d6ac33e921076491301)

本地下载：[vm.58d83ab038a31d6ac33e921076491301](/attach/vm.58d83ab038a31d6ac33e921076491301)

**提示**

\[hint0\]: hex2ascii

\[hint1\]: 'HACK_THE_PLANET' is not the flag!

### 神秘系统: 400

**描述**

米特尼克掌握了THU安全专家的一些信息，但是这个专家是否还掌握更多的信息，米特尼克必须探个究竟，通过社工办法，他拿到了这个专家的部分磁盘镜像，帮助米特尼克从中找到更多的信息吧！

[http://bctf.cn/files/downloads/bctfos.3bbbcae1ea13b566477c99941a5eee63](http://bctf.cn/files/downloads/bctfos.3bbbcae1ea13b566477c99941a5eee63)

本地下载：[bctfos.3bbbcae1ea13b566477c99941a5eee63](/attach/bctfos.3bbbcae1ea13b566477c99941a5eee63)

### 最简单的题目: 500

**描述**

最简单的题目

这是米特尼克从BAT公司内网中得到的一款商业程序的一部分。他在逃亡途中计划先将其破解，日后再放出来。但是因为逃亡路上时间有限，且大部分公交车、出租车上都没有电源，米特尼克发现他很难长时间专注地分析这个程序。请小伙伴们帮他搞定这个程序吧！

\[文件1\] [http://bctf.cn/files/downloads/TheEasiestChal.ab056547108ee3a068ccbe741c17ad46](http://bctf.cn/files/downloads/TheEasiestChal.ab056547108ee3a068ccbe741c17ad46)

\[文件2\] [http://bctf.cn/files/downloads/enc.bin.512706a4c6741c0a4e090c887ec4914f](http://bctf.cn/files/downloads/enc.bin.512706a4c6741c0a4e090c887ec4914f)

本地下载：[TheEasiestChal.ab056547108ee3a068ccbe741c17ad46](/attach/TheEasiestChal.ab056547108ee3a068ccbe741c17ad46)、[enc.bin.512706a4c6741c0a4e090c887ec4914f](/attach/enc.bin.512706a4c6741c0a4e090c887ec4914f)

**提示**

\[hint0\]: 如果只是爆破的话，米特尼克自己也能搞定，就用不着大家帮忙了。

\[hint1\]: 老师经常教导我们，做题前先要读懂题。黑客也应该这样吧？

\[hint2\]: MP

\[hint3\]:它真的是在解密么？

**公告**

hint3:它真的是在解密么？

提示已放出。

## WEB

### 分分钟而已: 100

**描述**

米特尼克看到现代的互联网这么发达简直惊呆了，但几秒钟之后他就回过了神，摩拳擦掌准备一试身手，他需要拿到BAT公司中一个名叫Alice员工的秘密文件，Alice只是个初级的网络管理员，所以想来拿他的文件也不过是分分钟的小游戏而已。

[http://218.2.197.237:8081/472644703485f950e3b746f2e3818f49/index.php](http://218.2.197.237:8081/472644703485f950e3b746f2e3818f49/index.php)

### 真假难辨: 200

**描述**

唯有游戏与美食不可辜负。米特尼克拿到Alice的资料之后接着在BAT内网游荡，他发现了一个被限制的游戏，只有管理员Alice自己才能玩，但区区一个管理员的限制怎么能挡住米特尼克爱游戏的心！

[http://218.2.197.238:8081/76446cb94ef19b1d49c3834a384938d1/web200/](http://218.2.197.238:8081/76446cb94ef19b1d49c3834a384938d1/web200/)

**公告**

本题发现一个bug，不影响之前提交通过的队伍。题目代码有变更，请重新测试。

### 见缝插针: 300

**描述**

在玩过管理员的小游戏并发现秘密信息之后，米特尼克决定研究一下这个管理员管理的所有站点，大多数都被米特尼克翻了个底朝天，直到他发现了这个网站。

[http://218.2.197.239:1337/9b30611986fe1822304bdc98fa317cde123/web300/](http://218.2.197.239:1337/9b30611986fe1822304bdc98fa317cde123/web300/)

**公告**

Web 300 下线维护~

web300重新上线，求fxxk。

bug fixing “汪汪冒险岛”发现题目非预期漏洞，命题组正在修复中，给与“汪汪冒险岛”额外130分奖励。

### 冰山一角: 400

**描述**

在上一个站点中米特尼克学会了特殊的Web技巧，在开始渗透前，他会左顾右盼装作看风景。他对BAT这个公司的好奇与日俱增，似乎BAT并不像是表面上看起来的那样，仅仅是个互联网公司。他追寻一系列蛛丝马迹找到了这个站点，里面似乎隐藏着BAT的一项核心机密。

站点入口：[http://218.2.197.240:1337/0cf813c68c3af2ea51f3e8e1b8ca1141/index.php](http://218.2.197.240:1337/0cf813c68c3af2ea51f3e8e1b8ca1141/index.php)

（注意：本题flag非“BCTF{可见字符串}”形式）

**公告**

小hint，盐在头中。

解决这道题不需要命令注入，不需要扫描器，不需要XSS，你所需要的只是SQLi，SQLi，SQLi！

### 花钱如流水: 500

**描述**

米特尼克之前从FBI那里搞到一大笔比特币，一秒钟变土豪，提现之后挥霍无度，更是被街上兜售绝世武林秘籍的老大爷狠狠地骗了一笔，结果一大笔巨款竟然被他分分钟用完了，他只好把目光投向了一个比特币交易平台M7G0x，85w比特币在等待着你哟少年。

[http://218.2.197.241:9080/d5a9b455db0929e17a2e12d21e786643/](http://218.2.197.241:9080/d5a9b455db0929e17a2e12d21e786643/)

**公告**

神爱注入，还是SQLi，仔细找找注入点，别妄想用sqlmap，出题人睡了，我只能帮你们到这儿了。

大家快来看土豪！！！ [http://bctf.cn/files/downloads/hint_web500.jpg](http://bctf.cn/files/downloads/hint_web500.jpg)

市场上又有btc土豪出现！

这道题使用的是btc的testnet，第一步的目标参见“帮助”。

本地下载：[hint_web500.jpg](/attach/hint_web500.jpg)