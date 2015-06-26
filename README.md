# appcan-release-android
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


### 2015/6/19版本更新记录

####Android引擎：            版本号：android_Engine_3.1_150616_01  
   更新内容：解决第三方应用调用appcan应用时参数丢失的问题。 	          ####Android插件：
 1. 插件名称及版本号：uexWeiXin-3.1.30     更新内容：修复微信支付返回时偶尔没有回调的问题。
 2. 插件名称及版本号：uexEasemob-3.0.6      更新内容： 
    * 添加getTotalUnreadMsgCount接口
    * 获取全部公开群改成分页获取
        

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
