# appcan-release-android
### 2016/04/15版本更新记录
####Android插件：
1. 版本号：uexListView-3.0.10   更新内容：	删除universalimageloader源码		
2. 版本号：uexXunfei-3.0.0   更新内容：新增uexXunfei插件	

### 2016/03/26版本更新记录
####Android插件：
1. 版本号： uexVideo-3.0.6   更新内容：优化了视频录制的接口——   * 支持控制录制时间;   * 支持控制录制分辨率;   * 支持控制录制视频质量;* 优化了视频播放接口——   * 性能优化:采用全新的API去播放视频,优化了视频的加载速度,降低了CPU占用;   * 界面优化: UI美化;支持各种常用手势去控制播放;网络视频拥有预加载条提示;   * 支持小窗播放，支持小窗跟随网页滑动;   * 对全屏播放的细节做了处理:现在全屏模式下播放器强制横屏，并且不会随手机设置而自动旋转;   * 更多的可选参数去定制播放器界面;   * 为播放状态和播放器被关闭增加了监听;	2. 版本号：uexScrawl-3.0.0   更新内容：新增涂鸦功能插件	
3. 版本号：uexGaodeNavi-3.0.0   更新内容：新增高德导航插件
4. 版本号：uexQcloudAV-3.0.0	   更新内容：新增腾讯云视频直播插件
   
5. 版本号：uexNIM-3.0.0   更新内容：新增网易云信插件
   
6. 版本号：uexBackground-3.3.0

   更新内容：新增实现后台运行JS的功能（对应uexlocation插件更新了，配合测试
   
7. 版本号：uexLocation-3.0.7

   更新内容：新功能，优化定位权限,支持后台定位

   ***

### 2016/03/16版本更新记录
####Android插件：
1. 版本号： uexLoadingView-3.0.6    更新内容：* 优化空指针报错问题2. 版本号：uexScanner-3.0.15   更新内容：新增charset字段设置编码
3. 版本号：uexImage-3.0.11   更新内容：    * 优化所有手机剪裁图片的方案（针对华为、部分三星）。优化在打开图片浏览器显示图片列表，最新图片在最上方（倒序）          
    * 针对保存图片到相册接口，修复开启增量更新时的res协议路径的bug
4. 版本号：uexPopoverMenu-3.0.0   更新内容：新增弹出窗插件
   
5. 版本号：uexCamera-3.0.17   更新内容：
   * 修复了在三星手机上照片旋转方向不一致的问题
   * 优化了多次点击照相按钮，再点重拍照相按钮失效的问题。
6. 版本号：uexEasemob-3.0.20

   更新内容：* 优化setNotifyBySoundAndVibrate无效的问题

   ***
### 2016/03/14版本更新记录
####Android引擎：
1. 版本号：android_Engine_3.2_160302_01
     更新内容：引擎新添share 调用系统分享接口
   
####Android插件：
					1. 版本号：uexScanner-3.1.5	
   更新内容：添加charset字段设置编码				
***### 2016/03/12版本更新记录
####Android引擎：  1. 版本号：android_Engine_3.3_160310_01
    	 更新内容：
  	 * uexWindow添加获取window宽高的方法         * 分享支持res://协议        * 修复uexWindow.setWindowFrame调用之后第二次进页面异常的问题
     
####Android插件：
1. 版本号：uexPopoverMenu-3.0.0
    更新内容：弹出窗2. 版本号：uexLoadingView-3.0.6 
   更新内容：解决空指针报错问题3. 版本号：uexCamera-3.0.17

   更新内容：
   * 修复了在三星手机上照片旋转方向不一致的问题;修复了多次点击照相按钮，再点重拍照相按钮失效的问题   * 修复Activity拒绝服务漏洞的问题，修复了openViewCamera拒绝使用系统拍照权限后程序崩溃的问题
  4. 版本号：uexControl-3.0.7
   更新内容：修复日期不在范围内时，点击“确定”按钮能获取日期的问题5. 版本号：uexVideo-3.0.5
   更新内容：新加了createPlay接口 和 removePlay6. 版本号：uexEasemob-3.0.20
   更新内容：修复setNotifyBySoundAndVibrate无效的问题7. 版本号：uexSlidePager-3.0.16
   更新内容：openSlidePager接口添加option参数8. 版本号：uexInputTextFieldView-3.2.12
   更新内容：修改兼容性问题,添加新的接口和回调,调整优化代码逻辑,解决键盘遮蔽问题9. 版本号：uexZip-3.0.2
   更新内容：修复plugin.xml10. 版本号：uexImage-3.0.11
    更新内容：
    * 优化所有手机剪裁图片的方案（针对华为、部分三星）    * 优化在打开图片浏览器显示图片列表，最新图片在最上方（倒序）
   ***

### 2016/03/08版本更新记录
####Android插件：
1. 版本号： uexAudio-3.0.7   更新内容：* 优化了录音时用户禁止其权限的问题2. 版本号：uexImage-3.0.10   更新内容：* 优化针对保存图片到相册接口开启增量更新时的res协议路径
3. 版本号：uexListView-3.0.9   更新内容：* 优化plugin.xml
4. 版本号：uexPie-3.0.6   更新内容：* 优化plugin.xml
   
5. 版本号：uexFileMgr-3.0.13   更新内容：* 新增复制文件的方法***

### 2016/03/02版本更新记录
####Android插件：
1. 版本号： uexSecurityKeyboard-3.0.0   更新内容：* 新增uexSecurityKeyboard安全键盘输入框插件2. 版本号：uexDownloaderMgr-3.0.14   更新内容：* 优化下载过程中下载进度过快导致应用异常的问题
***
### 2016/02/24版本更新记录
####Android插件：
1. 版本号：uexDevice-3.0.4   更新内容：* 优化多次截屏失效的问题
   ***
### 2016/02/22版本更新记录
####Android插件：
1. 版本号：uexJPush-3.0.9   更新内容：* 优化setTags返回格式不正确的问题2. 版本号：uexScanner-3.0.14   更新内容：* 优化扫描框为正方形3. 版本号：uexDevice-3.0.3   更新内容：* 新增判断功能是否开启,以及打开设置界面接口
 ***

### 2016/01/26版本更新记录
####Android引擎：
   版本号：android_Engine_3.2_160120_01      更新内容：
   ＊新增支持网页内定位   ＊优化JS注入漏洞    ＊新增容器接口    
####Android插件：
1. 版本号：uexSina-3.0.11   更新内容：* 优化分享图片不能读取wgts://格式的文件问题
***
### 2016/01/16版本更新记录
####Android插件：
1. 版本号：uexControl-3.0.6   更新内容：* 解决华为手机上输入日期不生效的问题;新增openDatePickerWithConfig可配置日期范围的日期选择器接口。     

### 2016/01/11版本更新记录
####Android插件：
1. 版本号：uexUploaderMgr-3.0.8     更新内容：*  优化plugin文件uexFileMgr的plugin方法被覆盖的问题2. 版本号：uexContact-3.0.1     更新内容：* 新增searchItem接口增加返回信息条数配置;addItem接口增加是否弹出提
3. 版本号：uexDevice-3.0.2     更新内容：* 新增截图，听筒和扩音器切换， 设置/获取音量等接口示框配置
 ***
### 2016/01/07版本更新记录
####Android插件：
1. 版本号：uexBluetoothLE-3.0.3   更新内容：*  优化回调数据不正确的问题 ***


### 2015/12/31版本更新记录
####Android插件：
1. 版本号：uexDownloaderMgr-3.0.13     更新内容：优化有些url被encode不能下载的问题2. 版本号：uexVideo-3.0.4     更新内容：优化删除无用资源，修复Gradle编译不过的问题 ***

### 2015/12/26版本更新记录
####Android插件：
1. 版本号：uexWeiXin-3.1.33     更新内容：优化和完善抛出异常的捕获2. 版本号：uexScanner-3.0.13     更新内容：优化拍照权限被禁止情况处理3. 版本号：uexChart-3.0.2     更新内容： 新增barChart和lineChart  option参数  4. 版本号：uexGaodeMap-3.0.12     更新内容：优化闪退的问题 ***

### 2015/12/19版本更新记录
####Android插件：
1. 版本号：uexCoverFlow2-3.0.7   更新内容：优化open接口添加跟随webview滚动参数2. 版本号：uexScrollPicture-3.0.2   更新内容：优化闪退的问题3. 版本号：uexGestureUnlock-3.0.0   更新内容：新增 4. 版本号：uexUmeng-3.0.0   更新内容：新增 5. 版本号：uexUnionPay-3.0.0   更新内容：新增 6. 版本号：uexLocalNotification-3.0.8   更新内容：优化部分机型通知没有提示音的问题7. 版本号：uexEasemob-3.0.19   更新内容：优化cbGetMessageHistory与文档不一致的问题8. 版本号：uexSina-3.0.10   更新内容：优化cbRegisterApp回调openId和token9. 版本号：uexGaodeMap-3.0.11   更新内容：优化闪退的问题
 ***

### 2015/12/09版本更新记录
####Android插件：
1. 版本号：uexAudio-3.0.6
	更新内容：	* 新增听筒模式接口,修复小米手机音量设置无效的问题
	
	* 优化uexAudio.record方法不支持录音文件存储为.mp3格式的问题   2. 版本号：uexTimeMachine-3.0.5   更新内容：优化id覆盖关闭不掉的情况，修复传入小数错误的问题
 ***
### 2015/12/04版本更新记录
####Android插件：
 1. 版本号：uexLocalNotification-3.0.7    更新内容：优化部分机型闪退的问题 2. 版本号：uexBaiduMap-3.2.28    更新内容：优化open接口传入的中心点不生效的问题 3. 版本号：uexEasemob-3.0.17    更新内容：优化initEasemob配置key，无需自定义插件 4. 版本号：uexBluetoothLE-3.0.2    更新内容：优化init自动开启蓝牙；cbConnect没有回调的问题
 5. 版本号：uexInputTextFieldView-3.2.11    更新内容：优化关闭输入框时,键盘未自动收起的问题
***

### 2015/12/03版本更新记录
####Android引擎：
 版本号：android_Engine_3.2_151203_01 更新内容：
  * 新增浮动窗口动画
 * 新增引擎关闭全部硬件加速方法 
***
### 2015/11/30版本更新记录
####Android插件：
 1. 版本号：uexTent-3.0.11    更新内容：优化取消授权时程序崩溃的问题 2. 版本号：uexCalendarView-3.0.3    更新内容：优化month拼写错误的问题 3. 版本号：uexSina-3.0.9    更新内容：优化SinaSDK，重写授权登陆相关接口；新增login、logout、getUserInfo接口； 4. 版本号：uexWeiXin-3.1.32    更新内容：新增setCallbackWindowName接口，解决偶尔收不到回调的问题；

### 2015/11/23版本更新记录
####Android插件：
1. 版本号：uexCamera-3.0.13
   更新内容：修复新引擎不能用的问题2. 版本号：uexBaiduMap-3.1.27
   更新内容：修改插件，使其支持config配置APIKey；3. 版本号：uexChatKeyboard-3.0.11
   更新内容：去掉LocalActivityManager
***
### 2015/11/13版本更新记录
####Android引擎：
   版本号：android_Engine_3.2_151113_01      更新内容：去掉ActivityGroup，需要配套使用最新插件
####Android插件：
1. uexActionSheet-3.0.3 uexAreaPickerView-3.0.4 uexBaiduMap-3.1.26 uexChart-3.0.1 uexCoverFlow2-3.0.6 uexEditDialog-3.0.1 uexGaodeMap-3.0.10 uexImage-3.0.2 uexLoadingView-3.0.4 uexPDFReader-3.0.3 uexPie-3.0.5 uexPieChart-3.0.1 uexSearchBarView-3.0.1 uexSina-3.0.8 uexTent-3.0.10 uexTimeMachine-3.0.4 uexWheel-3.0.15 共17个插件 更新内容：引擎中去掉ActivityGroup。2. 插件名称及版本号：uexFileMgr-3.0.11    更新内容：    * 修改getFileRealPath指定回调名时，只回调一个参数（与ios统一）
 ***

### 2015/11/09版本更新记录
####Android引擎：
   版本号：android_Engine_3.1_151023_01	      更新内容：
   * Window支持侧滑关闭  * 优化openMultiPopover：优先加载默认页面索引的网页，待其加载完成后，再加载剩下的网页  * 支持锚点链接的跳转，支持ionic
 ***
### 2015/10/30版本更新记录
####Android插件：
1. 插件名称及版本号：uexImage-3.0.2       更新内容：    * 修复了图片压缩时质量出错问题
        * 修复选择图片时返回的json格式错误问题   2. 插件名称及版本号：uexDocumentReader-3.0.2       更新内容：修改打开不存在文件时崩溃的问题
***
### 2015/10/23版本更新记录
####Android引擎：            版本号：android_Engine_3.1_151023_01	      更新内容：
      * UserAgent增加Appcan字段；   * 代码漏洞修复    * Root窗口中的浮动窗口调用引擎的alert接口，无法弹出对话框；   * 浮动窗口中不能打开窗口；   * 下载附件名显示有误、下载附件乱码、图片下载后无法用图库打开查看；   * 只有右侧滑菜单时阴影显示不正确；   * 关闭子应用时应用崩溃；   * 修改多浮动窗口打开外网界面混乱问题；   * 修改无法通知侧滑页面事件问题；   * 三星S6显示空菜单键问题；   * 去掉判断Debug的逻辑(不去掉PDF插件无法使用)。 以上由pingping-jiang修改   * 修复部分机型出现弹出键盘又立刻消失的问题；   * 新增setIsSupportSlideCallback接口，设置网页是否支持滑动的相关监听方法。

####Android插件：

 1. 插件名称及版本号：uexBaiduNavi-3.0.2          更新内容：修复终点有偏差的问题    2. 插件名称及版本号：uexFileMgr-3.0.9       更新内容：修复闪退的问题   
     3. 插件名称及版本号：uexImage-3.0.1          更新内容：新增
***
### 2015/10/16版本更新记录
####Android引擎：            版本号：android_Engine_3.1_151016_01	      更新内容：修复Android 5.0启动页不显示的问题

####Android插件：
 1. 插件名称及版本号：uexGaodeMap-3.0.9       更新内容：解决高德地图打开时闪一下的问题
 2. 插件名称及版本号：uexQQ-3.0.6       更新内容：支持config.xml配置
 3. 插件名称及版本号：uexBaiduNavi-3.0.1       更新内容：修复仅有起点、终点经纬度坐标时路径规划失败问题。
 4. 插件名称及版本号：uexDocumentReader-3.0.1       更新内容：国际化
 5. 插件名称及版本号：uexEmail-3.0.1       更新内容：国际化
 6. 插件名称及版本号：uexFileMgr-3.0.8       更新内容：国际化
 
 7. 插件名称及版本号：uexLog-3.0.1       更新内容：国际化
 8. 插件名称及版本号：uexCalendarView-3.0.2       更新内容：国际化
 9. 插件名称及版本号：uexBaiduMap-3.1.25       更新内容：国际化
    
***

### 2015/10/10版本更新记录
####Android引擎：            版本号：android_Engine_3.1_151008_02
      更新内容：修复横屏情况下网页上滑下滑监听不生效的问题

####Android插件：
 1. 插件名称及版本号：uexDownloaderMgr-3.0.11       更新内容：修复调用cancelDownload之后，即使不清除已下载的临时文件，下次下载时不能断点续传的问题。
 2. 插件名称及版本号：uexBluetoothLE-3.0.1       更新内容：
    * 修改读写的字符串均为为Base64编码
    * 修改回调接口
 3. 插件名称及版本号：uexBaiduMap-3.1.24       更新内容：修改百度地图中引用的jar包，解除与百度导航插件之间的打包冲突问题
***
### 2015/9/25版本更新记录
####Android插件：
1. 插件名称及版本号：uexWheel-3.0.14       更新内容：修复四分之一圆盘在页面切换之后不能正常打开的问题
    
2. 插件名称及版本号：uexUnisound-3.0.0       更新内容：新增

3. 插件名称及版本号：uexJsonXmlTrans-3.0.0       更新内容：新增
***

### 2015/9/21版本更新记录
####Android插件：
 1. 插件名称及版本号：uexGaodeMap-3.0.6.zip       更新内容：open接口增加地图是否随网页滚动接口
***

### 2015/9/18版本更新记录
####Android引擎：            版本号：android_Engine_3.1_150918_01
      更新内容：修复应用引擎的uexwindow.prompt,弹出的提示框退出时，软键盘还在的问题

####Android插件：
 1. 插件名称及版本号：uexFileMgr-3.0.7       更新内容：修改接口getFileRealPath
 2. 插件名称及版本号：uexDownloaderMgr-3.0.10       更新内容：增加新的 header
 3. 插件名称及版本号：uexUploaderMgr-3.0.7       更新内容：增加新的 header
 4. 插件名称及版本号：uexXmlHttpMgr-3.0.20       更新内容：增加新的 header
 5. 插件名称及版本号：uexChatKeyboard-3.0.10       更新内容：open接口新增参数inputMode默认输入方式
 6. 插件名称及版本号：uexJPush-3.0.8       更新内容：修复通知不含extras时闪退的问题
 
 7. 插件名称及版本号：uexBaiduNavi-3.0.0       更新内容：新增    
***

### 2015/9/17版本更新记录
####Android引擎：            版本号：android_Engine_3.1_150917_01
      更新内容：修复：支持js调用返回值
***

### 2015/9/14版本更新记录

####Android插件：
 1. 插件名称及版本号：uexESurfingRtc-3.1.4       更新内容：升级RTC sdk

***
### 2015/9/11版本更新记录
####Android引擎：            版本号：android_Engine_3.1_150911_01
      更新内容：    
   * 修复startActivityForResult是通过三方应用调起时，收不到回调的问题
      * 修复load html内容带有中文时乱码的问题
   * 修复引擎video标签播放视频只有声音没有图像的问题   

####Android插件：
 1. 插件名称及版本号：uexJPush-3.0.7       更新内容：修复setTags和setAlias返回错误的问题
     2. 插件名称及版本号：uexEasemob-3.0.16
       更新内容：
    * 修复退出再登陆，聊天记录只有一条的问题
    * 去掉特殊字符
***  
### 2015/8/28版本更新记录

####Android插件：
 1. 插件名称及版本号：uexEasemob-3.0.14       更新内容：修复CMD消息json不能解析的问题
     2. 插件名称及版本号：uexGaodeMap-3.0.5      更新内容：
    * 新增自定义按钮相关接口
    * 地理编码和反地理编码回调接口增加参数
     3. 插件名称及版本号：uexBaiduMap-3.1.23      更新内容：修复地理编码接口当地址错误时程序崩溃的问题
    
 4. 插件名称及版本号：uexCall-3.0.3      更新内容：plugin文件中添加call接口，兼容老版本插件
 5. 插件名称及版本号：uexSMS-3.0.3      更新内容：plugin文件中添加send接口，兼容老版本插件    
***

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
