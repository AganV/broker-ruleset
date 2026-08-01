# Broker Ruleset

个人收集、整理与维护的 Surge 券商分流规则集。目前仅包含富途牛牛（Futubull / FTNN）。

**Surge**

```ini
DOMAIN,softwaredownload.futunn.com,DIRECT
RULE-SET,https://raw.githubusercontent.com/AganV/broker-ruleset/main/Futubull.list,[Replace with your policy]
```

富途软件更新下载域名优先直连，并应置于主分流规则之前。后续直连域名增多时再整理为独立规则集。

## 许可证

本项目采用 [MPL-2.0](https://www.mozilla.org/MPL/2.0/) 许可证发布，不提供任何担保。

本项目为非官方项目，与富途牛牛或富途控股没有关联。
