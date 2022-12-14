# 如何在公共 Wi-Fi 网络上保持安全

> 原文：<https://lifehacker.com/how-to-stay-safe-on-public-wi-fi-networks-5576927>

公共 Wi-Fi 网络——如咖啡店或酒店中的网络——远没有你想象的那么安全。即使他们有密码，你也在和成千上万的其他人共享一个网络，这意味着你的数据面临风险。以下是如何在外出时保持安全的方法。



仅仅因为大多数无线路由器都有防火墙来保护您免受互联网的攻击，并不意味着您可以免受连接到同一网络的其他人的攻击。在同一个网络上， [窃取某人的用户名和密码](http://lifehacker.com/firesheep-sniffs-out-facebook-and-other-user-credential-5672313) ，或者 [查看他们在做什么](http://lifehacker.com/how-to-hack-your-own-network-and-beef-up-its-security-w-1649785071) 非常容易。不要冒这个险。我们将向您展示哪些设置是最重要的，以及如何在您每次连接到公共网络时自动将您的设置更改为适当的安全级别。

[](http://lifehacker.com/tag/blast-from-the-past)**是 Lifehacker 的一个每周专题，我们在其中恢复旧的，但仍然相关的帖子，供你阅读和黑客乐趣。本周，我们提醒大家出门在外时 Wi-Fi 安全的重要性。**

### *背景*

*首先，我们先来说说什么设置和应用可以保证你的安全。无论公共 Wi-Fi 是否有密码保护，都要确保随时启用这些功能。如果你不认识的其他人在同一个网络上，你想保护自己。*

#### *1.关闭共享*

*当您在家时，您可以共享文件、打印机，甚至允许从网络上的其他电脑远程登录。当你在公共网络上时，你会想要关闭这些东西，因为任何人都可以访问它们——他们甚至不需要成为黑客，根据你的设置，其中一些东西可能甚至没有密码保护。以下是关闭共享的方法:*

***在 Windows** 中:打开你的控制面板，然后浏览到网络和互联网>网络和共享中心，然后点击选择更改高级共享设置。一旦到了这里，您肯定应该关闭文件和打印机共享，您也可以关闭网络发现和公共文件夹共享。如果您将网络指定为公共网络，这其中的一些操作将由 Windows 自动完成(稍后将详细介绍)。*

***在 OS X** :进入系统偏好设置>共享，确保所有的复选框都没有被选中。*

*您还会想要关闭网络发现，这将在同一个地方。这将防止其他人甚至在网络上看到你的机器，这意味着你不太可能成为目标。在 Windows 上(正如我提到的)，它只是高级共享设置下的另一个复选框。在 OS X，它将被称为“隐身模式”，并在您的防火墙的高级设置(见下文)。*

#### *2.启用您的防火墙*

*如今，大多数操作系统都至少配备了一个基本的防火墙，这是一个简单的步骤来防止不受欢迎的本地用户窥探你的电脑。你可能已经使用了防火墙，但为了以防万一，进入你的安全设置(在 Windows 下控制面板>系统和安全> Windows 防火墙；在 Mac 上，在系统偏好设置>安全性&隐私>防火墙)下，确保你的防火墙已经打开。您还可以通过点击 Windows 中的“允许程序或功能”和 OS X 中的“高级”来编辑允许访问的应用程序。您的防火墙 [不是万能的保护者](http://lifehacker.com/nine-common-myths-and-misconceptions-about-viruses-exa-5560567) ，但确保它处于打开状态总是一个好主意。*

#### *3.尽可能使用 HTTPS 和 SSL*

*HTTP 上的常规网站连接通过您所连接的无线网络交换大量纯文本，具有适当技能和不良意图的人可以很容易地嗅出这些流量。当文本是你在 Lifehacker 上输入的一些搜索词时，这没什么大不了的，但当它是你电子邮件帐户的密码时，这就大不了了。 [使用 HTTPS](https://lifehacker.com/why-should-i-care-about-https-on-facebook-or-other-web-5745086) (用于访问网站)或启用 SSL(当使用访问互联网的应用程序时，如电子邮件客户端)可以加密在您的计算机和 web 服务器之间来回传递的数据，使其免受窥探。*

*许多网站——包括脸书、Gmail 和其他网站——会自动这样做，但要留意地址栏，确保当你交换敏感信息时，“https”中的“s”总是在那里。如果它消失了，你应该立即注销。其他网站将默认为 HTTP 连接，但支持 HTTPS，如果你手动输入它。*

*请注意，如果敏感浏览可以等待，特别是如果是非常敏感的信息，如银行或信用卡信息，那么**您应该在家等待进行敏感浏览**。没有理由冒不必要的风险。*

*如果您从桌面客户端(如 Outlook 或 Apple Mail)访问您的电子邮件，您需要确保您的帐户在设置中进行了 SSL 加密。否则，人们不仅可以从理论上阅读你的电子邮件，还可以获得你的用户名、密码或任何他们想要的东西。你需要确保你的域支持它，有时设置可能需要不同的设置或端口，这不仅仅是选中“使用 SSL”框的问题，所以请查看你的电子邮件帐户的帮助页面以了解更多详细信息。如果它不支持 SSL，请确保在公共网络上时退出该应用程序。*

#### *4.考虑使用虚拟专用网络*

 *[https://lifehacker.com/embed/inset/iframe?id=youtube-video-rdZYi-voWBY&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-rdZYi-voWBY&start=0)* 

*不幸的是，并不是所有的网站都提供 SSL 加密。其他搜索引擎和电子邮件提供商可能仍然容易受到监视你活动的人的攻击，所以如果你经常使用这些网站中的一个(或者真的只是想要额外的保护)，你可能想尝试使用 VPN，或虚拟专用网络。这些服务让你通过一个单独的安全的专用网络来路由你的所有活动，因此即使你在一个公共网络上，也能给你一个专用网络的安全性。*

*你有 [很多选择](https://lifehacker.com/why-you-should-be-using-a-vpn-and-how-to-choose-one-5940565)[我们在这里收集了一些最好的 VPN](http://lifehacker.com/five-best-vpn-service-providers-5935863)——但是如果你不想做研究，我们推荐 [CyberGhost](http://www.cyberghostvpn.com/en_us) 作为一个非常简单、免费的选择。把它安装在你的电脑上，只要你在公共网络上就打开它，你会比没有它安全得多。*

#### *5.不使用时，请关闭 Wi-Fi*

*如果你想保证你的安全，并且你不经常使用互联网，只需关闭你的 Wi-Fi。这在 Windows 和 OS X 中都非常容易。在 Windows 中，您只需右键单击任务栏中的无线图标即可将其关闭。在 Mac 上，只需点按菜单栏中的 Wi-Fi 图标，然后选择关闭 AirPort 选项。同样，如果你需要互联网，这并不那么有用，但当你不积极使用它时，暂时关闭它并不是一个坏主意。你保持联系的时间越长，人们注意到你在那里并开始四处窥探的时间就越长。*

### *如何自动化您的公共 Wi-Fi 安全设置*

*显然，您不希望每次在咖啡店和安全的家庭网络之间来回切换时都必须手动调整所有这些设置。幸运的是，有一些方法可以自动完成这一过程，这样当您连接到公共 Wi-Fi 网络时，就可以自动获得额外的保护。*

#### *在 Windows 上*

*当您第一次连接到 Windows 上的任何给定网络时，系统会询问您是连接到家中、工作场所的网络，还是公共网络。这些选择中的每一个都将触发预设设置列表上的开关。公共环境自然会给你最大的安全感。您可以通过打开控制面板并导航到网络和共享中心>高级共享设置来自定义每个预设所需的内容。在那里，您可以为不同的配置文件打开或关闭网络发现、文件共享、公共文件夹共享、媒体流和其他选项。*

 *[https://lifehacker.com/embed/inset/iframe?id=youtube-video-uSaCLuEFb2w&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-uSaCLuEFb2w&start=0)* 

*这是一个好的开始，但如果你想要更多的控制，前面提到的[NetSetMan](http://www.netsetman.com/index.php?s=nsm)是一个很好的程序，可以为不同的网络定制您的网络配置文件；每次连接到预设的网络时，您可以选择 IP 地址、DNS 服务器，甚至运行脚本(打开窗口进行几乎任何操作)。*

#### *在 OS X*

*OS X 没有像 Windows 一样内置这些选项，但像 [ControlPlane](http://www.controlplaneapp.com/) 这样的应用程序可以进行大量的定制。有了它，你可以打开你的防火墙，关闭共享，连接到一个虚拟专用网络，等等，这一切都取决于你连接的网络。*

#### *在您的浏览器中*

*前面提到的[HTTPS Everywhere](https://www.eff.org/https-everywhere)Firefox 扩展自动为一系列流行的网站选择安全 HTTPS 选项，包括纽约时报、Twitter、脸书、谷歌搜索等，确保您每次访问时都能安全地连接到任何支持的网站。您甚至可以将自己的文件添加到他们的 XML 配置文件中。注意，作为 Firefox 的扩展，它可以在 Windows、Mac 和 Linux 上工作。*

#### *考虑“安全第一”的方法*

*如果你是一个真正的频繁出差族，你可能会发现自己添加了如此多的配置文件，以至于在过程中的每一步都自动设置安全设置似乎是一项繁重的工作。虽然像星巴克或麦当劳这样的大多数连锁店应该为他们的每个 Wi-Fi 网络使用相同的名称(因此您的配置文件将继续使用)，但更好的方法可能是将您更安全的设置作为您系统的默认设置，并为您的家庭网络只创建一个配置文件。因此，默认情况下，文件共享将被关闭，您的防火墙将处于最安全的状态，等等——然后，当您回到受保护网络的家中时，您可以让 Airport Location 或 NetSetMan 打开安全性较低的设置。*

* * *

*这无论如何都不是包罗万象的，但是应该给你一个每次连接到公共网络时应该做的事情的快速清单。当然你还可以做很多其他的事情(比如 [通过 SSH](http://lifehacker.com/geek-to-live-encrypt-your-web-browsing-session-with-a-237227) 或者 [安装这些扩展](https://lifehacker.com/the-best-browser-extensions-that-protect-your-privacy-479408034) )，但是当你浏览这些公共热点的时候，这些步骤会让你在安全的道路上走得很远。当然，你们中的一些人已经有了自己的公共浏览程序，所以一定要在评论中分享你的安全网络技巧。*