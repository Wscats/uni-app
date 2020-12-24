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
