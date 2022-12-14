# 应用背后:推推的故事

> 原文：<https://lifehacker.com/behind-the-app-the-story-of-pushbullet-1657859652>

当我们的目光从手机转移到笔记本电脑和平板电脑时，我们都生活在多个屏幕之间。当你的数字生活像凌乱的办公室里的文书工作一样杂乱无章时，你如何让自己保持有序？ [推推](https://www.pushbullet.com/) 正在朝着一个答案努力。



在其最简单的形式中，Pushbullet 充当了桌面和手机之间的中继，因此您可以在桌面上接收文本消息和其他通知，或者将数据推送到您的手机。当然，这种功能被嵌入到一些较新的操作系统 中，但是推推是 [旨在桥接任何设备和操作系统](https://lifehacker.com/how-to-use-pushbullet-to-bridge-the-gap-between-all-you-1548595270) 。

它始于 Ryan Oldenburg 在 2012 年的一个附带项目，并于次年推出，受到了 Android 用户的欢迎，这些用户正在寻找更好的方法在设备之间传递信息。我们采访了 Ryan，以了解该项目启动的原因以及他对未来的想法。

#### 这款应用的创意来自哪里？你是在试图解决你经历过的问题，还是灵感来自其他地方？

Ryan Oldenburg: 我开始使用 Pushbullet 是因为我觉得在手机和电脑之间发送信息很痛苦。我最终会用电子邮件给自己发送链接和文件，只是为了把它们从一个发送到另一个。我知道几乎每个人现在也是这样，这是一种令人沮丧的搞笑方式。Pushbullet 最初是一种在设备之间移动链接和文件的更简单快捷的方式。

当 Jelly Bean (Android 4.1)问世时，Pushbullet 实际上可以实现这一点的方式让我印象深刻。Jelly Bean 增加了对丰富通知的支持，可以让你看到通知中的内容，甚至有按钮。当我看到这让我不用打开 Gmail 应用程序就可以阅读我的电子邮件(甚至存档它们)时，我很明显地意识到通知托盘现在是我手机中最有用的部分。

几乎在同一时间，我尝试了谷歌的 [Chrome 手机](https://lifehacker.com/chrome-to-phone-sends-links-text-and-numbers-to-andro-5581392) 扩展，觉得它真的很酷。该扩展可以让你立即发送一个网页到手机的通知托盘。谷歌放弃了这个项目，认为它只是一个技术演示，但我知道即时转账结合超级便捷访问通知的概念有巨大的潜力。

在使设备间的链接和文件传输变得非常简单之后，我意识到我们所构建的设备间信息共享系统还有很多其他的潜在用途。我们接下来添加的第一个功能使人们能够在电脑上查看和取消手机通知。

能够在我的电脑上查看和取消我手机的通知，完全是出于个人愿望。在电脑前工作时不必一直拿着手机，这不仅非常方便，而且本质上也是“事情应该如何工作”事实上，我收到一封电子邮件不仅仅是为了我的手机，而是为了我自己。我应该可以在我所有的数字设备上看到这个通知，并且只需要关闭一次。这似乎是显而易见的，但在我们建造它之前，这是不存在的。

#### 你想出这个主意后，下一步是什么？

开始构建。

当我在 [Hipmunk](https://www.hipmunk.com/) 全职工作时，我开始把推推作为一个兼职项目。首先，我决定在第一个版本中需要的功能，以证明我不是唯一一个想要这个应用程序的人(我从简单的链接传输开始)，然后我在假期中开始构建 Android 应用程序、网站和后端。

#### 你如何选择目标平台，忽略或等待哪些平台？

我开始使用 Android 是因为我已经做了几年的 Android 开发人员，这使得这个选择很容易。

#### 你遇到的最大障碍是什么，你是如何克服的？

我最大的障碍可能是让所有的部分一起工作并进入可交付状态。这很困难，因为正如我所说，Pushbullet 是作为一个附带项目开始的。全职工作，然后把所有的空闲时间都花在兼职项目上并不容易。我认为当你开始一个兼职项目时，倒计时就开始了:你需要及时发布你的第一个版本，否则你会筋疲力尽。

对我来说，虽然我对 Android 很有信心，但我已经多年没有建立后端或网站了。当我有，它是在一个现有的系统之上。让一切从零开始，包括前端设计、数据库、服务器、身份验证系统、注册电子邮件——甚至决定应用程序的名称和颜色——这一切加起来很快，可能会让一个人不知所措。

#### 对你来说，发射是什么样的？

Pushbullet 的推出实际上相当成功。我认为我们很幸运，但我当然不会抱怨。

我在一个周日发布了 Pushbullet，这样我就不用工作了，可以专注于发生的任何事情。

发布包括向 Reddit 的 [Android 社区](http://www.reddit.com/r/Android/) 和 [黑客新闻](https://news.ycombinator.com/) 提交 [发布博文](https://blog.pushbullet.com/2013/01/20/hello-pushbullet/) 。这两篇文章都链接到了文章的底部。

虽然黑客新闻有些接受，但 Reddit 的 Android 社区反应极其热烈，这太棒了。根据他们的反馈， [我赶制了一个 Chrome 扩展](https://blog.pushbullet.com/2013/01/27/chrome-extension-released/) 在下周推出。

从那里开始， [推推网在短短两周内就有了 15000 名用户](https://blog.pushbullet.com/2013/02/03/from-0-to-15000-users-in-2-weeks/) 。你可以想象我有多兴奋，从那以后我们基本上就这样了。

#### 你如何有效地处理用户的要求和批评？

对我们来说，处理好用户的请求和批评很大程度上是关于看到反馈和被看到对反馈的回应。我们在公共场合得到很多反馈，所以我们也在公共场合回应。

这包括 Android subreddit 和 [我们自己的 subreddit](http://www.reddit.com/r/pushbullet) ，我们的 [Google+ page](https://plus.google.com/+Pushbullet/) 和 [beta 社区](https://plus.google.com/communities/100882548202034244563) ，以及对我们博客帖子的评论和媒体写的任何关于我们的帖子。

我们阅读了所有这些帖子和对它们的评论，并试图每次都回复大量的帖子。因此，我们赢得了响应迅速、平易近人的声誉。这种声誉为我们赢得了很多好感，也让人们更愿意给我们反馈。考虑到良好的反馈对持续增长的重要性，这是一个很大的好处。

#### 现在，如何在开发新功能和管理现有功能之间分配时间？

我相信没有什么比不可靠的软件更烦人的了。这意味着我们一听到臭虫的消息就集中精力消灭它们。

这确实需要时间，但是通过保持在它们之上，这样 bug 列表就不会失去控制，这真的不需要太多时间。这也是 Pushbullet 如何赢得了它作为最受好评和最可靠的应用之一的地位。

开发新功能是我们花大部分时间去做的事情。然而，新功能，并不是我想描述的那样。我认为我们所做的大部分都是“缺失的特性”——意思是我们显然应该添加，但是还没有能够构建的东西。

我们专注于填补功能上的空白，而不是“新把戏”，这意味着我们避免了失去重点，我们的应用程序只是“变得更大”相反，Pushbullet 实际上一直在变得更好。

#### 我注意到你倾向于在开发新功能的同时发布它们，而不是对应用程序进行零星但较大的修改。快速迭代是你优先考虑的事情吗？

这些天来，重复想法并快速实现是一条经典的建议。我相信这也是绝对正确的。虽然许多人认为这样做的原因在于能够快速响应反馈并改进产品，但我认为我们的理由要复杂一些:

首先，背后有真正的动力感觉很好。它让我们不断前进，也让我们的用户兴奋地听到下一次更新，因为他们知道它即将到来。

这也意味着我们避免了那些真正可怕的发射，在那里一切都变了，你只能祈祷一切顺利。这些会严重挫伤积极性。

不被锁定在一个大版本中也意味着我们可以快速响应反馈或修复错误。不是几周或几个月那样的“快”——我的意思是几小时或几天那样的快，这取决于我们在谈论什么。

归根结底，我们作为开发人员的经验告诉我们，经常发布对我们的动机和精力来说更好。当事情慢下来的时候，基本上一切都会变得更糟。

#### 你认为 Pushbullet 几年后会是什么样子？

未来几年，每个人的生活中只会有更多的设备。手机、平板电脑和电脑继续变得越来越普遍。这意味着 Pushbullet 节省人们时间和实现独特便捷功能的机会只会越来越令人兴奋。

#### 你会给那些想从事类似项目的人什么建议？

Pushbullet 已经发展成为一个相当大的软件，在许多方面看起来似乎很简单。然而，如果我开始开发它时，既有构建今天这个样子的雄心，又固执地要求在第一个版本中包含我们当前的所有功能，那么 Pushbullet 就不会存在。这么多伟大的想法从来没有在世界上实现，因为从事它的人没有在停止之前发布项目。

如果你真的对一个项目很感兴趣，完成它的最好方法是一开始就保持简单。你总可以从你的应用或服务中提炼出一些单一的元素。尽可能快地释放最基本附加值，感受真实世界对它的看法。从那里开始成长真是太棒了。

* * *

<small></small>*[<small>*App 背后*</small>](http://lifehacker.com/behindtheapp) <small>*让我们深入了解一些我们最喜欢的应用是如何诞生的——从创意到发布(以及之后)。有你想看到的人吗？邮箱*</small> [<small>*安迪*</small>](mailto:andy@lifehacker.com) <small>*。*</small>*