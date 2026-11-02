# Loon 分流规则

- 订阅规则不绑定节点；在 Loon 添加远程规则集时自行选择节点/策略组。
- Bybit_Global.list：Bybit 国际版（包含社区整理的候选域名，不能保证全部仍为 App 所用）。
- Bybit_EU.list：Bybit EU。
- Bybit_All.list：两个 Bybit 版本的合并规则。
- Yahoo_Japan.list：Yahoo Japan 通用域名。
- Yahoo_Auctions_JP.list：Yahoo! 日本拍卖，部分共享 Yahoo 域名需要 Yahoo Japan 规则补充。
- 已包含的域名是初始覆盖，不代表全部 App 网络请求；建议在 Loon 日志中检查未命中的连接。

发布至公开 GitHub 仓库后，采用 https://raw.githubusercontent.com/<owner>/<repo>/<branch>/Loon/<filename> 格式订阅。
