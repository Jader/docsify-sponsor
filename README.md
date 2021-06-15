# docsify-sponsor

<p align="center">
  <img src="https://docsify.js.org/_media/icon.svg" />
  <br />
  <code>docsify-sponsor</code>
</p>

[![jsdelivr](https://data.jsdelivr.com/v1/package/npm/docsify-sponsor/badge)](https://www.jsdelivr.com/package/npm/docsify-sponsor)
[![](https://img.shields.io/npm/v/docsify-sponsor.svg)](https://www.npmjs.com/package/docsify-sponsor)
[![](https://img.shields.io/npm/l/docsify-sponsor)](https://github.com/JaderH/docsify-sponsor/blob/master/LICENSE)

>docsify的赞助插件 Sponsor plugin for docsify

本项目参考自 [sponsor-page](https://github.com/Kaiyuan/sponsor-page)

## 使用 Usage

1. 插入样式 Insert the style

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify-sponsor@latest/dist/sponsor.min.css" />
```

2. 插入脚本 Insert the script

```html
<script src="//cdn.jsdelivr.net/npm/docsify-sponsor@latest/dist/sponsor.min.js"></script>
```

3. 添加配置 Add settings

```js
window.$docsify = {
    sponsor: {
        github: '',
        alipay_donate_qrcode: "",
        alipay_donate_link: "",
        wechat_donate_qrcode: "",
    }
}
```
## 配置说明 Configuration description

| 属性名 Attribute | 类型 Type | 解释 Description | 默认值 Defaults |
| --------------- | -------- | --------------- | ----------- |
| github | string | GitHub 链接地址 GitHub link address  | https://github.com/Jader |
| alipay_donate_qrcode | string | 支付宝二维码图片地址 Alipay two-dimensional code picture address | https://cdn.jsdelivr.net/gh/Jader/Jader.github.io@master/assets/AliPayQR.png |
| alipay_donate_link | string | 支付宝二维码链接地址 Alipay QR code link address | https://qr.alipay.com/fkx14579f8hzpauqxrteze9 |
| wechat_donate_qrcode | string | 微信二维码图片地址 WeChat QR code picture address | https://cdn.jsdelivr.net/gh/Jader/Jader.github.io@master/assets/WeChanSQ.png |