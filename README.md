# appcan-release-android
### 2015/8/21版本更新记录

####Android插件：
 1. 插件名称及版本号：uexEasemob-3.0.13       更新内容：
    * 支持声音和震动
    
	* 发送附件支持wgt,wgts协议    	* 修复重新登陆后消息记录remoteUrl为空的问题
 2. 插件名称及版本号：uexJPush-3.0.6      更新内容：解决自定义消息附带extras时，json格式错误的问题
 3. 插件名称及版本号：uexInputTextFieldView-3.0.8      更新内容：修改EditText和webview中的输入框抢焦点的问题

***

### 2015/8/14版本更新记录

####Android插件：
 1. 插件名称及版本号：uexJPush-3.0.5      更新内容：解决获取通知附带extras时，json格式错误的问题
 2. 插件名称及版本号：uexSearchBarView-3.0.0      更新内容：新增

***
### 2015/7/31版本更新记录

####Android插件：
 1. 插件名称及版本号：uexAudio-3.0.5      更新内容：修复uexAudio.record方法不支持录音文件存储为.mp3格式的问题
 2. 插件名称及版本号：uexFileMgr-3.0.5      更新内容：新增cbWriteFile回调方法
 3. 插件名称及版本号：uexChatKeyboard-3.0.7
 	更新内容：添加返回输入工具条高度的接口
 4. 插件名称及版本号：uexBluetoothLE-3.0.0
 	更新内容：新增
  5. 插件名称及版本号：uexEasemob-3.0.11
 	更新内容：
 	* 新增API:getRecentChatters，onMessageSent
 	* 添加创建群回调onGroupCreated
***

### 2015/7/24版本更新记录
####Android引擎：            版本号：android_Engine_3.1_150724_01
      更新内容：修复多个appcan.window.alert()同时执行时，只会弹出一次的问题

####Android插件：
 1. 插件名称及版本号：uexAliPay-3.0.8      更新内容：更新支付宝SDK，解决当用户手机没有安装支付宝快捷支付服务时，会出现解析包错误的问题
 2. 插件名称及版本号：uexGaodeMap-3.0.3      更新内容：新增离线地图相关方法，优化添加标注接口使其支持自定义气泡
 ***

### 2015/7/17版本更新记录

####Android插件：
 1. 插件名称及版本号：uexEasemob-3.0.9      更新内容：支持离线消息
 2. 插件名称及版本号：uexIndexBar-3.0.2      更新内容：    * 索引表可以设置是否随网页滑动    * 修改多次open之后不能成功close的问题
 3. 插件名称及版本号：uexBaiduMap-3.1.22
 	更新内容：修复加入百度地图插件后uexLocation.openLocation()中的onchange事件不能使用问题
***

### 2015/7/10版本更新记录
####Android插件：

1.	插件名称及版本号：uexScanner-3.0.12 
	
	更新内容：去除读取联系人权限	

2.	插件名称及版本号：uexClipboard-3.0.1
		
	更新内容：修复被复制的文本包含换行符会导致插件异常的bug
	
3.	插件名称及版本号：uexJPush-3.0.3
	
	更新内容：
	* 修复onReceiveNotificationOpen,调整初始化时机    * 修复4.4以下版本点击通知闪退的问题

4.	插件名称及版本号：uexAreaPickerView-3.0.3  
	
	更新内容：返回数据添加空格便于分割


	

***

### 2015/7/3版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150703_01
      更新内容：

 1. 新增isAppInstalled，cbIsAppInstalled判断是否安装某第三方应用方法及其回调方法
 2. 新增cbStartApp启动第三方应用的回调方法。 	          ####Android插件：
 1. 插件名称及版本号：uexImageBrowser-3.0.21     更新内容：修复多选图片接口在手机上没有图片时崩溃的问题
 2. 插件名称及版本号：uexLocalNotification-3.0.6     更新内容：修复应用在后台被杀后无法通知的问题
 3. 插件名称及版本号：uexGaodeMap-3.0.2     更新内容：新增removeMarkersOverlays、removeOverlays、setScaleVisible、setMyLocationButtonVisible、setZoomVisible接口。 4. 插件名称及版本号：uexEasemob-3.0.8     更新内容：getGroup添加groupName,groupDescription字段
 5. 插件名称及版本号：uexChatKeyboard-3.0.6     更新内容：修复点击表情，再点击空白区域，再点击输入框时撑满屏幕的问题
 6. 插件名称及版本号：uexChart-3.0.1     更新内容：替换ActivityGroup
***
### 2015/6/25版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150624_01
   更新内容：
   1. 修复弹出两次增量更新提示问题
   2. 修复低版本手机开启增量更新开关崩溃问题
   3. 修复外置sd卡路径图片无法显示的问题 	          ####Android插件：
 1. 插件名称及版本号：uexBaiduMap-3.1.20     更新内容：
    * 修复点击路径规划中的起终点标注时，应用崩溃的问题
    * 去除多余的权限
 2. 插件名称及版本号：uexCall-3.0.2     更新内容：兼容老版本插件
 3. 插件名称及版本号：uexSMS-3.0.2     更新内容：兼容老版本插件
 4. 插件名称及版本号：uexAreaPickerView-3.0.2     更新内容：新增
 5. 插件名称及版本号：uexCalendarView-3.0.1     更新内容：新增
 6. 插件名称及版本号：uexChatKeyboard-3.0.5     更新内容：新增
 7. 插件名称及版本号：uexCityListView-3.0.0     更新内容：新增
 8. 插件名称及版本号：uexInputTextFieldView-3.0.6     更新内容：新增
 9. 插件名称及版本号：uexLoadingView-3.0.3     更新内容：新增
 10. 插件名称及版本号：uexFileMgr-3.0.4     更新内容：添加renameFile接口
 11. 插件名称及版本号：uexIndexBar-3.0.1     更新内容：clean时不删除view
 12. 插件名称及版本号：uexEasemob-3.0.7
      更新内容：getChatterInfo返回新加好友的聊天记录            
***

### 2015/6/19版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150616_01  
   更新内容：解决第三方应用调用appcan应用时参数丢失的问题。 	          ####Android插件：
 1. 插件名称及版本号：uexWeiXin-3.1.30     更新内容：修复微信支付返回时偶尔没有回调的问题。
 2. 插件名称及版本号：uexEasemob-3.0.6      更新内容： 
    * 添加getTotalUnreadMsgCount接口
    * 获取全部公开群改成分页获取
        
***
### 2015/6/12版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150612_02     
   更新内容：

1. 修复低版本安卓机找不到isHardwareAccelerated 的问题2. 支持网页&lt;input type="file”&gt;3. toggleSlidingWindow添加reload参数 	          ####Android插件：
 1. 插件名称及版本号：uexBaiduMap 3.1.19
     更新内容： 解决百度地图上箭头不转动的问题
     2. 插件名称及版本号： uexEasemob 3.0.5
     更新内容：升级环信SDK 3. 插件名称及版本号： uexCall 3.0.1
        更新内容：  去掉直接拨打电话的接口及权限  4. 插件名称及版本号：uexSMS 3.0.1
        更新内容： 去掉直接发送短信功能及权限 5. 插件名称及版本号： uexJPush 3.0.1
        更新内容：  修复退出应用时收到推送闪退的问题 6. 插件名称及版本号：uexScanner-3.0.11
        更新内容：  增加扫描本地图片功能。         7. 插件名称及版本号：新增uexChart几何图表插件

***
### 2015/6/5版本更新记录
####Android插件：

1.	插件名称及版本号：uexWeiXin-3.1.29
	
	更新内容：uexWeiXin插件，支付sdk升级。
	

	

***
	
### 2015/5/29版本更新记录
   ####Android插件：
 1. 插件名称及版本号：uexScrollPicture-3.0.1
 	更新内容：新增插件 2. 插件名称及版本号：uexEasemob-3.0.3
 	更新内容：新增发送视频，发送回执接口 3. 插件名称及版本号：uexJPush-3.0.0
 	更新内容：新增插件*** 	

### 2015/5/20版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150522_01       
   更新内容：

1. 修复Android 4.4版本关闭子应用后键盘并没有关闭问题；2. 新增onPopoverLoadFinishInRootWnd(name,url)监听方法；3. 添加webview嵌view方法（非API接口，供自定义插件调用）；4. 修复部分网页加密后显示网页源码的问题。 	          ####Android插件：
 1. 插件名称及版本号：uexAliPay-3.0.7
 	更新内容：支付宝插件升级 2. 插件名称及版本号：uexXmlHttpMgr-3.0.15
 	更新内容：onData回调函数参数修改 3. 插件名称及版本号：uexDownloaderMgr-3.0.7
 	更新内容：修复不支持HTTPS问题 4. 插件名称及版本号：uexUploaderMgr-3.0.4
 	更新内容：修复不支持HTTPS问题 5. 插件名称及版本号：uexImageBrowser-3.0.19
 	更新内容：修复加密情况下，网页读取img标签的src路径图片打不开的问题 6. 插件名称及版本号：uexGaodeMap-3.0.1
 	更新内容：新增高德地图插件 7. 插件名称及版本号：uexScanner-3.0.10
 	更新内容：二维码扫描优化
