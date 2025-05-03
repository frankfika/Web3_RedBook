# 行研 | 微信小程序 VS Telegram的Mini App；9亿月活，泼天的富贵!

![图片](/Users/fangchen/Github/Web3完全指南/5、公链专题/Ton链/行研 | 微信小程序 VS Telegram的Mini App；9亿月活，泼天的富贵!.assets/640-20250503213311808)



- Telegram目前的月活已经达到了9个亿
- 现在仿照微信在做MiniApp的生态
- 目前已经好几个上线的游戏在短时间获得数千万的用户



**这波天降的富贵，可千万不要错过啊！
**







**01 账户体系**

------



在微信小程序里面，账户体系其实非常简单明了，就是微信的用户id作为唯一的全局追溯，当然你也可以获取用户的手机号作为辅助的判断手段。

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



但是这个在Telegram的MiniApp中可大不一样。因为Ton本身就是一条公链，在Web3的账户体系，从来都是一对多的概念，即**一个用户可以拥有多个钱包（wallet），每个钱包即代表一个账户**。



Telegram的MiniApp延用了这个规矩，以钱包地址作为用户在MiniApp中的追溯Id，以Telegram的用户id作为辅助。这也就导致了一个很有意思的现象：

- 有的MiniApp指明需要你的Telegram只能对应唯一一个钱包地址，多了无效；
- 但是更多的是和Telegram的Id送绑定，即以钱包地址作为账户的唯一识别手段，也就是说你可以没有Telegram或者不使用Telegram内置的wallet，可以使用类似于ton keeper的第三方wallet，这样其实你就可以不断切换地址，来实现不同的账户在同一个Telegram小程序里面的登陆。
- 同样这还导致一个有意思的事情就是Ton 小程序不等于Telegram小程序，Telegram的小程序是可以不和Ton绑定直接存在的，比如Wave Wallet的钓鱼应用就是SUI链的应用在Telegram部署了小程序。







**02 支付体系**

------



![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



**Ton Wallet**

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



**微信钱包**





Telegram的MiniApp和微信小程序最大的不同就是在于支付体系。相比较于微信的法币支付体系，Telegram本身拥有自己的公链-**Ton**，所有的交易支付都是建立于Ton的加密货币体系之上。

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



另外今年早些时候，Ton和泰达币（USDT）正式绑定，Ton上也上线了自己的基于Tether的USDT，这无疑是一个重磅炸弹，标志着**Telegram上已经拥有了一个和法币一样的价值锚定物**。不过这也是一个灰色地带，因为不受监管，所以很容易被人用作一些不正当交易。比如卖淫嫖娼，现在都可以直接收加密货币了，并且聊天也在Telegram上，不会存留任何证据，给监管带来了极大的难度。







**03 宣发方式**

------



微信小程序发布之时，那可真是声势浩大，无论是互联网广告，还是微信自己的入口，都在极力告诉宣传他家小程序。但是Telegram的MiniApp好像是偷偷摸摸的。



![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)

![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)





先说说Telegram的内置wallet，大部分人可能都找不到wallet在Telegram里面的入口在哪里。因为如果你没有登陆过Telegram里面的MiniApp或者没有人给你转过任何钱到你的ton上（通过Telegram转账），你的菜单里面就不会出现wallet的tab。这点我和很多朋友都验证过了，甚至很多原生web3的朋友都没有意识到这点，这其实也从侧面证明了Telegram的小程序覆盖面还是有限，有极大的上升空间。



同时Telegram的MiniApp很有意思的是他没有一个清晰的统一入口，他是完全依附于Telegram的bot里面的，你得关注了bot才能找到，这种方式也让很多非极客的人想找小程序找不到。虽然有TrendingApps的Channel（下图）勉强算是AppStore，但是藏得极为隐秘。



![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



至于为什么这么设计，用灰度测试，且不给公开入口。我个人猜测是两个原因

- 首先Ton和Telegram虽然本质是一家，且大股东都是Telegram老板，但是因为出于监管和Telegram上市的角度来考虑，不能走得太近。原来Ton叫Telegram Open Network，现在是叫The Open Network，不排除是Telegram刻意避嫌的原因。
- 另外持续灰度测试，也不排除Telegram在憋了一个大招。等待释放。







**04 面向人群**

------



微信小程序的人群其实很好描述，就是华人社区为主，使用法币为主。但是Telegram的群体似乎有些不一样。Telegram早期起家是因为不受监管，可以自由交流，所以很多种子用户都是有些灰色地带的人群；后面Web3的崛起，Telegram又成为了Web3人群的主要沟通工具。



所以目前Telegram的核心人群就是一群灰产和赌徒，当然也不排除一些正常的人士想要做隐秘交流。这也导致了Telegram的MiniApp和微信小程序的主要内容不大一样，Telegram的MiniApp现在最火的都是ClickApp或者一些非常无脑的小游戏，一方面适合这个人群，另一方，这种简单的形式也方便科学家薅羊毛去撸空投和获取代币。







**04 开发难度**

------



![图片](data:image/svg+xml,%3C%3Fxml version='1.0' encoding='UTF-8'%3F%3E%3Csvg width='1px' height='1px' viewBox='0 0 1 1' version='1.1' xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink'%3E%3Ctitle%3E%3C/title%3E%3Cg stroke='none' stroke-width='1' fill='none' fill-rule='evenodd' fill-opacity='0'%3E%3Cg transform='translate(-249.000000, -126.000000)' fill='%23FFFFFF'%3E%3Crect x='249' y='126' width='1' height='1'%3E%3C/rect%3E%3C/g%3E%3C/g%3E%3C/svg%3E)



从开发难度来讲，Telegram的MiniApp要远远低于微信小程序。

- 第一个他是支持网页直接转成miniapp，你只需要向botfather发送一个链接就可以，直接将h5转换成miniapp。
- 其次，他提供完整的ton的sdk。很多朋友担心合约过于复杂，对于web2的开发者难以进入，其实没那么麻烦。你的大部分数据其实并不在链上进行交互，都是中心化操作为主；你真正和链上进行交互的其实就两步，
	- 第一步，登陆时候获取ton wallet钱包作为用户名；
	- 第二步，在支付的时候，调用ton的接口。当然你如果要发行自己的代币，那么就需要你会一些更多的上链和发行的设置，但是这步也没有那么繁琐，且大部分游戏都是用积分替代代币，所以这部分你也不需要在短期内考虑。

  





