---
title: Shadowrocket常见问题 - 疑难解答与技术支持
description: 全面解答Shadowrocket使用过程中的常见问题，包括连接故障、配置问题和性能优化等方面的技术支持。
head:
  - - link
    - rel: canonical
      href: https://shadowrocket.uk/faq.html
---

# 常见问题

## 基础问题

### Shadowrocket是什么？

[Shadowrocket](/)（小火箭）是一款运行在iOS平台上的轻量级网络工具，支持多种协议，能够帮助用户更好地访问互联网资源。它以简洁的界面、稳定的性能和丰富的功能而受到用户欢迎。

### Shadowrocket支持哪些设备？

Shadowrocket仅支持iOS设备，包括iPhone、iPad和iPod touch。**目前不支持Android、Windows或macOS系统。** 电脑端建议使用[Clash Verge](https://clash-verge-rev.org)或者[Mihomo Party](https://mihomo.bid)



### Shadowrocket需要付费吗？

是的，Shadowrocket是一款付费应用，目前在App Store的价格为2.99美元（价格可能因地区和时间而变动）。这是一次性付费，购买后可在同一Apple ID下的所有设备上使用，无需额外订阅。

## 下载安装

### 为什么在App Store搜索不到Shadowrocket？

由于App Store区域限制，中国大陆地区的App Store无法搜索到Shadowrocket。您需要使用非中国大陆地区的Apple ID（如美国、香港等地区）才能下载。

### 如何创建非中国大陆地区的Apple ID？

创建非中国大陆地区的Apple ID的步骤：

1. 打开App Store，点击右上角的头像
2. 滚动到底部，点击退出当前账号
3. 点击任意免费应用的「获取」按钮
4. 选择「创建新的Apple ID」
5. 按照提示填写信息，选择目标地区（如美国）
6. 完成验证步骤后即可使用新账号

::: warning 注意
如果注册不成功或者怕麻烦，也可以使用共享ID或者购买小火箭成品ID。

以下是公益共享 Apple ID 网站推荐：
    
  -   [https://idshare001.me/applego.html](https://idshare001.me/applego.html)
  -   [https://id001.me/applego.html](https://id001.me/applego.html)

-   如共享账号无法使用，建议自行购买外区带有 Shadowrocket 的账号，**以后可以永久使用**。
    
    推荐商家：
    
  -   [水果商店](https://applego.idbb.me)


- [苹果账号正确登录AppStore下载App教程](https://wiki.applego.win/posts/苹果账号正确登录AppStore下载App教程.html)
:::

### 购买后无法下载怎么办？

如果已购买但无法下载，请尝试以下方法：

1. 检查网络连接是否稳定
2. 确认Apple ID余额是否充足
3. 重启设备后再次尝试
4. 联系Apple支持获取帮助

## 使用配置

### 首次使用如何配置？

首次使用Shadowrocket需要添加服务器信息：

1. 获取有效的服务器订阅链接或节点信息
2. 打开Shadowrocket，点击右上角「+」按钮
3. 选择添加服务器或订阅
4. 填写相关信息并保存
5. 选择服务器并点击连接开关

详细步骤请参考[使用教程](/tutorial.html)。

### 如何更新订阅？

更新订阅的步骤：

1. 打开Shadowrocket应用
2. 在首页点击右上角的「更新」按钮
3. 等待更新完成，服务器列表将显示最新节点

### 如何切换节点？

在Shadowrocket首页的服务器列表中，点击任意服务器即可选中并切换到该节点。确保顶部的连接开关处于开启状态。

## 连接问题

### 连接失败怎么办？

连接失败的常见解决方法：

1. 检查网络连接是否正常
2. 确认服务器信息是否正确
3. 尝试切换其他服务器
4. 更新订阅获取最新服务器列表
5. 重启Shadowrocket应用和设备
6. 检查VPN权限是否已授予

### 连接后无法上网怎么办？

连接成功但无法上网的解决方法：

1. 检查全局路由模式是否正确设置
2. 确认规则配置是否有误
3. 尝试切换到「全局代理」模式测试
4. 检查DNS设置是否正确
5. 尝试使用其他节点

### 为什么连接速度很慢？

连接速度慢的可能原因和解决方法：

1. 服务器负载过高：尝试切换到其他节点
2. 距离过远：选择地理位置较近的节点
3. 网络拥塞：在非高峰时段使用
4. 带宽限制：检查您的套餐是否有速度限制
5. 本地网络问题：测试您的基础网络速度

## 高级设置

### 如何设置规则分流？

设置规则分流的步骤：

1. 点击底部菜单栏中的「配置」
2. 选择当前使用的配置文件
3. 点击「规则」选项
4. 点击右上角「+」添加新规则
5. 选择规则类型并填写内容
6. 设置相应的策略（代理、直连等）
7. 保存设置

### 如何使用本地DNS？

设置本地DNS的步骤：

1. 点击底部菜单栏中的「设置」
2. 选择「DNS」选项
3. 开启「本地DNS映射」
4. 添加域名和对应的IP地址
5. 保存设置

### 如何备份和恢复配置？

备份配置的步骤：

1. 点击底部菜单栏中的「配置」
2. 长按需要备份的配置文件
3. 选择「导出」选项
4. 选择保存方式（iCloud、文件等）

恢复配置的步骤：

1. 点击底部菜单栏中的「配置」
2. 点击右上角「+」按钮
3. 选择「从文件导入」
4. 选择之前备份的配置文件

## 故障排除

### 应用闪退怎么办？

应用闪退的解决方法：

1. 强制关闭应用后重新打开
2. 重启设备
3. 检查iOS系统是否需要更新
4. 卸载并重新安装应用（注意备份配置）
5. 联系开发者报告问题

### 特定网站无法访问怎么办？

特定网站无法访问的解决方法：

1. 检查规则设置是否正确
2. 尝试切换全局路由模式
3. 添加或修改特定网站的规则
4. 清除浏览器缓存和Cookie
5. 尝试使用其他节点

### VPN权限被拒绝怎么办？

VPN权限被拒绝的解决方法：

1. 打开设备「设置」
2. 点击「通用」>「VPN与设备管理」
3. 找到Shadowrocket相关配置
4. 重新授予VPN权限
5. 如果仍然无法解决，尝试重启设备

## 其他问题

### Shadowrocket和其他同类工具有什么区别？

Shadowrocket与其他同类工具的主要区别：

1. **轻量级**：占用资源少，运行流畅
2. **多协议支持**：支持多种主流协议
3. **规则系统**：强大的分流规则系统
4. **脚本支持**：可运行自定义脚本
5. **价格合理**：一次性付费，无需订阅

### 如何获取技术支持？

获取技术支持的渠道：

1. 查阅本网站的[使用教程](/tutorial.html)
2. 在社交媒体或技术论坛寻求帮助
3. 联系您的服务提供商获取支持
4. 参考Shadowrocket的官方文档

### 使用Shadowrocket是否安全？

Shadowrocket本身是安全的应用，但安全性还取决于：

1. 您的服务提供商的安全措施
2. 您的使用习惯和网络环境
3. 是否及时更新应用到最新版本
4. 是否从官方渠道下载应用

为确保安全，建议仅从App Store下载应用，选择可信的服务提供商，并定期更新应用。

如果您的问题在此页面未得到解答，请参考我们的[使用教程](/tutorial.html)获取更多信息，或联系您的服务提供商获取专业支持。

::: tip 🎉 节点推荐
- 🚀 [Cyberguard: 解锁Netflix/Hbo/Disney+/Dazn等流媒体,18.00元/月](https://www.cyberguard.best/#/register?code=XsreC0T5)<br>
- 🚀 [优信云：IEPL/IPLC 高速专线，￥15.00/月](https://www.优信云.com/#/register?code=JRtE5uIV)<br>
- 🚀 [尔湾云：最大峰值1000Mbps，全流媒体及ChatGPT解锁！最低12元/月](https://erwan6.net/auth/register?code=BoObCd)<br>
- 🚀 [TNTCloud：新开机场，季付30，每月低至￥10.00/月](https://haibing822.tntvipaff.cc/#/register?code=GtjJVgml)<br>
- 🚀 [魔戒：不限时，不限制使用人数，直至套餐流量用完，低至￥14.9/130G流量](https://mojie.app/#/register?code=sSdtPtLo)<br>
- 🚀 [宝可梦星云：新用户首单：9折优惠码：9999，低至5.9/月 ](https://love.52pokemon.cc/register?code=56ERkkxp)<br>
- 🚀 [NanoCloud: 绑定TG机器人每天领取免费流量，月付最低1元/月](https://edu.uodoo.bid/auth/register?code=JMiOQDHf)<br>
- [肥猫云：全专线中转隧道，高速大宽带不限设备数，低至6元/月（年付）](https://fchb1188.fcvipaff.cc/register?aff=X1vZd2wf)<br>
- [疾风云：包年 6.9折 优惠码: jf2025](https://homes.tr25.cn?code=ReCm)<br>
- [闪狐云：不限速，不限设备。高速专线。20元/月](https://inv02.ffaff.cc/register?aff=WQApz2pv)
:::