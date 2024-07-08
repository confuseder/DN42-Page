# MMR’s DN42 Network

### 简介
  这是 DN42 AS 4242420839 的信息展示页面。

  欢迎您与我建立 Peer。

### 基础信息
- **ASN**: 4242420839
- **DN42 IPv4**: `172.23.161.0/27`
- **DN42 TPv6**: `fd84:f015:38ad::/48`

### 联系方式
  - **Telegram:** [@MMR_839](https://t.me/MMR_839)
  - **E-mail:** [me@mail.rakov.cc](me@rakov.cc)
    
### 要求
  - 只接受使用 `Wireguard` 隧道的连接并启用 IP 地址限制。另外请在隧道中使用 `IPv6 Link-Local` 地址。
```
AllowedIPs = 172.20.0.0/14, 10.0.0.0/8, 172.31.0.0/16, fd00::/8, fe80::/64
```
  - 您的 AS 信息必须已经在 DN42 的 [Git 仓库](git.dn42.dev) 中注册并且被合并。
  - 您只能宣告属于您的 AS 的路由，另外，您**必须执行 ROA 检查**。[^1]
  - 长期不活动或无人管理的连接会被删除并且可能不会得到通知。
  - 您应该和除我以外的其他网络建立 Peer，而不是单点连接。
  - 您应该尽可能地支持 `多协议 BGP` 和 `拓展的下一跳`.

### Looking Glass

[**Looking Glass**](https://lg-dn42.rakov.cc)

### 提交对等请求
```text
// Wireguard
Node = < US / CN >
Endpoint = <0.0.0.0:0>
Publickey = <xxxxxxxx>
IPv6 = <fe80::0000>
IPv4 = <none>
// BGP
Sessions: IPv6 or IPv4
ASN = <424242xxxx>
```
### 节点列表

> 仅有 CN 节点接受来自中国大陆的隧道连接
>
> CN 节点仅接受来自中国大陆的隧道连接

#### 1. 🇺🇸 US (RackNerd VPS, IPv4 Only) (Recommand)
  1. ##### Endpoint
     
     `us1.dn42.rakov.cc`
     
  4. ##### DN42 IP

     `172.23.161.3`
     
     `fd84:f015:38ad::3`
     
  6. ##### Public Key

     `nUYHVi/fEbAD/dbrsaTZx1AtPc3RaIhzpzITeNzaf1I=`

  7. ##### BandWidth
     
     `1G / 1G`

#### 1. 🇩🇪 DE (IPv6 Only)
  1. ##### Endpoint

     `de.dn42.rakov.cc`

  3. ##### DN42 IP

     `172.23.161.2`

     `fd84:f015:38ad::2`

  4. ##### Public Key

     `0F4hkpNefamtVi5O8kmYtH/QsTfWdJAfXbPuUR6HpWs=`

  5. ##### BandWidth

     `?`

#### 1. ~~🇨🇳 CN (家庭宽带, 活动IP地址, IPv4 Only)~~ (Don't Work Now)
  1. ##### Endpoint

     `cn.dn42.rakov.cc`
     
  3. ##### DN42 IP

     `172.23.161.1`
     
     `fd84:f015:38ad::1`
     
  5. ##### Public Key

     `nUYHVi/fEbAD/dbrsaTZx1AtPc3RaIhzpzITeNzaf1I=`

  6. ##### BandWidth
     `1G / 100M`

### 注释
[^1]: 参考[文档](https://wiki.dn42.us/howto/Bird#route-origin-authorization_roa-tables)中的方式。(针对 Bird / Bird2)
