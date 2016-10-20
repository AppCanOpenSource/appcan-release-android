# appcan-release-android

### 2016/10/20版本更新记录#### Android插件：1. 版本号：uexScanner-android-3.0.22	   更新内容：优化扫描速度，解决图像变形问题；新增recognizeFromImage方法
### 2016/10/13版本更新记录#### Android插件：1. 版本号：uexEasemob-android-3.0.28		   更新内容：修复ShowNotificationInBackgroud参数无效的问题   2. 版本号：uexImage-android-3.0.20		   更新内容：修复图片有时候加载不出来的问题

### 2016/9/22版本更新记录#### Android插件：1. 版本号：uexGaodeMap-android-3.0.14		   更新内容：解决与高德导航冲突的问题   2. 版本号：uexGaodeNavi-android-3.0.2		   更新内容：解决与高德地图冲突的问题

### 2016/9/20版本更新记录   #### Android插件：1. 版本号：uexMQTT-android-3.3.0		   更新内容：新增MQTT插件

### 2016/9/18版本更新记录   #### Android插件：1. 版本号：uexChatKeyboard-android-3.0.15		   更新内容：添加@好友相关接口

### 2016/9/14版本更新记录   #### Android插件：1. 版本号：uexEasemob-android-3.0.27		   更新内容：支持小米推送2. 版本号：uexMiPush-android-3.0.0   更新内容：新增小米推送插件

### 2016/9/13版本更新记录
   
#### Android插件：
1. 版本号：uexSecurityKeyboard-android-3.0.1		

   更新内容：新增isScrollWithWeb参数控制是否随网页滚动

2. 版本号：uexAliPay-android-3.0.9		

   更新内容：SDK升级

#### Android引擎：
 版本号：android_Engine_3.4_160913_01		

   更新内容：1.增加接口uexWindow.setPopoverVisibility；2.沉浸式通知栏

### 2016/9/9版本更新记录

#### Android插件：
1. 版本号：uexLocation-Android-3.0.11		

   更新内容：新增getAddressByType接口，支持指定类型的经纬度返回

### 2016/9/2版本更新记录

#### Android插件：
1. 版本号：uexUploaderMgr-android-3.0.11		

   更新内容：修复回调过快的问题

### 2016/8/19版本更新记录
####Android插件：
1. 版本号：uexImage-3.0.19		

   更新内容：图片预览时支持隐藏或显示标题和底部


####Android引擎：
 版本号：android_Engine_3.3_160815_01		

   更新内容：修复全局进度条打开页面被关闭的问题


### 2016/7/29版本更新记录
####Android插件：
1. 版本号：uexCamera-3.0.21		

   更新内容：* 修复了小内存手机压缩图片时发生OOM的问题 * 修复inSampleSize不生效的问题
2. 版本号：uexVideo-3.0.8		

   更新内容：添加播放完毕后的监听
3. 版本号：uexXunfei-3.0.1		

   更新内容：添加语音识别功能

4. 版本号：uexLocation-3.0.10		

   更新内容：升级逆地理编码

	
####Android引擎：
版本号：android_Engine_3.3_160729_01		
更新内容：解决高德与百度插件冲突的问题
***
### 2016/7/22版本更新记录
####Android插件：
1. 版本号：uexLocalNotification-3.0.10	

   更新内容：新增收到通知和点击通知相关的回调。
2. 版本号：uexMobSMS-3.0.1	

   更新内容：新增错误信息返回值
3. 版本号：uexPDFReader-3.0.5	

   更新内容：UI改善
	
####Android引擎：	
版本号：android_Engine_3.3_160720_01

更新内容：EBrowserActivity添加对onNewIntent生命周期的反射处理，插件可拦截该生命周期。

***

### 2016/07/18版本更新记录
####Android引擎：

版本号：android_Engine_3.3_160715_01_3.3.4

更新内容：crosswalk引擎
***

### 2016/07/09版本更新记录
####Android插件：
1. 版本号：uexImage-3.0.18

   更新内容：* 废弃了第三方aar							
2. 版本号：uexRongCloud-3.0.0

   更新内容：* 新增融云插件

3. 版本号：uexContact-3.0.6

   更新内容：* 更新UI，解决多选联系人慢的问题   
***

### 2016/07/01版本更新记录
####Android插件：
1. 版本号：uexQcloudAV-3.3.1	

   更新内容：* 新增播放错误状态返回值										
2. 版本号：uexQQ-3.0.8

   更新内容：* 更新qq SDK

3. 版本号：uexBaiduMap-3.2.38

   更新内容：* 解决搜索结果总数被覆盖的问题

***
      
### 2016/06/24版本更新记录
####Android引擎：

版本号：android_Engine_3.3_160620_01

更新内容：

* 修复不支持横竖屏切换的问题 
* config.xml支持配置全屏  
***
### 2016/06/12版本更新记录
####Android插件：
1. 版本号：uexAudio-3.0.9

   更新内容：* 主要修复了Android不同手机的听筒距离感应器最大值不同导致的部分手机听筒模式后无法还原正常模式播放的问题。										
2. 版本号：uexScanner-3.0.17

   更新内容：* 修复了当扫描线高度过小时，获取View的高度小于等于0造成的程序崩溃问题；添加是否显示从相册选择按钮配置开关
***
   
### 2016/06/04版本更新记录
####Android插件：
1. 版本号：uexNIM-3.0.1	

   更新内容：* 新增聊天室功能										
2. 版本号：uexSocketMgr-3.0.5	

   更新内容：* 添加创建连接时设置编码参数
***

### 2016/05/28版本更新记录
####Android插件：
1. 版本号：uexSina-3.0.13	
 
   更新内容：* 优化了registerApp回调不执行的问题										
2. 版本号：uexUploaderMgr-3.0.11

   更新内容：	* 优化上传进度不准确的问题。										
3. 版本号：uexImage-3.0.17	

   更新内容：* 优化了方形裁剪在部分手机上失效的问题

***
### 2016/05/20版本更新记录
####Android引擎：

版本号：android_Engine_3.3_160520_01	

更新内容：

* 新增uexWidget.closeLoading                                                                           
* 新增uexWindow.setLoadingImagePath
* 支持自定义错误页面
   
####Android插件：
1. 版本号：uexFileMgr-3.0.21	

   更新内容：
   * 优化部分成功失败的状态回调返回的回调数据类型错误的问题 
   * 优化图片以Base64写入后打开失败的问题
   
2. 版本号：uexImage-3.0.16	

   更新内容：当进行图片方形裁剪时，固定图片的尺寸

   
3. 版本号：uexUploaderMgr-3.0.10	

   更新内容：支持后台上传


4. 版本号：uexTabBarWithPopMenu-3.0.0

   更新内容：新增uexTabBarWithPopMenu 插件


5. 版本号：uexALiBaiChuan -3.0.0	

   更新内容：新增阿里百川插件


6. 版本号：uexQupai-3.0.0	

   更新内容：新增趣拍插件

7. 版本号：uexNBlistview-3.0.0	

   更新内容：新增uexNBlistview插件



***

### 2016/05/13版本更新记录
####Android插件：
1. 版本号：uexWeiXin-3.1.35	
 
   更新内容：* 优化SDK，优化代码逻辑完善调试所需要的信息；* 优化规范代码，删除无用代码，增加log和注释。*文档：增加错误返回码说明
2. 版本号：uexEasemob-3.0.24	 

   更新内容：优化创建群组时，Android 支持initialWelcomeMessage参数
3. 版本号：uexControl-3.0.8	

   更新内容：优化了在Android 5.0+机器上选择日期会crash的问题
4. 版本号：uexImage-3.0.15	

   更新内容：优化选择图片时quality为1时的处理逻辑，防止图片质量有细微差别。
5. 版本号：uexJPush-3.0.14	

   更新内容：*优化了缺少配置GET_TASKS权限导致的部分机型程序崩溃问题； *优化了数据库推送不自动清空的问题；* 更新JPush SDK到2.1.6  *优化了当应用程序正常退出后，依然可以收到推送(所有机型)
6. 版本号：uexCamera-3.0.20	

   更新内容：优化了open时选择不压缩导致的拍照不能保存的问题   

***
### 2016/05/05版本更新记录
####Android引擎：								
版本号：android_Engine_3.3_160429_01

更新内容：

新增： 

                                                            
* uexWindow.prompt添加hint参数                                      
* 新增uexWindow.openPresentWindow接口
* 新增uexWindow.publishChannelNotificationForJson接口  
* 新增uexWindow.disturbLongPressGesture接口                                            

优化：


* 优化快速滑动slider时，多浮动窗口会跟着滑动 
* 打开已订阅过的浮动窗口subscribe失败，publish不执行问题 
* 优化侧滑窗口会闪白色背景问题，增加4.0推送自定义通知布局文件 
* 支持url 打开APP情况下的参数获取 
* 支持远程调试  

####Android插件：
1. 版本号：uexCamera360-3.0.0	

   更新内容：新增uexCamera360插件							
2. 版本号：uexGaodeMap-3.0.13	

   更新内容：优化open接口没有回调的问题						
3. 版本号：uexImage-3.0.13	

   更新内容：优化图片选择器按照图片修改时间排序							
4. 版本号：uexLocation-3.0.8	

   更新内容：新增坐标系转换接口,支持wgs84,gcj02,bd09格式相互转换							
5. 版本号：uexPDFReader-3.0.4	

   更新内容：

   *由于一些特殊字体的pdf无法打开，基于mupdf重写uexPDFReader插件

   
   *兼容一些特殊字体的pdf

   
   *优化了方法数,使插件更轻量级;方法数从6837减至1016


   *用本地广播实现close方法


   *插件包动态加载dex，避免方法数过多问题"							
6. 版本号：uexSegmentControl-3.0.4	

   更新内容：修正无选中效果的问题,优化选中逻辑							
7. 版本号：uexSina-3.0.12	

   更新内容：修复图片路径读取的问题							
8. 版本号：uexWheelPickView-3.0.1	

   更新内容：

   * 新增默认值选项 

   * 点击"确定"按钮时，关闭选择器


9. 版本号：uexCamera-3.0.19	 

   更新内容：

   * cbOpenViewCamera回调方法,返回的JSON中增加字段label,替换之前的location
   * 优化了EUExCamera代码逻辑，优化了压缩图片算法，增加注释，规范代码							

   
10. 版本号：uexContact-3.0.4	

    更新内容：

    * 新增search,modifyWithId,deleteWithId接口以及cbSearch,cbModifyWithId,cbDeleteWithId回调. 

    * 优化查询逻辑							
11. 版本号：uexDevice-3.0.6	

    更新内容：Android6.0支持获取wifi mac地址							
12. 版本号：uexEasemob-3.0.23	

    更新内容：

    * 升级环信SDK至3.1.2  

    * 添加客服功能 

    * group新增黑名单					
13. 版本号：uexFileMgr-3.0.19	

    更新内容：

    * 添加base64支持 

    * 修正readFile接口的option参数可以为空

    * 修复多选文件时会导致显示选择数量不正确的问题 	

   ***
### 2016/04/23版本更新记录
####Android插件：
1. 版本号：uexFileMgr 3.0.16	

   更新内容：* 优化对文件的各种操作的opId支持非纯数字（与IOS保持一致）* 优化拒绝服务漏洞的问题  							
2. 版本号：uexContact-3.0.3 	

   更新内容：优化执行过慢影响UI线程的问题,修正当增删改查存在的部分回调错误问题							
3. 版本号：uexCamera-3.0.18	

   更新内容：优化了CameraView代码逻辑，优化了照片处理，优化了OOM问题处理，并做了为null判断，避免程序因空指针崩溃							
4. 版本号：uexImage-3.0.12	

   更新内容：更换图片加载中资源文件							
5. 版本号：uexWheelPickView-3.0.0	

   更新内容：新增uexWheelPickView插件

### 2016/04/15版本更新记录
####Android插件：
1. 版本号：uexListView-3.0.10

   更新内容：	删除universalimageloader源码		

2. 版本号：uexXunfei-3.0.0

   更新内容：新增uexXunfei插件	
***
### 2016/03/26版本更新记录
####Android插件：
1. 版本号： uexVideo-3.0.6

   更新内容：优化了视频录制的接口——
   * 支持控制录制时间;
   * 支持控制录制分辨率;
   * 支持控制录制视频质量;* 优化了视频播放接口——
   * 性能优化:采用全新的API去播放视频,优化了视频的加载速度,降低了CPU占用;
   * 界面优化: UI美化;支持各种常用手势去控制播放;网络视频拥有预加载条提示;
   * 支持小窗播放，支持小窗跟随网页滑动;
   * 对全屏播放的细节做了处理:现在全屏模式下播放器强制横屏，并且不会随手机设置而自动旋转;
   * 更多的可选参数去定制播放器界面;
   * 为播放状态和播放器被关闭增加了监听;	

2. 版本号：uexScrawl-3.0.0

   更新内容：新增涂鸦功能插件	

3. 版本号：uexGaodeNavi-3.0.0

   更新内容：新增高德导航插件


4. 版本号：uexQcloudAV-3.0.0	

   更新内容：新增腾讯云视频直播插件

   
5. 版本号：uexNIM-3.0.0

   更新内容：新增网易云信插件

   
6. 版本号：uexBackground-3.3.0

   更新内容：新增实现后台运行JS的功能（对应uexlocation插件更新了，配合测试
   
7. 版本号：uexLocation-3.0.7

   更新内容：新功能，优化定位权限,支持后台定位


   
***

### 2016/03/16版本更新记录
####Android插件：
1. 版本号： uexLoadingView-3.0.6 

   更新内容：* 优化空指针报错问题

2. 版本号：uexScanner-3.0.15

   更新内容：新增charset字段设置编码

3. 版本号：uexImage-3.0.11

   更新内容：
    * 优化所有手机剪裁图片的方案（针对华为、部分三星）。优化在打开图片浏览器显示图片列表，最新图片在最上方（倒序）          

    * 针对保存图片到相册接口，修复开启增量更新时的res协议路径的bug


4. 版本号：uexPopoverMenu-3.0.0

   更新内容：新增弹出窗插件

   
5. 版本号：uexCamera-3.0.17

   更新内容：

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

***
### 2016/03/12版本更新记录

####Android引擎：
  1. 版本号：android_Engine_3.3_160310_01

  
  	 更新内容：

  	 * uexWindow添加获取window宽高的方法    
     * 分享支持res://协议   
     * 修复uexWindow.setWindowFrame调用之后第二次进页面异常的问题

     
####Android插件：
1. 版本号：uexPopoverMenu-3.0.0
 
   更新内容：弹出窗

2. 版本号：uexLoadingView-3.0.6 


   更新内容：解决空指针报错问题

3. 版本号：uexCamera-3.0.17

   更新内容：
   * 修复了在三星手机上照片旋转方向不一致的问题;修复了多次点击照相按钮，再点重拍照相按钮失效的问题
   * 修复Activity拒绝服务漏洞的问题，修复了openViewCamera拒绝使用系统拍照权限后程序崩溃的问题
  
4. 版本号：uexControl-3.0.7

   更新内容：修复日期不在范围内时，点击“确定”按钮能获取日期的问题

5. 版本号：uexVideo-3.0.5


   更新内容：新加了createPlay接口 和 removePlay

6. 版本号：uexEasemob-3.0.20

   更新内容：修复setNotifyBySoundAndVibrate无效的问题

7. 版本号：uexSlidePager-3.0.16

   更新内容：openSlidePager接口添加option参数

8. 版本号：uexInputTextFieldView-3.2.12

   更新内容：修改兼容性问题,添加新的接口和回调,调整优化代码逻辑,解决键盘遮蔽问题

9. 版本号：uexZip-3.0.2

   更新内容：修复plugin.xml

10. 版本号：uexImage-3.0.11

    更新内容：

    * 优化所有手机剪裁图片的方案（针对华为、部分三星）
    * 优化在打开图片浏览器显示图片列表，最新图片在最上方（倒序）

   
***

### 2016/03/08版本更新记录
####Android插件：
1. 版本号： uexAudio-3.0.7

   更新内容：* 优化了录音时用户禁止其权限的问题

2. 版本号：uexImage-3.0.10

   更新内容：* 优化针对保存图片到相册接口开启增量更新时的res协议路径

3. 版本号：uexListView-3.0.9

   更新内容：* 优化plugin.xml


4. 版本号：uexPie-3.0.6

   更新内容：* 优化plugin.xml

   
5. 版本号：uexFileMgr-3.0.13

   更新内容：* 新增复制文件的方法
***

### 2016/03/02版本更新记录
####Android插件：
1. 版本号： uexSecurityKeyboard-3.0.0

   更新内容：* 新增uexSecurityKeyboard安全键盘输入框插件

2. 版本号：uexDownloaderMgr-3.0.14

   更新内容：* 优化下载过程中下载进度过快导致应用异常的问题

***
### 2016/02/24版本更新记录
####Android插件：
1. 版本号：uexDevice-3.0.4

   更新内容：* 优化多次截屏失效的问题

   ***
### 2016/02/22版本更新记录
####Android插件：
1. 版本号：uexJPush-3.0.9

   更新内容：* 优化setTags返回格式不正确的问题

2. 版本号：uexScanner-3.0.14

   更新内容：* 优化扫描框为正方形

3. 版本号：uexDevice-3.0.3

   更新内容：* 新增判断功能是否开启,以及打开设置界面接口



 ***

### 2016/01/26版本更新记录
####Android引擎：
   版本号：android_Engine_3.2_160120_01
   
   更新内容：

   ＊新增支持网页内定位
   ＊优化JS注入漏洞 
   ＊新增容器接口 
   
####Android插件：
1. 版本号：uexSina-3.0.11

   更新内容：* 优化分享图片不能读取wgts://格式的文件问题

***
### 2016/01/16版本更新记录
####Android插件：
1. 版本号：uexControl-3.0.6

   更新内容：* 解决华为手机上输入日期不生效的问题;新增openDatePickerWithConfig可配置日期范围的日期选择器接口。     

### 2016/01/11版本更新记录
####Android插件：
1. 版本号：uexUploaderMgr-3.0.8

     更新内容：*  优化plugin文件uexFileMgr的plugin方法被覆盖的问题

2. 版本号：uexContact-3.0.1

     更新内容：* 新增searchItem接口增加返回信息条数配置;addItem接口增加是否弹出提

3. 版本号：uexDevice-3.0.2

     更新内容：* 新增截图，听筒和扩音器切换， 设置/获取音量等接口示框配置



 ***

### 2016/01/07版本更新记录
####Android插件：
1. 版本号：uexBluetoothLE-3.0.3

   更新内容：*  优化回调数据不正确的问题

 ***


### 2015/12/31版本更新记录
####Android插件：
1. 版本号：uexDownloaderMgr-3.0.13

     更新内容：优化有些url被encode不能下载的问题

2. 版本号：uexVideo-3.0.4

     更新内容：优化删除无用资源，修复Gradle编译不过的问题
 ***

### 2015/12/26版本更新记录
####Android插件：
1. 版本号：uexWeiXin-3.1.33

     更新内容：优化和完善抛出异常的捕获

2. 版本号：uexScanner-3.0.13

     更新内容：优化拍照权限被禁止情况处理

3. 版本号：uexChart-3.0.2

     更新内容： 新增barChart和lineChart  option参数  

4. 版本号：uexGaodeMap-3.0.12

     更新内容：优化闪退的问题
 ***

### 2015/12/19版本更新记录
####Android插件：
1. 版本号：uexCoverFlow2-3.0.7

   更新内容：优化open接口添加跟随webview滚动参数

2. 版本号：uexScrollPicture-3.0.2

   更新内容：优化闪退的问题

3. 版本号：uexGestureUnlock-3.0.0

   更新内容：新增 

4. 版本号：uexUmeng-3.0.0

   更新内容：新增 

5. 版本号：uexUnionPay-3.0.0

   更新内容：新增 

6. 版本号：uexLocalNotification-3.0.8

   更新内容：优化部分机型通知没有提示音的问题

7. 版本号：uexEasemob-3.0.19

   更新内容：优化cbGetMessageHistory与文档不一致的问题

8. 版本号：uexSina-3.0.10

   更新内容：优化cbRegisterApp回调openId和token

9. 版本号：uexGaodeMap-3.0.11

   更新内容：优化闪退的问题

 ***

### 2015/12/09版本更新记录
####Android插件：
1. 版本号：uexAudio-3.0.6

	更新内容：
	* 新增听筒模式接口,修复小米手机音量设置无效的问题
	
	* 优化uexAudio.record方法不支持录音文件存储为.mp3格式的问题
   
2. 版本号：uexTimeMachine-3.0.5

   更新内容：优化id覆盖关闭不掉的情况，修复传入小数错误的问题

 ***
### 2015/12/04版本更新记录
####Android插件：
 1. 版本号：uexLocalNotification-3.0.7

    更新内容：优化部分机型闪退的问题


 2. 版本号：uexBaiduMap-3.2.28

    更新内容：优化open接口传入的中心点不生效的问题


 3. 版本号：uexEasemob-3.0.17

    更新内容：优化initEasemob配置key，无需自定义插件

 4. 版本号：uexBluetoothLE-3.0.2

    更新内容：优化init自动开启蓝牙；cbConnect没有回调的问题

 5. 版本号：uexInputTextFieldView-3.2.11

    更新内容：优化关闭输入框时,键盘未自动收起的问题
***

### 2015/12/03版本更新记录
####Android引擎：
 版本号：android_Engine_3.2_151203_01

 更新内容：

 
 * 新增浮动窗口动画

 * 新增引擎关闭全部硬件加速方法 
***
### 2015/11/30版本更新记录
####Android插件：
 1. 版本号：uexTent-3.0.11

    更新内容：优化取消授权时程序崩溃的问题


 2. 版本号：uexCalendarView-3.0.3

    更新内容：优化month拼写错误的问题


 3. 版本号：uexSina-3.0.9

    更新内容：优化SinaSDK，重写授权登陆相关接口；新增login、logout、getUserInfo接口；

 4. 版本号：uexWeiXin-3.1.32

    更新内容：新增setCallbackWindowName接口，解决偶尔收不到回调的问题；

### 2015/11/23版本更新记录
####Android插件：
1. 版本号：uexCamera-3.0.13

   更新内容：修复新引擎不能用的问题

2. 版本号：uexBaiduMap-3.1.27


   更新内容：修改插件，使其支持config配置APIKey；

3. 版本号：uexChatKeyboard-3.0.11


   更新内容：去掉LocalActivityManager

***
### 2015/11/13版本更新记录
####Android引擎：
   版本号：android_Engine_3.2_151113_01
   
   更新内容：去掉ActivityGroup，需要配套使用最新插件

####Android插件：

1. uexActionSheet-3.0.3 uexAreaPickerView-3.0.4 uexBaiduMap-3.1.26 uexChart-3.0.1 uexCoverFlow2-3.0.6 uexEditDialog-3.0.1 uexGaodeMap-3.0.10 uexImage-3.0.2 uexLoadingView-3.0.4 uexPDFReader-3.0.3 uexPie-3.0.5 uexPieChart-3.0.1 uexSearchBarView-3.0.1 uexSina-3.0.8 uexTent-3.0.10 uexTimeMachine-3.0.4 uexWheel-3.0.15 
共17个插件
 更新内容：引擎中去掉ActivityGroup。


2. 插件名称及版本号：uexFileMgr-3.0.11
    更新内容：
    * 修改getFileRealPath指定回调名时，只回调一个参数（与ios统一）

 ***

### 2015/11/09版本更新记录
####Android引擎：
   版本号：android_Engine_3.1_151023_01	
   
   更新内容：

   * Window支持侧滑关闭 
 * 优化openMultiPopover：优先加载默认页面索引的网页，待其加载完成后，再加载剩下的网页 
 * 支持锚点链接的跳转，支持ionic

 ***
### 2015/10/30版本更新记录
####Android插件：
1. 插件名称及版本号：uexImage-3.0.2
   
    更新内容：
    * 修复了图片压缩时质量出错问题

    
    * 修复选择图片时返回的json格式错误问题  

 2. 插件名称及版本号：uexDocumentReader-3.0.2
   
    更新内容：修改打开不存在文件时崩溃的问题
***
### 2015/10/23版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_151023_01	
   
   更新内容：

   
   * UserAgent增加Appcan字段；
   * 代码漏洞修复 
   * Root窗口中的浮动窗口调用引擎的alert接口，无法弹出对话框；
   * 浮动窗口中不能打开窗口；
   * 下载附件名显示有误、下载附件乱码、图片下载后无法用图库打开查看；
   * 只有右侧滑菜单时阴影显示不正确；
   * 关闭子应用时应用崩溃；
   * 修改多浮动窗口打开外网界面混乱问题；
   * 修改无法通知侧滑页面事件问题；
   * 三星S6显示空菜单键问题；
   * 去掉判断Debug的逻辑(不去掉PDF插件无法使用)。 以上由pingping-jiang修改
   * 修复部分机型出现弹出键盘又立刻消失的问题；
   * 新增setIsSupportSlideCallback接口，设置网页是否支持滑动的相关监听方法。

####Android插件：

 1. 插件名称及版本号：uexBaiduNavi-3.0.2   
   
    更新内容：修复终点有偏差的问题   

 2. 插件名称及版本号：uexFileMgr-3.0.9
   
    更新内容：修复闪退的问题   

    
 3. 插件名称及版本号：uexImage-3.0.1   
   
    更新内容：新增
***
### 2015/10/16版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_151016_01	
   
   更新内容：修复Android 5.0启动页不显示的问题

####Android插件：

 1. 插件名称及版本号：uexGaodeMap-3.0.9
   
    更新内容：解决高德地图打开时闪一下的问题

 2. 插件名称及版本号：uexQQ-3.0.6
   
    更新内容：支持config.xml配置

 3. 插件名称及版本号：uexBaiduNavi-3.0.1
   
    更新内容：修复仅有起点、终点经纬度坐标时路径规划失败问题。

 4. 插件名称及版本号：uexDocumentReader-3.0.1
   
    更新内容：国际化

 5. 插件名称及版本号：uexEmail-3.0.1
   
    更新内容：国际化

 6. 插件名称及版本号：uexFileMgr-3.0.8
   
    更新内容：国际化
 
 7. 插件名称及版本号：uexLog-3.0.1
   
    更新内容：国际化

 8. 插件名称及版本号：uexCalendarView-3.0.2
   
    更新内容：国际化

 9. 插件名称及版本号：uexBaiduMap-3.1.25
   
    更新内容：国际化

    
***

### 2015/10/10版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_151008_02

   
   更新内容：修复横屏情况下网页上滑下滑监听不生效的问题

####Android插件：

 1. 插件名称及版本号：uexDownloaderMgr-3.0.11
   
    更新内容：修复调用cancelDownload之后，即使不清除已下载的临时文件，下次下载时不能断点续传的问题。

 2. 插件名称及版本号：uexBluetoothLE-3.0.1
   
    更新内容：

    * 修改读写的字符串均为为Base64编码

    * 修改回调接口

 3. 插件名称及版本号：uexBaiduMap-3.1.24
   
    更新内容：修改百度地图中引用的jar包，解除与百度导航插件之间的打包冲突问题
***
### 2015/9/25版本更新记录
####Android插件：
1. 插件名称及版本号：uexWheel-3.0.14
   
    更新内容：修复四分之一圆盘在页面切换之后不能正常打开的问题

    
2. 插件名称及版本号：uexUnisound-3.0.0
   
    更新内容：新增

3. 插件名称及版本号：uexJsonXmlTrans-3.0.0
   
    更新内容：新增

***

### 2015/9/21版本更新记录
####Android插件：

 1. 插件名称及版本号：uexGaodeMap-3.0.6.zip
   
    更新内容：open接口增加地图是否随网页滚动接口
***

### 2015/9/18版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_150918_01

   
   更新内容：修复应用引擎的uexwindow.prompt,弹出的提示框退出时，软键盘还在的问题

####Android插件：

 1. 插件名称及版本号：uexFileMgr-3.0.7
   
    更新内容：修改接口getFileRealPath

 2. 插件名称及版本号：uexDownloaderMgr-3.0.10
   
    更新内容：增加新的 header

 3. 插件名称及版本号：uexUploaderMgr-3.0.7
   
    更新内容：增加新的 header

 4. 插件名称及版本号：uexXmlHttpMgr-3.0.20
   
    更新内容：增加新的 header

 5. 插件名称及版本号：uexChatKeyboard-3.0.10
   
    更新内容：open接口新增参数inputMode默认输入方式

 6. 插件名称及版本号：uexJPush-3.0.8
   
    更新内容：修复通知不含extras时闪退的问题
 
 7. 插件名称及版本号：uexBaiduNavi-3.0.0
   
    更新内容：新增
    
***

### 2015/9/17版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_150917_01

   
   更新内容：修复：支持js调用返回值

***

### 2015/9/14版本更新记录

####Android插件：

 1. 插件名称及版本号：uexESurfingRtc-3.1.4
   
    更新内容：升级RTC sdk

***
### 2015/9/11版本更新记录
####Android引擎：
         
   版本号：android_Engine_3.1_150911_01

   
   更新内容：    

   * 修复startActivityForResult是通过三方应用调起时，收不到回调的问题
   
   * 修复load html内容带有中文时乱码的问题

   * 修复引擎video标签播放视频只有声音没有图像的问题
   

####Android插件：

 1. 插件名称及版本号：uexJPush-3.0.7
   
    更新内容：修复setTags和setAlias返回错误的问题

    
 2. 插件名称及版本号：uexEasemob-3.0.16

   
    更新内容：

    * 修复退出再登陆，聊天记录只有一条的问题

    * 去掉特殊字符

***  
### 2015/8/28版本更新记录

####Android插件：

 1. 插件名称及版本号：uexEasemob-3.0.14
   
    更新内容：修复CMD消息json不能解析的问题

    
 2. 插件名称及版本号：uexGaodeMap-3.0.5
  
    更新内容：

    * 新增自定义按钮相关接口

    * 地理编码和反地理编码回调接口增加参数

    
 3. 插件名称及版本号：uexBaiduMap-3.1.23
  
    更新内容：修复地理编码接口当地址错误时程序崩溃的问题

    
 4. 插件名称及版本号：uexCall-3.0.3
  
    更新内容：plugin文件中添加call接口，兼容老版本插件

 5. 插件名称及版本号：uexSMS-3.0.3
  
    更新内容：plugin文件中添加send接口，兼容老版本插件

    
***

### 2015/8/21版本更新记录

####Android插件：

 1. 插件名称及版本号：uexEasemob-3.0.13
   
    更新内容：

    * 支持声音和震动

    
	* 发送附件支持wgt,wgts协议
    
	* 修复重新登陆后消息记录remoteUrl为空的问题

 2. 插件名称及版本号：uexJPush-3.0.6
  
    更新内容：解决自定义消息附带extras时，json格式错误的问题

 3. 插件名称及版本号：uexInputTextFieldView-3.0.8
  
    更新内容：修改EditText和webview中的输入框抢焦点的问题

***

### 2015/8/14版本更新记录

####Android插件：

 1. 插件名称及版本号：uexJPush-3.0.5
  
    更新内容：解决获取通知附带extras时，json格式错误的问题

 2. 插件名称及版本号：uexSearchBarView-3.0.0
  
    更新内容：新增

***
### 2015/7/31版本更新记录

####Android插件：

 1. 插件名称及版本号：uexAudio-3.0.5
  
    更新内容：修复uexAudio.record方法不支持录音文件存储为.mp3格式的问题

 2. 插件名称及版本号：uexFileMgr-3.0.5
  
    更新内容：新增cbWriteFile回调方法

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
####Android引擎：
         
   版本号：android_Engine_3.1_150724_01

   
   更新内容：修复多个appcan.window.alert()同时执行时，只会弹出一次的问题

####Android插件：

 1. 插件名称及版本号：uexAliPay-3.0.8
  
    更新内容：更新支付宝SDK，解决当用户手机没有安装支付宝快捷支付服务时，会出现解析包错误的问题

 2. 插件名称及版本号：uexGaodeMap-3.0.3
  
    更新内容：新增离线地图相关方法，优化添加标注接口使其支持自定义气泡

 ***

### 2015/7/17版本更新记录

####Android插件：

 1. 插件名称及版本号：uexEasemob-3.0.9
  
    更新内容：支持离线消息

 2. 插件名称及版本号：uexIndexBar-3.0.2
  
    更新内容：
    * 索引表可以设置是否随网页滑动
    * 修改多次open之后不能成功close的问题

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
	* 修复onReceiveNotificationOpen,调整初始化时机
    * 修复4.4以下版本点击通知闪退的问题

4.	插件名称及版本号：uexAreaPickerView-3.0.3  
	
	更新内容：返回数据添加空格便于分割


	

***

### 2015/7/3版本更新记录

####Android引擎：
         
   版本号：android_Engine_3.1_150703_01

   
   更新内容：

 1. 新增isAppInstalled，cbIsAppInstalled判断是否安装某第三方应用方法及其回调方法
 2. 新增cbStartApp启动第三方应用的回调方法。

 	
          
####Android插件：

 1. 插件名称及版本号：uexImageBrowser-3.0.21
 
    更新内容：修复多选图片接口在手机上没有图片时崩溃的问题

 2. 插件名称及版本号：uexLocalNotification-3.0.6
 
    更新内容：修复应用在后台被杀后无法通知的问题

 3. 插件名称及版本号：uexGaodeMap-3.0.2
 
    更新内容：新增removeMarkersOverlays、removeOverlays、setScaleVisible、setMyLocationButtonVisible、setZoomVisible接口。
 4. 插件名称及版本号：uexEasemob-3.0.8
 
    更新内容：getGroup添加groupName,groupDescription字段

 5. 插件名称及版本号：uexChatKeyboard-3.0.6
 
    更新内容：修复点击表情，再点击空白区域，再点击输入框时撑满屏幕的问题

 6. 插件名称及版本号：uexChart-3.0.1
 
    更新内容：替换ActivityGroup
***
### 2015/6/25版本更新记录

####Android引擎：
         
   版本号：android_Engine_3.1_150624_01

   更新内容：

   1. 修复弹出两次增量更新提示问题

   2. 修复低版本手机开启增量更新开关崩溃问题

   3. 修复外置sd卡路径图片无法显示的问题

 	
          
####Android插件：

 1. 插件名称及版本号：uexBaiduMap-3.1.20
 
    更新内容：

    * 修复点击路径规划中的起终点标注时，应用崩溃的问题

    * 去除多余的权限

 2. 插件名称及版本号：uexCall-3.0.2
 
    更新内容：兼容老版本插件

 3. 插件名称及版本号：uexSMS-3.0.2
 
    更新内容：兼容老版本插件

 4. 插件名称及版本号：uexAreaPickerView-3.0.2
 
    更新内容：新增

 5. 插件名称及版本号：uexCalendarView-3.0.1
 
    更新内容：新增

 6. 插件名称及版本号：uexChatKeyboard-3.0.5
 
    更新内容：新增

 7. 插件名称及版本号：uexCityListView-3.0.0
 
    更新内容：新增

 8. 插件名称及版本号：uexInputTextFieldView-3.0.6
 
    更新内容：新增

 9. 插件名称及版本号：uexLoadingView-3.0.3
 
    更新内容：新增

 10. 插件名称及版本号：uexFileMgr-3.0.4
 
    更新内容：添加renameFile接口

 11. 插件名称及版本号：uexIndexBar-3.0.1
 
    更新内容：clean时不删除view

 12. 插件名称及版本号：uexEasemob-3.0.7

  
    更新内容：getChatterInfo返回新加好友的聊天记录    
    
    
***

### 2015/6/19版本更新记录

####Android引擎：
         
   版本号：android_Engine_3.1_150616_01  

   更新内容：解决第三方应用调用appcan应用时参数丢失的问题。

 	
          
####Android插件：

 1. 插件名称及版本号：uexWeiXin-3.1.30
 
    更新内容：修复微信支付返回时偶尔没有回调的问题。

 2. 插件名称及版本号：uexEasemob-3.0.6
  
    更新内容： 

    * 添加getTotalUnreadMsgCount接口

    * 获取全部公开群改成分页获取

    
    
***
### 2015/6/12版本更新记录

####Android引擎：
         
   版本号：android_Engine_3.1_150612_02     

   更新内容：

1. 修复低版本安卓机找不到isHardwareAccelerated 的问题
2. 支持网页&lt;input type="file”&gt;
3. toggleSlidingWindow添加reload参数

 	
          
####Android插件：

 1. 插件名称及版本号：uexBaiduMap 3.1.19

 
    更新内容： 解决百度地图上箭头不转动的问题

    
 2. 插件名称及版本号： uexEasemob 3.0.5

 
    更新内容：升级环信SDK

 3. 插件名称及版本号： uexCall 3.0.1

    
    更新内容：  去掉直接拨打电话的接口及权限
 
 4. 插件名称及版本号：uexSMS 3.0.1

    
    更新内容： 去掉直接发送短信功能及权限

 5. 插件名称及版本号： uexJPush 3.0.1

    
    更新内容：  修复退出应用时收到推送闪退的问题

 6. 插件名称及版本号：uexScanner-3.0.11

    
    更新内容：  增加扫描本地图片功能。
        
 7. 插件名称及版本号：新增uexChart几何图表插件

***
### 2015/6/5版本更新记录
####Android插件：

1.	插件名称及版本号：uexWeiXin-3.1.29
	
	更新内容：uexWeiXin插件，支付sdk升级。
	

	

***
	
### 2015/5/29版本更新记录
   
####Android插件：

 1. 插件名称及版本号：uexScrollPicture-3.0.1

 	更新内容：新增插件

 2. 插件名称及版本号：uexEasemob-3.0.3

 	更新内容：新增发送视频，发送回执接口

 3. 插件名称及版本号：uexJPush-3.0.0

 	更新内容：新增插件

*** 	

### 2015/5/20版本更新记录

####Android引擎：
         
   版本号：android_Engine_3.1_150522_01       

   更新内容：

1. 修复Android 4.4版本关闭子应用后键盘并没有关闭问题；
2. 新增onPopoverLoadFinishInRootWnd(name,url)监听方法；
3. 添加webview嵌view方法（非API接口，供自定义插件调用）；
4. 修复部分网页加密后显示网页源码的问题。
 	
          
####Android插件：

 1. 插件名称及版本号：uexAliPay-3.0.7

 	更新内容：支付宝插件升级

 2. 插件名称及版本号：uexXmlHttpMgr-3.0.15

 	更新内容：onData回调函数参数修改

 3. 插件名称及版本号：uexDownloaderMgr-3.0.7

 	更新内容：修复不支持HTTPS问题

 4. 插件名称及版本号：uexUploaderMgr-3.0.4

 	更新内容：修复不支持HTTPS问题

 5. 插件名称及版本号：uexImageBrowser-3.0.19

 	更新内容：修复加密情况下，网页读取img标签的src路径图片打不开的问题

 6. 插件名称及版本号：uexGaodeMap-3.0.1

 	更新内容：新增高德地图插件

 7. 插件名称及版本号：uexScanner-3.0.10

 	更新内容：二维码扫描优化
