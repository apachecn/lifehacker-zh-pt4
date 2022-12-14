# USB 有一个你无法察觉的基本安全缺陷

> 原文：<https://gizmodo.com/usb-has-a-fundamental-security-flaw-that-you-cant-detec-1613833339>

我们都依赖 USB 来互连我们的数字生活，但《连线》 首先报道的新研究 [揭示，在不起眼的通用串行总线的工作方式中存在一个根本的安全缺陷，它可以被用来对任何计算机进行破坏。](http://www.wired.com/2014/07/usb-security/)



[《连线》报道](http://www.wired.com/2014/07/usb-security/) 安全研究人员 Karsten Nohl 和 Jakob Lell 对控制 USB 基本通信功能的固件进行了逆向工程。不仅如此，他们还编写了一款名为 BadUSB、 [的恶意软件，可以](http://www.wired.com/2014/07/usb-security/) “安装在 USB 设备上，完全接管电脑，无形中改变从记忆棒安装的文件，甚至重定向用户的互联网流量。”

嵌入 USB 设备(从拇指驱动器到键盘到智能手机)的是一个控制器芯片，它允许设备和它所连接的计算机来回发送信息。这就是 Nohl 和 Lell 的目标，这意味着他们的恶意软件不在闪存中，而是隐藏在固件中，除了最有技术知识的人之外，其他人都无法删除。 [Lell 向连线](http://www.wired.com/2014/07/usb-security/) 解释道:

> “你可以把它交给你的 it 安全人员，他们扫描它，删除一些文件，然后把它还给你，告诉你它是‘干净的’...[但这些]问题无法修补。我们正在利用 USB 的设计方式。"

最大的问题是，几乎不可能检查设备的固件是否被篡改，即使被篡改，也没有一个可信的版本可供检查。同样值得指出的是，它可以双向传播:比如说，一个 u 盘可以用它的恶意软件感染一台电脑，然后这台电脑可以感染任何插入它的 USB 设备。

因此，令人相当担忧的是，两位研究人员已经证明——并将在即将于拉斯维加斯举行的黑帽安全会议上展示——该漏洞可以在拇指驱动器、鼠标、键盘甚至安卓智能手机上被利用。(理论上，它可以在任何可以重新编程固件的 USB 设备上工作)。《连线》杂志的一些消息来源 甚至推测黑客可能已经被美国国家安全局所利用。

这是一个坏消息——那么你能做些什么呢？从技术上讲，非常少:没有可以用来解决这个问题的代码补丁。相反，USB 实施者论坛和研究人员 [指出](http://www.wired.com/2014/07/usb-security/) 改变我们使用 USB 的方式是唯一的解决办法:不要把 USB 设备插入任何你不百分之百信任的计算机，也不要把不信任的 USB 设备插入你的计算机。这可能会很不方便——但也可能会让你免于一场令人讨厌的意外。【T5】连线 T7】

*图片由* [*【塔莎】拥有者*](https://www.flickr.com/photos/foryoudesigns/13025826093) *在知识共享许可下*