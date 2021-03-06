# JavaScript


|API|Prefix|Description|
|-|-|-|
|`APP-PLUS`|platform-app,platform-app-plus,app,app-plus|APP 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`APP-NVUE`|platform-app-nvue,platform-app-plus-nvue,app-nvue,app-plus-nvue|APP-NVUE 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`H5`|platform-h5,h5|H5 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-WEIXIN`|platform-mp-weixin,platform-weixin,platform-mp-wechat,platform-wechat,mp-weixin,weixin,mp-wechat,wechat|微信小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-ALIPAY`|platform-mp-alipay,platform-alipay,platform-mp-ali,platform-ali,mp-alipay,alipay,mp-ali,ali|支付宝小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-BAIDU`|platform-mp-baidu,platform-baidu,mp-baidu,baidu|百度小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-TOUTIAO`|platform-mp-toutiao,platform-toutiao,platform-mp-bytedance,platform-bytedance,mp-toutiao,toutiao,mp-bytedance,bytedance|字节跳动小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-QQ`|platform-mp-qq,platform-qq,mp-qq,qq|QQ 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-360`|platform-mp-360,platform-360,mp-360,360|360 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP`|platform-mp,mp|小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW`|platform-quickapp,platform-quickapp-webview,quickapp,quickapp-webview|快应用通用对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-UNION`|platform-quickapp-union,platform-quickapp-webview-union,quickapp-union,quickapp-webview-union|快应用联盟对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-HUAWEI`|platform-quickapp-huawei,platform-quickapp-webview-huawei,quickapp-huawei,quickapp-webview-huawei|快应用华为对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`/* #ifdef $1 */,$2,/* #endif */`|#ifdef,ifdef|条件编译，处理某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`/* #ifndef $1 */,$2,/* #endif */`|#ifndef,ifndef|条件编译，排除某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`<!-- #endif -->`|#endif,endif|结束条件编译。更多信息查看 https://uniapp.dcloud.io/platform。|
|`process.env.NODE_ENV === 'development'`|process.env.NODE_ENV === 'development'|判断是否为生产环境。更多信息查看 https://cli.vuejs.org/zh/guide/mode-and-env.html。|
|`process.env.NODE_ENV !== 'development'`|process.env.NODE_ENV !== 'development'|判断是否不为生产环境。更多信息查看 https://cli.vuejs.org/zh/guide/mode-and-env.html。|
|`process.env.NODE_ENV === 'production'`|process.env.NODE_ENV === 'production'|判断是否为生产环境。更多信息查看 https://cli.vuejs.org/zh/guide/mode-and-env.html。|
|`process.env.NODE_ENV !== 'production'`|process.env.NODE_ENV !== 'production'|判断是否不为生产环境。更多信息查看 https://cli.vuejs.org/zh/guide/mode-and-env.html。|
|`console.log("${1:object}", ${1:object})$0`|clg,clog,console.log|打印 log 日志。更多信息查看 https://uniapp.dcloud.io/api/log?id=log。|
|`console.info("${1:object}", ${1:object})$0`|cin,console.info|打印 info 日志。更多信息查看 https://uniapp.dcloud.io/api/log?id=info。|
|`console.warn("${1:object}", ${1:object})$0`|cwa,console.warn|打印 warn 日志。更多信息查看 https://uniapp.dcloud.io/api/log?id=warn。|
|`console.error("${1:object}", ${1:object})$0`|cer,console.error|打印 error 日志。更多信息查看 https://uniapp.dcloud.io/api/log?id=error。|
|`setTimeout(() => {$1}, ${2:1000})$0`|sto,setTimeout|设置一次性定时器。更多信息查看 https://uniapp.dcloud.io/api/timer?id=settimeout。|
|`clearTimeout($1)$0`|csto,clearTimeout|清理一次性定时器。更多信息查看 https://uniapp.dcloud.io/api/timer?id=cleartimeout。|
|`setInterval(() => {$1}, ${2:1000})$0`|sti,setInterval|设置周期性定时器。更多信息查看 https://uniapp.dcloud.io/api/timer?id=setinterval。|
|`clearInterval($1)$0`|csti,clearInterval|清理周期性定时器。更多信息查看 https://uniapp.dcloud.io/api/timer?id=clearinterval。|
|`uni.base64ToArrayBuffer(${1:base64})$0`|uni.base64ToArrayBuffer|将 base64 字符串转成 ArrayBuffer。更多信息查看 https://uniapp.dcloud.io/api/base64ToArrayBuffer。|
|`uni.arrayBufferToBase64(${1:arrayBuffer})$0`|uni.arrayBufferToBase64|将 ArrayBuffer 字符串转成 base64。更多信息查看 https://uniapp.dcloud.io/api/arrayBufferToBase64。|
|`onLaunch() {$1}$0`|onLaunch|应用生命周期，只能在 App.vue 中监听。uni-app 初始化完成时触发，全局只触发一次。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e5%ba%94%e7%94%a8%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onShow() {$1}$0`|onShow|应用生命周期，只能在 App.vue 中监听。uni-app 启动时或从后台进入前台时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e5%ba%94%e7%94%a8%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onHide() {$1}$0`|onHide|应用生命周期，只能在 App.vue 中监听。uni-app 从前台进入后台时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e5%ba%94%e7%94%a8%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onError() {$1}$0`|onError|应用生命周期，只能在 App.vue 中监听。uni-app 报错时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e5%ba%94%e7%94%a8%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onThemeChange() {$1}$0`|onThemeChange|应用生命周期，只能在 App.vue 中监听。系统主题变化时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e5%ba%94%e7%94%a8%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onLoad(options) {$1}$0`|onLoad|页面生命周期。页面加载时触发，参数是上个页面传递的数据，类型是 object。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onShow() {$1}$0`|onShow|页面生命周期。页面在屏幕上显示时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onReady() {$1}$0`|onReady|页面生命周期。页面初次渲染完成时触发，如果渲染速度快，会在页面进入动画完成前触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onHide() {$1}$0`|onHide|页面生命周期。页面在屏幕上隐藏时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onUnload() {$1}$0`|onUnload|页面生命周期。页面卸载时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onResize() {$1}$0`|onResize|页面生命周期。窗口尺寸变化时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onPullDownRefresh() {$1}$0`|onPullDownRefresh|页面生命周期。用户下拉时触发，一般用于下拉刷新。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onReachBottom() {$1}$0`|onReachBottom|页面生命周期。页面滚动到底部时触发，一般用于触底加载数据。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onTabItemTap({ index, pagePath, text }) {$1}$0`|onTabItemTap|页面生命周期。点击 Tab 时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onShareAppMessage() {$1}$0`|onShareAppMessage|页面生命周期。点击右上角分享时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onPageScroll({ scrollTop }) {$1}$0`|onPageScroll|页面生命周期。页面滚动时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onNavigationBarButtonTap({ index }) {$1}$0`|onNavigationBarButtonTap|页面生命周期。原生标题栏按钮被点击时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onBackPress({ from }) {$1}$0`|onBackPress|页面生命周期。页面返回时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onNavigationBarSearchInputChanged() {$1}$0`|onNavigationBarSearchInputChanged|页面生命周期。原生标题栏搜索输入框输入时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onNavigationBarSearchInputConfirmed() {$1}$0`|onNavigationBarSearchInputConfirmed|页面生命周期。原生标题栏搜索输入框确认搜索时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onNavigationBarSearchInputClicked() {$1}$0`|onNavigationBarSearchInputClicked|页面生命周期。原生标题栏点击搜索输入框时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onShareTimeline() {$1}$0`|onShareTimeline|页面生命周期。点击右上角转发到朋友圈时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`onAddToFavorites() {$1}$0`|onAddToFavorites|页面生命周期。点击右上角收藏时触发。更多信息查看 https://uniapp.dcloud.io/collocation/frame/lifecycle?id=%e9%a1%b5%e9%9d%a2%e7%94%9f%e5%91%bd%e5%91%a8%e6%9c%9f。|
|`getApp() // 如果要使用 globalData，请考虑使用 vuex 实现同样的效果$0`|getApp|获取当前应用实例，可以进一步获取 globalData。更多信息查看 https://uniapp.dcloud.io/collocation/frame/window?id=getapp。|
|`getCurrentPages()$0`|getCurrentPages|获取当前页面栈实例，数组形式，第一个元素是首页。更多信息查看 https://uniapp.dcloud.io/collocation/frame/window?id=getcurrentpages。|
|`uni.$emit(${1:eventName}, ${2:{}})$0`|uni.$emit|触发全局自定义事件。过多的全局自定义事件容易导致代码混乱且难以调试，请控制全局自定义事件数量。更多信息查看 https://uniapp.dcloud.io/collocation/frame/communication?id=emit。|
|`uni.$on(${1:eventName}, (${2:data}) => {$3})$0`|uni.$on|监听全局自定义事件。过多的全局自定义事件容易导致代码混乱且难以调试，请控制全局自定义事件数量。更多信息查看 https://uniapp.dcloud.io/collocation/frame/communication?id=on。|
|`uni.$once(${1:eventName}, (${2:data}) => {$3})$0`|uni.$once|一次性监听全局自定义事件。过多的全局自定义事件容易导致代码混乱且难以调试，请控制全局自定义事件数量。更多信息查看 https://uniapp.dcloud.io/collocation/frame/communication?id=once。|
|`uni.$off(${1:eventName}$0)`|uni.$off|移除全局自定义事件监听。过多的全局自定义事件容易导致代码混乱且难以调试，请控制全局自定义事件数量。更多信息查看 https://uniapp.dcloud.io/collocation/frame/communication?id=off。|
|`uni.request({,	url: '$1',,	data: {$2},,	header: {,		Accept: 'application/json',,		'Content-Type': 'application/json',,		'X-Requested-With': 'XMLHttpRequest',	},,	method: ${3:'GET'},,	sslVerify: ${4:true},,	success: ({ data, statusCode, header }) => {$5},,	fail: (error) => {$6},})$0`|uni.request|发起网络请求。请考虑使用已经封装好的库，如 uni-ajax 和 luch-request。更多信息查看 https://uniapp.dcloud.io/api/request/request。|
|`uni.uploadFile({,	url: '$1',,	fileType: '${2:image}',,	filePath: ${3:tempFilePaths[0]},,	name: '${4:file}',,	success: ({ data, statusCode }) => {$5},,	fail: (error) => {$6},})$0`|uni.uploadFile|上传文件。更多信息查看 https://uniapp.dcloud.io/api/request/network-file?id=uploadfile。|
|`uni.downloadFile({,	url: '$1',,	success: ({ tempFilePath, statusCode }) => {$2},,	fail: (error) => {$3},})$0`|uni.downloadFile|下载文件。更多信息查看 https://uniapp.dcloud.io/api/request/network-file?id=downloadfile。|
|`uni.connectSocket({,	url: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.connectSocket|创建 WebSocket 连接。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=connectsocket。|
|`uni.onSocketOpen((result) => {$1})$0`|uni.onSocketOpen|监听 WebSocket 连接打开。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=onsocketopen。|
|`uni.onSocketError((result) => {$1})$0`|uni.onSocketError|监听 WebSocket 错误。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=onsocketerror。|
|`uni.sendSocketMessage({,	data: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.sendSocketMessage|通过 WebSocket 发送数据。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=sendsocketmessage。|
|`uni.onSocketMessage(({ data }) => {$1})$0`|uni.onSocketMessage|监听 WebSocket 接收消息。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=onsocketmessage。|
|`uni.closeSocket({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.closeSocket|关闭 WebSocket 连接。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=closesocket。|
|`uni.onSocketClose((result) => {$1})$0`|uni.onSocketClose|监听 WebSocket 关闭。更多信息查看 https://uniapp.dcloud.io/api/request/websocket?id=onsocketclose。|
|`uni.navigateTo({,	url: '/pages/$1',})$0`|uni.navigateTo|保留当前页面，跳转到某个非 TabBar 页面。更多信息查看 https://uniapp.dcloud.io/api/router?id=navigateto。|
|`uni.redirectTo({,	url: '/pages/$1',})$0`|uni.redirectTo|关闭当前页面，跳转到某个非 Tab 页面。更多信息查看 https://uniapp.dcloud.io/api/router?id=redirectto。|
|`uni.reLaunch({,	url: '/pages/$1',})$0`|uni.reLaunch|关闭所有页面，打开到某个页面。更多信息查看 https://uniapp.dcloud.io/api/router?id=relaunch。|
|`uni.switchTab({,	url: '/pages/$1',})$0`|uni.switchTab|关闭所有非 TabBar 页面，跳转到 TabBar 页面。更多信息查看 https://uniapp.dcloud.io/api/router?id=switchtab。|
|`uni.navigateBack({,	delta: ${1:1},})$0`|uni.navigateBack|关闭当前页面并返回。更多信息查看 https://uniapp.dcloud.io/api/router?id=navigateback。|
|`uni.setStorage({,	key: '${1:key}',,	data: ${2:data},,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.setStorage|异步存储本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=setstorage。|
|`uni.setStorageSync('${1:key}', ${2:data})$0`|uni.setStorageSync|同步存储本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=setstoragesync。|
|`uni.getStorage({,	key: '${1:key}',,	success: ({ data }) => {$2},,	fail: (error) => {$3},})$0`|uni.getStorage|异步读取本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=getstorage。|
|`uni.getStorageSync('${1:key}')$0`|uni.getStorageSync|同步读取本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=getstoragesync。|
|`uni.getStorageInfo({,	success: ({ keys, currentSize, limitSize }) => {$1},,	fail: (error) => {$2},})$0`|uni.getStorageInfo|异步读取存储信息。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=getstorageinfo。|
|`uni.getStorageInfoSync()$0`|uni.getStorageInfoSync|同步读取存储信息。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=getstorageinfosync。|
|`uni.removeStorage({,	key: '${1:key}',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.removeStorage|异步移除本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=removestorage。|
|`uni.removeStorageSync('${1:key}')`|uni.removeStorageSync|同步移除本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=removestoragesync。|
|`uni.clearStorage({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.clearStorage|异步清空本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=clearstorage。|
|`uni.clearStorageSync()`|uni.clearStorage|同步清理本地数据。更多信息查看 https://uniapp.dcloud.io/api/storage/storage?id=clearstoragesync。|
|`uni.getLocation({,	type: '${1:gcj02}',,	success: ({ longitude, latitude }) => {$2},,	fail: (error) => {$3},})$0`|uni.getLocation|获取当前地理位置。如果需要转换坐标到不同坐标系，建议使用已经封装好的库，如 gcoord 和 coordtransform。更多信息查看 https://uniapp.dcloud.io/api/location/location?id=getlocation。|
|`uni.chooseLocation({,	success: ({ name, address, longitude, latitude }) => {$1},,	fail: (error) => {$2},});`|uni.chooseLocation|打开地图选择位置。更多信息查看 https://uniapp.dcloud.io/api/location/location?id=chooselocation。|
|`uni.openLocation({,	longitude: ${1:longitude},,	latitude: ${2:latitude},,	name: '${3:name}',,	address: '${4:address}',})`|uni.openLocation|使用内置地图查看位置。更多信息查看 https://uniapp.dcloud.io/api/location/open-location。|
|`uni.createMapContext(${1:mapId}, ${2:this})`|uni.createMapContext|创建地图上下文对象。更多信息查看 https://uniapp.dcloud.io/api/location/map?id=createmapcontext。|
|`uni.chooseImage({,	sourceType: ${1:['album', 'camera']},,	success: ({ tempFilePaths, tempFiles }) => {$2},,	fail: (error) => {$3},})$0`|uni.chooseImage|选择相册图片或使用相机拍照。更多信息查看 https://uniapp.dcloud.io/api/media/image?id=chooseimage。|
|`uni.previewImage({,	urls: ${1:tempFilePaths},,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.previewImage|预览图片。更多信息查看 https://uniapp.dcloud.io/api/media/image?id=unipreviewimageobject。|
|`uni.getImageInfo({,	src: $1,,	success: ({ width, height, path, orientation, type }) => {$2},,	fail: (error) => {$3},})$0`|uni.getImageInfo|获取图片信息。更多信息查看 https://uniapp.dcloud.io/api/media/image?id=getimageinfo。|
|`uni.saveImageToPhotosAlbum({,	filePath: $1,,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.saveImageToPhotosAlbum|保存图片到相册。更多信息查看 https://uniapp.dcloud.io/api/media/image?id=saveimagetophotosalbum。|
|`uni.compressImage({,	src: $1,,	quality: ${2:80},,	success: ({ tempFilePath }) => {$3},,	fail: (error) => {$4},})$0`|uni.compressImage|压缩图片。更多信息查看 https://uniapp.dcloud.io/api/media/image?id=compressimage。|
|`uni.chooseFile({,	type: '${1:all}',,	success: ({ tempFilePaths, tempFiles }) => {$2},,	fail: (error) => {$3},})$0`|uni.chooseFile|选择本地文件。更多信息查看 https://uniapp.dcloud.io/api/media/file?id=choosefile。|
|`uni.getRecorderManager()$0`|uni.getRecorderManager|获取全局唯一录音管理器。更多信息查看 https://uniapp.dcloud.io/api/media/record-manager?id=getrecordermanager。|
|`uni.getBackgroundAudioManager()$0`|uni.getBackgroundAudioManager|获取全局唯一背景音频管理器。更多信息查看 https://uniapp.dcloud.io/api/media/background-audio-manager?id=getbackgroundaudiomanager。|
|`uni.createInnerAudioContext()$0`|uni.createInnerAudioContext|创建音频上下文对象。更多信息查看 https://uniapp.dcloud.io/api/media/audio-context?id=createinneraudiocontext。|
|`uni.chooseVideo({,	sourceType: ${1:['album', 'camera']},,	camera: '${2:back}',,	success: ({ tempFilePath }) => {$3},,	fail: (error) => {$4},})$0`|uni.chooseVideo|选择相册视频或使用相机录像。更多信息查看 https://uniapp.dcloud.io/api/media/video?id=choosevideo。|
|`uni.saveVideoToPhotosAlbum({,	filePath: ${1:tempFilePath},,	success: ({ errMsg }) => {$2},,	fail: (error) => {$3},})$0`|uni.saveVideoToPhotosAlbum|保存视频到相册。更多信息查看 https://uniapp.dcloud.io/api/media/video?id=savevideotophotosalbum。|
|`uni.createVideoContext(${1:videoId}, ${2:this})$0`|uni.createVideoContext|创建视频上下文对象。更多信息查看 https://uniapp.dcloud.io/api/media/video-context?id=createvideocontext.|
|`uni.createCameraContext()$0`|uni.createCameraContext|创建相机上下文对象。更多信息查看 https://uniapp.dcloud.io/api/media/camera-context?id=createcameracontext。|
|`uni.createLivePlayerContext(${1:livePlayerId}, ${2:this})$0`|uni.createLivePlayerContext|创建直播拉流上下文对象。更多信息查看 https://uniapp.dcloud.io/api/media/live-player-context?id=createliveplayercontext。|
|`uni.createLivePusherContext(${1:livePusherId}, ${2:this})$0`|uni.createLivePusherContext|创建直播推流上下文对象。更多信息查看 https://uniapp.dcloud.io/api/media/live-player-context?id=createlivepushercontext。|
|`uni.getSystemInfo({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.getSystemInfo|异步获取系统信息。更多信息查看 https://uniapp.dcloud.io/api/system/info?id=getsysteminfo。|
|`uni.getSystemInfoSync()$0`|uni.getSystemInfoSync|同步获取系统信息。更多信息查看 https://uniapp.dcloud.io/api/system/info?id=getsysteminfosync。|
|`uni.canIUse('$1')$0`|uni.canIUse|判断 API、回调、参数、组件等是否在当前版本可用。更多信息查看 https://uniapp.dcloud.io/api/system/info?id=caniuse。|
|`uni.onMemoryWarning(() => {$1})$0`|uni.onMemoryWarning|内存不足告警时触发。更多信息查看 https://uniapp.dcloud.io/api/system/memory。|
|`uni.getNetworkType({,	success: ({ networkType }) => {$1},,	fail: (error) => {$2},})$0`|uni.getNetworkType|获取网络类型。更多信息查看 https://uniapp.dcloud.io/api/system/network?id=getnetworktype。|
|`uni.onNetworkStatusChange(({ isConnected, networkType }) => {$1})$0`|uni.onNetworkStatusChange|网络状态变化时触发。更多信息查看 https://uniapp.dcloud.io/api/system/network?id=onnetworkstatuschange。|
|`uni.onAccelerometerChange(({ x, y, z }) => {$1})$0`|uni.onAccelerometerChange|监听加速度数据。更多信息查看 https://uniapp.dcloud.io/api/system/accelerometer?id=onaccelerometerchange。|
|`uni.offAccelerometerChange(() => {$1})$0`|uni.offAccelerometerChange|取消监听加速度数据。更多信息查看 https://uniapp.dcloud.io/api/system/accelerometer?id=offaccelerometerchange。|
|`uni.startAccelerometer({,	interval: '${1:normal}',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.startAccelerometer|开始监听加速度数据。更多信息查看 https://uniapp.dcloud.io/api/system/accelerometer?id=startaccelerometer。|
|`uni.stopAccelerometer({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopAccelerometer|停止监听加速度数据。更多信息查看 https://uniapp.dcloud.io/api/system/accelerometer?id=stopaccelerometer。|
|`uni.onCompassChange(({ direction }) => {$1})$0`|uni.onCompassChange|监听罗盘数据。更多信息查看 https://uniapp.dcloud.io/api/system/compass?id=oncompasschange。|
|`uni.offCompassChange(() =>  {$1})$0`|uni.offCompassChange|取消监听罗盘数据。更多信息查看 https://uniapp.dcloud.io/api/system/compass?id=offcompasschange。|
|`uni.startCompass({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.startCompass|开始监听罗盘数据。更多信息查看 https://uniapp.dcloud.io/api/system/compass?id=startcompass。|
|`uni.stopCompass({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopCompass|停止监听罗盘数据。更多信息查看 https://uniapp.dcloud.io/api/system/compass?id=stopcompass。|
|`uni.onGyroscopeChange(({ x, y, z }) => {$1})$0`|uni.onGyroscopeChange|监听陀螺仪数据。更多信息查看 https://uniapp.dcloud.io/api/system/gyroscope?id=ongyroscopechange。|
|`uni.offGyroscopeChange(() => {$1})$0`|uni.offGyroscopeChange|取消监听陀螺仪数据。更多信息查看 https://uniapp.dcloud.io/api/system/gyroscope?id=offgyroscopechange。|
|`uni.startGyroscope({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.startGyroscope|开始监听陀螺仪数据。更多信息查看 https://uniapp.dcloud.io/api/system/gyroscope?id=startgyroscope。|
|`uni.stopGyroscope({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopGyroscope|停止监听陀螺仪数据。更多信息查看 https://uniapp.dcloud.io/api/system/gyroscope?id=stopgyroscope。|
|`uni.makePhoneCall({,	phoneNumber: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.makePhoneCall|拨打电话。更多信息查看 https://uniapp.dcloud.io/api/system/phone。|
|`uni.scanCode({,	onlyFromCamera: ${1:false},,	scanType: ${2:['qrCode', 'barCode']},,	success: ({ result, scanType, charSet, path }) => {$3},,	fail: (error) => {$4},})$0`|uni.scanCode|扫码。更多信息查看 https://uniapp.dcloud.io/api/system/barcode。|
|`uni.setClipboardData({,	data: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.setClipboardData|设置剪贴板内容。更多信息查看 https://uniapp.dcloud.io/api/system/clipboard。|
|`uni.getClipboardData({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.getClipboardData|获取剪贴板内容。更多信息查看 https://uniapp.dcloud.io/api/system/clipboard。|
|`uni.setScreenBrightness({,	value: $1,,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.setScreenBrightness|设置屏幕亮度。更多信息查看 https://uniapp.dcloud.io/api/system/brightness?id=setscreenbrightness。|
|`uni.getScreenBrightness({,	success: ({ value }) => {$1},,	fail: (error) => {$2},})$0`|uni.getScreenBrightness|获取屏幕亮度。更多信息查看 https://uniapp.dcloud.io/api/system/brightness?id=getscreenbrightness。|
|`uni.setScreenBrightness({,	keepScreenOn: ${1:false},,	success: ({ errMsg }) => {$2},,	fail: (error) => {$3},})$0`|uni.setScreenBrightness|设置屏幕亮度。更多信息查看 https://uniapp.dcloud.io/api/system/brightness?id=setscreenbrightness。|
|`uni.onUserCaptureScreen(() => {$1})$0`|uni.onUserCaptureScreen|监听截屏。更多信息查看 https://uniapp.dcloud.io/api/system/capture-screen。|
|`uni.vibrate({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.vibrate|使手机振动。更多信息查看 https://uniapp.dcloud.io/api/system/vibrate?id=vibrate。|
|`uni.vibrateLong({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.vibrateLong|使手机长振动。更多信息查看 https://uniapp.dcloud.io/api/system/vibrate?id=vibratelong。|
|`uni.vibrateShort({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.vibrateShort|使手机短振动。更多信息查看 https://uniapp.dcloud.io/api/system/vibrate?id=vibrateshort。|
|`uni.addPhoneContact({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.addPhoneContact|添加手机联系人。更多信息查看 https://uniapp.dcloud.io/api/system/contact。|
|`uni.openBluetoothAdapter({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.openBluetoothAdapter|初始化蓝牙模块。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.startBluetoothDevicesDiscovery({,	services: ${1:[]},,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.startBluetoothDevicesDiscovery|开始搜寻蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.onBluetoothDeviceFound(({ devices }) => {$1})$0`|uni.onBluetoothDeviceFound|监听搜寻到蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.stopBluetoothDevicesDiscovery({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopBluetoothDevicesDiscovery|停止搜寻蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.onBluetoothAdapterStateChange(({ available, discovering }) => {$1})$0`|uni.onBluetoothAdapterStateChange|监听蓝牙适配器状态变化。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.getConnectedBluetoothDevices({,	services: ${1:[]},,	success: ({ devices }) => {$2},,	fail: (error) => {$3},})$0`|uni.getConnectedBluetoothDevices|根据 uuid 获取已经连接的蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.getBluetoothDevices({,	success: ({ devices }) => {$1},,	fail: (error) => {$2},})$0`|uni.getBluetoothDevices|获取蓝牙模块生效期间所有已发现的蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.getBluetoothAdapterState({,	success: ({ available, discovering }) => {$1},,	fail: (error) => {$2},})$0`|uni.getBluetoothAdapterState|获取蓝牙适配器状态。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.getBluetoothAdapterState({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.closeBluetoothAdapter|关闭蓝牙模块。更多信息查看 https://uniapp.dcloud.io/api/system/bluetooth。|
|`uni.setBLEMTU({,	deviceId: '$1',,	mtu: $2,,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.setBLEMTU|设置蓝牙最大传输单元。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.writeBLECharacteristicValue({,	deviceId: '$1',,	serviceId: '$2',,	characteristicId: '$3',,	value: $4,,	success: (result) => {$5},,	fail: (error) => {$6},})$0`|uni.writeBLECharacteristicValue|向低功耗蓝牙设备特征值写入二进制数据。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.readBLECharacteristicValue({,	deviceId: '$1',,	serviceId: '$2',,	characteristicId: '$3',,	success: (result) => {$4},,	fail: (error) => {$5},})$0`|uni.readBLECharacteristicValue|读取低功耗蓝牙设备特征值的二进制数据。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.onBLEConnectionStateChange(({ deviceId, connected }) => {$1})$0`|uni.onBLEConnectionStateChange|监听低功耗蓝牙连接状态改变。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.onBLECharacteristicValueChange(({,	deviceId,,	serviceId,,	characteristicId,,	value,}) => {$1})$0`|uni.onBLECharacteristicValueChange|监听低功耗蓝牙设备特征值变化。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.notifyBLECharacteristicValueChange({,	deviceId: '$1',,	serviceId: '$2',,	characteristicId: '$3',,	state: ${4:true},,	success: (result) => {$5},,	fail: (error) => {$6},})$0`|uni.notifyBLECharacteristicValueChange|启用低功耗蓝牙设备特征值变化时的 notify 功能。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.getBLEDeviceServices({,	deviceId: '$1',,	success: ({ services }) => {$2},,	fail: (error) => {$3},})$0`|uni.getBLEDeviceServices|获取蓝牙设备所有服务。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.getBLEDeviceRSSI({,	deviceId: '$1',,	success: ({ RSSI }) => {$2},,	fail: (error) => {$3},})$0`|uni.getBLEDeviceRSSI|获取蓝牙设备信号强度。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.getBLEDeviceCharacteristics({,	deviceId: '$1',,	serviceId: '$2',,	success: ({ characteristics }) => {$3},,	fail: (error) => {$4},})$0`|uni.getBLEDeviceCharacteristics|获取蓝牙设备某个服务所有特征值。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.createBLEConnection({,	deviceId: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.createBLEConnection|连接低功耗蓝牙设备。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.closeBLEConnection({,	deviceId: '$1',,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.closeBLEConnection|断开与低功耗蓝牙设备的连接。更多信息查看 https://uniapp.dcloud.io/api/system/ble。|
|`uni.onBeaconServiceChange(({ available, discovering }) => {$1})$0`|uni.onBeaconServiceChange|监听 iBeacon 服务状态变化。更多信息查看 https://uniapp.dcloud.io/api/system/ibeacon。|
|`uni.onBeaconUpdate(({ beacons }) => {$1})$0`|uni.onBeaconUpdate|监听 iBeacon 设备更新。更多信息查看 https://uniapp.dcloud.io/api/system/ibeacon。|
|`uni.getBeacons({,	success: ({ beacons }) => {$1},,	fail: (error) => {$2},})$0`|uni.getBeacons|获取所有已搜索到的 iBeacon 设备。更多信息查看 https://uniapp.dcloud.io/api/system/ibeacon。|
|`uni.startBeaconDiscovery({,	uuids: $1,,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.startBeaconDiscovery|开始搜索附近 iBeacon 设备。更多信息查看 https://uniapp.dcloud.io/api/system/ibeacon。|
|`uni.stopBeaconDiscovery({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopBeaconDiscovery|停止搜索附近 iBeacon 设备。更多信息查看 https://uniapp.dcloud.io/api/system/ibeacon。|
|`uni.startSoterAuthentication({,	requestAuthModes: ${1:['fingerPrint', 'facial']},,	challenge: '$2',,	authContent: '$3',,	success: ({ authMode, resultJSON, resultJSONSignature, errCode, errMsg }) => {$4},,	fail: (error) => {$5},})$0`|uni.startSoterAuthentication|开始 SOTER 生物认证。更多信息查看 https://uniapp.dcloud.io/api/system/authentication?id=startsoterauthentication。|
|`uni.checkIsSupportSoterAuthentication({,	success: ({ supportMode }) => {$1},,	fail: (error) => {$2},})$0`|uni.checkIsSupportSoterAuthentication|获取支持的 SOTER 生物认证方式。更多信息查看 https://uniapp.dcloud.io/api/system/authentication?id=checkissupportsoterauthentication。|
|`uni.checkIsSoterEnrolledInDevice({,	checkAuthMode: '${1:fingerPrint|facial}',,	success: ({ isEnrolled, errMsg }) => {$2},,	fail: (error) => {$3},})$0`|uni.checkIsSoterEnrolledInDevice|获取设备内是否录入生物信息。更多信息查看 https://uniapp.dcloud.io/api/system/authentication?id=checkissoterenrolledindevice。|
|`uni.showToast({,	title: '$1',,	icon: '${2:success|none}',,	mask: true,})`|uni.showToast|显示消息提示框。这可能与加载提示框冲突，请在测试时以真机测试为准。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=showtoast。|
|`uni.hideToast()$0`|uni.hideToast|隐藏消息提示框。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=hidetoast。|
|`uni.showLoading({,	title: '${1:加载中}',,	mask: ${2:true},})$0`|uni.showLoading|显示加载中提示框。这可能与消息提示框冲突，请在测试时以真机测试为准。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=showloading。|
|`uni.hideLoading()$0`|uni.hideLoading|隐藏加载中提示框。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=hideloading。|
|`uni.showModal({,	title: '${1:提示}',,	content: '$2',,	showCancel: ${3:true},,	success: ({ confirm, cancel }) => {$4},})$0`|uni.showModal|显示模态弹窗。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=showmodal。|
|`uni.showActionSheet({,	itemList: [$1],,	success: ({ tapIndex }) => {$2},,	fail: (error) => {$3},})$0`|uni.showActionSheet|显示操作菜单。更多信息查看 https://uniapp.dcloud.io/api/ui/prompt?id=showactionsheet。|
|`uni.setNavigationBarTitle({,	title: '$1',})$0`|uni.setNavigationBarTitle|动态设置当前页面标题。更多信息查看 https://uniapp.dcloud.io/api/ui/navigationbar?id=setnavigationbartitle。|
|`uni.setNavigationBarColor({,	frontColor: '${1:#000000|#ffffff}',,	backgroundColor: '${2:#ff0000}',})$0`|uni.setNavigationBarColor|设置页面导航条颜色。更多信息查看 https://uniapp.dcloud.io/api/ui/navigationbar?id=setnavigationbarcolor。|
|`uni.showNavigationBarLoading()$0`|uni.showNavigationBarLoading|在当前页面显示导航条加载动画。更多信息查看 https://uniapp.dcloud.io/api/ui/navigationbar?id=shownavigationbarloading。|
|`uni.hideNavigationBarLoading()$0`|uni.hideNavigationBarLoading|在当前页面隐藏导航条加载动画。更多信息查看 https://uniapp.dcloud.io/api/ui/navigationbar?id=hidenavigationbarloading。|
|`uni.hideHomeButton()$0`|uni.hideHomeButton|隐藏返回首页按钮。更多信息查看 https://uniapp.dcloud.io/api/ui/navigationbar?id=hidehomebutton。|
|`uni.setTabBarItem({,	index: $1,,	text: '$2',,	iconPath: '/static/$3',,	selectedIconPath: '/static/$4',})$0`|uni.setTabBarItem|动态设置 TabBar 某一项内容。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=settabbaritem。|
|`uni.setTabBarStyle({,	color: '${1:#FF0000}',,	selectedColor: '${2:#00FF00}',,	backgroundColor: '${3:#0000FF}',,	borderStyle: '${4:black|white}',})$0`|uni.setTabBarStyle|动态设置 TabBar 整体样式。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=settabbarstyle。|
|`uni.hideTabBar()$0`|uni.hideTabBar|隐藏 TabBar。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=hidetabbar。|
|`uni.showTabBar()$0`|uni.showTabBar|显示 TabBar。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=showtabbar。|
|`uni.setTabBarBadge({,	index: $1,,	text: '$2',})$0`|uni.setTabBarBadge|设置 TabBar 某一项徽标。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=settabbarbadge。|
|`uni.removeTabBarBadge({,	index: $1,})$0`|uni.removeTabBarBadge|移除 tabBar 某一项徽标。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=removetabbarbadge。|
|`uni.showTabBarRedDot({,	index: $1,,})$0`|uni.showTabBarRedDot|设置 TabBar 某一项红点。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=showtabbarreddot。|
|`uni.hideTabBarRedDot({,index: $1,,})$0`|uni.hideTabBarRedDot|移除 tabBar 某一项红点。更多信息查看 https://uniapp.dcloud.io/api/ui/tabbar?id=hidetabbarreddot。|
|`uni.setBackgroundColor({,	backgroundColor: '${1:#ffffff}',,	backgroundColorTop: '${2:#ffffff}',,	backgroundColorBottom: '${3:#ffffff}',})$0`|uni.setBackgroundColor|动态设置窗口背景色。更多信息查看 https://uniapp.dcloud.io/api/ui/bgcolor?id=setbackgroundcolor。|
|`uni.setBackgroundTextStyle({,	textStyle: '{$1:dark|light}',})$0`|uni.setBackgroundTextStyle|动态设置下拉背景字体、加载图的样式。更多信息查看 https://uniapp.dcloud.io/api/ui/bgcolor?id=setbackgroundtextstyle。|
|`uni.createAnimation({$1})$0`|uni.createAnimation|创建动画实例。更多信息查看 https://uniapp.dcloud.io/api/ui/animation。|
|`uni.pageScrollTo({,	scrollTop: ${1:0},})$0`|uni.pageScrollTo|将页面滚动到目标位置。更多信息查看 https://uniapp.dcloud.io/api/ui/scroll。|
|`uni.onWindowResize(({ size: { windowWidth, windowHeight } }) => {$1})$0`|uni.onWindowResize|监听窗口尺寸变化。更多信息查看 https://uniapp.dcloud.io/api/ui/window?id=onwindowresize。|
|`uni.offWindowResize(() => {$1})$0`|uni.offWindowResize|取消监听窗口尺寸变化。更多信息查看 https://uniapp.dcloud.io/api/ui/window?id=offwindowresize。|
|`uni.loadFontFace({,	family: '$1',,	source: 'url($2)',,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.loadFontFace|动态加载网络字体。更多信息查看 https://uniapp.dcloud.io/api/ui/font。|
|`uni.startPullDownRefresh({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.startPullDownRefresh|开始下拉刷新。更多信息查看 https://uniapp.dcloud.io/api/ui/pulldown?id=startpulldownrefresh。|
|`uni.stopPullDownRefresh({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.stopPullDownRefresh|停止下拉刷新。更多信息查看 https://uniapp.dcloud.io/api/ui/pulldown?id=startpulldownrefresh。|
|`uni.createSelectorQuery()$0`|uni.createSelectorQuery|创建查询节点信息的实例。更多信息查看 https://uniapp.dcloud.io/api/ui/nodes-info。|
|`uni.getMenuButtonBoundingClientRect()$0`|uni.getMenuButtonBoundingClientRect|获取菜单按钮信息。更多信息查看 https://uniapp.dcloud.io/api/ui/menuButton。|
|`uni.saveFile({,	tempFilePath: ${1:tempFilePaths[0]},,	success: ({ savedFilePath }) => {$2},,	fail: (error) => {$3},})$0`|uni.saveFile|保存文件到本地。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=savefile。|
|`uni.getSavedFileList({,	success: ({ fileList, errMsg }) => {$1}),,	fail: (error) => {$2},})$0`|uni.getSavedFileList|获取本地已保存的文件列表。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=getsavedfilelist。|
|`uni.getSavedFileInfo({,	filePath: ${1:fileList[0].filePath},,	success: ({ size, createTime, errMsg }) => {$2},	fail: (error) => {$3},})$0`|uni.getSavedFileInfo|获取本地文件的文件信息。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=getsavedfileinfo。|
|`uni.removeSavedFile({,	filePath: ${1:fileList[0].filePath},,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.removeSavedFile|删除本地存储的文件。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=removesavedfile。|
|`uni.uni.getFileInfo({,	filePath: ${1:fileList[0].filePath},,	success: ({ size, digest, errMsg }) => {$2},	fail: (error) => {$3},})$0`|uni.getFileInfo|获取文件信息。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=getfileinfo。|
|`uni.openDocument({,	filePath: ${1:tempFilePath},,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.openDocument|新开页面打开文档。更多信息查看 https://uniapp.dcloud.io/api/file/file?id=opendocument。|
|`uni.createCanvasContext({ canvasId: '${1:canvasId}' })$0`|uni.createCanvasContext|创建画布上下文。更多信息查看 https://uniapp.dcloud.io/api/canvas/createCanvasContext。|
|`uni.canvasToTempFilePath({ canvasId: '${1:canvasId}' })$0`|uni.canvasToTempFilePath|导出画布内容。更多信息查看 https://uniapp.dcloud.io/api/canvas/canvasToTempFilePath。|
|`uni.getProvider({,	service: ${1:oauth|share|payment|push},,	success: ({ service, provider }) => {$2},,	fail: (error) => {$3},})$0`|uni.getProvider|获取服务供应商。更多信息查看 https://uniapp.dcloud.io/api/plugins/provider。|
|`uni.login({,	provider: $1,,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.login|登录。更多信息查看 https://uniapp.dcloud.io/api/plugins/login?id=login。|
|`uni.checkSession({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.checkSession|检查登录状态。更多信息查看 https://uniapp.dcloud.io/api/plugins/login?id=unichecksession。|
|`uni.getUserInfo({,	provider: $1,,	withCredentials: ${2:true},,	success: ({ userInfo, rawData, signature, encryptedData, iv, errMsg }) => {$3},,	fail: (error) => {$4},})$0`|uni.getUserInfo|检查登录状态。更多信息查看 https://uniapp.dcloud.io/api/plugins/login?id=unichecksession。|
|`uni.share({,	provider: $1,,	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.share|分享。更多信息查看 https://uniapp.dcloud.io/api/plugins/share?id=share。|
|`uni.showShareMenu({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.showShareMenu|原生菜单显示分享按钮。更多信息查看 https://uniapp.dcloud.io/api/plugins/share?id=showsharemenu。|
|`uni.hideShareMenu({,	success: (result) => {$1},,	fail: (error) => {$2},})$0`|uni.hideShareMenu|原生菜单隐藏分享按钮。更多信息查看 https://uniapp.dcloud.io/api/plugins/share?id=hidesharemenu。|
|`uni.requestPayment({,	provider: $1,,	orderInfo: $2,,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.requestPayment|支付。更多信息查看 https://uniapp.dcloud.io/api/plugins/payment。|
|`uni.authorize({,	scope: '$1',	success: (result) => {$2},,	fail: (error) => {$3},})$0`|uni.authorize|授权。更多信息查看 https://uniapp.dcloud.io/api/other/authorize。|
|`uni.getSetting({,	success: ({ authSetting }) => {$1},,	fail: (error) => {$2},})$0`|uni.openSetting|打开设置界面。更多信息查看 https://uniapp.dcloud.io/api/other/setting?id=opensetting。|
|`uni.getSetting({,	success: ({ authSetting, subscriptionsSetting }) => {$1},,	fail: (error) => {$2},})$0`|uni.getSetting|获取当前设置。更多信息查看 https://uniapp.dcloud.io/api/other/setting?id=getsetting。|
|`uni.chooseAddress({,	success: ({,		userName,,		postalCode,,		provinceName,,		cityName,,		detailInfo,,		nationalCode,,		telNumber,,		errMsg,	}) => {$1},,	fail: (error) => {$2},})$0`|uni.chooseAddress|获取当前设置。更多信息查看 https://uniapp.dcloud.io/api/other/choose-address。|
|`uni.chooseInvoiceTitle({,	success: ({,		type,,		title,,		taxNumber,,		companyAddress,,		telephone,,		bankName,,		bankAccount,,		errMsg,	}) => {$1},,	fail: (error) => {$2},})$0`|uni.chooseInvoiceTitle|获取当前设置。更多信息查看 https://uniapp.dcloud.io/api/other/invoice-title。|
|`uni.navigateToMiniProgram({,	appId: '$1',,	path: '$2',,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.navigateToMiniProgram|打开小程序。更多信息查看 https://uniapp.dcloud.io/api/other/open-miniprogram?id=navigatetominiprogram。|
|`uni.navigateToMiniProgram({,	appId: '$1',,	path: '$2',,	success: (result) => {$3},,	fail: (error) => {$4},})$0`|uni.navigateToMiniProgram|从打开的小程序返回。更多信息查看 https://uniapp.dcloud.io/api/other/open-miniprogram?id=navigatebackminiprogram。|
|`uni.getAccountInfoSync()$0`|uni.getAccountInfoSync|同步获取账号信息。更多信息查看 https://uniapp.dcloud.io/api/other/getAccountInfoSync。|
|`uni.report({,	${1:eventName},	${2:''|{}},})$0`|uni.report|统计。更多信息查看 https://uniapp.dcloud.io/api/other/report。|
|`uni.getUpdateManager()$0`|uni.getUpdateManager|获取全局唯一版本更新管理器。更多信息查看 https://uniapp.dcloud.io/api/other/update。|
|`uni.setEnabledDebug({,	enableDebug: ${1:true},	success: (result) => {$2},,	fail: (error) => {$3},})`|uni.setEnableDebug|设置调试开关。更多信息查看 https://uniapp.dcloud.io/api/other/set-enable-debug。|



# HTML

|API|Prefix|Description|
|-|-|-|
|`APP-PLUS`|`platform-app,platform-app-plus,app,app-plus`|APP 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`APP-NVUE`|`platform-app-nvue,platform-app-plus-nvue,app-nvue,app-plus-nvue`|APP-NVUE 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`H5`|`platform-h5,h5`|H5 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-WEIXIN`|`platform-mp-weixin,platform-weixin,platform-mp-wechat,platform-wechat,mp-weixin,weixin,mp-wechat,wechat`|微信小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-ALIPAY`|`platform-mp-alipay,platform-alipay,platform-mp-ali,platform-ali,mp-alipay,alipay,mp-ali,ali`|支付宝小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-BAIDU`|`platform-mp-baidu,platform-baidu,mp-baidu,baidu`|百度小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-TOUTIAO`|`platform-mp-toutiao,platform-toutiao,platform-mp-bytedance,platform-bytedance,mp-toutiao,toutiao,mp-bytedance,bytedance`|字节跳动小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-QQ`|`platform-mp-qq,platform-qq,mp-qq,qq`|QQ 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-360`|`platform-mp-360,platform-360,mp-360,360`|360 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP`|`platform-mp,mp`|小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW`|`platform-quickapp,platform-quickapp-webview,quickapp,quickapp-webview`|快应用通用对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-UNION`|`platform-quickapp-union,platform-quickapp-webview-union,quickapp-union,quickapp-webview-union`|快应用联盟对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-HUAWEI`|`platform-quickapp-huawei,platform-quickapp-webview-huawei,quickapp-huawei,quickapp-webview-huawei`|快应用华为对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`<!-- #ifdef $1 -->,$2,<!-- #endif -->`|`#ifdef,ifdef`|条件编译，处理某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`<!-- #ifndef $1 -->,$2,<!-- #endif -->`|`#ifndef,ifndef`|条件编译，排除某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`<!-- #endif -->`|`#endif,endif`|结束条件编译。更多信息查看 https://uniapp.dcloud.io/platform。|
|`<view>$1</view>$0`|`view,<view>`|视图容器，用于包裹各种元素内容。更多信息查看 https://uniapp.dcloud.io/component/view。|
|`<scroll-view scroll-${1:y}>,	$2,</scroll-view>$0`|`scroll-view,<scroll-view>`|可滚动视图区域。竖向滚动时，需要给一个固定高度。更多信息查看 https://uniapp.dcloud.io/component/scroll-view。|
|`<swiper,	indicator-dots,	autoplay,	circular,>,	<swiper-item>$1</swiper-item>,</swiper>$0`|`swiper,<swiper>`|滑块视图容器。子组件只能是 swiper-item。竖向滑动时，需要给一个固定高度。更多信息查看 https://uniapp.dcloud.io/component/swiper?id=swiper。|
|`<swiper-item>$1</swiper-item>$0`|`swiper-item,<swiper-item>`|只能是 swiper 的子组件，宽高自动设置为 100%。更多信息查看 https://uniapp.dcloud.io/component/swiper?id=swiper-item。|
|`<match-media $1>$2</match-media>$0`|`match-media,<match-media>`|可适配不同屏幕的基本视图组件。更多信息查看 https://uniapp.dcloud.io/component/match-media。|
|`<movable-area ${1:scale-area}>,	<movable-view,		direction="${2:all}",		:x="$3",		:y="$4",		@change="$5",		@scale="$6",	>,		$7,	</movable-view>,</movable-area>$0`|`movable-area,<movable-area>`|可拖动区域组件，指代可拖动的范围。子组件只能是 movable-view。更多信息查看 https://uniapp.dcloud.io/component/movable-view?id=movable-area。|
|`<movable-view,	direction="${1:all}",	:x="$2",	:y="$3",	@change="$4",	@scale="$5",>,	$6,</movable-view>$0`|`movable-view,<movable-view>`|可移动的视图容器。只能是 movable-area 的子组件。更多信息查看 https://uniapp.dcloud.io/component/movable-view?id=movable-view。|
|`<cover-view>$1</cover-view>$0`|`cover-view,<cover-view>`|覆盖在原生组件上的文本视图。更多信息查看 https://uniapp.dcloud.io/component/cover-view?id=cover-view。|
|`<cover-image src="$1"></cover-image>$0`|`cover-image,<cover-image>`|覆盖在原生组件上的图片视图。可以嵌套在 cover-view 里。更多信息查看 https://uniapp.dcloud.io/component/cover-view?id=cover-image。|
|`<icon,	type="$1",	:size="${2:23}",	color="$3",/>$0`|`icon,<icon>`|图标。更多信息查看 https://uniapp.dcloud.io/component/icon。|
|`<text>$1</text>$0`|`text,<text>`|文本组件。用于包裹文本内容。更多信息查看 https://uniapp.dcloud.io/component/text。|
|`<rich-text :nodes="$1"></rich-text>$0`|`rich-text,<rich-text>`|富文本。更多信息查看 https://uniapp.dcloud.io/component/rich-text。|
|`<progress :percent="$1" />$0`|`progress,<progress>`|进度条。更多信息查看 https://uniapp.dcloud.io/component/progress。|
|`<button,	:disabled="$1",	:loading="$2",	open-type="$3",	hover-class="button-hover",	@click="$4",>,	$5,</button>$0`|`button,<button>`|按钮。更多信息查看 https://uniapp.dcloud.io/component/button。|
|`<checkbox-group @change="$1">,	<label>,		<checkbox,			:value="$2",			:checked="$3",		/>,		$4,	</label>,</checkbox-group>$0`|`checkbox-group,<checkbox-group>`|多选框组。更多信息查看 https://uniapp.dcloud.io/component/checkbox?id=checkbox-group。|
|`<checkbox,	:value="$1",	:checked="$2",/>$0`|`checkbox,<checkbox>`|多选框。更多信息查看 https://uniapp.dcloud.io/component/checkbox?id=checkbox。|
|`<editor $1></editor>$0`|`editor,<editor>`|富文本编辑器，可以对图片、文字格式进行编辑和混排。更多信息查看 https://uniapp.dcloud.io/component/editor。|
|`<form,	@submit="$1",	@reset="$2",>,	$3,	<button form-type="submit">${4:提交}</button>,	<button form-type="reset">${5:重置}</button>,</form>$0`|`form,<form>`|表单，将组件内的用户输入的 switch input checkbox slider radio picker 提交。更多信息查看 https://uniapp.dcloud.io/component/form。|
|`<input,	v-model="$1",	placeholder="$2",	placeholder-class="input-placeholder",	@input="$4",/>$0`|`input,<input>`|输入框。更多信息查看 https://uniapp.dcloud.io/component/input。|
|`<label>$1</label>$0`|`label,<label>`|用来改进表单组件的可用性。更多信息查看 https://uniapp.dcloud.io/component/label。|
|`<picker,	mode="selector",	:range="$1",	:range-key="$2",	:value="$3",	@change="$4",>,	$5,</picker>$0`|`picker-selector,<picker-selector>`|单列选择器。更多信息查看 https://uniapp.dcloud.io/component/picker?id=%e6%99%ae%e9%80%9a%e9%80%89%e6%8b%a9%e5%99%a8。|
|`<picker,	mode="multiSelector",	:range="$1",	:range-key="$2",	:value="$3",	@change="$4",>,	$5,</picker>$0`|`picker-multi,picker-multi-selector,<picker-multi>,<picker-multi-selector>`|多列选择器。更多信息查看 https://uniapp.dcloud.io/component/picker?id=%e5%a4%9a%e5%88%97%e9%80%89%e6%8b%a9%e5%99%a8。|
|`<picker,	mode="time",	:value="$1",	@change="$2",>,	$3,</picker>$0`|`picker-time,<picker-time>`|时间选择器。更多信息查看 https://uniapp.dcloud.io/component/picker?id=%e6%97%b6%e9%97%b4%e9%80%89%e6%8b%a9%e5%99%a8。|
|`<picker,	mode="date",	:value="$1",	@change="$2",>,	$3,</picker>$0`|`picker-date,<picker-date>`|日期选择器。更多信息查看 https://uniapp.dcloud.io/component/picker?id=%e6%97%a5%e6%9c%9f%e9%80%89%e6%8b%a9%e5%99%a8。|
|`<picker,	mode="region",	:value="$1",	@change="$2",>,	$3,</picker>$0`|`picker-region,<picker-region>`|区域选择器。更多信息查看 https://uniapp.dcloud.io/component/picker?id=%e7%9c%81%e5%b8%82%e5%8c%ba%e9%80%89%e6%8b%a9%e5%99%a8。|
|`<picker-view,	:value="$1",	@change="$2",>,	<picker-view-column>$3</picker-view-column>,</picker-view>$0`|`picker-view,<picker-view>`|比 picker 更灵活的嵌入页面的滚动选择器。子组件只能是 picker-view-column。更多信息查看 https://uniapp.dcloud.io/component/picker-view?id=picker-view。|
|`<picker-view-column>$1</picker-view-column>$0`|`picker-view-column,<picker-view-column>`|只能是 picker-view 的子组件。更多信息查看 https://uniapp.dcloud.io/component/picker-view?id=picker-view-column。|
|`<radio-group @change="$1">,	<label>,		<radio,			:value="$2",			:checked="$3",		/>,		$4,	</label>,</radio-group>$0`|`radio-group,<radio-group>`|单选框组。更多信息查看 https://uniapp.dcloud.io/component/radio?id=radio-group。|
|`<radio,	:value="$1",	:checked="$2",/>$0`|`radio,<radio>`|单选框。更多信息查看 https://uniapp.dcloud.io/component/radio?id=radio。|
|`<slider,	:value="$1",	@change="$2",/>$0`|`slider,<slider>`|滑动选择器。更多信息查看 https://uniapp.dcloud.io/component/slider。|
|`<switch,	:checked="$1",	@change="$2",/>$0`|`switch,<switch>`|开关选择器。更多信息查看 https://uniapp.dcloud.io/component/switch。|
|`<textarea,	v-model="$1",	placeholder="$2",	placeholder-class="textarea-placeholder",	@input="$4",/>$0`|`textarea,<textarea>`|多行输入框。更多信息查看 https://uniapp.dcloud.io/component/textarea。|
|`<navigator,	url="/pages/$1",	open-type="${2:navigate}",	hover-class="navigator-hover",>,	$3,</navigator>$0`|`navigator,<navigator>`|页面跳转组件。只能跳转本地页面。目标页面必须已注册。更多信息查看 https://uniapp.dcloud.io/component/navigator。|
|`<custom-tab-bar,	direction="${1:horizontal}",	:show-icon="${2:false}",	:selected="${3:0}",	@onTabItemTap="$4",>,</custom-tab-bar>$0`|`custom-tab-bar,<custom-tab-bar>`|【H5 专用】自定义 TabBar 组件。更多信息查看 https://uniapp.dcloud.io/component/custom-tab-bar。|
|`<!-- 请考虑使用 uni.createInnerAudioContext 代替 -->,<audio,	id="$1",	src="$2",	${3:controls},	@error="$4",	@play="$5",	@pause="$6",	@timeupdate="$7",	@ended="$8",/>$0`|`audio,<audio>`|音频组件。更多信息查看 https://uniapp.dcloud.io/component/audio。|
|`<!-- 请考虑使用 uni.chooseImage 或 uni.chooseVideo 代替 -->,<camera,	mode="${1:normal}",	device-position="${2:back}",	flash="${3:auto}",/>$0`|`camera,<camera>`|页面内嵌的区域相机组件。更多信息查看 https://uniapp.dcloud.io/component/camera。|
|`<image,	src="$1",	mode="${2:scaleToFill}",/>$0`|`image,<image>`|图片组件。更多信息查看 https://uniapp.dcloud.io/component/image。|
|`<video src="$1" />$0`|`video,<video>`|视频组件。更多信息查看 https://uniapp.dcloud.io/component/video。|
|`<live-player,	id="$1",	src="$2",	${3:autoplay},/>$0`|`live-player,<live-player>`|直播拉流组件。更多信息查看 https://uniapp.dcloud.io/component/live-player。|
|`<live-pusher url="$1" />$0`|`live-pusher,<live-pusher>`|直播推流组件。更多信息查看 https://uniapp.dcloud.io/component/live-pusher。|
|`<map,	longitude="$1",	latitude="$2",	markers="$3",/>$0`|`map,<map>`|地图组件。更多信息查看 https://uniapp.dcloud.io/component/map。|
|`<canvas canvas-id="${1:canvasId}" />$0`|`canvas,<canvas>`|画布组件。更多信息查看 https://uniapp.dcloud.io/component/canvas。|
|`<web-view src="$1" />$0`|`web-view,<web-view>`|浏览器组件，自动铺满整个页面。更多信息查看 https://uniapp.dcloud.io/component/web-view。|
|`<ad $1 />$0`|`ad,<ad>`|应用内展示的广告组件。更多信息查看 https://uniapp.dcloud.io/component/ad。|
|`<navigation-bar $1 />$0`|`navigation-bar,<navigation-bar>`|页面导航条配置节点，用于指定导航栏的一些属性。只能是 page-meta 组件第一个子组件。更多信息查看 https://uniapp.dcloud.io/component/navigation-bar。|
|`<page-meta $1>,	<navigation-bar $2 />,</page-meta>$0`|`page-meta,<page-meta>`|页面属性配置节点，用于指定页面的一些属性、监听页面事件。只能是页面内第一个组件。更多信息查看 https://uniapp.dcloud.io/component/page-meta。|
|`<open-data type="$1" />$0`|`open-data,<open-data>`|用于展示平台开放的数据。更多信息查看 https://uniapp.dcloud.io/component/open-data。|


## CSS

|API|Prefix|Description|
|-|-|-|
|`APP-PLUS`|platform-app,platform-app-plus,app,app-plus|APP 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`APP-NVUE`|platform-app-nvue,platform-app-plus-nvue,app-nvue,app-plus-nvue|APP-NVUE 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`H5`|platform-h5,h5|H5 对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-WEIXIN`|platform-mp-weixin,platform-weixin,platform-mp-wechat,platform-wechat,mp-weixin,weixin,mp-wechat,wechat|微信小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-ALIPAY`|platform-mp-alipay,platform-alipay,platform-mp-ali,platform-ali,mp-alipay,alipay,mp-ali,ali|支付宝小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-BAIDU`|platform-mp-baidu,platform-baidu,mp-baidu,baidu|百度小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-TOUTIAO`|platform-mp-toutiao,platform-toutiao,platform-mp-bytedance,platform-bytedance,mp-toutiao,toutiao,mp-bytedance,bytedance|字节跳动小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-QQ`|platform-mp-qq,platform-qq,mp-qq,qq|QQ 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP-360`|platform-mp-360,platform-360,mp-360,360|360 小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`MP`|platform-mp,mp|小程序对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW`|platform-quickapp,platform-quickapp-webview,quickapp,quickapp-webview|快应用通用对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-UNION`|platform-quickapp-union,platform-quickapp-webview-union,quickapp-union,quickapp-webview-union|快应用联盟对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`QUICKAPP-WEBVIEW-HUAWEI`|platform-quickapp-huawei,platform-quickapp-webview-huawei,quickapp-huawei,quickapp-webview-huawei|快应用华为对应的 %PLATFORM 值。更多信息查看 https://uniapp.dcloud.io/platform。|
|`/* #ifdef $1 */,$2,/* #endif */`|#ifdef,ifdef|条件编译，处理某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`/* #ifndef $1 */,$2,/* #endif */`|#ifndef,ifndef|条件编译，排除某平台。更多信息查看 https://uniapp.dcloud.io/platform。|
|`/* #endif */`|#endif,endif|结束条件编译。更多信息查看 https://uniapp.dcloud.io/platform。|
|`var(--status-bar-height)`|--status-bar-height,var(--status-bar-height)|系统状态栏高度变量。更多信息查看 https://uniapp.dcloud.io/frame?id=css%e5%8f%98%e9%87%8f。|
|`var(--window-top)`|--window-top,var(--window-top)|内容区域距离顶部的距离变量。更多信息查看 https://uniapp.dcloud.io/frame?id=css%e5%8f%98%e9%87%8f。|
|`var(--window-bottom)`|--window-bottom,var(--window-bottom)|内容区域距离底部的距离变量。更多信息查看 https://uniapp.dcloud.io/frame?id=css%e5%8f%98%e9%87%8f。|

