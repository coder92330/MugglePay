简体中文 | [English](/README.md)

<p align="center">
  <a href=" https://www.mugglepay.com">
    <img src="https://dcdn.mugglepay.com/dt/pay/logo/mplogo1.png" />
  </a>
</p>

# MugglePay

<img src="http://dcdn.mugglepay.com/pay/media/git/git-license.png" height="20px" /></a>
<img src="http://dcdn.mugglepay.com/pay/media/git/git-build.png" height="20px" /></a>
<img src="http://dcdn.mugglepay.com/pay/media/git/git-codecov.png" height="20px" /></a>
<img src="http://dcdn.mugglepay.com/pay/media/git/git-build.png" height="20px" /></a>

让数字货币支付更简单

## MugglePay商户平台
MugglePay是为有在线收款需求的商家提供的数字货币解决方案。将MugglePay SDK集成到您的网站/App即可享受安全高效的数字货币收款。

### 特点
 - 支持多种主流数字货币：BTC、BTC（Lightning Network）、ETH、USDT、BCH、LTC、EOS
 - 五分钟完成对接
 - 手续费低至0%

<p align="center">
<img src="https://dcdn.mugglepay.com/pay/media/git/cryptos.png" width="250px"/>
</p>

### 产品介绍

 - [MugglePay主页介绍, 让数字货币支付更简单](https://www.mugglepay.com)
 - [麻瓜宝钱包](https://wallet.mugglepay.com)
 - [商户平台](https://merchants.mugglepay.com)

### 支持更多币种
我们随时接纳更多的币种，如果你想让你所支持的币种在数千个商家中能购买商品或服务，欢迎联系我们。

### 成为麻瓜
麻瓜团队是个去中心化的开放团队，我们随时欢迎更多的麻瓜加入我们一起创造魔法。

1. 开发者

2. 捐赠者

我们不接受纯的志愿者和捐赠者，成为麻瓜后每个成员都可以获得分红。


## 支持平台

涵盖主流电商平台。5分钟内开启数字货币收款。

### Shopify

<a href="https://medium.com/@mugglepay/mugglepay-crypto-payment-plugin-launches-on-shopify-6904f3c3eca">
<img src="https://dcdn.mugglepay.com/pay/media/git/shopify.png" height="50px" style="padding-right: 50px;"/>  
</a>

中国电商品牌出海优选SaaS平台，全球175个国家100万商家信赖_一站式体验_完善生态系统_集云端建站,库存管理,多渠道销售于一体。

<a href="https://cdn.maguapay.com/pdf/MugglePay%20setup%20guide%20for%20Shopify.pdf">
Tutorial
</a>

### WHMCS

<a href="https://github.com/bitpaydev/bitpayxForWHMCS">
<img src="https://dcdn.mugglepay.com/pay/media/git/whmcs.png" height="50px" style="padding-right: 50px;"/>
</a>

WHMCS是一套国外流行的域名主机管理软件，跟国内众所周知的IDCSystem一样，主要在用户管理、财务管理、域名接口、服务器管理面板接口等方面设计的非常人性化。WHMCS是一套全面支持域名注册管理解析，主机开通管理，VPS开通管理和服务器管理。

### WHMCS8

<a href="https://github.com/MugglePay/MugglePayForWHMCS8">
WHMCS8 Tutorial
</a>

### V2Board

<a href="https://github.com/v2board/v2board">
<img src="https://camo.githubusercontent.com/15b835c7ce768a70a7a3c6d9505f895293e92692/68747470733a2f2f757365722d676f6c642d63646e2e786974752e696f2f323031392f31312f31382f313665376631633339623539653532623f773d35303026683d35303026663d706e6726733d3835303535" height="50px" style="padding-right: 50px;"/>
</a>

### SSPanel

<a href="https://github.com/bitpaydev/bitpayx/tree/master/bitpayx">
<img src="https://dcdn.mugglepay.com/pay/media/git/sspanel.png" height="50px" style="padding-right: 50px;"/>
</a>

### 风铃发卡
<a href="https://github.com/Tai7sy/card-gateway/tree/master/Pay/MugglePay">
风铃发卡
</a>,发卡程序，界面 UI 非常美观，致力于便捷、绿色、安全、快速的销售和购买体验。

### ZFAKA发卡系统  
<a href="https://github.com/huangfengye/MugglepayForZfaka">
<img src="https://github.com/zlkbdotnet/zfaka/blob/master/public/favicon.ico" height="50px" style="padding-right: 50px;"/> <br>
ZFAKA发卡系统
</a>,发卡程序，界面 UI 非常美观，致力于便捷、绿色、安全、快速的销售和购买体验。



## 安装流程
1. 注册[MugglePay商家账户](https://merchants.mugglepay.com/user/register?ref=MP37E56967)：
2. 在开发者中心中获取私钥
3. 根据使用的不同面板进行对接


## 商户API文档

[查看更多API简介](/API/Readme-CN.md)
  - API概述
    - [马上开始](/API/faq/GetStarted.md)
    - [API概述](/API/faq/Overview.md)
    - [订单状态](/API/basic/OrderStatus.md)
    - [错误码](/API/basic/ErrorCodes.md)
    - [接口认证](/API/basic/Authentication.md)
  - 支付API
    - [创建订单](/API/order/CreateOrder.md)
    - [支付回调(异步请求)](/API/order/PaymentCallback.md)
  - 内置API
    - [获取一个订单](/API/order/GetOrder.md)
    - [获取所有订单](/API/order/GetOrders.md)
    - [选择订单支付货币](/API/order/CheckoutOrder.md)
    - [取消订单](/API/order/CancelOrder.md)
    - [退款](/API/order/Refund.md)
  - FAQ
    - [用户FAQ](/API/faq/CustomerFAQ.md)
    - [商户FAQ](/API/faq/MerchantFAQ.md)


## 联系我们
 - [用户FAQ](/API/faq/CustomerFAQ.md)
 - [商户FAQ](/API/faq/MerchantFAQ.md)
 - 商户后台提交工单
 - business@mugglepay.com

## License
[BSD](https://www.wikiwand.com/en/BSD_licenses)
[LICENSE](/LICENSE)
Copyright (c) 2018-present, Muggles Foundation All rights reserved.
