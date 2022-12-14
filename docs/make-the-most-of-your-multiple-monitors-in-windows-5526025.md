# 充分利用 Windows 中的多显示器

> 原文：<https://lifehacker.com/make-the-most-of-your-multiple-monitors-in-windows-5526025>

这些年来，额外显示器的价格稳步下降，质量有所提高，Windows 比以往任何时候都更加支持多显示器。以下是如何在 Windows 7 和 8 中充分利用多显示器设置的方法。



[](http://lifehacker.com/tag/blast-from-the-past)**是 Lifehacker 的一个新的每周专题，我们在其中恢复了旧的，但仍然相关的帖子，供您阅读和黑客娱乐。本周，我们将深入挖掘并在多台显示器上恢复一项旧功能，并为那些已经升级到 Windows 8 的显示器增加一些新功能。**

*早在 2007 年，我们就向您展示了如何充分利用您的双显示器 。自该指南发布以来，Windows XP 已经开始了它的冥河之旅，比以往任何时候都多的人正在摇动多显示器，Windows 7 将多屏幕设置视为完全平常和例行公事(这很好)。*

*有多常规？假设你有支持多显示器的显卡，在 Windows 7 和 8 中设置多显示器是最少的，而且通常完全没有问题。例如，我正在运行三台显示器:一台连接到主板，两台连接到双头显卡。板载显卡基于 NVIDIA 芯片组，扩展卡基于 ATI。这种安排导致 Windows XP 完全失去了理智，需要数小时的治疗和干预才能将 GPU 分裂的人格恢复到一起。(说真的，我无法描述在 Windows XP 下运行三显示器有多么令人头疼，更不用说使用两个显卡了。)相比之下，Windows 7 下的过程非常简单，我实际上不得不查看官方的设置步骤，以确保我不是带着玫瑰色眼镜回忆设置过程。*

### *在 Windows 中设置多台显示器*

*如果您还没有购买额外的显示器，那么在安装时，您将会有所收获。一些电脑支持开箱即用的多显示器(如果您的电脑背面有两个 DVI 或 VGA 端口，您的电脑可能已经可以处理双显示器)。如果没有，你需要安装一个新的视频卡，如我们的计算机构建指南 中所述——但是与 Windows 中轻松的安装相比，安装视频卡将是这个过程中最长的部分。*

*如果您已经有一台可以处理多台显示器的计算机，只需插入显示器的电源线，并将其连接到额外的 VGA 或 DVI 端口。那么是时候真正开始了。*

*通过右键单击桌面并选择“屏幕分辨率”，或在“开始”菜单搜索框中键入“调整屏幕分辨率”，访问 Windows 的屏幕设置。单击“识别”按钮，在每个屏幕上弹出数字来识别它们，然后拖放它们来匹配您当前的排列。*

*在您希望作为主显示器的显示器上选中“将此作为我的主显示器”，主任务栏和“开始”菜单将出现在这里，以及大多数应用程序窗口的初始运行。所有显示器都应该在“多显示器”下拉菜单中选择“将桌面扩展到该显示器”。唯一需要花费大量时间调整显示设置的时候是当你有多台不匹配的显示器时——当我第一次开始使用多台显示器时，我有一台 17 英寸和 15 英寸的显示器，不匹配的尺寸和分辨率非常尴尬。(虽然你也可以通过调整这里的一个设置来修复“光标漂移”问题 )。*

*如果您在 Windows 7 之前从未尝试过多显示器，那么您应该庆幸，您是在多显示器得到很好支持并且动画制作所需的巫术最少的时候加入的。现在，您已经连接了显示器，并将桌面扩展到所有显示器上，是时候开始学习 Windows 7 中的多显示器技巧，并在必要时为其补充软件了。*

### *利用内置工具*

*多显示器的好处是显而易见的；你可以展开你的工作，比较文档，过着几乎不用在窗口间来回切换的生活。尽管如此，多显示器的生活，尤其是现代显示器的分辨率惊人，与单一小屏幕的生活相比，有着自己的一系列挑战。*

#### ***扩展任务栏(仅限 Windows 8)***

*人们可能讨厌 Windows 8，但如果你有多台显示器， Windows 8 有一些不错的升级。最值得一提的是能够在两台显示器上扩展任务栏。*

*只需右键单击任务栏，转到属性，并选中“在所有显示器上显示任务栏”框。在那里，你可以根据自己的喜好调整它——在所有任务栏上显示任务栏按钮，或者只在窗口打开的监视器上显示。请注意，如果您仍然使用 Windows 7，您可以通过 DisplayFusion 获得此功能，如下一节所述。*

#### ***加速光标位置***

*以简单的鼠标光标为例。在一排显示器上很容易丢失一个微小的 16x16 像素光标，我目前的设置是 4800x900 像素，在我眼前跨越了大约 60 英寸的物理弧。你只能直接关注这么多的显示器，每天至少几次，我关注的部分和鼠标光标不同步。幸运的是，Windows 有一个内置的工具可以帮助你毫不费力地找到一个任性的光标。这对于 Windows 7 来说肯定不新鲜，但它的省时功能值得一提。*

*打开控制面板中的鼠标设置，导航到“指针选项”选项卡。在底部——见上面的截图——你会看到一个复选框，写着“当我按下 CTRL 键时显示指针的位置”,选中它。现在，当你按下 CTRL 键时——但不是当它是键盘组合键的一部分时——光标周围会形成一个大约 200 像素宽的圆圈，并向它扫去。这是一个很小的调整，但是当你盯着显示器阵列的一个角落，想知道光标去了哪里，而它却在你最远的显示器的另一边时，这真是太方便了。*

#### ***磨练你的捷径——符***

*如果你以前不是键盘快捷键的狂热爱好者，你将很快成为一个。将光标从显示器阵列的一端一直拖到另一端，仅仅是为了执行一个需要两次击键的命令，就会变得非常快。*

*这些来自 Windows 7 的便捷快捷方式也适用于单显示器，但它们使使用多显示器和大量打开的窗口变得更容易，并为多显示器用户提供了一些特殊技巧:*

*   ***Win+Home:** 清除除活动窗口以外的所有窗口。*
*   ***Win+Space:** 所有的窗口都变成透明的，这样你就可以看透桌面了。*
*   ***Win+向上箭头:**最大化活动窗口。*
*   ***Shift+Win+向上箭头:**垂直最大化活动窗口。*
*   ***Win+向下箭头:**最小化窗口/最大化后恢复窗口。*
*   ***Win+Left/Right arrows:** 将窗口停靠在当前显示器的一侧，额外的按压会将应用程序推到下一个显示器边缘，然后居中，然后是相对的边缘，在所有可用的显示器上以这种模式继续。*
*   ***Shift+Win+左/右箭头键:**将窗口移动到监视器的左边或右边。*
*   ***Win+G:** 显示/隐藏您的 Windows 边栏小工具*

*更多快捷方式请查看新 Windows 7 快捷方式[及其 Windows 8 对应的](http://lifehacker.com/how-to-not-get-lost-in-windows-8-the-best-shortcuts-an-5955162) 的主列表。*

### *用第三方工具补充 Windows 的多显示器处理*

*虽然 Windows 在初始显示器设置和快捷键等基本功能方面做得非常好，但你会发现不缺乏明显的疏忽(特别是如果你仍然使用 Windows 7，它没有 Windows 8 那么多的多显示器功能)。*

*您可以用两种方法之一来解决 Windows 多显示器处理的缺点。你可以安装十几个奇怪的程序，有些是免费的，有些不是，它们会逐渐增加一些小的调整——这里一个任务栏扩展，那里一个移动窗口按钮，等等。—或者，您可以选择主要的多显示器应用程序套件之一。虽然我们和其他人一样喜欢免费的啤酒，但有时不值得费这么大的劲去尝试将一堆小应用程序和调整拼凑在一起，以实现一个花费只有您显示器花费 1/20 的程序所能做到的事。*

*[两大玩家](https://lifehacker.com/five-best-tools-for-managing-your-multi-monitor-setup-5519833) 分别是 [UltraMon](http://www.realtimesoft.com/ultramon/) 和 [DisplayFusion](http://www.binaryfortress.com/displayfusion/) 。UltraMon 较旧，但 DisplayFusion 是第一个针对 Windows 7 进行彻底更新的，并且 [更新更频繁](http://lifehacker.com/displayfusion-5-0-adds-more-multi-monitor-features-to-w-5983780) 。两者都是非常可靠的产品，但对于本指南来说，我们选择了 DisplayFusion 的性价比——display fusion Pro 是 25 美元，而完整的 UltraMon 套装是 40 美元。*

*以下是我们在 DisplayFusion 中最喜欢的一些功能:*

*   ***管理多显示器壁纸:** Windows 8 内置了一些不错的多显示器壁纸功能，例如可以在每台显示器上使用不同的壁纸，或者在两台显示器上拉伸一张壁纸，但 DisplayFusion 仍然拥有大量高级选项，从微调到自动旋转。*
*   ***窗口对齐**:让你的窗口对齐任何屏幕的边缘。*
*   *多显示器屏幕保护程序:在每台显示器上播放一个，或者在两台显示器上播放一个。*
*   ***多显示器任务栏(适用于 Windows 7 用户):**多显示器任务栏与现有的 Windows 7 任务栏平滑融合。你可以设置它显示全文按钮或折叠图标-就像你的主栏一样。*
*   ***用于移动窗口的键盘快捷键和按钮:** DisplayFusion 具有对窗口移动的热键支持，可以捕捉到显示器的侧面，最大化以跨越所有显示器，并且能够根据工作区域的百分比调整窗口的大小。如果默认的热键不包含您想要的功能，您可以使用非常全面的热键创建工具来创建自己的热键:*

*同样，UltraMon 和 DisplayFusion 都是可靠的产品，我们对 DisplayFusion 优于 UltraMon 的关注完全基于性价比最高的评估。如果你真的想把它们的高级功能放在一起，这两者提供的免费试用都是值得的。*

### *用一个键盘和鼠标控制多台显示器上的计算机*

*对于那些使用多显示器*和*多台计算机的人来说——无论是运行相同操作系统的测试设备还是运行不同操作系统的开发设备——如果你没有使用 [Synergy](http://synergy2.sourceforge.net/) ，你就错过了机会。*

*Synergy 是一个很棒的程序，可以让你用同样的键盘和鼠标控制多台电脑。如果您有多台机器连接到您的监控库，那么您真的需要对 Synergy 进行一次测试。查看 [我们的设置协同指南，了解更多信息](https://lifehacker.com/how-to-control-multiple-computers-with-a-single-keyboar-254648) 。*

### *带来赏心悦目的东西*

*多显示器的真正好处是极大地提高了工作效率，但说实话。除了用显示器覆盖你的桌子的实际原因之外，你不可能拒绝定制那一大片像素。即使你一天只看几次你的桌面壁纸，不装饰 4000+像素的区域也是一种犯罪。*照片由*[*yomi 955*](http://www.flickr.com/photos/yomi955/783099682/)*拍摄。**

#### ***多显示器壁纸***

*过去，多显示器壁纸的唯一选择是找到大图像，然后将它们裁剪下来或渲染成你自己的图像。现在多显示器越来越主流，越来越多的网站出现了多显示器尺寸的壁纸，或者完全只迎合多显示器设置。您可以查看我们的指南，了解找到多显示器壁纸 的 [最佳地点，或者直接进入以下列表:](https://lifehacker.com/best-places-to-find-multi-monitor-wallpaper-5114997)*

*   *[Mandolux](http://www.mandolux.com/)--[有些人](https://lifehacker.com/9612115) 发现浏览自己的 [Flickr 流](http://www.flickr.com/photos/mandolux/) 更容易。*
*   *[界面 LIFT](http://interfacelift.com/wallpaper_beta/downloads/date/any/)*
*   *[DeviantART](http://browse.deviantart.com/customization/wallpaper/multidisplay/?order=9)*
*   *[弗拉德工作室](http://www.vladstudio.com/wallpapers/)*
*   *[社交壁纸](http://www.socwall.com/)*
*   *[数字亵渎](http://www.digitalblasphemy.com/freegallery.shtml)*
*   *[双显示器和三显示器壁纸@ MintyWhite](http://mintywhite.com/tech/category/wallpaper/)*
*   *DualScreenWallpaper.com*
*   *DualMonitorBackgrounds.com*
*   *[我们自己的壁纸周三专题](http://lifehacker.com/set-your-multiple-desktops-to-these-dual-monitor-wallpa-5904834) ，其中 [偶尔贴出多显示器壁纸](http://lifehacker.com/set-your-multiple-desktops-to-these-ultra-wide-dual-mo-5980192) ！*

*当你很难通过常规来源找到你真正喜欢的壁纸图片时，点击 [【谷歌图片](http://images.google.com/) 也无妨。转动“大于...”在左侧栏中设置，然后裁剪找到的大图像以适合您的显示器——或者只需将它们扔进 DisplayFusion 的壁纸工具并调整它们以适应显示器。*

#### ***多显示器屏幕保护程序***

*当谈到屏幕保护程序和多显示器时，根据你的设置，应用程序可能会有点有限和粗略——例如，我使用的板载视频和双头视频卡设置不喜欢与大多数屏幕保护程序一起播放——但它不是完全无用的。你可以使用简单明了的基本 Windows 屏幕保护程序，它们可以在你所有的显示器上运行。或者，如果你真的喜欢屏保，你可以花钱购买 UltraMon，在每台显示器上启用自定义屏保。*

*然而，对于真正的惊喜因素，你会想要求助于可以在多显示器上运行的屏幕保护程序——并且具有最大的影响力。上面的截图是 Hypersace 屏幕保护程序，它是真正光滑的 提供的 [免费开放 GL 屏幕保护程序包的一部分。](http://www.reallyslick.com/)*

*如果你对更难的极客化感兴趣，不要忘记看看 [电动绵羊](http://electricsheep.org/) ，这是一个合作的抽象艺术项目，使用世界各地数千台闲置的计算机来生成“群”恍惚的抽象图像。这些图像被共享为屏保， [在线存档](http://v2d7c.sheepserver.net/cgi/node?id=20802) 。*

* * *

*在快捷方式、多显示器定制套件和令人赏心悦目的丰富内容之间，您应该能够掌控一台高效且漂亮的电脑！—监视器阵列。尽情享受吧！*

**<small>画面由</small>*[*<small>Jezper</small>*](http://www.shutterstock.com/pic.mhtml?id=86043082&src=id)*<small>(Shutterstock)</small>*[*<small>约翰霍华德</small>*](http://www.flickr.com/photos/spadgy/313251515) *<small>和</small>*[*<small>yomi 955</small>*](http://www.flickr.com/photos/yomi955/783099682/)T36*