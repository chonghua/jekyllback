---
layout: post
title: "Evernote 代替品"
tagline: ""
description: ""
category: 经验总结
tags: [Evernote]
last_updated: 2016-10-04
---


Evernote 最近一次的 Policy 更新[^policy] 真的太人人失望啦。如果说增加功能，增加收费，我完全不反对，我反对的是将现有的免费功能加入到收费功能中。

一些代替品：

OneNote, Google Keep, WizNote, Simplenote, youdao, Laverna

<http://alternativeto.net/software/evernote/>

我的简单需求：

1. 多平台同步(Mac, Windows, Linux) + web + Android online and offline
2. 好用的 clip Chrome 插件
3. 最好支持多人编辑
4. 支持笔记分享
5. 支持代码高亮，其实这一点 Evernote 也做不到

## OneNote

很早就在用了，只是当时并不支持多端同步，所以在 Android 崛起之后就渐渐的转到了 Evernote。OneNote 从各个方面来看都完全符合我的要求，并且最近的更新 Chrome 插件也做的非常不错。只是 Android 端实在太烂，让我提不起兴趣的还有微软的名号，以及缺乏 Linux 客户端。

## Google Keep
在我看来只适合轻量级的笔记，网页摘录也做的不是很好。

## WizNote
其实之前也一直在使用中，但由于之前 Evernote Chrome Clipper 做的实在太棒了，所以一直没转过来，为知笔记还是很多人推荐的，容量同步 500M/月， 30M / 单笔记，相比 Evernote 已经很不错了。笔记分享这款做的并不是很好，但觉得可以一试。并且 WizNote 支持 markdown 这一条还是非常赞的。

## Simplenote
虽然很多人推荐，但是没有 Chrome Clipper，并且注册账号登陆看了一眼 Web 版，功能比较简单，并且就是功能比不上 Evernote 的复刻版，并不是太想使用它，哪一天它也变成 Evernote 怎么办

## youdao
有道云笔记在国内还是很多人使用的，但是登陆一看总共3G 空间，顿时让我不想用了。

## Laverna
这次寻找的过程最让我感到意外的就是这个了，开源，Linux端，集成 Dropbox 同步，代码高亮， Markdown 格式，简直就是完美的代替品，它的 Github 主页上就光明正大的写着 Evernote alternative。但是在我看来它已经完全超越了 Evernote，出了没有一个公司去运营它，它在功能上已经完全超越了 Evernote。

<https://laverna.cc>

经过以上的总结，接下来在 WizNote 以及 Laverna 中尝试选择一个当笔记同步使。为知笔记的Chrome [扩展](https://chrome.google.com/webstore/detail/jfanfpmalehkemdiiebjljddhgojhfab) ，相对 Evernote 弱了一些，但是也非常不错。 WizNote 当然各个客户端都有，最棒的是 Linux 客户端也有。多人编辑和笔记分享这一点 WIzNote 非 VIP 用户无法使用，但是单纯的当做笔记来用已经完全足够了。 最后代码高亮很早就已经支持了的。

剩下的用 Evernote 来共享笔记，和别人协作好了。

## 两个月之后更新

现在已经稳定使用 WizNote 了， Evernote 中的数据基本导出到 WizNote，而目前 WizNote 使用过程中基本没有产生什么问题。现在就做一个 WizNote Review。官方的宣传中突出了如下特点：

	多级目录、多级标签、Markdown、无限存贮空间

而这4点确实很吸引人，多级目录和标签可以让文件夹更加整洁，原生支持 Markdown 让写作更加便捷，无限空间就让人不用担心。

### Linux Mint 安装
参考 [GitHub](https://github.com/WizTeam/WizQTClient) 或者 [官网](http://www.wiz.cn/wiznote-linux.html)，都有详细的安装说明。基本上使用如下命令即可。

    $ sudo add-apt-repository ppa:wiznote-team
    $ sudo apt-get update
    $ sudo apt-get install wiznote

### Evennote 迁移 WizNote
WizNote 菜单中能很方便的导入 Evernote 中导出的文件。就不展开细讲了。

### 扩展工具

- Chrome Web clip，参考官网: <http://www.wiz.cn/downloads-webclipper.html>
- url2wiz 工具，提供 url 就可以将内容保存到笔记：<https://note.wiz.cn/url2wiz>
- 利用 IFTTT 可以将 InoReader 加心文章保存到 WizNote，查看我的 Recipe ： <https://ifttt.com/recipes/470673-save-star-article-in-inoreader-to-wiznote>

###
如果你也想用 WizNote ，可以用我的邀请码： <https://note.wiz.cn/i/eaa1f6a0> ，捂脸。

[^policy]: Evernote [限制两台设备](https://blog.evernote.com/blog/2016/06/28/changes-to-evernotes-pricing-plans/)