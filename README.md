jd_auction
==========

京东夺宝岛抢拍插件

使用方法：
1.安装插件
2.登录京东，访问夺宝岛，进入商品页面可看到页面顶端增加了抢拍的div。
3.在输入框输入自己愿意出的最高价格，点击"后台抢拍"，程序自动查询当前价格并加价1元 并完成出价。
4.抢拍过程可以打开控制台（console）查看日志

程序原理：
当浏览器url地址匹配到"http://paimai.jd.com/*"时自动加载插件，插件加载一个输入框，输入用户愿意的最高出价，然后点击“后台出价”按钮一次，程序自动后台查询最新价格后+1 完成出价提交到京东。


解决几个问题：
1.抢拍时最后一秒你的价格被人超了；
2.你想重新出价却时间不够了（最后几秒出价非常激烈）；
3.你为了抢到商品，不得不出一个“非常高”的价格（此程序只会在别人价格上+1）；
4.解决京东官方提示的最新价格延迟的问题（京东提示的当前价格通常会延迟5s左右，非常影响抢拍的出价）；
5.解决抢拍网速问题（为了看到最新的价格，通常会刷新整个页面，一次刷新会2-10s不等，通过程序仅仅后台一个请求）；
6.提高出价效率，只需不到0.1s的时间即可完成一次别人出价+1的抢拍，就看你点的速度；



==============抢拍日志==============

***京东夺宝岛抢拍-谁与争锋***
提供自动报价(半自动)和自动抢拍（全自动）两种功能
六折价（原价6折值，为抢拍出价提供参考）
最高出价（自己愿接受的最高价，程序会自动在当前商品报价+1，到达最高价放弃出价，放弃此商品。)
 jd.js:6
有任何问题  QQ 244320233 jd.js:7
个人主页：http://zhanghang.org jd.js:8
……
自动报价，5295077自动输入价格。 jd.js:28
……
抢拍商品5301558自动提交抢拍价。 jd.js:45
恭喜您！  出价成功 
# jdpaimai
