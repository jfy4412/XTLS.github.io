---
alwaysopen: false
date: "2020-12-23T00:00:00.000Z"
description: Project X 的文档.
# head: <hr/>
hide:
# - toc
post: "&nbsp;"
title: 大史记
weight: 1
---
## 2021.01.25
- 全互联网最好最详细的秘籍入门篇同学们练熟了吗? 🍉老师开始连载[秘籍第一层](../../documents/level-1/)咯...
- [英文版文档网站](/en)逐渐增加内容ing, 感谢各位大佬的辛苦付出~!

<br />

## 2021.01.22

###  [v1.2.3](https://github.com/XTLS/Xray-core/releases/tag/v1.2.3)
---
- 对 SS 协议的支持**又**变强了, 支持单端口多用户!
- 对 trojan 协议的支持也**又**变强了, trojan 的回落也解锁 SNI 分流的新姿势啦~!
- _(VLESS: 嘤嘤嘤)_
- UDP 奇奇怪怪的 BUG 被干掉了, 一个字, "稳定".
- 嗅探可以排除你不想嗅探的域名, 可以开启一些新玩法.
- 向发现问题->开issue->自行测试->自行分析->自行找到问题->自行解决->然后给上下游提交PR的大佬 <img src="https://avatars2.githubusercontent.com/u/8384161?s=32" width="32px" height="32px" alt="a"/> [@Bohan Yang](https://github.com/bohanyang) 致敬!
- 其他美味小樱桃, 惯例更新品尝就对啦.

<br />

## 2021.01.19
- 一些数字
  - 版本发布了 10&nbsp;&nbsp; 个 tag 
  - 解决掉了 100&nbsp; 个 issue
  - 复刻了 300&nbsp; 个 fork
  - 点了 2000 个 star
  - 群 3000 个 人

<br />

## 2021.01.17
- 辛苦的翻译工作开始了, 感谢<img src="https://avatars2.githubusercontent.com/u/60207794?s=32" width="32px" height="32px" alt="a"/> [@玖柒Max](https://github.com/jiuqi9997)和其他所有的翻译大佬们.
- [English version](https://xtls.github.io/en/)

<br />

## 2021.01.15
###  [v1.2.2](https://github.com/XTLS/Xray-core/releases/tag/v1.2.2)
---
- 回落分流又解锁了奇怪的新姿势! 回落中可以根据 SNI 分流啦~! 
- 之前预告的 UUID 修改正式上线.([往下看往下看](#2021.01.12))
- 日志现在看起来比上一次顺眼又更顺眼了一丢丢.
- 远程 DOH 和其他的DNS模式一样学会了走路由分流.
- 当然还有其他各种小糖果.(更新品尝就对了)
- 啊, 还有, 世界上第一個 M1 上跑起 Xray 的男人是 Anthony TSE

<br />

## 2021.01.12
---
- 将要到来的 UUID 修改, 支持自定义字符串和 UUID 之间的映射. 这意味着你将可以这样在配置文件中写id来对应用户.
  - 客户端写    "id": "我爱🍉老师1314",
  - 服务端写    "id": "5783a3e7-e373-51cd-8642-c83782b807c5" (此UUID是 `我爱🍉老师1314` 的 UUID 映射)
- 🍉老师的[小小白白话文](../../documents/level-0/)大结局, 撒花.

<br />

## 2021.01.10
---
- [小小白白话文](../../documents/level-0/)连载上线啦,🍉老师呕心沥血之作, 手把手教你从什么都不会到熟练配置Xray! 
- (可能是整个互联网上, 最详细最有耐心的教你从0开始配置的教程)
- [透明代理](../../documents/level-2/)也增加了更多文章.
- 还有很多细节修改, 文档将会越来越规范! 
- 感谢 [@ricuhkaen](https://github.com/ricuhkaen) , [@BioniCosmos](https://github.com/BioniCosmos), [@kirin](https://github.com/kirin10000)

###  [v1.2.1](https://github.com/XTLS/Xray-core/releases/tag/v1.2.1)
---
- 大量的 UDP 相关修复, 甚至可以在育碧的土豆服务器上玩彩虹六号! 
- Google Voice 应该也可以正常使用 v2rayNG 拨打了.
- 日志现在看起来更顺眼.

<br />

## 2021.01.07
---
- 礼貌和尊重本应是社区不需要明说的准则之一。

<br />


## 2021.01.05
---
- 文档网站正在悄悄的进行着某些神秘的变化。。。，🙊🙊🙊

<br />

## 2021.01.03
---
- 文档仓库第一个PR。🎉<br>
[透明代理（TProxy）配置教程 ](../../documents/level-2/tproxy) ，感谢<img src="https://avatars2.githubusercontent.com/u/41363844?s=32" width="32px" height="32px" alt="a"/> [@BioniCosmos](https://github.com/BioniCosmos)
- tg群突破2500。

<br />

## 2021.01.01
---

【祝大家新年快乐，嗨皮牛耶！】🎆🎇🎆

###  [v1.2.0](https://github.com/XTLS/Xray-core/releases/tag/v1.2.0)
---

🎁在元旦的最后几分钟，v1.2.0它来了，带着周五必更的惯例，带着各位贡献大佬的心血以及 @rprxx 的黑眼圈，不负众望的来了!
- 圣诞礼物[v1.1.5](#20201225)后的元旦礼物🎁，游戏玩家大福利，全面 FullCone。
- （UDP还会继续增强！）
- 如果你已经拆过圣诞礼物，这次还有比圣诞礼物更精美的包装和小糖果哦。（同样不用问，更新品尝就对了）
- （不，下面不是广告，是里程碑。）
- Xray 是有史以来第一个不受限制的多协议平台：只需 Xray 即可解决问题，无需借力其它实现。
  - 一人扛起了所有！支持各大主流协议！
  - 一骑绝尘的性能!
  - 日趋完善的功能!
  - 可怕的生命力与社区亲和力！
- Xray 将继续保持前行！ 因此 [Xray 需要更多的英雄！！](https://github.com/XTLS/Xray-core/discussions/56)！
- PS：请品，请细品[release notes](https://github.com/XTLS/Xray-core/releases/tag/v1.2.0)每一句。似乎有一个小秘密小彩蛋 ~~（啊，有人敲门...我一会和你们说）~~

<br />

## 2020.12.29
透明代理的游戏玩家利好！ Xray-core tproxy 入站， socks出站 UDP FullCone 测试版, [TG群](https://t.me/projectXray)火热测试中

<br />

## 2020.12.25
---
圣诞节快乐！

###  [v1.1.5](https://github.com/XTLS/Xray-core/releases/tag/v1.1.5)
---
- 游戏玩家的圣诞礼物！你可以用xray爽快的打游戏啦！因为有了 SS/trojan UDP fullcone 
- 你可以用你喜欢的格式写配置文件了，比如yaml，比如toml...
- （VLESS 的 UDP fullcone和更多增强很快就到！）
- 无须再担心证书验证被墙，OCSP stapling 已经上线!
- kirin带来了一大波   脚本更新.[脚本在此](https://github.com/XTLS/Xray-install)
- 还有更多美味小樱桃！（不用问，更新品尝就对了）

<br />

## 2020.12.24
因为某些不可描述的原因，Xray 的文档网站已在发布日前偷跑上线。<br>
网址为：[没错你正在看的就是](https://xtls.github.io)

大家可以查阅各种内容也欢迎纠错/提出建议（可发往文档github仓库的issue区）

文档网站需要不断完善和增加内容，以及完善设计。<br>
因此更欢迎大家一起为文档建设添砖加瓦。<br>
[文档的仓库](https://github.com/XTLS/XTLS.github.io)

仓库的readme中有简略教程说明如何帮助xray改进文档网站.<br>
欢迎大家查看，纠错，修改，增加心得。

<br />

## 2020.12.23
Xray-core Shadowsocks UDP FullCone 测试版, [TG群](https://t.me/projectXray)火热测试中

<br />

## 2020.12.21
---
- Project X 群人数 2000+
- 群消息(含游戏群) 日均破万

<br />

## 2020.12.18
---
###  [v1.1.4](https://github.com/XTLS/Xray-core/releases/tag/v1.1.4)
---
- 更低的启动内占用和内存使用优化
- 随意定制的 TLS 提高你的SSL评级
- 支持 XTLS 入站的 Splice 以及支持 trojan 的 XTLS
- 还有在您路由器上使用的Splice最佳使用模式建议

<br />

## 2020.12.17
---

鉴于日益增长群人数和游戏需求, 开启了[TG游戏群](https://t.me/joinchat/UO4NixbB_XDQJOUjS6mHEQ)

<br />

## 2020.12.15
---

[安装脚本dev分支](https://github.com/XTLS/Xray-install/tree/dev)开启, 持续更新功能中.

<br />

## 2020.12.11
---
### [v1.1.3](https://github.com/XTLS/Xray-core/releases/tag/v1.1.3)
---
- 完整版本的 REDIRECT 透明代理模式.
- 软路由 splice 流控模式的优化建议.

<br />

## 2020.12.06
---
### [v1.1.2](https://github.com/XTLS/Xray-core/releases/tag/v1.1.2)
---
- 流控增加 splice 模式, Linux限定, 性能一骑绝尘.
- 增强了 API 兼容

<br />

## 2020.12.04
---
增加 splice 模式

<br />

## 2020.11.27
---
- Project X 的 GitHub 主仓库 Xray-core 已获 500+ stars
- 登上了 GitHub Trending
- Project X 群人数破千，频道订阅数 500+

<br />

## 2020.11.25
---
### [v1.0.0](https://github.com/XTLS/Xray-core/releases/tag/v1.0.0)
---
Xray的第一个版本.
- 基于 v2ray-core 修改而来，改动较大
- 全面增强, 性能卓越, 完全兼容

<br />

## 2020.11.23
---
project X start
