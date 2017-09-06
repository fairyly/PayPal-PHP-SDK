# REST API SDK for PHP

![Home Image](https://raw.githubusercontent.com/wiki/paypal/PayPal-PHP-SDK/images/homepage.jpg)

[![Build Status](https://travis-ci.org/paypal/PayPal-PHP-SDK.svg?branch=master)](https://travis-ci.org/paypal/PayPal-PHP-SDK)
[![Coverage Status](https://coveralls.io/repos/paypal/PayPal-PHP-SDK/badge.svg?branch=master)](https://coveralls.io/r/paypal/PayPal-PHP-SDK?branch=master)

__Welcome to PayPal PHP SDK__. This repository contains PayPal's PHP SDK and samples for REST API.

## Please Note
> **The Payment Card Industry (PCI) Council has [mandated](https://blog.pcisecuritystandards.org/migrating-from-ssl-and-early-tls) that early versions of TLS be retired from service.  All organizations that handle credit card information are required to comply with this standard. As part of this obligation, PayPal is updating its services to require TLS 1.2 for all HTTPS connections. At this time, PayPal will also require HTTP/1.1 for all connections. [Click here](https://github.com/paypal/tls-update) for more information**

> **Connections to the sandbox environment use only TLS 1.2.**

## SDK Documentation

[Our PayPal-PHP-SDK Page](http://paypal.github.io/PayPal-PHP-SDK/) includes all the documentation related to PHP SDK. Everything from SDK Wiki, to Sample Codes, to Releases. Here are few quick links to get you there faster.

* [PayPal-PHP-SDK Home Page](https://paypal.github.io/PayPal-PHP-SDK/)
* [Wiki](https://github.com/paypal/PayPal-PHP-SDK/wiki)
* [Samples](https://paypal.github.io/PayPal-PHP-SDK/sample/)
* [Installation](https://github.com/paypal/PayPal-PHP-SDK/wiki/Installation)
* [Make your First SDK Call](https://github.com/paypal/PayPal-PHP-SDK/wiki/Making-First-Call)
* [PayPal Developer Docs](https://developer.paypal.com/docs/)

## Latest Updates

- SDK now allows injecting your logger implementation. Please read [documentation](https://github.com/paypal/PayPal-PHP-SDK/wiki/Custom-Logger) for more details.
- If you are running into SSL Connect Error talking to sandbox or live, please update your SDK to latest version or, follow instructions as shown [here](https://github.com/paypal/PayPal-PHP-SDK/issues/474)
- Checkout the latest 1.0.0 release. Here are all the [breaking Changes in v1.0.0](https://github.com/paypal/PayPal-PHP-SDK/wiki/Breaking-Changes---1.0.0) if you are migrating from older versions.
- Now we have a [Github Page](https://paypal.github.io/PayPal-PHP-SDK/), that helps you find all helpful resources building applications using PayPal-PHP-SDK.


## Prerequisites

   - PHP 5.3 or above
   - [curl](https://secure.php.net/manual/en/book.curl.php), [json](https://secure.php.net/manual/en/book.json.php) & [openssl](https://secure.php.net/manual/en/book.openssl.php) extensions must be enabled


## Direct Credit Card Support
[Braintree Direct](https://www.braintreepayments.com/products/braintree-direct) is PayPal's preferred integration solution for accepting direct credit card payments in your mobile app or website. Braintree, a PayPal service, is the easiest way to accept credit cards, PayPal, and many other payment methods.


## License

Read [License](LICENSE) for more licensing information.

## Contributing

Read [here](CONTRIBUTING.md) for more information.

## More help
   * [Going Live](https://github.com/paypal/PayPal-PHP-SDK/wiki/Going-Live)
   * [PayPal-PHP-SDK Home Page](http://paypal.github.io/PayPal-PHP-SDK/)
   * [SDK Documentation](https://github.com/paypal/PayPal-PHP-SDK/wiki)
   * [Sample Source Code](http://paypal.github.io/PayPal-PHP-SDK/sample/)
   * [API Reference](https://developer.paypal.com/webapps/developer/docs/api/)
   * [Reporting Issues / Feature Requests](https://github.com/paypal/PayPal-PHP-SDK/issues)
   * [Pizza App Using Paypal REST API](https://github.com/paypal/rest-api-sample-app-php)
   
   
   
   
-------------------------------------------


# new add(自己新加部分)

* [下载phpSDK](https://github.com/paypal/PayPal-PHP-SDK/releases)
* [PHP SDK HOME PAGE](https://paypal.github.io/PayPal-PHP-SDK/)
* [Sample Source Codes代码](http://paypal.github.io/PayPal-PHP-SDK/sample/)
* [PayPal-PHP-SDK（V1.7.4）支付接口实现](http://blog.csdn.net/alexander_phper/article/details/52057524)

* paypal支付接口准备工作

  - 首先去申请一个paypal账号，https://www.paypal.com/。
  - 申请完毕并登录，进入https://developer.paypal.com/developer/accounts/。即可看到你申请账号自动配属的两个测试账号，账号类别分别是：BUSINESS和     PERSONAL，PERSONAL的账号里面有$9999，测试费用，表激动。
  - 下面去给两个账号设置密码，点击账号展开，然后点击Profile，会弹出账号信息框，里面可以设置密码等一堆属性。如果点击账号始终无法展开，请吐槽下           paypal，然后F5再点。
  - 下面进入https://developer.paypal.com/developer/applications/申请APP，点击REST API apps栏目下面的Create App按钮，写进一个APP名称，然后选择     一个测试账户作为此APP绑定的账号，如果你在上一步没有申请新的测试账号，那么这里默认就是选择了BUSINESS账号。
  - 然后打开创建的APP，可以看到APP的clientId和clientSecret。
    paypal的测试环境域名为sandbox.paypal.com，正式域名为www.paypal.com。一下测试均为测试环境。
  - 至此准备工作差不多了，开始动代码。

## 接入步骤

* [1.安装 PHPSDK](https://github.com/paypal/PayPal-PHP-SDK/wiki)
  - Using Composer  OR Using Direct Download
* [2.Making First Call](https://github.com/paypal/PayPal-PHP-SDK/wiki/Making-First-Call)
* [3.Adding Configurations](https://github.com/paypal/PayPal-PHP-SDK/wiki/Adding-Configurations)
* [4.run Samples](https://github.com/paypal/PayPal-PHP-SDK/wiki/Samples)
