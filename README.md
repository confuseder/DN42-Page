# MMR’s DN42 Network

### 简介
  这是 DN42 AS 4242420839 的信息展示页面。

  欢迎您与我建立 Peer。

### 联系方式
  - **Telegram:** [@MMR_839](https://t.me/MMR_839)
  - **E-mail:** [g200803092018@gmail.com](g200803092018@gmail.com)
    
### 要求
  - 只接受使用 `Wireguard` 隧道的连接并启用 IP 地址限制。另外请在隧道中使用 `IPv6 Link-Local` 地址。
```
AllowedIPs = 172.20.0.0/14, 10.0.0.0/8, 172.31.0.0/16, fd00::/8, fe80::/64
```
  - 您的 AS 信息必须已经在 DN42 的 [Git 仓库](git.dn42.dev) 中注册并且被合并。
  - 您只能宣告属于您的 AS 的路由，另外，您**必须执行 ROA 检查**。[^1]
  - 长期不活动 | 无人管理 的连接会被删除并且可能不会得到通知。
  - 您应该和除我以外的其他网络建立 Peer，而不是单点连接。
  - 您应该尽可能地支持 `多协议 BGP` 和 `拓展的下一跳`.


[^1]: 参考[文档](https://wiki.dn42.us/howto/Bird#route-origin-authorization_roa-tables)中的方式。(针对 Bird / Bird2)
