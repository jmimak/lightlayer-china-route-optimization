# lightlayer 三网优化到底优化在哪：洛杉矶、台湾、香港、新加坡的回程路由差在哪？$24.99 年付该选哪个机房？（附全套餐价格表）

LightLayer 的三网优化按机房分成四套走法：洛杉矶优化款回程三网全部强制走移动 CMIN2（AS58807），台湾走电信 CN2/CTGNet、联通 4837、移动 CMI，新加坡电信双程 CN2、联通直连，香港虽然标着优化线路，IP 却不是原生。年付 $24.99 这一档四个机房同价，带宽却从 5Mbps 到 20Mbps 不等。

所以选机房比选配置重要。下面把每条回程的实测路由拆开，再对一遍价格和限制，最后给按场景的选择规则。

## 选购速览

> **多数人的答案**：主要给国内用户访问、预算压在 $24.99/年，选洛杉矶 LA-VP01-A（20Mbps 不限流量、回程全 CMIN2）或台湾 TW-VP01-A（5Mbps 不限）。需要离大陆最近的节点、能接受非原生 IP，选香港 HK-VP02-A（10Mbps 不限，$24.99/年）。要跑国际流量、不在乎回国延迟，看洛杉矶 1Gbps 年付款，国际线路 $29.99/年。
>
> 👉 [查看 LightLayer 年付 $24.99 套餐与当前库存](https://account.lightlayer.net/?affid=74)

## 全套餐对比

### 年付 $24.99 特价档

这一档统一是 1 核 1GB 内存、50GB 硬盘、$24.99/年，差别全在带宽、流量和线路。硬盘类型按机房不同：洛杉矶用 NVMe，台湾是 SSD。

| 机房·方案 | 配置 | 带宽/流量 | 线路 | 年付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| 洛杉矶 LA-VP01-A | 1核/1G/50G | 20Mbps 不限 | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=217) |
| 洛杉矶 LA-VP03-A | 1核/1G/50G | 30Mbps / 1TB | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=218) |
| 洛杉矶 LA-VS01-A | 1核/1G/50G | 50Mbps 不限 | Standard | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=219) |
| 洛杉矶 LA-VS03-A | 1核/1G/50G | 100Mbps / 1TB | Standard | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=220) |
| 洛杉矶 LA-VG01-A | 1核/1G/50G | 100Mbps 不限 | Global | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=221) |
| 洛杉矶 LA-VG03-A | 1核/1G/50G | 200Mbps / 1TB | Global | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=222) |
| 台湾 TW-VP01-A | 1核/1G/50G | 5Mbps 不限 | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=213) |
| 台湾 TW-VP03-A | 1核/1G/50G | 10Mbps / 1TB | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=214) |
| 台湾 TW-VG01-A | 1核/1G/50G | 10Mbps 不限 | Global | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=215) |
| 台湾 TW-VG03-A | 1核/1G/50G | 20Mbps / 1TB | Global | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=216) |
| 香港 HK-VP02-A | 1核/1G/50G | 10Mbps 不限 | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=463) |
| 新加坡 SG-VP02-A | 1核/1G/50G | 10Mbps 不限 | Premium | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=364) |
| 新加坡 SG-VG02-A | 1核/1G/50G | 20Mbps 不限 | Global | $24.99 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=365) |

新加坡两个年付款在部分时段会显示售罄，下单前看一眼库存状态。

### 月付常规套餐

月付适合先试一个月再决定要不要上年付，也适合配置需求超过 1 核 1G 的场景。

| 机房·方案 | 配置 | 带宽/流量 | 线路 | 月付 | 购买 |
| --- | --- | --- | --- | --- | --- |
| 洛杉矶 LA-VP01 | 1核/1G/50G NVMe | 20Mbps 不限 | Premium | $4 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=51) |
| 香港 HK-VP01 | 1核/1G/50G | 10Mbps 不限 | Premium | $5 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=236) |
| 香港 Global 款 | 1核/1G/50G | 20Mbps 不限 | Global | $5 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=440) |
| 新加坡 Premium 款 | 1核/1G/50G | 10Mbps 不限 | Premium | $7 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=330) |
| 菲律宾 Premium 款 | 1核/1G/50G | 10Mbps 不限 | Premium | $7 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=52) |
| 台湾 Premium 款 | 1核/1G/50G | 10Mbps 不限 | Premium | $9 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=82) |
| 日本东京 Premium 款 | 1核/1G/50G | 10Mbps 不限 | Premium | $9 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=382) |
| 圣何塞 Premium 款 | 1核/1G/50G | 1Gbps / 1TB | Premium | $9.9 | [购买](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=316) |

洛杉矶还有 1Gbps 端口的年付款，国际线路 $29.99/年、标准线路 $39.99/年、优化线路 $49.99/年，都是 1 核 1G、50GB NVMe、1TB 流量。跑大文件传输或国际业务，这个档比 20Mbps 不限流量实用得多。

## 三网优化到底优化在哪

LightLayer 把网络分三档：Premium（优化）、Standard（标准）、Global（国际）。只有 Premium 是面向中国大陆做的回国优化，三档差价不小，下面说的全是 Premium 款。

### 洛杉矶：回程三网全部走移动 CMIN2

去程电信和联通走各自骨干到美国西海岸自有节点，再接 Cogent 进洛杉矶机房；移动直接 CMI 落地。

回程是三网全部强制走移动 CMIN2 / AS58807 回国，到国内再分别转电信 AS4134、联通 AS17816、移动 AS9808。

2024 年 5 月的一份测评用中国大陆和北美 435 个节点测，洛杉矶回国平均延迟约 170ms。这比原生 CN2 GIA 的洛杉矶机器慢 20ms 上下，好处是移动用户不吃亏。测试用的 30Mbps 优化套餐在国内三网测速基本跑满。

硬件是 AMD EPYC 7H12，NVMe 硬盘 IO 约 225MB/s，不支持 IPv6，IP 为美国原生。

### 台湾：电信 CN2、联通 4837、移动 CMI

去程上海电信走 CN2 经香港到台湾，上海联通走 AS10099（CUG）经香港，上海移动走 CMIN2。

回程分三路：广州电信走 CN2 / CTGNet 经香港直连回国；广州联通同样经香港 CTGNet 到广州再转联通 4837；广州移动走 CMI 经香港直连。

2026 年 10 月的一份测评里，三网平均延迟 71ms，最快的广东广州联通 25ms。这个数字比洛杉矶好看得多，代价是带宽只有 5Mbps 或 10Mbps。

测试机型是 E5-2630 v4，GB5 单核 577、多核 565，UnixBench 单核 730.8。10Mbps 套餐实测大陆三网多线程下载最高 9.71Mbps、上传 12.22Mbps，带宽吃得很干净。

IP 不是台湾原生，测试显示归属地对不上。

### 新加坡：电信双程 CN2，联通直连，移动去程 CMIN2 回程借道 CN2

电信去程 CN2 直达新加坡，回程先连电信香港 CN2 节点（AS4809）再走 CTG/CN2 回国。

联通去程直连（AS4837 + AS10099），回程直连香港 AS10099 后走 4837 回国。

移动去程 CMIN2 直达，回程借道电信香港 CN2 回国，走的是电信高端链路。

硬件是 E5-2678v3，IO 约 221MB/s，官方对硬盘 IO 有限制，属于防滥用的常规做法。不支持 IPv6。IP 非新加坡原生，测试显示为捷克原生 IP，解锁流媒体的能力反而比香港、台湾好。

### 香港：标着优化线路，但 IP 不是原生

香港的公开资料只到「优化线路、10Mbps 不限流量、$5/月起」，没有完整的三网回程 traceroute。能确认的是 IP 不是原生，解锁 Netflix、Disney+ 这类服务可能受限。

香港的价值在物理距离，华南访问的下限比美西低。如果你的用途是建站、API、远程办公，不需要流媒体解锁，它是四个机房里延迟最占优的选择。

👉 [用 $24.99 年付开通洛杉矶 LA-VP01-A（20Mbps 不限、回程全 CMIN2）](https://account.lightlayer.net/?cmd=cart&action=add&affid=74&id=217)

## 年付到底省多少，以及省下来的代价

拿两个最常见的选择算一下。

洛杉矶 20Mbps 优化款月付 $4，一年 $48。年付 $24.99，折合每月 $2.08，省 48%。

香港 10Mbps 优化款月付 $5，一年 $60。年付 $24.99，折合每月 $2.08，省 58%。

省下来的钱换来两个约束。

**特价年付一般不支持升降级。** 买的时候是 1 核 1G，后来发现要跑 WordPress 或者数据库，只能重新买一台，原来那台的钱不退。所以预算不紧的话，先用月付 $4 或 $5 跑两周，确认性能扛得住再转年付。

**不限流量套餐只能升带宽，限流量套餐只能升流量、不能升带宽。** 这条规则很容易踩。洛杉矶 LA-VP01-A 是 20Mbps 不限流量，之后嫌慢只能加钱升带宽；LA-VP03-A 是 30Mbps / 1TB，之后流量不够只能加流量，带宽锁死在 30Mbps。

台湾那两个同价 SKU 也值得算一笔。5Mbps 不限流量满载一个月约 1.6TB；10Mbps / 1TB 按满载算大概 9 天就把 1TB 用完。长期挂下载或者做代理，5Mbps 不限更保险；建站、跑 API 这种流量零星、但希望单次响应快一点的，10Mbps / 1TB 体验更好。

## 当前能用的优惠

2026 年 11 月 11 日下午开始的双十一活动，限量供应，续费同价，季付、半年付、年付都可以叠加，每个客户每个产品限购 2 台：

- 圣何塞云机 1核 1G / 50G SSD / 1Gbps 优化 / 1TB 流量，原价 $9.9，特价 **$4.95**，优惠码 `SJCLOUD50`，限量 50 台
- 新加坡云机 1核 1G / 50G SSD / 10Mbps 优化，原价 $7，特价 **$3.5**，优惠码 `SGCLOUD50`，限量 50 台
- 香港独服 Gold 6138 20 核 / 32G / 1T SSD / 2 IP，原价 $120，特价 **$84**，优惠码 `HKGOLD30`，限量 20 台
- 洛杉矶独服 E5-2660 8 核 / 8G / 1T HDD / 2 IP，原价 $80，特价 **$40**，优惠码 `LAE52660`，限量 30 台

限量的意思是卖完就恢复原价，下单时以结账页是否接受优惠码为准。另外超过 1 小时未支付的订单会被取消，别先下单再慢慢付款。

## 不适合谁，以及几个必须先知道的限制

**要原生 IP 解锁流媒体，别选香港和台湾。** 洛杉矶是四家里唯一确认原生 IP 的机房；新加坡虽然不是本地原生，但测试显示是捷克原生 IP，解锁能力不错。香港明确不是原生，台湾测试下来 Netflix 只有 Originals、Disney+ 直接不可用。

**没有明确退款政策。** 官方没有公开的退款条款，买之前先用月付试一个月，是唯一稳妥的做法。

**不支持 IPv6。** 洛杉矶和新加坡的测评都显示没有 IPv6 地址，如果你的业务依赖 IPv6 只能另找。

**客服是工单制，主要英文，没有 7×24 在线。** 响应通常几个小时，简单问题能解决，复杂故障别指望实时。

**装 Windows 需要至少 2GB 内存。** 1G 的年付款装不了，要上 Windows 就得从 2G 起配，年付 $24.99 这一档直接排除。

**大型生产环境不合适。** 这是轻量级云的定位，没有明确的 SLA 承诺，1 核 1G 跑个人站和测试环境没问题，高并发业务应该另找。

## 常见问题

**三网优化是走 CN2 还是 CMIN2？**
看机房。洛杉矶回程三网全部走 CMIN2 / AS58807；台湾电信走 CN2 / CTGNet、联通走 4837、移动走 CMI；新加坡电信双程 CN2、联通直连、移动去程 CMIN2 回程借道 CN2。同一个品牌名下的「三网优化」，路由完全不是一回事。

**香港和台湾哪个延迟低？**
台湾有公开实测数据，三网平均 71ms，广东联通 25ms。香港没有完整的三网回程测试公开，物理距离更近，但具体数字没有可靠来源，别拿别人的估算当结论。如果延迟是唯一指标，台湾的 71ms 是能查证的。

**$24.99 年付够不够建站？**
静态站、小型博客、API 服务够用。跑 WordPress 建议 2G 内存起，1G 会频繁吃 swap。另外年付款不支持升降级，配置估低了只能重买。

**支持支付宝吗？**
支持 PayPal 和支付宝。信用卡没有可靠来源确认，别默认能刷。

**能不能中途升级配置？**
弹性云服务器可以升级 CPU、内存、硬盘、带宽，降级要联系客服。特价年付套餐一般不支持升降级。

## 按场景给出最终选择

只需要一个便宜的国内访问节点、流量用得不多 → 洛杉矶 LA-VP01-A，$24.99/年，20Mbps 不限流量，回程全 CMIN2，是国内三网都不吃亏的选择。

更在意延迟、能接受 5Mbps 或 10Mbps → 台湾 TW-VP01-A 或 TW-VP03-A，$24.99/年，三网平均 71ms 是四家里唯一有实测数字的。

要离大陆最近、不需要流媒体解锁 → 香港 HK-VP02-A，$24.99/年，10Mbps 不限流量，注意 IP 非原生。

要跑国际流量、回国延迟无所谓 → 洛杉矶 1Gbps 年付款，国际线路 $29.99/年，1TB 流量比 20Mbps 不限流量能扛。

需要原生 IP 做流媒体相关 → 只考虑洛杉矶，或者新加坡（显示捷克原生 IP）。

下单前确认三件事：目标机房当前是否有库存（新加坡年付款时不时售罄）、优惠码在结账页是否被接受、以及你选的这个 SKU 之后能不能升级。这三点都比省几美元影响大。

👉 [进 LightLayer 核对各机房当前价格与库存](https://account.lightlayer.net/?affid=74)
