##Egret Android Support Based On Android Studio Release Notes 
---

### Egret Android Support 5.0.1 Release Notes
--
更新时间：2017年06月29日

miniSDKVersion:14

- **[修复]** 修复播放短音频可能会重复播放的问题。
- **[修复]** 修复进入后台可能会导致音频不能播放的问题。
- **[修复]** 修复drawToTexture可能渲染出错的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 4.1.0 Release Notes
--
更新时间：2017年05月23日

miniSDKVersion:14

- **[修复]** 修复播放声音引起卡顿和闪退的问题。
- **[修复]** 修复设置背景透明无效的问题。
- **[修复]** 修复开启优化后部分场景渲染出错的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 4.0.3 Release Notes
--
更新时间：2017年03月08日

miniSDKVersion:14

- **[修复]** 修复drawToTexture接口保存的图片在部分情况下渲染出错的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 4.0.2 Release Notes
--
更新时间：2017年02月21日

miniSDKVersion:14

- **[修复]** 修复在几个输入框之间频繁切换可能导致闪退的问题。
- **[修复]** 修复开启滤镜在部分机型上闪退的问题。
- **[修复]** 修复部分小体积的音频可能导致闪退的问题。
- **[修复]** 修复在部分分辨率下输入框表现不对的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 4.0.1 Release Notes
--
更新时间：2017年01月24日

miniSDKVersion:14

- **[新特性]** 提供图片选择器功能（使用方法请参考开发者中心的相关文档）。
- **[新特性]** 支持将ArrayBuffer或Base64转换为贴图（使用方法请参考开发者中心的相关文档）。
- **[修复]** 修复开启CmdBatch之后部分场景矢量图设置透明度无效的问题。
- **[修复]** 修复热更新相关的问题。
- **[修复]** 修复部分机型下滤镜shader不能编译的问题。
- **[修复]** 修复输入框在开始编辑前可能被键盘遮挡的问题。
- **[修复]** 修复4.0.0中出现的WebSocket不能连接非默认端口的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 4.0.0 Release Notes
--
更新时间：2017年01月09日

miniSDKVersion:14

- **[新特性]** 添加对wss的支持。
- **[修复]** 修改自定义热更新的模版，默认以旧版本的方式启动。
- **[修复]** 修复热更新失败后仍然会更新版本信息的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.6 Release Notes
--
更新时间：2016年12月27日

miniSDKVersion:14

- **[改进]** 增加自定义热更新的模版。
- **[改进]** https请求不再需要验证证书。
- **[修复]** 修复热更新失败后不能再次启动的问题。
- **[修复]** 修复启动本地zip游戏包不会出现GameLoadingView的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.5 Release Notes
--
更新时间：2016年12月13日

miniSDKVersion:14

- **[修复]** 修复3.2.4中出现的不进行热更新时不出现GameLoadingView的问题。
- **[修复]** 修复设置GLSurfaceView的层级之后，输入框被遮挡的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.4 Release Notes
--
更新时间：2016年11月29日

miniSDKVersion:14

- **[修复]** 修复设置音频起始播放时间有时无效的问题。
- **[修复]** 修复部分滤镜表现错误的问题。
- **[修复]** 重写热更新的逻辑，考虑网络断开等情况。
- **[修复]** 修复部分场景下设置单行输入无效的问题。
- **[新特性]** 添加绘制纹理的效率优化开关。
- **[新特性]** 新增Splash功能。应用启动瞬间会显示一张图片。使用方式见SplashActivity中的注释。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.3 Release Notes
--
更新时间：2016年11月15日

miniSDKVersion:14

- **[修复]** 修复设置音量无效的问题。
- **[修复]** 修复多次主动停止音频造成部分音频不能播放的问题。
- **[修复]** 修复游戏在部分模拟器上闪退的问题。
- **[修复]** 修复输入框获得焦点时光标不在文本最后的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.2 Release Notes
--
更新时间：2016年11月01日

miniSDKVersion:14

- **[修复]** 修复部分情况下渲染出错的问题。
- **[修复]** 修复带有提示文字的输入框第一次输入时颜色显示不对的问题。
- **[改进]** 增加渲染效率优化的开关(说明: http://developer.egret.com/cn/github/egret-docs/Engine2D/native/other/index.html )。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.1 Release Notes
--
更新时间：2016年10月18日

miniSDKVersion:14

- **[注意]** 注意：此版本添加了对渲染效率的优化，如果渲染时出现了异常请在引擎中关闭优化。
- **[改进]** 支持修改游戏所在的View的层级。
- **[修复]** 修复部分情况下渲染出错的问题。
- **[修复]** 修复部分机型中文字位置偏移的问题。
- **[修复]** 处理同时加载音频的数量过多的情况。
- **[修复]** 修复其它BUG

### Egret Android Support 3.2.0 Release Notes
--
更新时间：2016年09月27日

miniSDKVersion:14

- **[注意]** 注意：此版本添加了对渲染效率的优化，如果渲染时出现了异常请在引擎中关闭优化。
- **[新特性]** 支持渲染滤镜。
- **[新特性]** 支持渲染Mesh。
- **[改进]** 提高渲染效率。
- **[改进]** 提高稳定性。
- **[修复]** 修复部分机型中渲染默认字体时，文字位置向上偏移的问题。
- **[修复]** 修复第一次启动游戏一定会进行热更新的问题。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.8 Release Notes
--
更新时间：2016年09月02日

miniSDKVersion:14

- **[修复]** 修复输入框提示文字不会自动消失的问题。
- **[修复]** 修复播放声音引起的闪退问题。
- **[改进]** 提高稳定性。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.7 Release Notes
--
更新时间：2016年08月25日

miniSDKVersion:14

- **[修复]** 修复设置非法颜色值造成崩溃的问题。
- **[修复]** 修复播放声音导致游戏崩溃的问题。
- **[修复]** 修复不能在线加载音频的问题。
- **[修复]** 修复退出游戏后音频没有释放完全的问题。
- **[新特性]** 支持斜体文本。
- **[新特性]** 添加ColorTransform滤镜。
- **[改进]** 提高稳定性。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.6 Release Notes
--
更新时间：2016年08月08日

miniSDKVersion:14

- **[修复]** 修复输入框高度与行高不一致时，输入框位置错误的问题。
- **[修复]** 修复多个音效同时播放发生卡顿的问题。
- **[改进]** 提高稳定性。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.5 Release Notes
--
更新时间：2016年07月25日

miniSDKVersion:14

- **[新特性]** 最低支持 Android Level14 。
- **[改进]** 提高稳定性。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.4 Release Notes
--
更新时间：2016年07月12日

- **[新特性]** 获取原生设备的电池电量信息。
- **[改进]** 提高稳定性。
- **[修复]** 修复其它BUG

### Egret Android Support 3.1.3 Release Notes
--
更新时间：2016年06月27日

- **[改进]** 提高稳定性。
- **[修复]** EUI label中替换文字造成崩溃。
- **[修复]** 修复其它BUG
