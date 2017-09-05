---
title: 小系统：文件和工具架构
categories: 
  - 小系统
---

今天终于把域名结构付诸了行动，同时理清了各个软件和文件的信息流及交互。

## 1
文件架构是这样子的：
![Screen Shot 2017-07-28 at 19.58.01](http://7xs0kh.com1.z0.glb.clouddn.com/2017-07-28-Screen Shot 2017-07-28 at 19.58.01.png)
重点是：
book.heshengjun.com：一上来某个领域，就要想着写一本书。同步至gitbook，同时备份至云。
gist.heshengjun.com：放自己的文章，用textmate同步至gist，同时备份至云。
keynote.heshengjun.com：放自己的keynote。备份至云。

其他几个：
archive.heshengjun.com放一些参考过后无用的文件，备份至云。
bigv027.github.io：作为版本库放github上的博客显示。原体在icloud的mweb文件夹，同时备份至云。
papers.heshengjun.com：放的主要是Zotero的数据库及参考（非学术）文献。备份至云。
personal.heshengjun.com：放自己的个人文件。

##2
工具架构：

ibooks：单体精品epub书，直接软件中全部打开，icould备份及云同步。省去了需要delete everywhere和搜索出现重复的麻烦。ios端可以同步进度。
mweb：library模式放卡片和博客本体；外部模式放重点的book和gist域名文件夹。ios端同步。
textmate：做全文检索和上传gist用。
Zotero：书籍，论文等pdf的降维管理。storage目录建立快捷映射至dropbox文件夹，备份至云。
多看阅读（ios）：对多级目录支持特别好，所以阅读合集类的epub，笔记也可以一键导出到evernote。
Foxit（ios）：支持webdav云，主要ipad端看PDF。Zotero上的PDF可以通过zotfile推送至云。论文阅读多后替换为收费的notability+apple pencile。
Kindle：主用与看虚构类的小说，以及mobi格式的备份。

##3
工具架构的优化大大提高了信息的流动效率。节省的时间可以专注在阅读难书和输出卡片上。几个原则：

- 理论上优质实体书要想方设法收集全，逐步建立信息优势。
- 能读原版书尽量读原版书。
- 不再花大把时间做收集、存储、整理的低保真低效能活动。而是anytime，anywhere——无所不在的学习与成长：

> 凡走过必有学习，凡接触必有长进，凡看过必多懂一些，凡遇到必追根究底，凡高手必不放过，穷追猛打，追问到底。

##小结
时刻把自己想象成机器人，建立机器能识别的接口和协议，剥削机器，批量处理，一次做对，终究提高效率。同理让自己与社会的接口稳定，终究形成信任。

