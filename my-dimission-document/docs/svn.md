# svn项目链接文档和项目介绍文档
	创建于20190503

<br/>
## 1688
### 牛店长
	`https://svn.wonbao.net/svn/2018/wonbao/1688/wb-ndz-web`
### 1688交易
	`https://svn.wonbao.net/svn/2018/wonbao/1688/wb-1688-web`
#### <h4 style="color:red">1688交易项目节点记录</h4>
	1、物流云授权
		物流云授权开发文档：https://open.taobao.com/doc.htm?docId=107149&docType=1
	2、菜鸟电子面单
		菜鸟电子面单开发文档：https://global.link.cainiao.com/#/homepage/api/logistics/merchant_electronic_sheet/CLOUDPRINT_CMD_RENDER?_k=fdah62
	3、项目文件控制器路径在 /wb-1688-web/src/main/java/net/wonbao/tb1688/web/controller/cainiao 包下

<br/>
## 小程序
### 旺衣库小程序
	`https://svn.wonbao.net/!/#2018/view/head/wyiku/period-01/程序源码/mall`
<h4 style="color:red">旺衣库小程序目录结构</h4>
	├── api
	│   └── api.js  //接口文件
	├── app.wpy		//入口文件
	├── components	//组件文件存放位置
	│   ├── common	//公共组件文件存放位置
	├── images		//图片文件存放位置
	├── pages		//页面文件存放位置
	├── plugins		//插件文件存放位置
	├── styles		//样式文件存放位置
	├── utils  		//工具类文件存放位置
	└── wxs			//帮助类文件存放位置

#### <h4 style="color:red">旺衣库小程序接口文档</h4>
<a href="https://docs.qq.com/sheet/Db01QSE9uYUJ0SEVm?opendocxfrom=admin&tab=jhqrco&coord=A1%24A1%240%240%240%240" target="_blank">旺衣库小程序接口文档点击进入查看</a>

<br/>
## 微信
###	moto酒吧	
	`https://svn.wonbao.net/svn/2018/moto/wechat/moto-music-tavern-wechat`
#### <h4 style="color:red">moto酒吧项目节点记录</h4>
```
	《moto音乐酒馆微信服务号》项目测试环境启动------------
	
	tomcat8.5  jdk1.7
	
	启动:tomcat服务器启动
	
	访问路径：localhoat:8080
	
	项目控制器入口都在该路径文件夹下：/moto-music-tavern-wechat/src/main/java/net/wonbao/wechat/web/
```

### 旺店宝微信公众号接口开放客户端
	`https://svn.wonbao.net/svn/2018/wonbao/wechat/wb-wechat-client`
###	旺店宝微信服务号系统
	`https://svn.wonbao.net/svn/2018/wonbao/wechat/wb-wechat-web`
#### <h4 style="color:red">旺店宝微信服务号系统项目节点记录</h4>
	修改微信公众号菜单，只需修改对应菜单按钮内容和类型，直接执行main方法即可，执行文件的路径如下
	/wb-wechat-web/src/test/java/net/wonbao/weixin/test/MenuTest.java

###	旺店宝微信WEB端
	`https://svn.wonbao.net/svn/wonbao2016/serve/wechat/bs-project/wechatWeb`
#### <h4 style="color:red">旺店宝微信WEB端项目节点记录</h4>
	迁移项目SVN地址

### 文档项目路径
	`https://svn.wonbao.net/svn/2018/wonbao/wechat`

<br/>
## 旺店宝
### 旺店宝PC主项目
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/bs-project/wonbaoWeb`
#### <h4 style="color:red">旺店宝PC主项目节点记录</h4>
	1、图片编辑器类，文件类路径
		(wonbaoWeb/src/net/wonbao/web/editor/service/impl/PosterDesignServiceImpl.java)
	2、更换EJB后，测试优惠券是否能正常显示，文件类路径
		(wonbaoWeb/src/net/wonbao/web/action/web/MainAction.java)
	3、更换EJB后，测试用户消息中心是否正常，文件类路径
		(wonbaoWeb/src/net/wonbao/web/action/web/user/message/biz/UserMessageBiz.java)
		(wonbaoWeb/src/net/wonbao/web/action/web/user/message/MessageAction.java)
	4、修改上架时间的显示，文件类路径
		(WonbaoWeb/WEV-INF/view/web/trffic/listing/monitor-record.jsp)
	5、修改指定自动上下架时间，文件类路径
		(wonbaoWeb/WebRoot/js/web/biz/traffic/shelf/item-list.js)
		(wonbaoWeb/WebRoot/js/web/biz/traffic/shelf/item-onsale.js)
	6、修改保存主图图标的时候增加一个标识，文件类路径
		(wonbaoWeb/src/net/wonbao/web/action/web/marketing/marknew/TemplateAction.java)
	7、标题优化：非热词去除重复，文件类路径
		(wonbaoWeb/src/net/wonbao/web/action/web/traffic/title/biz/WordService.java)
	8、制作或者直接投放模板保存时新增一个系统模板ID，文件类路径
		(wonbaoWeb/src/net/wonbao/web/action/web/marketing/mark/TemplateAction.java)
		(wonbaoWeb/src/net/wonbao/web/action/web/marketing/phoneposter/TemplateAction.java)
		(wonbaoWeb/src/net/wonbao/web/action/web/marketing/poster/TemplateAction.java)
		(wonbaoWeb/src/net/wonbao/web/editor/service/impl/PosterDesignServiceImpl.java)
		(wonbaoWeb/src/net/wonbao/web/editor/service/PosterDesignService.java)
		(wonbaoWeb/src/net/wonbao/web/editor/servlet/PosterDesignServlet.java)
	9、处理一键添加黑名单，重复添加的问题，文件路径
		(wonbaoWeb/src/net/wonbao/web/action/web/dsr/autorate/SettingAction.java)

### 旺店宝手机端
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/bs-project/wonbaoPhone`
#### <h4 style="color:red">旺店宝手机端节点记录</h4>
	1、满就送、首件优惠、个性打折、全店打折、统一打折功能EJB更换，从 SQLServer语法 切换为 MYSQL语法

### 旺店宝打印项目
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/bs-project/WonbaoTradeWeb`
### 旺店宝自动橱窗项目
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/cs-project/wonbao_traffic_showcase`
### 旺店宝自动上下架项目
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/cs-project/wonbao_ons_shelf`
	`https://svn.wonbao.net/svn/2018/wonbao/tb/biz/wb-auto-shelf-server`
### 旺店宝引流项目
	`https://svn.wonbao.net/svn/2018/wonbao/tb/biz/wb-auto-shelf`

<br/>
## 自动评价
###	自动评价项目
	`https://svn.wonbao.net/svn/wonbao2016/wonbao/cs-project/wonbaoAutoRateApp`
### 新自动评价项目
	`https://svn.wonbao.net/svn/wonbao2016/_ziqi/wb-auto-rate-delay`
<h4 style="color:red">新自动评价项目节点记录</h4>
	1、创建用户评价设置数据传输对象<br/>
	2、API评价模块<br/>
	3、数据库评价模块<br/>
	4、自动添加黑名单功能<br/>
	5、自动评价文档，<a href="https://svn.wonbao.net/svn/wonbao2016/_ziqi/wb-auto-rate-delay/document" target="_blank">点击查看更多</a>，文档启动查看方式与此文档一致

<br/>
## 速递交易
###	速递交易
	`https://svn.wonbao.net/svn/2018/wonbao/qn-sdjy`
#### <h4 style="color:red">速递交易项目节点记录</h4>
	1、订单全链路监控，文件类路径
		(wonbao/qn-sdjy/qnTradeWeb/com/taobao/servers/qnpc/action/print/printAction.java)
	2、辅助查看订单推送情况
	3、新增TMC订阅状态
		(wonbao/qn-sdjy/qnTradeWeb/com/taobao/servers/qnpc/action/print/printAction.java)
	4、修改LOGO跳转地址
	5、在发货页面时提醒用户使用淘系、菜鸟面单发货
	6、根据淘宝公告进行接口调整，公告地址如下
		https://open.taobao.com/announcement.htm?spm=a219a.7386653.0.0.7676669anHLcMg&source=search&docId=25434&docType=12
	7、根据淘宝公告对订单一致性改造跟进，公告地址如下
		 https://open.taobao.com/announcement.htm?spm=a219a.7386653.0.0.417a669aDTUyrW&source=search&docId=25429&docType=12
	8、每月进行速递交易项目压测

### 速递交易自动评价项目
	`https://svn.wonbao.net/svn/2018/wonbao/qn-sdjy/scheduler/qnTradeAutoRateApp`
	`https://svn.wonbao.net/svn/2018/wonbao/qn-sdjy/scheduler/qnTradeAutoRateRDSApp`

<br/>
## 帮助中心
### 帮助中心
	`https://svn.wonbao.net/svn/2018/wonbao/faq`
#### <h4 style="color:red">帮助中心项目节点记录</h4>
	1、用户登陆session拦截器，(/faq-web/src/main/java/com/wonbao/admin/interceptor/SessionUserInterceptor.java)拦截器文件路径
	2、用户模块，(/faq-web/src/main/java/com/wonbao/admin/controller/UserController.java)用户控制器文件路径
	3、问题模块，(/faq-web/src/main/java/com/wonbao/admin/controller/QuestionController.java)问题控制器文件路径
	4、类目模块，(/faq-web/src/main/java/com/wonbao/admin/controller/CategoryController.java)类目控制器文件路径
	5、根据问题生成问题答案文件,(/faq-web/src/main/java/com/wonbao/admin/quartz/service/QuartzService.java)文件路径，方法GenerateFiles(Model param)
	6、负责前后端对接、编写接口文档
	
<br/>
## 需求中心
###	需求中心
	`https://svn.wonbao.net/svn/wonbao2016/serve/dms/bs-project/DMS`
#### <h4 style="color:red">需求中心项目节点记录</h4>
	1、测试用户操作权限流程并做记录
#### 需求中心文档
	`https://svn.wonbao.net/svn/2018/wonbao/dms`

<br/>
## 旺牛数据
### 旺牛数据
	`https://svn.wonbao.net/svn/wonbao2016/qn/wnsj/bs-project/qnDataWeb`
#### <h4 style="color:red">旺牛数据项目节点记录</h4>
	1、根据淘宝公告接口调整，进行接口改造，公告地址如下
		https://open.taobao.com/announcement.htm?spm=a219a.7386653.0.0.7676669anHLcMg&source=search&docId=25434&docType=12
	2、更改JNDI[jndienvironment] 从 ejb.rds.wonbao.net  改成    ejb.kf.wonbao.net
		文件：/qn/wnsj/bs-project/qnDataWeb/src/application.xml

<br/>
## 新后台项目
### 后台项目
	`https://svn.wonbao.net/svn/2018/wonbao/manageWeb`

<br/>
## EJB项目
### EJB项目地址
	`https://svn.wonbao.net/svn/wonbao2016/serve/admin`
<h4 style="color:red">创建EJB项目</h4>
	1、创建EJB项目过程，详细记录<a href="https://blog.csdn.net/weixin_44010710/article/details/88350331" target="_blank">点击查看更多</a>
