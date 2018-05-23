# 面对面翻译小程序


面对面翻译小程序是微信团队针对中英文面对面沟通的场景开发的流式语音翻译小程序，基于微信同声传译插件封装实现，提供了中英文语音识别，文本翻译等功能。



## 预览
![面对面翻译小程序](image/qr.jpg)


## 下载与使用

1. 克隆代码
2. `project.config.json` 中的 `appid` 替换成在公众平台申请的项目 id
3. 在 `公众平台 → 设置 → 第三方服务 → 插件管理` 中 添加微信同声传译插件 (`wx069ba97219f66d99`)
4. 打开微信开发者工具中添加项目


## 微信版本要求

由于使用插件，需要 基础库版本 >= `1.9.6`


## 微信同声传译插件支持功能

- 语音识别 (目前支持 `zh_CN（中国大陆）`,  `en_US（英语）`)
- 文本翻译 (目前支持 `zh_CN（中国大陆）`,  `zh_TW（中国台湾）`, `zh_HK（中国香港）`, `en_US（英语）`)
- 语音合成 (目前支持 `zh_CN（中国大陆）`,  `zh_TW（中国台湾）`, `zh_HK（中国香港）`)


## License

[The MIT License](./LICENSE.txt)