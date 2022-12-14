# 用手机买东西的幕后发生了什么

> 原文：<https://gizmodo.com/what-happens-behind-the-scenes-when-you-buy-things-with-1704726941>

你决定买一双新鞋，你要用你的智能手机点击收银台来付款。这就像使用你的信用卡——除了它不是。以下是你手机上的钱真正发生了什么，当你花的时候，当你只是带着它到处走的时候。



### 窃听电话

所以回到那双鞋。你把它们放在柜台上，然后拿出你的手机点击它。交易发生时，你的手机正在使用 NFC 或近场通信与收银台联网。

你的手机有一个 NFC 芯片，它使用一个非常小的电磁场将你的信用卡信息发送到收银台读卡器中的 NFC 芯片。它只能在几厘米的距离内工作，所以你必须把手机握得很近。一旦你的支付信息被传输，这个过程就像你刷了一张塑料信用卡一样。

### 获得付款批准

在登记簿上写着“批准”之前的一两秒钟里，在店员给你收据的时候，有很多事情发生了。结帐终端将您的数据发送到收单银行，收单银行是为商店处理信用卡交易的银行。它被称为“收单”银行，或简称为“收单机构”

收单方向发行你的信用卡的银行发送请求，要求授权；本质上，收购者确保你的账户是有效的，并且有足够的钱支付鞋子。你的发卡机构——如果你是维萨卡或万事达卡持卡人，可能是你的银行；如果你使用 Discover 或 American Express，信用卡公司也是你的发卡机构——向收单机构发送授权码，收单机构告诉商家继续向你出售鞋子。

### 但是你实际上还没有付钱

你穿着新鞋走出商店，但你刚刚花的钱还没有真正转手。你的交易会和商店一天中的其他交易一起保存，当天晚上，商店会将所有这些交易批量发送给收单机构。

第二天，当你穿新鞋时，商店的收单机构通过信用卡网络发送这批交易——这是你信用卡上的品牌，在美国通常是 Visa、MasterCard、American Express 或 Discover。然后，信用卡网络将你的交易发送到你的银行，银行从你的账户中提取资金，并通过信用卡网络将其发送回收单机构，收单机构为你的鞋子向商店付款。这就是为什么你购买的东西有时需要一两天才能真正从你的账户中出来，或者为什么它们有时会显示为“待定”几天。

无论你是用磁条卡、EMV 芯片卡还是智能手机支付，这个过程都是一样的。但当你设置手机使用谷歌钱包、Apple Pay 或其他电子钱包应用时，手机内部会发生什么呢？

### 钱包技术

这里有点复杂，因为有不同的方法来存储 NFC 支付的账户信息，每个移动钱包似乎都有稍微不同的方法。有些人通过将你的信用卡信息存储在手机的安全硬件中来保护你的信用卡信息。其他人将你的卡信息存储在云中，然后将该信息的加密版本作为支付“令牌”发送到你的手机上。还有一些结合了前两者，将你的卡信息存储在安全硬件*和*上，确保结账终端只能看到代币，而不是真实的卡号。

让我们来看看一些主要的移动钱包实际上是如何工作的。

### Apple Pay 和 Samsung Pay

如果你有一部 iPhone 6、一部三星 Galaxy S6 或少数几部老款智能手机中的一部，你的手机包含一个名为嵌入式安全元件的芯片，可以存储你的信用卡信息。当你在结账终端点一下手机，嵌入式安全元件就会通过手机的 NFC 芯片将你的卡信息发送到结账处。这就是 Apple Pay 和 Samsung Pay 存储你的卡信息的方式——有点像。实际上要复杂一点。

当你注册 Apple Pay 时，你的真实信用卡号码并没有存储在你 iPhone 的安全元件中；它存储在云中。你的信用卡网络与苹果公司合作，发行代币，代币是你真实卡号的替代品，并将它们存储在你手机的嵌入式安全元件中。

这些令牌看起来像普通的信用卡号码，但它们只在你的个人 iPhone 上有效，所以犯罪分子无法窃取 Apple Pay 令牌并在网上使用。也不可能从代币上破译你的真实卡号。因此，令牌化背后的想法是，即使犯罪分子设法窃取了您的令牌，它们也没什么价值。

Samsung Pay 使用略有不同的流程来创建令牌，它们通常只会工作一次。三星的令牌也存储在嵌入式安全元件中，或者存储在手机内存中一个名为可信执行环境的安全区域中。

那么，回到你买鞋的问题上来:当你点击你的 iPhone 或 Galaxy S6 来购买这些鞋子时，你的手机使用令牌和你的交易信息来创建一个“令牌密码”，这个密码通过收单机构发送到你的卡网络，它可以将令牌追溯到你的真实卡号(这被称为“重新映射”)，然后*再*将交易信息发送到你的银行。商店和它的收单机构永远看不到你的真实卡号。

要让你的银行卡进入那些移动钱包，你的银行必须与三星或苹果公司签署协议，这需要花钱。当你使用信用卡时，商店向发卡银行支付一笔小额的“交换费”。如果你的银行想加入 Apple Pay 或 Samsung Pay，作为回报，它必须向苹果或三星支付部分交换费。

手机制造商也可以将嵌入安全元素的空间出租给希望为客户推出自己的移动钱包的银行。这意味着银行可能会租用你手机的一小部分，即使你没有使用移动支付系统。

### 谷歌钱包

谷歌钱包的工作方式略有不同。你可以在谷歌钱包中添加信用卡，或者将你的银行账户链接到这项服务，谷歌会将账户信息存储在其服务器中；这有点像给 PayPal 账户添加一个卡或银行账户。

你的卡信息不会存储在你的 Android 手机上。相反，谷歌创建了一种虚拟信用卡，称为谷歌钱包虚拟卡，本质上是作为你真实账户信息的令牌。每笔交易的虚拟卡号都会改变——这是一种安全形式，就像 Samsung Pay 的一次性令牌一样。通过更改每次交易的号码，谷歌钱包可以防止您的令牌被盗和重复使用。

谷歌钱包没有使用安全元素，而是使用了一种称为 [主机卡仿真](https://developer.android.com/guide/topics/connectivity/nfc/hce.html) 的技术，该技术使用软件来完成与安全元素中的硬件相同的任务。

### NFC SIM 卡

苹果没有发明 NFC 支付；它们已经存在好几年了。基本想法是将您的卡信息存储在一个芯片上，当您点击支付时，该芯片使用 NFC 将信息发送到结账终端。一种方法是将你的信息存储在带有 NFC 芯片的 SIM 卡上，这种芯片可以从你的移动电话公司获得。例如，如果你是美国美国电话电报公司、T-Mobile 或威瑞森的客户，你可能会记得 Softcard(以前是 Isis，直到他们根据当前事件更改了名称以避免尴尬的混淆)，它使用 NFC SIM 卡来存储其移动钱包应用程序的卡信息。如果你住在欧洲，你可能见过你的移动电话公司尝试类似的方法。

如果你的移动电话公司决定推出自己的移动钱包版本，它可能会使用 NFC 模拟人生，因为这种方法让电话公司完全控制移动钱包。如果你想注册，你可以去离你的移动服务提供商最近的零售店申请一张 SIM 卡。他们可能会像 Softcard 一样免费提供给你，或者收取少量费用。然后，您将从应用商店下载移动钱包应用程序，并将您的卡添加到移动钱包中——如果您的银行支持的话。

如果一家银行想让其客户在电话公司的 SIM 卡上存储卡信息，该银行将不得不向电话公司支付一笔费用，以租用 SIM 卡上的空间。银行和移动电话公司还必须雇用另一家公司，称为可信服务经理，来处理一些安全服务；通常，每一方都聘请自己信任的服务经理，然后他们都必须进行协调。虽然谷歌钱包今年早些时候收购了 Softcard，但到目前为止，基于 SIM 卡的 NFC 支付在美国还不是很受欢迎。

当你使用移动钱包支付时，要记住的重要一点是，这些应用程序允许更多的玩家拥有更多的手机硬件。这也意味着您的移动服务提供商正在直接或间接地与您的银行建立合作关系。

当你用手机钱包买鞋时，你不仅仅是在使用一种新兴技术。你帮助培育了一批新的企业合作伙伴，这可能会像影响手机芯片一样影响你的银行业务。