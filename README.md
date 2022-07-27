# flipCountdown 翻页倒计时

基于 uni-app 的翻页倒计时

## 项目截图

![](https://img-cdn-aliyun.dcloud.net.cn/stream/plugin_screens/a80ff700-0d4b-11ed-b2b6-27f45db02c97_0.png?image_process=quality,q_70/format,webp&v=1658886156)


## 使用方法

```
<flip-countdown deadline="2022-08-16 12:00:00"></flip-countdown>
```

```
import FlipCountdown from "@/components/FlipCountdown/FlipCountdown.vue"
```

```
components:{
			FlipCountdown
		},
```

## props

| 参数 | 说明 |类型 |示例 |
| ---- | ---- | ---- | ---- |
| deadline    | 结束时间    |String |2022-08-16 12:00:00 |


## 平台兼容

| Vue2 | Vue3 |
| ---- | ---- |
| √    | ×    |

| App   | 快应用 | 微信小程序 | 支付宝小程序 | 百度小程序 | 字节小程序 | QQ 小程序 | 钉钉小程序 | 快手小程序 | 飞书小程序 | 京东小程序 |
| ----- | ------ | ---------- | ------------ | ---------- | ---------- | --------- | ---------- | ---------- | ---------- | ---------- |
| 3.4.0 | √      | √          | √            |            |            |           |            |            |            |

| H5-Safari | Android | Browser | 微信浏览器(Android) | QQ 浏览器(Android) | Chrome | IE  | Edge | Firefox | PC-Safari |
| --------- | ------- | ------- | ------------------- | ------------------ | ------ | --- | ---- | ------- | --------- |
| √         | √       | √       | √                   | √                  | √      | √   | √    | √       | √         |

## 插件地址

[uni-app插件市场](https://ext.dcloud.net.cn/plugin?id=8913)

## 版本

### 1.0.0

首次上线
