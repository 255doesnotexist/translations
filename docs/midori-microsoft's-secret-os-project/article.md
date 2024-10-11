> 原文链接：https://www.zdnet.com/article/whatever-happened-to-microsofts-midori-operating-system-project/
>
> 作者：Mary Jo Foley, Senior Contributing Editor
> 
> 发表日期：Nov. 10, 2015 at 8:59 a.m. PT

## 微软的“Midori”操作系统项目最终怎么了？

**商业 > 公司 > 微软**

[主页](/) > [商业](/topic/business/) > [公司](/topic/companies/) > [微软](/topic/microsoft/)


得益于一些现已分散的团队成员，有关微软一度秘密的“Midori”操作系统项目的更多信息正逐渐浮出水面。


**作者：Mary Jo Foley，高级特约编辑**

2015年11月10日上午8:59


距离我上次撰写关于微软的“Midori”秘密操作系统项目已经过去一年多了。

![microsoftmidori.jpg](https://www.zdnet.com/a/img/2015/11/10/703f5a92-36c9-4db1-8651-16f0fc4044a3/microsoftmidori.jpg)

但[一位项目参与者的新博客系列](http://joeduffyblog.com/2015/11/03/blogging-about-midori/) 重新燃起了我对现已解散的 Midori 团队及其从近十年开发项目中吸取的经验教训的兴趣。

我第一次在[2008年的博客中提到 Midori](https://www.zdnet.com/article/goodbye-xp-hello-midori/)。当时，微软正在组建[一支由顶尖工程师组成的团队](https://www.zdnet.com/article/microsofts-midori-whos-on-the-all-star-roster/)，以构建一个不基于 Windows 内核的全新操作系统。Midori 团队的任务不仅是从头开始构建操作系统，还要构建一个完整的软件栈，包括浏览器、相关工具等等。

根据团队成员 Chris Brumme 的[领英个人资料](https://www.linkedin.com/profile/view?id=AAEAAAr-uYgBBdqPB7R61HpywLNKXtIcFk26wjo)，Midori 的开发人员最多时曾达到 100 人。Brumme 将自己描述为“这个重要的操作系统孵化项目的联合创始人、架构师，以及最终的总经理”，该项目可以追溯到 2005 年。（Brumme 的个人资料显示，他于 2015 年加入了谷歌。）

Joe Duffy，Midori 的开发经理和语言架构师，最近启动了[一个计划包含十多篇博文的系列，主题是他在 Midori 上的工作](http://joeduffyblog.com/2015/11/03/blogging-about-midori/)。11 月 3 日的第一篇文章是关于[三种安全性（类型、内存和并发）](http://joeduffyblog.com/2015/11/03/a-tale-of-three-safeties/)的。Duffy 目前是微软编译器和语言平台部门的工程总监。

Duffy 在本月初的博客中写道，在 Midori 项目中，“尽管我们从 C# 和 .NET 开始，[但为了安全、可靠性和性能，我们被迫彻底放弃了它们](http://joeduffyblog.com/2015/11/03/blogging-about-midori/)”。“现在，我正在努力将许多经验教训应用回现有产品中，包括，也许令人惊讶的是，C++。我的大部分博文将集中讨论我们现在正试图应用回产品中的关键经验，例如无处不在的异步、零拷贝 IO、消除安全性和性能之间的错误二分法、基于能力的安全、安全的并发、建立技术辩论文化等等。”

### 阅读此文

[微软研究院构建安全的“Haven”以保护云中的应用程序](/article/microsoft-research-builds-a-safe-haven-for-shielding-apps-in-the-cloud/)

![microsoft-research-builds-a-safe-haven-for-shielding-apps-in-the-cloud.png](https://www.zdnet.com/a/img/resize/28a1eeb98bede4696ed24d3f91fd736621d6fa6f/2014/10/20/0d478b4e-5829-11e4-b6a0-d4ae52e95e57/microsoft-research-builds-a-safe-haven-for-shielding-apps-in-the-cloud.png?auto=webp&fit=crop&frame=1&height=238.5&width=459)


多年来，微软官员一直试图淡化，甚至掩盖 Midori 的存在。该项目的一些参与者含糊地提到了他们参与的微软秘密技术孵化项目。但如今，要找到关于 Midori 团队所从事组件的详细信息相当容易。

根据其领英个人资料，一位从 2011 年到 2015 年 4 月参与 Midori 项目的团队成员致力于“将分布式存储和计算引擎移植到托管语言，并使其在新操作系统环境中运行”。这位工程师，[Svitlana Tumanova](https://www.linkedin.com/profile/view?id=AAEAAAJiwbgBLDfXbFIFqEHBQjkNb5BLn866A9A&authType=name&authToken=tAj_&trk=prof-sb-browse_map-name)，还致力于帮助将现有的 C++ 代码库移植到更安全的语言，并在新操作系统上设计浏览器 DOM 树和 CSS 部分。

另一位从 2008 年到 2014 年 6 月参与 Midori 项目的工程主管兼架构师 Leif Kornstaedt 在其个人资料中指出，他致力于“[许多技术的前卫方法](https://www.linkedin.com/profile/view?id=AAEAAACdA_YBqtjMcIvpVNG0ZHQIneJn7lIqBWc)，例如进程间通信、promises、托管代码运行时、托管代码的提前编译、托管/原生互操作、并发垃圾回收、异步执行模型、JavaScript 执行和托管，以及 Web 浏览器架构”。


David Tarditi 的领英个人资料显示，他[从 2007 年到 2013 年 11 月领导了 Midori 工具团队](https://www.linkedin.com/profile/view?id=AAEAAABPTUMBpy1LbO-ZkWS7al60_f0ZLuSm2Qs&authType=name&authToken=k_xW&trk=prof-sb-browse_map-name)，并提供了一些关于 Midori 的历史：

> “我领导了 Midori 项目的工具团队，将团队从 4 人发展到许多人。Midori 是一个完全用 C# 编写的操作系统，其性能可与生产操作系统相媲美，而且没有用 C 或 C++ 编写的操作系统中存在的安全性和可靠性问题。我们继续开发在 Singularity 项目中使用的 Bartok 编译器，以便它可以用来用 C# 编写生产质量的系统软件。我们添加了对泛型、共享库、跨库的通用共享代码以及其他用于系统编程的出色功能的支持。我们将 Bartok 连接到 Phoenix 编译器基础架构，并大幅提高了 Phoenix 生成的代码的整体质量，使其在 SPEC 基准测试中与生产 C/C++ 编译器相比具有竞争力，并增加了对托管代码优化的广泛支持。”

（[M# 语言正是从 Midori 团队的编译器工作中发展而来的](https://www.zdnet.com/article/microsofts-midori-the-m-connection/)。）

正如我最喜欢的一位微软侦探“行走猫”（又名 Twitter 上的[h0x0d](https://twitter.com/h0x0d/status/661702841560502272)）多年来一直在记录的那样，许多 Midori 团队成员离开了微软。一旦该项目被移至当前的操作系统组之下，即使没有离开公司，更多的人最终也离开了团队。今年早些时候，据消息人士称是 Midori 的执行支持者的 Eric Rudder [也离开了公司](https://www.zdnet.com/article/microsofts-2015-reorg-whos-in-whos-out/)。


微软的官方说法是，操作系统组和公司的其他团队正在将 Midori 的“经验教训”融入到微软的未来产品中。

对于我们这些微软的观察者来说，微软最终计划如何处理 Midori 一直不清楚。从 Duffy 的博客来看，团队成员似乎也不是很确定。

Duffy 说：“我首先承认，我们都不知道 Midori 的最终结果会如何。研究通常都是这样。”


Duffy 补充说：“我最大的遗憾是我们没有从一开始就将其开源 (OSS)，让互联网的精英能够恰当地评判它的各个部分。与所有大公司一样，[围绕 Midori 核心技术命运的决策并不完全由技术驱动，而且可悲的是，甚至也不完全由业务驱动](http://joeduffyblog.com/2015/11/03/blogging-about-midori/)。但其中也包含了一些重要的教训。”

[编辑标准](/editorial-guidelines/)



## 相关文章

* [如果您是万豪客户，联邦贸易委员会称这家饱受数据泄露困扰的酒店连锁店欠您的](/article/if-youre-a-marriott-customer-ftc-says-the-breach-plagued-hotel-chain-owes-you/)
* [这款 8TB 三星 T5 固态硬盘在亚马逊十月 Prime 会员日之后仍然有 36% 的折扣](/article/samsung-t5-ssd-october-prime-day-deal-10-10-2024/)
* [最好的 Android Auto 无线适配器之一在亚马逊上有 20% 的折扣——我已经心动了](/article/one-of-the-best-android-auto-wireless-adapters-is-20-off-on-amazon-and-im-sold/)
