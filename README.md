# ECNU_captcha
[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)

这是一个油猴脚本，支持ECNU数据库网站的自动打码登录，开放自定义参数

目前实现的功能如下：
1. ECNU数据库网站验证码云端识别
2. 自动输入云端获取到的验证码
3. 自动点击登录按钮

## 内容列表

- [安全性](#安全性)
- [背景](#背景)
- [安装](#安装)
- [使用说明](#使用说明)
- [注意事项](#注意事项)
- [维护者](#维护者)
- [如何贡献](#如何贡献)
	- [贡献者](#贡献者)
- [使用许可](#使用许可)

## 安全性
此脚本完全开源，只会将验证码上传到服务器，不会上传任何用户信息

## 背景
我校登录平台中的验证码过于简单，既然要当懒狗，那就贯彻到底

## 安装
1. 前往Chrome应用商店下载[Tampermonkey（油猴脚本）](https://chrome.google.com/webstore/search/tampermonkey "Tampermonkey（油猴脚本）")
2. 前往[Greasy Fork - ECNU数据库自动登录](https://greasyfork.org/zh-CN/scripts/401381-ecnu%E6%95%B0%E6%8D%AE%E5%BA%93%E8%87%AA%E5%8A%A8%E7%99%BB%E5%BD%95 "Greasy Fork - ECNU数据库自动登录")，选择安装此脚本

## 使用说明
你可以选择即安即用，也可以选择相关的设置
1. 进入Tampermonkey（油猴脚本）管理面板中本脚本的编辑界面
2. 修改参数，time：点击登录的延时，captcha_url：验证码识别接口

## 注意事项
- 脚本输入的验证码和页面中验证码不一致是正常现象！
- 请不要恶意攻击默认的识别接口！被我逮住之后妹你好果汁吃嗷

## 维护者
告白于荆州（CiaranZhou）

## 如何贡献
如果你对本项目感兴趣，并且熟悉JavaScript语言 or PyTorch库那么你可以通过我在github或者博客中留的联系方式联系我。只要你做出任何有利贡献都将会被列入下方的贡献者名单中！

### 贡献者

感谢以下参与项目的人：

## 使用许可
[MIT](LICENSE) © Ciaran Zhou
