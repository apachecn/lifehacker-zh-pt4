# 如何用 Windows 和大图滚动自己的蒸汽机

> 原文：<https://lifehacker.com/how-to-roll-your-own-steam-machine-with-windows-and-big-1510663145>

自从 Valve 推出 SteamOS 以来，PC 游戏 [社区](http://i.imgur.com/PPanWZP.png) 一直渴望看到运行 Steam 的视频游戏主机会是什么样子。不幸的是，beta 还没有准备好迎接黄金时间。不过有一个特点:大图模式。



开箱即用，Big Picture 只是已经在您的 PC 上运行的 Steam 应用程序的一个替代界面。这很好，但是在窗口和全屏界面之间切换是一个巨大的跳跃。如果你想体验一下真正的蒸汽机是如何工作的，你只需要做一些调整就可以了。

### 为什么现在大屏幕更适合你的电视

SteamOS 最近一直占据头条新闻的最大份额，因为人们普遍对 Valve 可能成为游戏机领域的一员感到兴奋。不过，目前来看，定制的 Linux 变种真的只对发烧友和 beta 测试者有好处。你可以自己安装测试版，但你最终得到的将是一个不能运行你所有游戏的 Steam 版本，而且对其他方面也没什么用。

幸运的是，大图模式已经存在于您的常规 Steam 安装中。当在 Windows PC 上使用时，与 SteamOS 相比有几个明显的优势:

*   你所有的游戏都能正常运行。由于 SteamOS 运行在一个 Linux 变种上，所以只能玩已经适配运行在 Linux 上的游戏。简单地说，这并不是一个很大的数字。大图模式没有这样的问题(尽管 Mac 用户仍然会在他们的库中找到一些漏洞)。
*   你可以做的不仅仅是玩游戏。在大画面模式下，您可以选择最大限度地减少蒸汽，并启动您在电脑上可以做的任何事情。这包括但不限于运行媒体中心软件，如 XBMC 和按键映射软件，可以增强您的客厅游戏。
*   bug 会更少。总的来说，Steam 并不是没有缺点，但它在个人电脑上的基础是牢固的。另一方面，SteamOS 仍在努力构建对 AMD 和英特尔显卡或 [双引导和分区](http://lifehacker.com/steamos-beta-now-supports-dual-boot-and-custom-partitio-1506587090) 等基本事物的支持。

当然，长期 SteamOS 并非没有潜力——我们仍在等待流媒体功能被添加到操作系统中，例如，它将允许你通过 HTPC 上的 Wi-Fi 玩安装在 PC 上的游戏。然而，与此同时，你可以获得 SteamOS 提供的一切，甚至更多，而不必放弃你已经喜欢的有趣的东西。

### 阶段 1:直接启动到大图模式

如果你想要完整的控制台体验，你不能浪费时间摆弄 Windows。对于客厅里的专用机器，使用没有安装其他应用程序的访客帐户是最干净的方法。在未使用的帐户上安装 Steam，并遵循以下步骤:

1.  在 Steam 中，打开设置。选择“接口”
2.  如果尚未选中“当我的电脑启动时运行 Steam ”,请选中它。
3.  选中“以大画面模式启动 Steam”

不管你希望过渡有多整洁，上面的步骤将确保当你加载桌面时首先看到的是大图模式。为了更进一步，您应该启用几个调整:

*直接启动到桌面* -如果你运行的是 Windows 8.1，只有当你坐在开始屏幕上时，大图模式才会在后台加载。跳过步骤 a——就像这样:

1.  右键单击任务栏并选择“属性”。
2.  单击导航选项卡。
3.  选中“当我登录或关闭屏幕上的所有应用时，转到桌面而不是开始”

*绕过密码登录* -一般来说，不需要密码就直接进入你的账户并不是最好的主意。但是，如果您已经专门为 Steam 创建了一个帐户，您可以通过以下步骤让您的电脑直接登录该帐户:

1.  按 Ctrl-R 并输入 netplwiz。
2.  在弹出的窗口中，选中“用户必须输入这台计算机的用户名和密码”
3.  选择包含 Steam 安装的帐户的名称。
4.  取消选中“用户必须输入这台电脑的用户名和密码”

这两个调整一起将导致 Windows 自动启动和启动大图片模式。注意:如果你在这个帐户上有任何其他自动运行的应用程序，其中一个可能会在 Steam 后启动，这需要导航回大图模式才能使用它。如果你用鼠标和键盘来控制你的 HTPC，这没什么大不了的，但是控制器就有问题了。

对于现有的 XBMC 用户来说:如果你的 HTPC 和 [一样致命，我们 500 美元的版本](https://lifehacker.com/how-i-built-the-media-center-of-my-dreams-for-under-50-5936546) ，启动到 Steam 可能会和你的其他用法背道而驰。别担心。 [这个附加](http://forum.xbmc.org/showthread.php?tid=157499) 有你罩着。安装完成后，你可以从 XBMC 的程序区启动 Steam。这将在大图模式下直接打开 Steam。要返回 XBMC，只需退出 Steam，媒体中心应用程序就会立即打开。很简单。

### 阶段 2:充实控制器支持

开箱即用，许多 Steam 游戏都包含控制器支持。首选设备是 Xbox 360 控制器，我们强烈推荐它。然而，并不是每个标题都默认支持控制器。

对于那些不支持的游戏，你可以使用一个名为 [JoyToKey](http://joytokey.net/en/download) 的应用程序，将控制器的输入映射到你习惯的相应键盘和鼠标输入。很明显，你需要连接常规的 PC 输入来进行初始设置，但是一旦完成，你应该能够只用一个控制器来控制任何游戏。安装 JoyToKey 后:

1.  为每个你想映射的游戏创建一个新的档案。以那场比赛命名。
2.  将控制器的每个按钮映射到游戏中控件的相应按键。这里的按钮列表将帮助识别哪个按钮与哪个键映射相关联。对每个需要映射的不支持的游戏重复上述步骤。注意:这一步可能需要一些尝试和错误，所以在完成之前一定要测试你的布局。
3.  点按“设置”并选择“将描述文件与应用程序关联”
4.  单击“添加”开始新的配置文件关联。
5.  在第一个框中输入游戏名称。
6.  找到。exe 文件，并在第二个框中输入其完整的文件路径。
7.  在底部的下拉框中，选择您创建的要与该游戏关联的个人资料(应该同名)。
8.  单击确定。

JoyToKey 将在后台运行，并在启动时激活每个游戏所需的配置文件，这意味着在初始设置后，您不需要再触摸键盘或鼠标。但是，如果你添加一个没有控制器支持的新游戏，你就需要把那个硬件拿出来。

当然，JoyToKey 是一个免费的程序，但是界面有点笨重。你也可以尝试一下 [Xpadder](http://www.xpadder.com/) ，它的价格是 10 美元，界面也不那么迟钝。Mac 用户也可以试用前面提到的。