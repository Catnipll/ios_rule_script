# Global

## 前言

本项目的Global分流规则由爬虫程序自动维护。

定时爬取互联网上开源的Global分流规则，将其进行清洗、去重、合并、优化后，形成单一的分流规则文件，旨在解决引用大量外部规则造成规则重复的问题。



最后检查时间：2020-11-29 16:15:58。

## 规则统计

总计规则：785 条。

各类型规则统计：

| 类型 | 数量(条) |
| ---- | ---- |
| DOMAIN | 47 |
| DOMAIN-KEYWORD | 19 |
| DOMAIN-SUFFIX | 689 |
| IP-CIDR | 29 |
| PROCESS-NAME | 1 |
## 重复统计

Global分流规则，与本项目其他分流规则重复情况统计。

点击重复数量可以查看重复规则明细。

| 名称 | 数量 | 重复 | 重合度 |
| ---- | ---- | ---- | ------ |
|  [Adobe](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Adobe)    | 34   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Adobe.list)   |   2.94%  |
|  [Advertising](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Advertising)    | 93615   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Advertising.list)   |   0.01%  |
|  [AdvertisingTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AdvertisingTest)    | 109941   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/AdvertisingTest.list)   |   0.00%  |
|  [AdvertisingLite](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AdvertisingLite)    | 41534   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/AdvertisingLite.list)   |   0.00%  |
|  [AppStore](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AppStore)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/AppStore.list)   |   100.00%  |
|  [Apple](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Apple)    | 162   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Apple.list)   |   0.62%  |
|  [AppleBlock](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/AppleBlock)    | 6   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/AppleBlock.list)   |   100.00%  |
|  [Bahamut](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Bahamut)    | 4   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Bahamut.list)   |   100.00%  |
|  [BlackList](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/BlackList)    | 779   | [235](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/BlackList.list)   |   30.17%  |
|  [China](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/China)    | 579   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/China.list)   |   0.52%  |
|  [ChinaTest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/ChinaTest)    | 73332   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/ChinaTest.list)   |   0.01%  |
|  [Discord](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Discord)    | 6   | [3](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Discord.list)   |   50.00%  |
|  [Dubox](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Dubox)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Dubox.list)   |   100.00%  |
|  [Facebook](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Facebook)    | 25   | [25](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Facebook.list)   |   100.00%  |
|  [PayPal](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/PayPal)    | 4   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/PayPal.list)   |   50.00%  |
|  [Steam](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Steam)    | 16   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Steam.list)   |   6.25%  |
|  [Game](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Game)    | 28   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Game.list)   |   14.29%  |
|  [Google](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Google)    | 120   | [56](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Google.list)   |   46.67%  |
|  [YouTube](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/YouTube)    | 9   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/YouTube.list)   |   55.56%  |
|  [Microsoft](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Microsoft)    | 97   | [9](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Microsoft.list)   |   9.28%  |
|  [Niconico](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Niconico)    | 4   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Niconico.list)   |   100.00%  |
|  [Speedtest](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Speedtest)    | 4   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Speedtest.list)   |   25.00%  |
|  [Telegram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Telegram)    | 17   | [13](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Telegram.list)   |   76.47%  |
|  [Netflix](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Netflix)    | 39   | [27](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Netflix.list)   |   69.23%  |
|  [Disney](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Disney)    | 5   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Disney.list)   |   80.00%  |
|  [GlobalMedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/GlobalMedia)    | 233   | [135](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/GlobalMedia.list)   |   57.94%  |
|  [Github](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Github)    | 6   | [4](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Github.list)   |   66.67%  |
|  [Spotify](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spotify)    | 7   | [6](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Spotify.list)   |   85.71%  |
|  [Spark](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Spark)    | 4   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Spark.list)   |   50.00%  |
|  [TestFlight](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/TestFlight)    | 3   | [1](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/TestFlight.list)   |   33.33%  |
|  [Twitter](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Twitter)    | 11   | [10](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Twitter.list)   |   90.91%  |
|  [Proxy](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Proxy)    | 6093   | [514](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Proxy.list)   |   8.44%  |
|  [Instagram](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Instagram)    | 2   | [2](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Instagram.list)   |   100.00%  |
|  [Wikipedia](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Wikipedia)    | 12   | [5](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/Clash/Global/Repeat/Wikipedia.list)   |   41.67%  |
## 配置说明

实时版：爬虫程序定时更新，更新频率高，能尽快同步数据源变化

稳定版：不定时手动更新，更新频率低，稳定性好

### Clash 
实时版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rule/Clash/Global/Global.yaml

稳定版：

https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/release/rule/Clash/Global/Global.yaml

## 数据来源

本项目的Global分流规则的数据来自以下链接，通常已涵盖所有数据来源的分流规则。如果你正在使用这些分流规则，建议不要与本项目的Global分流规则混合使用，以免造成规则重复。

- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/ConnersHua/Profiles/master/Surge/Ruleset/GlobalMedia.list
- https://raw.githubusercontent.com/DivineEngine/Profiles/master/Surge/Ruleset/Global.list
- https://raw.githubusercontent.com/eHpo1/Rules/master/Surge4/Ruleset/Global.list


感谢以上分流规则作者的辛勤付出（排名不分先后）。

如果您有更好的分流规则，欢迎提交给我，我会将它加到数据源中继续完善。

## 最后

### 正则过滤

爬虫程序在清洗原始规则数据时，可根据正则定向过滤规则，以达到保留特定规则的目的。经过正则过滤的规则，无法100%涵盖原始规则数据，请知悉。

### 正则校验

从2020年11月25日开始，爬虫程序加入对正则合法性的校验。对于无法校验通过，且不明作用的正则，直接抛弃。如果对比数据源发现正则类型的规则较少，则很大可能是错误的正则都已被过滤掉。

### 黑名单

爬虫程序内置部分规则黑名单，在对原始数据进行清洗时，自动将可能引起异常的黑名单规则去除。经过黑名单去除的规则，无法100%涵盖原始规则数据，请知悉。

### 完善规则

如果您：

1. 有更优的原始规则数据
2. 有更多的黑名单规则数据
3. 有更好的优化建议
4. 在使用分流规则时出现异常
5. 有其他问题

欢迎通过[issues](https://github.com/blackmatrix7/ios_rule_script/issues/new)提交反馈，共同完善本项目的Global分流规则。

感谢

[@fiiir](https://github.com/fiiir) [@Tartarus2014](https://github.com/Tartarus2014) [@zjcfynn](https://github.com/zjcfynn) 

提供规则数据源及改进建议

### 其他问题

爬虫开发的初衷是为满足自己几方面需求：

1. 去除混用多个去广告规则造成的重复
2. 去除多个去广告规则中某些规则
3. 多个分流规则间重复情况检查
4. 定时同步数据源更新

本项目的分流规则还是以自用为主，请不要对外宣传此分流规则。所以，还是请低调使用吧。