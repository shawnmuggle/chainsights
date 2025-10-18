# 主要稳定币计划 (2023-2025)

> [稳定币与C2B支付概述](../Overview-ZH.md) 系列文章

## 引言

2023 到 2025 年之间,稳定币支付圈子几乎每季度都有新动作:大型金融科技、加密巨头轮番上线自己的打法,力求把稳定币送进主流支付场景。稳定币也因此从交易员的工具箱,升级成包含专用链、商户集成、机构流程的一整套基础设施。

下面挑出六个影响力最大的平台计划,看看它们是怎样改写消费者和企业的稳定币体验。

---

## 1. PayPal USD (PYUSD): 主流整合

### 推出与结构

2023年8月,PayPal通过推出由Paxos Trust发行的美元稳定币**PYUSD**而成为头条新闻。[^1][^2]

**关键特征:**
- 完全由美元存款和美国国债1:1支持
- 作为ERC-20代币(以太坊区块链)发行
- 可通过Paxos 1:1赎回为美元
- 定期由第三方认证储备
- 整合到PayPal和Venmo平台

### 平台整合

PayPal将PYUSD深度整合到其现有支付生态系统:

**消费者功能:**
- 在PayPal应用内购买、出售和持有PYUSD
- 向其他PayPal/Venmo用户发送点对点(P2P)转账
- 通过PayPal结账在数百万在线商户处资助购买
- PYUSD与其他加密货币之间的无缝转换
- 在Venmo上可用,扩大到年轻人群[^3]

**商户优势:**
- 通过现有PayPal集成接受PYUSD
- 以PYUSD即时结算或自动转换为美元
- 现有PayPal商户无需额外集成
- 与传统支付方式相比费用降低
- 访问加密货币原生客户群

### 战略意义

PayPal 下场这件事,让主流商业对稳定币的接受度直接上了新台阶。4 亿多用户、数百万家商户的体量,不是纯加密项目能轻易复制的分发能力。

**PayPal 怎么看这件事:**
> "我们认为稳定币是数字商务的自然演变,提供了一种既是数字原生又易于连接到法币的稳定工具。"[^4]

### 最新进展 (2025)

- 与 Coinbase 合作,降低费用、增强流动性
- 支持扩展到以太坊之外的链
- 接上部分 DeFi 协议,让持有者可以赚取收益
- 期间发生的误铸事件也提醒大家:中心化管控仍在,再保险丝一样关键[^5]

---

## 2. Stripe的双轨策略:集成 + Tempo区块链

Stripe 走的是双线推进的路线:一边帮商户直接用稳定币收款,另一边干脆自己搭一条专为支付设计的链。

### 轨道1:商户集成 (2024-2025)

**Shopify合作:**

2025年中期,Stripe与Shopify合作,使**34个国家**的数百万商户能够从客户那里接受USDC支付。[^6]

**工作原理:**
1. 购物者使用加密钱包支付USDC(最初是Coinbase的Base网络)
2. Stripe自动处理所有加密到法币的转换
3. 商户以本地法定货币收到资金到银行账户
4. 或者,商户可以选择保留USDC

**关键创新:**
商户无需更改现有结账流程或持有加密货币——Stripe抽象了所有复杂性。[^7][^8]

**附加功能:**
- **经常性稳定币支付**:订阅和SaaS可以像信用卡一样以USDC计费[^9]
- **全球覆盖**:进入银行访问受限或货币不稳定的市场
- **更低费用**:绕过传统卡网络费用
- **即时结算**:T+0而不是T+2或更长时间

### 轨道2: Tempo区块链 (2025)

Stripe与加密风投公司Paradigm合作,推出了**Tempo**——一个专为大批量稳定币支付而构建的新Layer-1区块链。[^10][^11]

**为什么需要新区块链?**

Stripe CEO 直接指出,稳定币交易量上来以后,不少现有公链在真实支付场景下都显得"不中用"。[^12]

**Tempo设计原则:**

**1. 高吞吐量、低成本架构**
- 亚秒级最终性
- 每秒数千笔交易
- 极低费用(几美分)
- 为支付模式而非通用计算优化

**2. 多稳定币原生Gas**
- 接受USDC、USDT和其他稳定币作为交易费用
- 无需单独的波动性代币
- 用户以他们交易的相同货币支付费用
- 技术上具有挑战性,但显著改善用户体验[^13][^14]

**3. 支付特定原语**
- 内置条件支付
- 计划/经常性支付支持
- 多方交易原语
- 协议级开发者友好支付API[^15]

**4. 企业级合作伙伴**
Tempo 背后的支持阵容也很豪华:
- **AI**: OpenAI、Anthropic
- **电商**: Shopify、Coupang
- **金融**: Visa、渣打
- 他们的角色是把真实支付需求带进设计过程[^16]

### Stripe的开放发行平台

除了接受稳定币外,Stripe还推出了"**开放发行**"——使企业能够创建自己的稳定币以:
- 从客户存款中获取利息
- 构建品牌忠诚度计划
- 创建闭环支付生态系统
- 向客户分配国债收益[^17][^18]

这与 Stripe 想象的"代理"式 AI 商务场景相呼应:自主系统随时代用户出手交易。

---

## 3. Coinbase x402协议: HTTP原生支付

当别家忙着优化商户收款体验时,Coinbase 选择从更底层入手,尝试把支付直接写进互联网协议里。

### x402标准

Coinbase共同创建了**x402**,复兴了互联网长期保留的**HTTP 402 "需要付款"**状态码作为使用稳定币进行无缝微支付的工具。[^19][^20]

**工作原理:**

传统流程:
```
客户端 → 服务器: GET /premium-article
服务器 → 客户端: 403 禁止访问 (付费墙)
[用户必须手动导航到支付页面,输入卡号等]
```

x402流程:
```
客户端 → 服务器: GET /premium-article
服务器 → 客户端: 402 需要付款
  价格: 0.05 USDC
  支付地址: 0x...
客户端 → 区块链: [自动支付]
客户端 → 服务器: GET /premium-article (附带支付证明)
服务器 → 客户端: 200 OK [文章内容]
```

### 用例

**1. API微支付**
- 按API调用付费而非月度订阅
- 基于支付的自动速率限制
- 无需预付承诺或账户设置

**2. 内容付费墙**
- 支付$0.10阅读文章
- 无需订阅
- 微支付后即时访问

**3. AI代理交易**
该协议特别预见**AI代理自主支付服务**:[^21]

- AI代理需要来自API的数据
- 遇到402需要付款
- 自动以USDC支付请求金额
- 接收并处理数据
- 无需人工干预

### x402基金会 (2025)

Coinbase和合作伙伴(包括Cloudflare)成立了**x402基金会**,将此作为通过加密货币进行互联网微交易的通用标准推广。[^22]

通过使用稳定币(主要是USDC)进行这些支付,x402确保:
- 定价稳定且熟悉
- 全球兼容性无需货币转换
- 机器可读的支付请求
- 无需中介的即时结算

### 战略愿景

x402 把稳定币推向"互联网原生货币"的角色,兑现了 HTTP 402 微支付这个多年来只停留在设想里的功能。AI 代理愈发常见,标准化的机器到机器付费方式就成了必备基础设施。

---

## 4. Circle的Arc区块链:垂直整合

USDC 发行方 Circle 在 2025 年走出更激进的一步,自己做了一条专门服务稳定币金融的 Layer-1——Arc。

### 为什么Arc存在

在看到合作伙伴在未为支付设计的通用链上挣扎后,Circle识别了特定痛点:[^23][^24]

**现有链的问题:**
- 不可预测的交易费用
- 以波动的ETH/其他代币支付Gas
- 企业隐私限制
- 比卡网络更慢的最终性
- 复杂的多链部署

**Arc的解决方案:**
构建专为稳定币交易设计的区块链,考虑企业需求。

### Arc技术特性

**1. USDC作为原生Gas货币**
所有费用以USDC支付,提供可预测的法币计价成本。[^25]
- 无需持有ETH、SOL或其他波动性代币
- 企业可以以熟悉的美元术语预算费用
- 简化会计和对账

**2. 内置外汇引擎**
稳定币之间的24/7链上货币兑换。[^26]
- 转换USDC ↔ EURC ↔ 其他法币稳定币
- 即时、链上外汇
- 无需链下中介的竞争性汇率

**3. 即时最终性**
亚秒级结算,确定性最终性。[^27]
- 匹配或超过卡网络速度
- <1秒内不可逆确认
- 企业级可靠性

**4. 可选隐私**
交易详情可以保密。[^28][^29]
- 公开验证而不暴露金额
- 业务交易的企业隐私
- 合规兼容设计

**5. 完整Circle整合**
与Circle现有服务的原生集成:[^30]
- Circle Account API
- Circle Payments
- 多币种稳定币
- 合规和身份服务

### 战略定位

Circle 想走的是一条**垂直整合路线**:

1. **发行USDC**(稳定币)
2. **构建Arc**(为USDC优化的区块链)
3. **运营基础设施**(节点、验证者)
4. **提供服务**(API、钱包、合规)
5. **捕获价值**(费用、利息、服务)

全栈都握在自己手里,意味着:[^31]
- Arc 上的每笔交易都会带来 USDC 需求
- Circle 可以顺势卖更多增值服务
- 不用看第三方脸色,更新节奏更快
- 能对企业客户承诺 SLA 和支持

Circle 希望 Arc 变成**企业用稳定币时的高速主干网**,既能补位以太坊等公链的不足,也保留开放生态的灵活度。[^32][^33]

---

## 5. Tether的Plasma和Stable链:生态系统控制

USDT 发行方 Tether 则在 2025 年一次性亮出两条链: **Plasma** 和 **Stable**,目标是把自己的生态握得更紧。[^34]

### 战略动机

Tether认识到了一个巨大的错失机会:

**问题:**
- Tether的USDT每月促成超过**1万亿美元的交易**
- USDT在其他网络上运行(以太坊、Tron、Solana等)
- 网络运营商获取所有交易费用
- 仅Tron就从USDT转账中赚取数十亿Gas费[^35][^36]
- Tether尽管交易量巨大,却**零交易费用**收入[^37][^38]

**解决方案:**
构建专有区块链以捕获USDT交易的价值流。

### Plasma:零费用零售支付

**Plasma区块链**(与姊妹公司Bitfinex开发)专注于效率和可及性:[^39][^40]

**关键特性:**
- **零费用USDT转账**,针对零售支付量
- 高吞吐量架构,用于数百万小额交易
- 直接与Tron竞争(目前零售USDT占主导地位)
- 在代币销售中筹集了3.73亿美元(展示市场兴趣)[^41]

**目标市场:**
当前"将其收入的2-3%让给"卡处理商的商户——为他们提供零费用替代方案。

### Stable:主要结算层

**Stable**被设想为"USDT的专属家园",具有双链架构:[^42]
- **Stable**:用于安全和最终性的主要结算链
- **Plasma**:用于微交易的高速并行链

**技术架构:**

**1. 基于USDT的Gas系统**
USDT本身用于支付费用,因此用户无需单独代币。[^43]
- 降低采用摩擦
- 熟悉的计价
- 无波动性代币暴露

**2. 专门的USDT变体**
- **gasUSDT**:用于支付交易费用
- **USDT0**:用于跨链桥接
- **所有变体**:与标准USDT挂钩1:1并可免费互换[^44]

**3. StableBFT共识**
用于支付可靠性的Tendermint自定义高吞吐量变体。[^45]

### 闭环生态系统

Tether正在构建一个完整的USDT宇宙:

**消费者层:**
- **Plasma One**:数字银行/钱包应用
  - USDT存款>10% APY[^46][^47]
  - 支付4%现金返还
  - 集成借记卡

**商户层:**
- 零费用接受
- 即时结算
- 全球覆盖

**基础设施层:**
- Plasma(高速支付)
- Stable(结算)
- 桥接(跨链)

**结果:**使用USDT的每个方面(交易、桥接、费用)都在USDT生态系统内发生,内部捕获价值。

### 重大验证:PayPal合作

2025年末,**PayPal投资Stable网络**并安排PYUSD也在Stable上免Gas费支持。[^48]

这说明老牌金融科技也愿意押注这些新链,把稳定币支付往前再推一步。

---

## 6. 传统支付巨头: Visa & Mastercard

传统支付网络没有袖手旁观——他们正在将稳定币整合到现有基础设施中。

### Visa的稳定币结算

Visa在2023-2024年扩展了其**稳定币结算试点**:[^49][^50]

**工作原理:**
1. 商户接受传统卡支付
2. Visa与商户收单机构结算每日余额
3. 结算以USDC在以太坊或Solana上进行
4. **结果**:近乎即时的跨境结算而非数天

**合作伙伴:**
- Worldpay(商户收单机构)
- Nuvei(支付处理商)
- 多个国际市场

**优势:**
- 显著加快跨境结算
- 减少货币转换复杂性
- 为消费者保持熟悉的卡支付用户体验
- 将Visa定位为"链上法币结算网络"

### Mastercard的计划

Mastercard推出了帮助银行和金融科技整合稳定币的计划:[^51]
- 多链支持基础设施
- 跨境流程优化
- 基于稳定币的B2B支付
- 中央银行数字货币(CBDC)实验

### 商户兴趣:Amazon & Walmart

有报道称**Amazon和Walmart**正在研究稳定币作为支付选项,特别是为了降低卡费:[^52]

背景:
- Walmart每年处理约6000亿美元
- 按2%卡费计算,相当于120亿美元费用
- 即使节省0.5% = 每年30亿美元

来自零售巨头的这种商户兴趣水平验证了稳定币支付的商业案例。

---

## 跨计划主题

在所有这些计划中,出现了几个共同模式:

### 1. 专用基础设施
从通用区块链转向支付优化网络(Tempo、Arc、Stable/Plasma)。

### 2. Gas抽象
消除单独的Gas代币,转而使用稳定币作为原生费用(Arc、Tempo、Stable)。

### 3. 机构整合
主要企业(Visa、PayPal、Shopify)在加密和传统金融之间架桥。

### 4. 垂直整合
稳定币发行者构建自己的区块链以捕获更多价值(Circle、Tether)。

### 5. 开发者平台
不仅仅是支付,而是构建支付应用的平台(Stripe、Coinbase)。

### 6. 多币种支持
超越美元:欧元(EURC)、英镑、日元稳定币正在为全球商务出现。

---

## 结论:"稳定币战争"

行业分析师将这一竞争格局称为**"稳定币战争"**[^53][^54]——一场定义下一代支付轨道的竞赛。

每个主要计划都带来独特优势:
- **PayPal**:主流分销
- **Stripe/Tempo**:开发者平台
- **Coinbase/x402**:互联网原生标准
- **Circle/Arc**:企业基础设施
- **Tether/Stable**:零售覆盖 + 生态系统控制
- **Visa**:传统网络整合

与其出现赢家通吃的结果,我们更可能看到:
- 针对不同用例的**专门网络**
- 在链之间路由的**抽象层**
- 连接生态系统的**互操作性协议**
- 接受多种稳定币的**商户灵活性**

这些计划(2023-2025)的速度和规模表明,稳定币支付已经从实验性转变为基础设施级,拥有数十亿投资和与世界最大公司的合作伙伴关系。

---

## 继续阅读

- [← 上一篇:为什么选择稳定币进行C2B支付](./why-stablecoins-for-c2b-payments.md)
- [下一篇:稳定币支付架构 →](./stablecoin-payment-architecture.md)
- [返回概述](../Overview-ZH.md)

## 相关文章

- [稳定币抽象层](./stablecoin-abstraction-layer.md)
- [主要参与者的战略定位](./major-players-strategies.md)
- [实施路线图](./implementation-roadmap.md)

---

## 参考文献

[^1]: [PayPal Newsroom – PayPal Launches U.S. Dollar Stablecoin (PYUSD)](https://newsroom.paypal-corp.com/2023-08-07-PayPal-Launches-U-S-Dollar-Stablecoin)
[^2]: [Paxos Trust – PYUSD Technical Documentation](https://paxos.com/pyusd)
[^3]: [PayPal – Venmo PYUSD Integration Announcement](https://newsroom.paypal-corp.com/2023-10-venmo-adds-pyusd-support)
[^4]: [PayPal PYUSD Launch Statement](https://newsroom.paypal-corp.com/2023-08-pyusd-launch)
[^5]: [PayPal PYUSD incident – Mint/burn correction (2025)](https://newsroom.paypal-corp.com/2025-pyusd-incident-response)
[^6]: [Stripe Newsroom – Shopify Merchants to Accept USDC via Stripe](https://stripe.com/newsroom/news/shopify-usdc-payments)
[^7]: [Stripe Documentation – Crypto Payment Processing](https://docs.stripe.com/crypto)
[^8]: [Shopify – Stablecoin Payment Integration Guide](https://help.shopify.com/en/manual/payments/alternative-payment-methods/cryptocurrency)
[^9]: [Stripe – Recurring Stablecoin Payments](https://stripe.com/blog/recurring-stablecoin-payments)
[^10]: [Paradigm (Matt Huang) – Tempo: The Blockchain Designed for Payments](https://www.paradigm.xyz/2025/02/tempo-blockchain-for-payments)
[^11]: [Stripe – Tempo Blockchain Announcement](https://stripe.com/blog/tempo-blockchain-launch)
[^12]: [Stripe CEO on blockchain payment optimization](https://stripe.com/blog/blockchain-payment-optimization)
[^13]: [Tempo Technical Documentation – Multi-Stablecoin Gas](https://docs.tempo.org/gas-abstraction)
[^14]: [Technical challenges of multi-currency gas fees](https://www.paradigm.xyz/2025/multi-currency-gas-challenges)
[^15]: [Tempo Protocol – Payment Primitives](https://docs.tempo.org/payment-primitives)
[^16]: [Tempo Foundation – Partnership Announcements](https://tempo.org/partners)
[^17]: [Stripe – Open Issuance Platform](https://stripe.com/blog/open-issuance-platform)
[^18]: [Stablecoin issuance for enterprise use cases](https://stripe.com/blog/enterprise-stablecoin-issuance)
[^19]: [Cognitive Revolution Podcast – Coinbase's x402 Micropayments Protocol](https://www.cognitiverevolution.ai/coinbase-x402-protocol)
[^20]: [Coinbase – x402 Protocol Documentation](https://docs.cloud.coinbase.com/x402)
[^21]: [x402 Foundation – Use Cases for AI Agent Payments](https://x402.org/use-cases)
[^22]: [x402 Foundation Launch Announcement](https://x402.org/launch)
[^23]: [Circle – Arc Blockchain Launch Announcement](https://www.circle.com/blog/introducing-arc-blockchain)
[^24]: [Circle on limitations of existing blockchain infrastructure](https://www.circle.com/blog/blockchain-payment-limitations)
[^25]: [Circle Arc Documentation – USDC Gas Mechanism](https://developers.circle.com/arc/docs/usdc-gas)
[^26]: [Circle Arc – Built-in FX Engine Technical Details](https://developers.circle.com/arc/docs/fx-engine)
[^27]: [Arc finality and performance benchmarks](https://developers.circle.com/arc/docs/performance)
[^28]: [Circle Arc – Privacy Features Overview](https://developers.circle.com/arc/docs/privacy)
[^29]: [Enterprise privacy requirements for on-chain payments](https://www.circle.com/blog/enterprise-privacy-requirements)
[^30]: [Circle Arc – Enterprise Integration Guide](https://developers.circle.com/arc/docs/enterprise-guide)
[^31]: [Circle – Arc Vertical Integration Strategy](https://www.circle.com/blog/arc-integration-strategy)
[^32]: [Circle Arc positioning for enterprise adoption](https://www.circle.com/blog/arc-enterprise-positioning)
[^33]: [Arc vs. public chain comparison for payment use cases](https://messari.io/report/arc-vs-public-chains-comparison)
[^34]: [ChainCatcher – Next Battle of Stablecoins (Arc, Plasma, Stable, Tempo)](https://www.chaincatcher.com/en/article/2024/stablecoin-blockchain-wars)
[^35]: [Tether transaction volume analysis (2024-2025)](https://www.theblock.co/data/stablecoins/usdt-transaction-volume)
[^36]: [Tron gas fee revenue from USDT transactions](https://tronscan.org/#/data/stats/gas-fees)
[^37]: [Tether revenue model before Plasma/Stable](https://tether.io/investor-relations/revenue-model)
[^38]: [Opportunity cost analysis for Tether](https://messari.io/report/tether-opportunity-cost-analysis)
[^39]: [Tether – Plasma Blockchain Announcement](https://tether.io/news/plasma-blockchain-launch)
[^40]: [Bitfinex – Plasma Development Partnership](https://www.bitfinex.com/posts/plasma-partnership-tether)
[^41]: [Plasma token sale results and market reception](https://www.coindesk.com/markets/plasma-token-sale-results)
[^42]: [Tether Stable – Architecture Overview](https://tether.io/stable/architecture)
[^43]: [Tether Stable – Gas Fee Mechanism](https://tether.io/stable/gas-fees)
[^44]: [Tether – USDT Variants Documentation (gasUSDT, USDT0)](https://tether.io/developers/usdt-variants)
[^45]: [StableBFT consensus mechanism details](https://tether.io/stable/consensus)
[^46]: [O'Daily News – Stablecoin Chains (Plasma One, Stable Pay)](https://www.odaily.news/en/post/stablecoin-payment-chains-2025)
[^47]: [Plasma One – Digital Wallet Launch](https://plasma.one/wallet)
[^48]: [PayPal investment in Stable network announcement](https://newsroom.paypal-corp.com/stable-network-investment)
[^49]: [Visa News – Stablecoin Settlement Expansion](https://usa.visa.com/visa-everywhere/blog/expanding-stablecoin-settlement-capabilities.html)
[^50]: [Visa USDC settlement pilot results](https://usa.visa.com/visa-everywhere/blog/usdc-settlement-pilot-results.html)
[^51]: [Mastercard stablecoin integration initiatives](https://www.mastercard.com/news/perspectives/2025/stablecoin-integration)
[^52]: [Reports: Amazon and Walmart stablecoin exploration](https://www.reuters.com/technology/amazon-walmart-explore-stablecoin-payments)
[^53]: [Industry analysis – "Stablecoin Wars" competitive landscape](https://www.coindesk.com/business/stablecoin-wars-analysis)
[^54]: [ChainCatcher – Competitive Analysis of New Stablecoin Chains](https://www.chaincatcher.com/en/article/2025/stablecoin-chain-competition)

---

*Chainsights关于稳定币、支付和C2B商务的通讯系列文章*
