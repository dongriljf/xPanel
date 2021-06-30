<img src="https://cdn.jsdelivr.net/npm/skx@0.1.3/img/uim-logo-round.png" alt="logo" width="130" height="130" align="left" />

<h1>xPanel</h1>

> Across the Great Wall we can reach every corner in the world

<br/>

[![License](https://img.shields.io/github/license/Anankke/SSPanel-Uim?style=flat-square)](https://github.com/xray-v2ray-ss/xPanel/blob/master/LICENSE)
![GitHub repo size](https://img.shields.io/github/repo-size/anankke/sspanel-uim?style=flat-square&color=328657)

演示站点(暂缺) | [使用文档](https://wiki.sspanel.host) | [更新日志](https://github.com/xray-v2ray-ss/xPanel/releases) | [配套SS/SSR后端](https://github.com/Anankke/shadowsocks-mod) | [Telegram 频道](https://t.me/XrayPanel) | [Telegram 交流群](https://t.me/xPanelChat) | [API 文档](https://marcosteam.gitbook.io/sspanel-api/)

## 简介

xPanel 是一款专为 Xray / Vless / xtls / V2Ray / vmess / Trojan / Shadowsocks(R) 设计的多用户管理面板，基于SSPanel-Uim开发。

节点地址写法，按照 [XrayR](https://github.com/XrayR-project/XrayR) 的推荐格式写。如果xtls有流控flow，则在最后增加: 
`|flow=flow-vlaue`  ,比如 ：
`xpanel.com;443;2;tcp;xtls;server=xpanel.com|host=xpanel.com|enable_vless=true|flow=xtls-rprx-direct` 

完全兼容SSPanel-Uim ，目前仅在 SSPanel-Uim  Mar 31, 2021 dev分支基础上增加了vless/xtls支持。

支持xtls、vless的免费开源后端推荐：[Air-Universe](https://github.com/crossfw/Air-Universe/) 、[XrayR](https://github.com/XrayR-project/XrayR)

## 给sspanel增加增加 Vless / xtls 支持
查看下面提交的代码变更记录，根据此记录修改你的sspanl即可。
请点此链接：
[给sspanel增加 Vless / xtls 支持1](https://github.com/xray-v2ray-ss/xPanel/commit/d874b56c758c931bc68f5867117c0f4c79e50ae2) 
或
[给sspanel增加 Vless / xtls 支持2](https://github.com/xray-v2ray-ss/xPanel/commit/04afae4de5858f96deed3f49b8a401d7c111d97e)

## 特性

- 集成支付宝当面付，PAYJS，码支付，Paymentwall等超过 8 种支付系统
- 重构面板首页、节点列表、商品列表；新增 SPA（Single Page Apps）版 UI
- 商品增加同时连接设备数，用户限速属性
- 新用户注册现金奖励、用户常规端口切换与指定
- 公共库文件加载使用 jsDelivr
- 支持  Xray / Vless / xtls / V2Ray / vmess / Trojan / Shadowsocks(R)
- 性能优化，程序逻辑改善，代码质量修正
- 更多新功能写不下了

## 安装

xPanel 的需要以下程序才能正常的安装和运行：

- Git
- MySQL
- PHP 7.2+
- Composer

xPanel 支持安装在 LNMP、宝塔面板、Plesk、Oneinstack 等集成环境中。安装教程请参阅 [文档](https://wiki.sspanel.host)。

## 演示

演示站(空缺) 每天更新 `dev` 分支最新源码。

```
账号：admin
密码：admin
mukey ShirakamiFubuki
```

## 文档

> 我们安装，我们更新，我们开发

[xPanel 的文档](https://wiki.sspanel.host)，在这里你可以找到大部分问题的解答。

## 贡献

[提出新想法 & 提交 Bug](https://github.com/xray-v2ray-ss/xPanel/issues/new) | [改善文档 & 投稿](https://github.com/xray-v2ray-ss/xPanel/Wiki) | [Fork & Pull Request](https://github.com/xray-v2ray-ss/xPanel/fork)

xPanel 欢迎各种贡献，包括但不限于改进，新功能，文档和代码改进，问题和错误报告。

## 协议

xPanel 使用 MIT License 开源、不提供任何担保。使用 xPanel 即表明，您知情并同意：

- 您在使用 xPanel 时，必须保留 Staff 页面（该页面包含了 MIT License）和页脚的 Staff 入口
- xPanel 不会对您的任何损失负责，包括但不限于服务中断、Kernel Panic、机器无法开机或正常使用、数据丢失或硬件损坏、原子弹爆炸、第三次世界大战、SCP 基金会无法阻止 SCP-3125 引发的全球 MK 级现实重构等。


## 鸣谢

### [贡献者](https://github.com/xray-v2ray-ss/xPanel/graphs/contributors)

xPanel 离不开所有 [贡献代码](https://github.com/xray-v2ray-ss/xPanel/graphs/contributors) 和提交 Issue 的人。

<details>
<summary>查看贡献者</summary>

[**xray-v2ray-ss**](https://github.com/xray-v2ray-ss)

- 面板现 **维护者**

[**Anankke**](https://github.com/Anankke) 、 [**dumplin**](https://github.com/dumplin233)

- 面板 **原作者**

- 码支付对接 + 码支付当面付二合一
- 邀请链接
- 商品增加限速和限制 ip 属性
- 多端口订阅

[**RinSAMA**](https://github.com/mxihan)

- 整理分类 config.php
- 美观性调整

[**miku**](https://github.com/xcxnig)

- 美观和性能优化

[**Tony Zou**](https://github.com/ZJY2003)

- 为公告增加群发邮件功能
- 节点负载情况显示&用户账户过期在首页弹窗提醒
- 增加返利列表

[**Indexyz**](https://github.com/Indexyz)

- 为面板增加 V2Ray 功能

[**NeverBehave**](https://github.com/NeverBehave)

- 添加 Telegram OAuth

[**CGDF**](https://github.com/TheCGDF)

- 用户列表分页加载

[**laurieryayoi**](https://github.com/laurieryayoi)

- 重做美化UI（~~援交~~圆角化）
- 重写节点列表，支持分级显示所有级别节点

[**Sukka**](https://github.com/SukkaW)

- 单元测试
- 全站 JavaScript 重写
- 新版 Wiki 的搭建和维护

[**GeekQu**](https://github.com/GeekQu)

- 面板 Bug 修复与维护

[**M1Screw**](https://github.com/M1Screw)

- Wiki 维护与重写部分安装教程
- 面板 Bug 修复与维护
- 前端公共库版本更新

</details>

## 捐赠

您对我们的帮助将是支持我们做下去的动力。您可以直接进行捐赠，也可以在购买部分产品或向他人推荐产品时从我们的返利链接购买。

#### xray-v2ray-ss

- xray-v2ray-ss 创建xPanel，增加支持vless/xtls支持。
- [机场主必买的服务器](https://nbhosts.com/aff.php?aff=151)

#### Anankke

- [Anankke 很可爱请给 Anankke 钱](https://t.me/anankke/7)

#### dumplin

- [码支付-微信收款功能开通](https://codepay.fateqq.com/i/39756)

#### galaxychuck

- [moecloud-美國VPS](https://lite.moe/aff.php?aff=56)

#### laurieryayoi

- [dmit-美国香港服务器](https://www.dmit.io/aff.php?aff=912)

