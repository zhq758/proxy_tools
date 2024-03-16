# 介绍
* 自用Subconverter订阅转换配置文件，修改自原作者[ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)  
* 自用Loon配置文件和[插件仓库](https://github.com/mphin/ProxyTools/blob/main/loon/README.md)
* ACL4SSR规则为基础合并碎片补充剔除重复
* Adblack广告规则来源于[anti-AD](https://github.com/privacy-protection-tools/anti-AD) 修改Actions每天自动构建
* 规则数量: 8324条
* 最近更新: 2024年03月17日06:06:16
## Clash订阅转换远程配置:
```
https://raw.githubusercontent.com/mphin/ProxyTools/main/config/ACL4SSR_Online_Full_MultiMode_777.ini
```
## Loon:
* [插件收集仓库](https://github.com/mphin/ProxyTools/blob/main/loon/README.md)
* 配置文件
  -  [点击一键导入Loon](https://www.nsloon.com/openloon/import?sub=https://raw.githubusercontent.com/mphin/ProxyTools/main/config/Loon_config_mphin.conf)
  -  通过复制链接从URL下载:
    ```
    https://raw.githubusercontent.com/mphin/ProxyTools/main/config/Loon_config_mphin.conf
    ```
## 策略组内容及顺序
> 规则集非碎片化，建议添加所有规则集确保完整性，注意规则集优先级
- **🎯 全球直连**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/LocalAreaNetwork.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/LocalAreaNetwork.list)
- **🚫 广告拦截**：(⚠️低性能设备不建议添加)
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Adblack.txt](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Adblack.txt)
- **📢 谷歌服务**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Google.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Google.list)
- **🤖 AI｜奈飞**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/OpenaiNetflix.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/OpenaiNetflix.list)
- **🎥 国外媒体**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ProxyMedia.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ProxyMedia.list)
- **Ⓜ️ 微软服务**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Microsoft.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Microsoft.list)
- **🍎 苹果服务**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Apple.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Apple.list)
- **📺 国内媒体**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ChinaMedia.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ChinaMedia.list)
- **🎮 游戏平台**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/GamesPlatform.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/GamesPlatform.list)
- **📡 IP｜测速**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/IpinfoSpeedtest.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/IpinfoSpeedtest.list)
- **📲 电报消息**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Telegram.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/Telegram.list)
- **✈️ 国外常规**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ProxyGFWlist.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/ProxyGFWlist.list)
- **🎯 全球直连**：
  - [https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/GlobalDirect.list](https://raw.githubusercontent.com/mphin/ProxyTools/main/rules/GlobalDirect.list)
- **🎯 全球直连**：GEOIP,CN
- **🐟 漏网之鱼**：FINAL

## 致谢
- [@ACL4SSR/ACL4SSR](https://github.com/ACL4SSR/ACL4SSR)
- [@Loon0x00/LoonExampleConfig](https://github.com/Loon0x00/LoonExampleConfig)
- [@privacy-protection-tools/anti-AD](https://github.com/privacy-protection-tools/anti-AD)
## 项目 Star 数增长趋势
[![Stargazers over time](https://starchart.cc/mphin/ProxyTools.svg)](https://starchart.cc/mphin/ProxyTools)

**本仓库创建于2023年7月2日**
