#个人简介
*   多个原生iOS开发经验，领域包括P2P平台，O2O，商城，音乐，功能包括IM，支付，分享，三方登陆。熟练使用Objective-C和Swift，掌握常用开发模式，对Http，Socket通讯有充分的了解，熟练解析JSON、XML等主流交互数据格式。
*   985，211高校，工科背景，2年技术开发经验，一年后端，一年前端。
*   纯理性思维者，爱弹吉他。

#技术经历
*   框架：MVC, MVVC
*   布局：AutoLayout, SizeClass, Interface Builder, Mansory
*   数据：Realm
*   传值；Delegate, block, KVO, 单例, 属性
*	线程：GCD
*	其他：Git，Cocoapods

#项目技术细节

##	  互惠中国

>中冶惠（上海）互联网金融信息服务股份有限公司，品牌名互惠中国，是中冶国福（上海）控股有限公司旗下的专业互联网金融信息服务平台，成立于2015年，注册资本1亿人民币，总部位于上海市静安区。

![](互惠之家2.1.0 拷贝.png)

*  简介：
	*  [中冶集团的p2p理财平台](http://www.huhuizg.com/)，iOS端的开发   
	*  通过转盘进入不同的tab，排行榜是通过UITableView展示的商品列表，理财课堂进入在线视频流播放，最		新活动进入UIWebView相对应的网页，收益列表显示账户的投资收益
*   职责：
	*	负责私人理财，收益之星，互惠众筹模块
	*	对AFNetWorking进行封装，整理常用工具库，包括时间戳，加密算法
	*	把IPA文件上传到蒲公英进行分发
*   语言：Objective-C
*   功能：理财商城，订单，三方登陆、分享，支付
*   三方库：AFNetworking, SDWebImage, ProgressHUD, ShareSDK
 

##		喵喵客

>喵喵客(miaomiaobank.com)是广群金融旗下独立品牌，于2015年2月上线。致力于搭建一个高效、透明、安全的智能化互联网理财产品交易平台，目前累计用户近30万。

![](miaomiaoban.gif)

[链接](https://itunes.apple.com/cn/app/miao-miao-ke-tou-zi-li-cai/id977918033?mt=8)

*	简介：
	* 	[喵喵客](http://www.miaomiaobank.com/)的iOS版本
	*	自定义手势实现Tab的转换，JS端通过WKWebView的代理方法进行交互调用Native的分享页面，通过UIPageViewController实现同一页面多个UITableView的切换和数据加载，使用连连支付的接口实现移动支付
*   职责：
	*	负责首页，理财，个人中心模块
	*	封装CircleView实现旋转进度条的效果，封装UIPageView实现多栏展示，加载，更新数据的效果
	*	对接连连支付，完成快捷支付
*	语言：Swift, Objective-C
*	功能：商品展示，支付，分享，手机验证，排序
*	三方库：SDWebImage, AFNetworking, MJRefresh


##	  美容院
>越南PlaSoftWate的外包项目

![](beautycare.png)

*	简介：
	*	美容院预约系统，后台集成现有的.Net后台进行接口封装
	*	主要有3个功能，建立预约，取消预约，预约历史
	*	最大的困难是语言的Localization，iOS前端的好配置，最大的挑战是后端集成，现有的http协议显示乱码，中途尝试过用.Net直接socket通讯，最终解决
*	职责
	*	负责项目整体的UI界面，架构设计，功能，网络通讯
	*	因为是越南的app，国内的手机短信提供商无法满足，寻找国际版的手机验证方案
*   语言: Swift
*   功能：建立、查看、取消预约，fabric手机验证
*   三方库：Fabric, Alamofire, ObjectMapper, ActionSheetPicker, Refresher


#其他开源项目和个人作品
## [美术馆](https://github.com/zxtcko/artMuseum)

![](https://github.com/zxtcko/artMuseum/blob/master/artmuseum.gif)

## [CustomEcho](https://github.com/zxtcko/customEcho)

![](https://github.com/zxtcko/customEcho/blob/master/preview/customEchoDemo.gif)

## [TripTree](http://www.chriscoder.me/ionic/TripTree/www/index.html)

![](triptreedemo.gif) 


#理想团队
+   高效
+   有大牛