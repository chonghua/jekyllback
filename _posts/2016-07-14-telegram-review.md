---
layout: post
title: "Telegram 技巧"
tagline: ""
description: ""
category: 产品体验
tags: [Telegram, IM, ]
last_updated: 
---


感觉是时候写一篇 Telegram 的安利文了。Telegram 简单介绍就是一款 IM， 及时聊天工具。当然其实他远远的超越了一个IM，却依然保持了作为一个IM应有的速度和快捷。

对于基本功能，[電腦玩物 Telegram 10技](http://www.playpcesor.com/2015/12/telegram-10.html) 已经将 Telegram 的主要功能及使用技巧说得非常明白了，就不再多说了。其中我最喜欢的几点：

- 跨平台，这也正是我一直坚持 Hangout 的原因之一，我不喜欢整天抱着手机，我在电脑前的时间可比拿手机的时间长，我也不希望我坐下之后需要花很长的时间，打开一个客户端输入密码，然后还要花一段时间同步消息，关键有些客户端之间还不能同步消息记录。而 Telegram 给我的体验就和 Hangout 一致，多个平台，多个设备几乎能够在同一时间受到消息，我也能够在任何一个客户端回复，并且所有客户端的消息都是同步的。
- Bot ，聊天机器人，很久之前的 Gtalk 也是支持机器人的，对那个自动翻译的机器人还是略有记忆，只是后来就没有后来了。而 Telegram 正是将聊天机器人这个命题重新书写了。开放的Bot系统，让 Telegram 成为了一个全能的平台，他是一个 IM ，他也可以是一个翻译工具，只需要一个翻译bot，他也可以是一个RSS阅读器，只需要一个RSS订阅bot，他也可以是一个Tinder，只需要一个约会bot...... Telegram 可以变成想要的任何工具，更不说官方集成的 @gif， @bold，@sticker [等等 bot](https://core.telegram.org/bots)  。
- 开放，作为一个 IM，应该能够包容万千也能够开放的分享，这就提到了 Telegram 支持的媒体内容，文字，链接，音频，视频，gif，表情贴图，能够想到的几乎所有内容都可以兼容，甚至有人直接 Telegram 来当音乐播放器。并且 Telegram 在图片以及 Gif 分享的时候做了很多的优化处理，我在日常使用中几乎没有感受到任何卡顿，甚至流量的消耗也在我可接受的范围。

## Sticker

说了这么多，其实重点想要谈谈他的贴图以及 Bot 系统。首先是贴图，在刚上手 Telegram 的时候，我就被他丰富的表情震撼到了，就像他在 [Blog 中所说](https://telegram.org/blog/stickers)， Telegram 觉得现存任何一个 IM 的表情系统设置都不是很理想，封闭，收费，并且糟糕透顶，于是 Telegram 大笔一挥自己做了一套系统，这是我迄今为止使用过最赞的表情贴图系统。尤其是在最近迷上 Pokemon Go 之后，更是找到了很多萌萌的小精灵。

从下面两个网站能够找到你想要的绝大多数表情，多到无法想象：

- <http://stickergram.ru/13.html>
- <http://telesticks.eu/>


如果这两个网站都无法让你满足，Google，以及官方的 @sticker 机器人都可以帮你找到喜欢的表情。

## Bots
几个神奇的内置 bot

### @gif
寻找 gif bot，使用最简单了，聊天时直接输入 `@gif whatever I like` ， Telegram 会帮你搜索 `whatever I like` 字段的内容，点击分享即可。


### @bold
Markdown bot 格式化输入

输入： <code>@bold this is *bold* , this is _Italic_ , and this is `some code with *bold*`</code> 。即可得到。

![Telegram bold bot](https://lh5.googleusercontent.com/-2OBcfO5Pxlk/V4eoHnsOnCI/AAAAAAAA_8M/TThMXecHLEkUBumQHiiqK_UPbbdO-cljgCLcB/w435-h72/telegram_bold_bot.png)

### @vote
@vote 用来创建投票

### @like
用来创建 emoji based Like 投票。

### @Stickerdownloadbot
发送给这个 bot 表情，他就自动将表情转换成 png 。

## Links

- 源代码：<http://telegram.org/apps#source-code>
- 通信协议： <https://core.telegram.org/mtproto>
- API : <https://core.telegram.org/api>
- 注销账户：<https://telegram.org/deactivate>
