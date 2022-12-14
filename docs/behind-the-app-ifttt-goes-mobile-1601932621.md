# 应用背后:IFTTT 走向移动

> 原文：<https://lifehacker.com/behind-the-app-ifttt-goes-mobile-1601932621>

if TTT——意思是“如果这个那么那个”——正迅速成为许多数字工具箱中的必备工具。该服务类似于跨平台编程:您可以创建触发器和动作来将信息从一个地方传输到另一个地方。听起来像是专为 Lifehacker 打造的。



在作为网络服务存在了几年之后，IFTTT 分别于 2013 年 7 月和 2014 年 4 月推出了他们的 [iOS](http://lifehacker.com/all-the-new-stuff-in-ifttt-for-ios-and-what-you-can-do-1032710106) 和 [Android](https://lifehacker.com/all-the-new-stuff-in-ifttt-for-android-and-what-you-can-1566974091) 应用，为移动设备提供独特的功能。我们采访了 IFTTT 的 Alexander Tibbets 和产品工程团队，了解他们对移动开发的尝试以及他们如何扩展服务。

#### iOS 和 Android 版 IFTTT 的想法是从哪里来的？

IFTTT 产品工程总监德文·弗利(Devin Foley)*:*if TTT 刚开始在网络上流行，用户就开始要求“IFTTT to go”本质上是 IFTTT 的一个版本，他们可以把它放在口袋里。我于 2012 年夏天加入该团队，开始了 IFTTT 移动体验的工作，并最终建立了我们的移动团队。

我们一开始就知道，我们希望在一个应用程序中提供 IFTTT.com 的所有功能。我们也知道，我们有一个很好的机会为 IFTTT 社区提供全新的、完全独一无二的移动产品。

#### 在你决定为 IFTTT 开展移动业务后，下一步是什么？

[*德文·弗利*](https://twitter.com/devinfoley) *:* 我们决定优先考虑 iOS 版 IFTTT 原因很简单，因为当时团队中的每个人都在使用 iPhones。

我们花了几个月的时间迭代产品和测试想法，慢慢地这个应用开始成形。就在我们以为已经接近终点的时候，我们突然意识到，通过将 IFTTT 与设备的照片、提醒和联系人集成，我们可以释放新的潜力，创造出一些真正令人惊叹的“食谱”。没有这些功能，这个应用突然觉得不完整，所以我们加倍努力，争取在 2013 年 7 月的 [发布会上及时添加这些功能。](http://ift.tt/for_iPhone).)

#### 对你来说，发射是什么样的？

[*乔纳森·赫什*](http://her.sh/) *，IFTTT 的 iOS 工程师:*首先你投入数不清的时间打磨动画，收集 beta 社区和焦点小组的反馈，痴迷于复制，在各种设备上评估应用程序，并对性能进行基准测试。然后你在苹果的开发者门户网站上按下一个蓝色的按钮——砰！您的所有准备工作在瞬间就有了回报，因为只需按下一个蓝色按钮，您就将您的骄傲和喜悦传遍了全球，您会看到人们立即开始安装。

这有点像情绪过山车，但最终都是值得的。我们乐于看到 IFTTT 社区创造性地控制他们喜爱的产品，并让互联网为他们服务。

#### 在推出 iOS 之后，你下一步的目标是什么平台？

[*乔丹·贝克*](https://twitter.com/jordansbeck) *，IFTTT 高级安卓工程师:【2013 年末，我被请来领导我们的安卓工程工作。Android 一直是 IFTTT 移动路线图的重要组成部分，因为它提供了许多独特的机会。还有许多挑战。*

iOS 应用程序非常受欢迎，我们显然希望 IFTTT for Android 能够做到这一点。Android 提供了许多新的选项——无论是访问电话信息、设置壁纸还是检测 WiFi 网络。这对我们所有人来说都是一个新的领域。

2014 年 4 月，经过整个团队近半年的努力，我们推出了适用于 Android 的 [IFTTT。通过 Android 可以讲述很多很酷的故事，令人兴奋的是我们还有很多要讲的。](https://lifehacker.com/all-the-new-stuff-in-ifttt-for-android-and-what-you-can-1566974091)

#### 你最大的障碍是什么，你是如何克服的？

[*德文·弗利*](https://twitter.com/devinfoley) *:* 像“将我的 iOS 照片保存到 Dropbox”这样的菜谱很难实现——如果它们不能在后台无缝运行，它们就不会那么有用。

虽然后台获取现在已经内置到 iOS 中，但在 2013 年，我们需要执行一些聪明的基于位置的黑客操作，让你的手机在后台运行食谱，而不会耗尽你的电池。

我们花了很多时间在一辆优步的后座进行测试，后座上布置了看起来像电子围栏的操作。

#### 你如何有效地处理用户的要求和批评？

[*查理·帕克*](https://twitter.com/charliepark) *，IFTTT 高级工程师:*我们从社区获得了很多他们想在 IFTTT 上看到的新功能的绝妙想法。各种各样的东西——新的频道请求、设计建议、触发器和动作的改进。得到这样的反馈(即使是批评性的)很有趣，因为这意味着人们对我们正在做的事情感到非常兴奋。

当有新想法出现时，我们会尽最大努力考虑它们如何融入我们的路线图，它们实现起来有多容易，以及它们会对社区产生多大的影响。

我们希望 IFTTT 简单易用，所以我们做的最重要(也是最难)的事情之一就是对一些伟大的想法说“不”。它让我们专注于影响更大的想法。但是我们从使用 IFTTT 的人们那里听到的越多，我们的工作就越有趣。所以请保持反馈！

#### 现在，如何在开发新功能和管理现有功能之间分配时间？

[*Max Meyers*](https://twitter.com/maxmeyers)*，IFTTT 的移动工程师:*这是 IFTTT 最艰难的挑战之一:优先考虑全新功能以及对现有功能的改进。尤其是考虑到我们现在在 Google Play、iTunes 和网络上有独特设计的产品。

幸运的是，我们有一个强大的工程师和产品设计师团队，他们不断地重新考虑什么样的功能或改进会对社区产生最大的影响。老实说，我们的关注点会根据一周或一个月的目标定期调整。

你可能需要关注我们对每个新版本应用程序的更新。在 Android Wear 和 Nest 恒温器等新频道旁边，你会看到一些改进，如特定的错误修复和更快的界面设计。

#### 你会给那些想从事类似项目的人什么建议？

[*德文弗利*](https://twitter.com/devinfoley) *:* 据说你只能发射一次。确保给自己留出时间来处理细节，创造一个让你引以为豪的产品。

* * *

<small></small>*[<small>*App 背后*</small>](http://lifehacker.com/behindtheapp) <small>*让我们深入了解一些我们最喜欢的应用是如何诞生的——从创意到发布(以及之后)。有你想看到的人吗？邮箱*</small> [<small>*安迪*</small>](mailto:andy@lifehacker.com) <small>*。*</small>*