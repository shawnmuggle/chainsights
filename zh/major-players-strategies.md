# 稳定币支付领域主要参与者的战略定位

> [稳定币与C2B支付概览](../Overview-ZH.md)系列文章

**最后更新:** 2025年10月

## 执行摘要

2025年的稳定币支付格局特点是主要技术和金融服务参与者之间的激烈竞争,每个参与者都在追求不同的战略方法,以在新兴的数字美元经济中获取价值。随着稳定币市值超过2750亿美元,2025年上半年交易量达到15.8万亿美元,[^1][^2]赌注是巨大的——在这个市场的定位可能决定哪些公司主导下一代支付基础设施。

本文分析七个主要参与者的战略定位: Stripe、Circle、Tether、Visa、PayPal、Coinbase和新兴挑战者。我们审视他们的不同方法——从Stripe的双轨商户和基础设施战略到Tether的闭环生态系统——评估他们的竞争优势和脆弱性,并预测竞争格局在未来24个月如何演变。

## 目录

1. [竞争格局](#competitive-landscape)
2. [Stripe: 双轨商户和基础设施战略](#stripe)
3. [Circle: 与Arc的垂直整合](#circle)
4. [Tether: 闭环USDT生态系统](#tether)
5. [Visa: 传统金融遇见链上结算](#visa)
6. [PayPal: 支付生态系统集成](#paypal)
7. [Coinbase: 互联网支付标准和基础设施](#coinbase)
8. [比较分析](#comparative-analysis)
9. [新兴挑战者](#emerging-challengers)
10. [战略展望和预测](#strategic-outlook)

---

## <a name="competitive-landscape"></a>竞争格局

### 市场结构

稳定币支付市场展现多边网络效应,具有不同的竞争层次:

**层级1: 稳定币发行**
- Circle(USDC): 370+亿美元市值
- Tether(USDT): 1200+亿美元市值
- PayPal(PYUSD): 6+亿美元市值
- 新兴发行人: MakerDAO(DAI)、Paxos、区域参与者

**层级2: 区块链基础设施**
- 通用链: Ethereum、Solana、Tron
- 支付优化链: Tempo(Stripe)、Arc(Circle)、Stable/Plasma(Tether)
- Layer-2扩展: Base(Coinbase)、Polygon、Arbitrum、Optimism

**层级3: 支付处理和商户服务**
- 进入加密的传统处理器: Stripe、PayPal、Visa
- 加密原生处理器: Coinbase Commerce、BitPay、Alchemy Pay
- 专业提供商: Wyre、MoonPay、Transak

**层级4: 消费者应用**
- 钱包: MetaMask、Coinbase Wallet、Rainbow、Ledger
- 支付应用: PayPal、Venmo、Cash App
- 嵌入式钱包: Privy、Magic、Web3Auth

### 战略定位模型

参与者使用根本不同的策略竞争:

**1. 垂直整合(Circle、Tether)**
- 控制发行人+区块链基础设施+分发
- 跨整个堆栈获取价值
- 更高的基础设施成本但更好的利润率
- 示例: Circle发行USDC,构建Arc区块链,运营支付服务

**2. 横向平台(Stripe、Visa)**
- 为多个发行人/链提供基础设施
- 多币、多链支持
- 通过商户采用的网络效应
- 示例: Stripe跨多条链接受USDC、USDT、PYUSD

**3. 生态系统锁定(PayPal)**
- 将稳定币集成到现有用户群
- 利用4亿+PayPal用户和商户关系
- 封闭生态系统内的专有稳定币(PYUSD)
- 示例: PYUSD在PayPal/Venmo内无缝工作但外部效用有限

**4. 基础设施游戏(Coinbase)**
- 提供基础协议和标准
- 开源、行业范围采用焦点
- 通过相邻服务盈利(交易所、托管、处理)
- 示例: x402协议对所有开放,Coinbase通过Commerce和交易所盈利

**5. 传统金融桥梁(Visa)**
- 利用现有支付网络和银行关系
- 向现有基础设施添加稳定币结算
- 定位为机构的受信任、受监管的入口
- 示例: Visa用USDC结算但维护卡网络接口

### 赢家通吃vs.多参与者均衡

**网络效应动态:**

**赢家通吃场景:**
- 商户采用(商户集成尽可能少的处理器)
- 消费者钱包(用户整合到1-2个主要钱包)
- 可能: 支付协议(单一标准胜出——像HTTP)

**多参与者均衡:**
- 稳定币发行(多个发行人共存服务不同需求)
- 区块链基础设施(不同链用于不同用例)
- 区域主导(不同地理位置不同赢家)

**当前轨迹**: 朝着多参与者均衡发展,每个类别都有主导领导者。尚无单一参与者在所有层级建立不可攻破的护城河。

---

## <a name="stripe"></a>Stripe: 双轨商户和基础设施战略

### 战略方法

Stripe追求并行策略: 通过现有Stripe基础设施使商户能够接受稳定币支付,同时构建Tempo——专为支付设计的全新区块链。[^3][^4]

**轨道1: 商户支付接受**

**启动**: 2025年年中,与Shopify合作[^5]
**能力**:
- 商户向现有Stripe集成添加稳定币接受
- 最初在Coinbase的Base网络上使用USDC
- 扩展到额外的稳定币和网络
- 结算灵活性: 立即法币转换或加密保留
- 统一仪表板: 加密支付与卡交易并列

**商户价值主张**:
- 最小集成努力(现有Stripe商户切换开关)
- 比卡更低的费用(0.5-1% vs. 2-3%典型卡费)
- 全球客户覆盖(接受来自无银行账户/银行服务不足者的支付)
- Stripe处理所有区块链复杂性
- 熟悉的对账和报告

**轨道2: Tempo区块链基础设施**

**公布**: 2025年,与Paradigm合作[^6][^7]
**架构**:
- 专为大量稳定币支付而构建的Layer-1区块链
- 多币Gas(USDC和USDT本地支付交易费)
- 亚秒级最终性实现即时支付确认
- 支付原语: 条件支付、计划支付、订阅逻辑内置于协议
- 高吞吐量: 为零售支付量设计

**合作伙伴生态系统**:
- **AI公司**: OpenAI、Anthropic(代理支付集成)
- **电子商务**: Shopify、Coupang(商户采用)
- **金融基础设施**: Visa、Standard Chartered(机构结算)

**战略理由**:

1. **竞争护城河**: 拥有Layer-1基础设施提供长期防御性
2. **垂直整合**: 从区块链到商户API控制完整堆栈
3. **创新速度**: 在协议级别构建支付功能(比适应现有链更快)
4. **经济获取**: 除商户处理外,在基础设施层赚取费用
5. **未来验证**: 通过合作伙伴和内置能力为AI/代理支付时代定位

### 竞争优势

**1. 商户分发**:
- 数百万现有Stripe商户
- 在线支付中的受信任品牌
- 简单集成路径(现有API)

**2. 开发者生态系统**:
- 一流的开发者体验
- 全面的文档和工具
- 大型开发者社区

**3. 监管合规**:
- 强大的金融科技合规基础设施
- 与全球监管机构的关系
- 应对复杂法规的记录

**4. 战略合作伙伴**:
- Shopify合作伙伴提供巨大的商户覆盖
- OpenAI/Anthropic合作伙伴为AI代理支付定位
- Visa/Standard Chartered带来机构信誉

### 脆弱性和风险

**1. 市场迟到**:
- 在Coinbase、PayPal、BitPay之后进入稳定币支付
- Tempo区块链启动进入竞争格局(Arc、Stable/Plasma已运营)
- 必须克服在位优势

**2. 多链复杂性**:
- 最初仅支持Base限制覆盖范围
- 构建Tempo创建两个并行策略(商户混淆风险)
- 随着生态系统分散需要跨链协调

**3. 发行人依赖**:
- 不发行自己的稳定币(依赖Circle、Tether等)
- 对稳定币经济学和政策的控制有限
- 如果发行人直接向商户提供服务,潜在的去中介化

**4. Tempo采用不确定性**:
- 推出新Layer-1极具挑战性
- 网络效应偏向现有链
- 开发者和用户采用不保证

### 战略展望

**最佳情况**: Stripe利用现有关系成为稳定币支付的主导商户处理器。Tempo获得吸引力作为特定支付链,特别是AI代理用例。Stripe在处理和基础设施层获取价值。

**适度情况**: Stripe成功将稳定币支付集成到商户平台,但Tempo面临缓慢采用。Stripe在多条链(包括Tempo)上作为处理器运营,而不实现区块链网络效应主导。

**最坏情况**: 商户在Stripe获得市场份额之前采用竞争解决方案(Coinbase、PayPal)。Tempo未能充分区分于现有链。Stripe成为加密支付的追随者而非领导者。

**概率评估**: 适度到最佳情况最可能。Stripe的商户关系和执行记录使其定位良好,但Tempo的成功仍不确定。

---

## <a name="circle"></a>Circle: 与Arc的垂直整合

### 战略方法

Circle的战略集中在垂直整合: 发行稳定币(USDC)、构建专用基础设施(Arc区块链)、提供企业支付服务——控制完整堆栈。[^8][^9]

**组件1: USDC发行**

**市场地位**:
- 370+亿美元市值(第二大稳定币)
- 美国和欧洲强劲采用
- 监管合规焦点(许可证、储备、透明度)
- 机构偏好(被认为比USDT更受监管)

**差异化**:
- 月度储备认证(vs. Tether的季度)
- 100%现金和短期美国国债(vs. Tether的更多样化储备)
- 上市公司(vs.私有Tether的透明度)
- 明确的监管参与(主要司法管辖区的许可证)

**组件2: Arc区块链**

**启动**: 2025年
**架构**:
- USDC作为原生Gas货币(消除单独的Gas代币)[^10]
- 内置外汇引擎用于24/7链上货币兑换[^11]
- 即时最终性(亚秒级结算)
- 可选隐私功能用于交易细节[^12]
- 企业级API和集成工具

**目标用例**:
- 跨境B2B支付
- 公司的财资管理
- 资本市场结算(代币化证券、债券)
- 大量商户支付接受

**组件3: 企业支付服务**

- 企业的Circle Account基础设施
- 开发者的支付API
- 托管和财资管理
- 法币入/出口服务
- 合规和风险管理工具

**战略理由**:

1. **控制**: 垂直整合防止去中介化(如果控制基础设施就不会被切断)
2. **利润率获取**: 在多个层级赚取(发行费、Gas费、处理费)
3. **USDC采用**: Arc设计用于最大化USDC效用,推动对Circle核心产品的需求
4. **企业焦点**: 针对愿意为合规和可靠性付费的高价值客户
5. **监管定位**: 严格控制使跨堆栈的监管合规成为可能

### 竞争优势

**1. USDC品牌和采用**:
- 具有强大网络效应的第二大稳定币
- 机构信任和偏好
- 与竞争对手相比的监管清晰度

**2. 监管合规**:
- 美国司法管辖区的持牌货币传输商
- 强大的合规基础设施
- 积极主动的监管参与
- 吸引风险规避企业

**3. 企业关系**:
- 与主要公司的现有关系
- 财资产品套件吸引CFO
- 与传统金融基础设施集成

**4. 技术控制**:
- 完整堆栈控制实现快速创新
- 可以专门为USDC优化Arc
- 不依赖外部区块链决策

### 脆弱性和风险

**1. 单稳定币焦点**:
- Arc为USDC优化;多币支持有限
- 如果USDT或其他稳定币保持主导地位,Arc可能被边缘化
- 商户通常想要多币接受(仅USDC限制)

**2. 网络效应挑战**:
- 推出新Layer-1区块链极其困难
- 开发者和用户集中在Ethereum、Solana、Tron
- 必须克服现有链上的巨大安装基础和流动性

**3. 发行人风险集中**:
- 单点故障: 如果USDC面临监管问题,整个策略面临风险
- 脱锚事件(2023年3月硅谷银行)展示脆弱性[^13]
- 监管变化可能破坏商业模式

**4. 企业销售周期**:
- 企业采用的长销售周期
- 零售/消费者市场不太可及(PayPal、Coinbase更强)
- 可能错过快速移动的消费者支付机会

**5. 来自平台无关处理器的竞争**:
- Stripe、Visa等跨多条链接受多种稳定币
- 商户可能更喜欢灵活性而非Circle集成但更窄的产品

### 战略展望

**最佳情况**: Arc成为企业支付和财资管理的首选区块链。USDC巩固作为机构稳定币标准的地位。Circle跨发行、基础设施和服务层获取显著价值。

**适度情况**: Arc在特定利基(B2B支付、资本市场)获得吸引力但未实现广泛采用。USDC保持强势地位但未取代USDT。Circle运营盈利但非主导业务。

**最坏情况**: Arc未能获得有意义的采用(现有链足够)。USDC失去市场份额给USDT或新兴竞争对手。Circle仅限于稳定币发行,面临商品化压力。

**概率评估**: 适度情况最可能。Circle的企业焦点和监管定位提供防御性,但Arc面临重大采用挑战。USDC可能保持强势地位而不实现USDT级别的主导。

---

## <a name="tether"></a>Tether: 闭环USDT生态系统

### 战略方法

Tether的战略围绕为USDT构建完整的闭环生态系统: 专用区块链(Plasma和Stable)、专门的USDT变体(gasUSDT、USDT0)、消费者应用(Plasma One钱包)和商户服务——所有这些都以最大化USDT采用和效用为中心。[^14][^15]

**组件1: USDT主导**

**市场地位**:
- 1200+亿美元市值(迄今最大的稳定币)
- 全球3.5亿+用户[^16]
- 在亚洲、拉丁美洲、非洲和新兴市场占主导地位
- 加密交易和DeFi的首选稳定币

**分发**:
- 在15+条区块链上可用(Ethereum、Tron、Solana、Avalanche等)
- 跨DEX和CEX的最深流动性
- 网络效应: 商户接受USDT因为用户拥有它;用户持有USDT因为商户接受它

**组件2: Plasma和Stable区块链**

**Plasma(零售支付)**:[^17]
- **零费用USDT转账**专门针对降低商户成本
- 微交易的高吞吐量
- 消费者支付的移动优先设计
- 与Bitfinex合作开发和流动性

**Stable(结算层)**:[^18]
- 具有更高安全性的主结算链
- USDT支付所有交易费(无单独代币)[^19]
- 跨链桥基础设施
- 验证器网络(使用USDT质押的权益证明)

**专门的USDT变体**:[^20]
- **gasUSDT**: 为费用支付优化
- **USDT0**: 用于在Stable和Plasma之间高效移动USDT的跨链桥代币

**组件3: 消费者应用**

**Plasma One钱包**:[^21]
- USDT存款>10% APY(收益生成)
- 购买4%返现(忠诚度激励)
- Plasma区块链上的零费用交易
- 移动优先用户体验

**战略意图**: 通过引人注目的收益和返现创造消费者需求,推动Plasma采用和USDT交易量。

**组件4: 商户服务**

**价值主张**:
- 零费用接受(vs. 2-3%卡费)
- 即时USDT结算
- 访问庞大的USDT用户群(3.5亿+)
- 与Plasma One钱包生态系统集成

**目标**: 新兴市场的商户和高量低利润业务(零售、餐饮服务、电子商务),其中卡费是痛点。

### 战略理由

1. **生态系统锁定**: 完整的USDT生态系统创造自我强化的网络效应
2. **成本领导**: 零费用Plasma在价格上削弱所有竞争对手
3. **新兴市场焦点**: USDT已在高增长市场占主导地位;基础设施强化这一点
4. **垂直整合**: 控制发行人+基础设施+分发=最大价值获取
5. **去中介化**: 直接面向消费者和直接面向商户的方法消除支付处理器

### 竞争优势

**1. USDT市场主导**:
- Circle USDC市值的3倍
- 建立的网络效应和流动性
- 用户偏好(特别是在新兴市场)

**2. 先发优势**:
- USDT于2014年建立(在USDC、PYUSD之前)
- 与加密交易所和DeFi深度集成
- 全球强大的品牌认知

**3. 成本结构**:
- 零费用Plasma创造无敌的成本主张
- 高APY和返现吸引用户
- 商户可将节省转嫁给客户(竞争优势)

**4. 地理定位**:
- 在高增长新兴市场占主导地位
- 在亚洲、拉丁美洲、非洲建立分销网络
- 这些市场中来自西方支付处理器的竞争较少

**5. 闭环经济学**:
- 完整生态系统实现交叉补贴(在发行上赚取,补贴支付)
- 收益生成资助返现和激励
- 自我维持的经济模式

### 脆弱性和风险

**1. 监管和透明度担忧**:
- 历史上比Circle透明度低(季度vs.月度认证)
- 储备构成更复杂(包括Bitcoin,历史上包括商业票据)
- 美国和欧洲持续的监管审查
- 监管行动的潜力(罚款、限制或禁止)

**2. 中心化风险**:
- 私人公司(无公开披露要求)
- 集中控制(Tether、Bitfinex关系)
- 大规模稳定币市场的单点故障
- PayPal PYUSD铸造/销毁事件展示中心化发行人风险[^22]

**3. Genius Act和MiCA合规**:
- 美国Genius Act和欧盟MiCA可能要求更改储备构成或运营[^23][^24]
- 合规成本可能破坏盈利能力
- 如果不合规可能被排除在受监管市场之外

**4. 脱锚风险感知**:
- USDT经历过轻微脱锚(交易价格为0.995-1.005美元)
- 市场对储备充足性的担忧
- 如果发生重大脱锚,USDT主导地位可能迅速蒸发

**5. 新链采用不确定性**:
- 推出Plasma和Stable造成分散(为什么不在Tron上使用USDT?)
- 新链的开发者和用户采用不保证
- 网络效应偏向Ethereum、Tron等现有USDT部署

### 战略展望

**最佳情况**: Plasma在新兴市场获得大规模采用,成为主导的零售支付区块链。USDT保持并扩大市场份额。Tether跨发行+基础设施获取巨大价值。监管担忧有利解决。

**适度情况**: Plasma在特定市场(亚洲、拉丁美洲)获得吸引力但未实现普遍采用。USDT保持主导地位但在受监管市场面临来自USDC的日益竞争。Tether保持盈利但面临持续的监管压力。

**最坏情况**: 监管行动迫使USDT退出主要市场(美国、欧盟)。Plasma未能获得采用。USDT失去市场份额给合规替代品(USDC、PYUSD)。Tether的商业模式崩溃。

**概率评估**: 适度到最佳情况。USDT的市场地位非常强,新兴市场焦点提供增长跑道。监管风险是真实的,但Tether迄今已应对挑战。Plasma的成功不确定,但USDT主导地位提供缓冲。

---

## <a name="visa"></a>Visa: 传统金融遇见链上结算

### 战略方法

Visa的战略将公司定位为传统支付网络和区块链结算之间的桥梁,利用其现有的商户和银行关系,同时添加稳定币能力。[^25][^26]

**核心策略: "链上法币的卡网络"**

**概念**:
- 维护现有卡网络和商户关系
- 添加使用稳定币的区块链结算选项
- 实现近实时跨境结算(vs.传统银行的数天)
- 定位为机构的受信任、受监管的入口

**实施**:

**1. 商户的稳定币结算**:
- Visa使用USDC与商户结算(并扩展到EURC、其他稳定币)[^27]
- 商户在几分钟而非几天内收到资金
- 跨境支付特别改善(无代理银行、无SWIFT延迟)
- 与全球商户的试点计划

**2. 多链、多币支持**:
- 不锁定单一区块链或稳定币
- 支持USDC、USDT、EURC,并扩展
- 跨Ethereum、Solana、Polygon和其他主要链工作
- 灵活的基础设施适应生态系统演变

**3. 银行合作伙伴模式**:
- 与发卡银行和收单银行合作
- 银行维护客户关系
- Visa提供区块链结算基础设施
- 渐进式迁移(银行准备好时选择稳定币结算)

**4. 机构焦点**:
- 最初针对企业支付,而非消费者零售
- B2B跨境支付主要用例
- 公司的财资管理
- 强调安全、合规和监管一致性

### 战略理由

1. **防御性**: 保护现有业务免受加密原生支付网络的去中介化
2. **渐进式创新**: 在不干扰核心卡业务的情况下添加稳定币结算
3. **利用资产**: 使用现有关系(银行、商户)分发区块链能力
4. **监管套利**: 建立的监管关系和合规基础设施提供vs.加密初创公司的竞争优势
5. **可选性**: 多链、多币方法避免选择赢家;可以支持任何成功的

### 竞争优势

**1. 现有网络**:
- 全球8000万+商户接受Visa
- 与全球银行的深厚关系
- 建立的基础设施(API、合规、欺诈检测)
- 品牌信任和认知

**2. 监管地位**:
- 高度监管的金融机构
- 现有许可证和合规框架
- 与全球监管机构的关系
- 被银行和商户视为"安全"合作伙伴

**3. 地理覆盖**:
- 全球运营(vs.区域加密参与者)
- 200+个国家/地区的存在
- 本地化合规和运营
- 跨境专业知识

**4. 企业信誉**:
- CFO和财资部门信任Visa
- 长期记录和财务稳定性
- 机构级安全和可靠性
- 无"加密风险"感知

### 脆弱性和风险

**1. 创新步伐**:
- 大型组织(vs.加密初创公司移动缓慢)
- 传统基础设施约束
- 文化对颠覆性变化的抵制
- 风险规避的合规文化可能减缓采用

**2. 利润率压力**:
- 稳定币结算削弱卡交换费(Visa的核心收入)
- 蚕食风险(商户转向较低费用的稳定币结算)
- 如果稳定币取代卡,Visa如何保持盈利能力不清楚

**3. 中介去中介化**:
- 直接商户对客户的稳定币支付完全绕过Visa
- 如果支付纯粹在链上,没有明确的增值
- 必须证明持续相关性(欺诈检测、争议解决、合规?)

**4. 加密原生竞争**:
- Stripe、Coinbase、Circle、Tether从头构建支付基础设施
- 可能证明更灵活和创新
- 可能在Visa扩展稳定币产品之前占领市场

**5. 身份危机**:
- 战略定位不清: Visa是卡网络还是区块链基础设施提供商?
- 混合信息可能使合作伙伴和客户困惑
- "卡在中间"的风险(对加密太慢,对传统银行太颠覆)

### 战略展望

**最佳情况**: Visa成功从卡网络过渡到多轨支付基础设施提供商。稳定币结算成为主要收入来源,抵消卡费压力。银行和商户大规模采用Visa的区块链基础设施,保留Visa的中介角色。

**适度情况**: Visa为特定用例(跨境B2B)提供稳定币结算作为利基产品。核心卡业务保持主导但面临缓慢的长期衰退。稳定币增长但Visa获取适度份额(非市场领导者)。

**最坏情况**: 稳定币支付使Visa去中介化。商户采用直接加密支付解决方案(Stripe、Coinbase)。Visa的稳定币努力未能获得吸引力。核心卡业务面临利润率压缩和量损失。

**概率评估**: 适度情况最可能。Visa的资产(关系、合规、品牌)提供防御性,但组织约束限制上行空间。不太可能成为主导的加密支付参与者,但将通过合作伙伴和渐进式创新保持相关性。

---

## <a name="paypal"></a>PayPal: 支付生态系统集成

### 战略方法

PayPal的战略集中在将PYUSD稳定币深度集成到其现有生态系统——4亿+用户、数百万商户、Venmo社交支付——创造闭环数字美元环境。[^28][^29]

**核心组件**:

**1. PYUSD发行**(由Paxos Trust发行):
- 2023年8月启动
- 6亿+美元市值
- 由美元存款和美国国债完全支持
- 月度储备认证
- ERC-20代币(Ethereum区块链)

**2. PayPal集成**:
- 在PayPal账户内购买、出售、持有PYUSD
- 向其他PayPal用户发送PYUSD(免费、即时)
- 使用PYUSD在数百万PayPal商户处为购买提供资金
- USD和PYUSD之间的无缝转换

**3. Venmo集成**:
- PYUSD在Venmo上可用(年轻人群、社交支付)
- 朋友间的P2P PYUSD转账
- 使用PYUSD分账
- 社交动态集成("用PYUSD支付")

**4. 商户接受**:
- PayPal商户可以接受PYUSD
- 如果商户更喜欢法币,自动转换为USD
- 与传统PayPal相同的结账体验
- 商户费用更低(鼓励PYUSD接受)

**5. Coinbase合作**:
- 公布合作以降低费用并改善互操作性[^30]
- 实现PayPal和外部钱包之间的PYUSD转账
- 将PYUSD效用扩展到PayPal生态系统之外

### 战略理由

1. **用户群杠杆**: 4亿PayPal用户=PYUSD的即时分发
2. **生态系统锁定**: PYUSD在PayPal/Venmo内无缝工作,创造切换成本
3. **利润率增强**: 加密交易可能比传统支付利润率更高
4. **创新定位**: 向市场发出PayPal创新而非遗留的信号
5. **防御性**: 防止加密原生支付应用侵蚀PayPal的用户群

### 竞争优势

**1. 分发**:
- 大规模现有用户群(4亿+用户,数百万商户)
- PYUSD无客户获取成本
- 即时临界质量

**2. 用户体验**:
- 无缝集成(用户无需理解区块链)
- 熟悉的界面(无学习曲线)
- 内置法币入/出口(轻松转换USD ↔ PYUSD)

**3. 监管合规**:
- PayPal高度监管(货币传输商许可证等)
- 强大的合规基础设施
- 主流用户的受信任品牌

**4. 商户关系**:
- 数百万商户已接受PayPal
- 易于添加PYUSD接受(切换开关)
- PayPal为商户处理所有复杂性

### 脆弱性和风险

**1. 封闭生态系统限制**:
- PYUSD主要在PayPal/Venmo内有用
- vs. USDC/USDT的外部效用有限(较少DeFi集成、较少链部署)
- 网络效应偏向开放稳定币

**2. 中心化控制担忧**:
- PayPal PYUSD铸造/销毁事件(2025)展示中心化控制[^31]
- 未授权铸造已纠正但引发信任问题
- 如果PayPal可以操纵供应,用户并不真正拥有PYUSD

**3. 来自发行人无关平台的竞争**:
- Stripe、Coinbase接受USDC、USDT、PYUSD(商户更喜欢灵活性)
- PayPal以PYUSD为中心的方法可能疏远持有其他稳定币的用户
- 竞争对手的多币接受降低PYUSD差异化

**4. 区块链效用缺口**:
- PYUSD未充分利用区块链优势(在PayPal内,它只是内部分类账)
- 寻求真正区块链功能的用户更喜欢USDC/USDT
- DeFi、跨链和可编程性有限

**5. 市场迟到/市场份额小**:
- PYUSD在USDT、USDC建立主导地位后启动
- 6亿美元市值vs. 1200亿美元(USDT)、370亿美元(USDC)=最小市场份额
- 显著市场份额增长的路径不清楚

**6. 监管风险**:
- Genius Act可能施加PayPal/Paxos当前不满足的要求
- 稳定币发行的潜在限制
- PayPal的双重角色(发行人+支付处理器)可能面临监管审查

### 战略展望

**最佳情况**: 由于PayPal的易用性和分发,PYUSD成为主流用户的首选稳定币。外部集成(Coinbase合作、DeFi协议)将效用扩展到PayPal之外。市场份额增长到100亿美元+,获取有意义的地位。

**适度情况**: PYUSD仍是PayPal/Venmo用户的利基稳定币。适度采用但不威胁USDC/USDT主导地位。PayPal成功集成加密而不干扰核心业务。PYUSD提供差异化但非主要收入驱动因素。

**最坏情况**: PYUSD未能获得吸引力。用户因开放性和流动性更喜欢USDC/USDT。PayPal的加密努力被视为噱头。监管问题迫使更改PYUSD模式。PayPal最终淡化或放弃PYUSD。

**概率评估**: 适度情况最可能。PayPal的分发提供底线(不会完全失败),但生态系统限制阻止主要市场份额。PYUSD成为成功的利基产品,但不是PayPal或稳定币市场的游戏规则改变者。

---

## <a name="coinbase"></a>Coinbase: 互联网支付标准和基础设施

### 战略方法

Coinbase的战略集中在为互联网原生支付构建基础协议和标准,将公司定位为基础设施提供商而不仅仅是支付处理器。[^32][^33]

**核心倡议**:

**1. x402协议**(互联网支付标准):

**概念**: 复活HTTP 402"需要支付"状态码用于无缝微支付[^34][^35]
- Web服务通过标准HTTP响应请求稳定币支付
- 钱包在用户定义的限制内自动执行批准的支付
- 实现按使用付费API、内容付费墙、AI代理交易

**战略意图**:
- 建立开放标准(像HTTP、SMTP)
- 实现生态系统范围的创新(非Coinbase特定)
- 随着支付量增长通过相邻服务(托管、交易所、处理)盈利

**2. Base区块链**(Ethereum上的Layer-2):

**启动**: 2023年
**特征**:
- 低成本、高速Ethereum Layer-2
- Coinbase运营但开放和无需许可
- 为稳定币支付和应用优化
- USDC原生集成

**战略意图**:
- 为支付和应用提供可扩展的基础设施
- 获取Gas费收入
- 推动Coinbase生态系统采用
- 在Coinbase控制的基础设施上实现创新

**3. Coinbase Commerce**(商户支付处理):

- 接受加密(包括稳定币)的商户支付网关
- 与电子商务平台(Shopify、WooCommerce等)集成
- 商户的仪表板和报告
- 托管和非托管选项

**4. 钱包基础设施**:

- Coinbase Wallet(自托管)
- 开发者的嵌入式钱包
- 其他应用的钱包即服务(WaaS)
- 智能钱包功能(账户抽象、Gas代付)

### 战略理由

1. **基础设施游戏**: 随着支付量增长通过提供基础设施获取价值
2. **开放标准**: x402开放协议创造使整个生态系统(包括Coinbase)受益的网络效应
3. **多边平台**: 交易所+托管+处理+基础设施=多样化收入
4. **开发者优先**: 吸引开发者在Base上构建并集成x402,创造生态系统锁定
5. **未来验证**: AI/代理支付代表下一个前沿;x402将Coinbase定位为推动者

### 竞争优势

**1. 加密原生专业知识**:
- 深厚的区块链和加密经验
- 受加密社区信任
- 技术信誉

**2. 监管地位**:
- 上市公司(透明度、治理)
- 美国基地和受监管
- 交易所的合规基础设施扩展到支付

**3. 多样化商业模式**:
- 不仅依赖支付处理
- 交易所、托管、质押和基础设施收入
- 可以投资生态系统发展(补贴以推动量)

**4. 开发者社区**:
- 强大的开发者关系和工具
- 开源贡献
- Base吸引开发者心智份额

**5. 有远见的定位**:
- x402将Coinbase定位为思想领袖
- 早期押注AI/代理支付
- "价值互联网"叙事与开发者产生共鸣

### 脆弱性和风险

**1. x402采用不确定性**:
- 协议需要广泛的钱包和商户采用才能成功
- 可能出现竞争标准(分散风险)
- 如果x402失败,Coinbase获益很少(开放协议=有限捕获)

**2. Base竞争格局**:
- 竞争Layer-2(Arbitrum、Optimism、Polygon)
- 竞争支付链(Tempo、Arc、Stable/Plasma)
- 必须实现显著网络效应才能维持

**3. 有限商户分发**:
- 比Stripe、PayPal、Visa更少的商户关系
- Coinbase Commerce比竞争对手小
- 商户采用的上市更难

**4. 监管不确定性**:
- Coinbase持续的监管审查(SEC诉讼等)
- 合规成本和限制可能限制增长
- 监管行动可能影响支付雄心

**5. 开放协议盈利挑战**:
- x402是开放的(任何人都可以使用而无需向Coinbase付费)
- 间接盈利(希望支付量推动交易所/托管使用)
- vs.直接支付处理费的收入模式不清楚

### 战略展望

**最佳情况**: x402成为互联网微支付的标准。AI代理使用x402协议交易数万亿。Base成为支付的主导Layer-2。尽管x402开放,Coinbase通过交易所、托管和基础设施获取显著价值。

**适度情况**: x402在特定用例(AI API访问、微支付)获得利基采用。Base作为几个成功Layer-2之一保持地位。Coinbase Commerce适度增长。多样化商业模式维持公司,即使支付领导地位未实现。

**最坏情况**: x402未能获得采用(钱包不实施,商户不集成)。Base输给竞争Layer-2。支付处理仍是Coinbase业务的小部分。核心交易所业务面临监管压力和竞争。

**概率评估**: 适度到最佳情况。x402是高风险、高回报押注——如果成功,巨大上行空间;如果失败,Coinbase有其他业务。Base有动力和Coinbase承诺。AI/代理支付的长期定位深思熟虑且差异化。

---

## <a name="comparative-analysis"></a>比较分析

### 战略定位矩阵

| 参与者 | 核心策略 | 稳定币焦点 | 基础设施控制 | 目标市场 | 竞争护城河 |
|--------|---------------|------------------|------------------------|---------------|------------------|
| **Stripe** | 双轨(商户+区块链) | 多币 | Tempo(构建中) | 商户、开发者 | 分发、UX |
| **Circle** | 垂直整合 | USDC(自有) | Arc(自有) | 企业、机构 | 监管合规 |
| **Tether** | 闭环生态系统 | USDT(自有) | Plasma/Stable(自有) | 新兴市场、零售 | 市场主导、成本 |
| **Visa** | 桥接传统+加密 | 多币 | 无关(合作伙伴) | 银行、企业 | 网络、品牌 |
| **PayPal** | 生态系统集成 | PYUSD(自有) | 无关(ERC-20) | 消费者、中小企业 | 用户群、UX |
| **Coinbase** | 基础设施协议 | 多币 | Base(自有) | 开发者、AI/代理 | 开放标准、开发者社区 |

### 优势和劣势总结

**Stripe**:
- **优势**: 商户关系、开发者生态系统、执行记录
- **劣势**: 市场迟到、Tempo未经证实、无自有稳定币

**Circle**:
- **优势**: 监管合规、USDC采用、企业信誉
- **劣势**: Arc采用挑战、单币焦点、B2C限制

**Tether**:
- **优势**: USDT主导、新兴市场实力、成本领导
- **劣势**: 监管风险、透明度担忧、中心化

**Visa**:
- **优势**: 网络规模、监管地位、全球覆盖
- **劣势**: 创新步伐、蚕食风险、差异化不清

**PayPal**:
- **优势**: 用户群分发、UX简单、主流品牌
- **劣势**: 封闭生态系统、有限市场份额、中心化控制

**Coinbase**:
- **优势**: 加密专业知识、x402创新、开发者社区
- **劣势**: 商户分发、监管不确定性、盈利挑战

### 市场份额预测(24个月)

**稳定币发行**:
- USDT(Tether): 保持50-60%市场份额(当前~44%)
- USDC(Circle): 增长到25-30%(当前~13%)
- PYUSD(PayPal): 适度增长到2-3%(当前<1%)
- 其他: 15-20%(DAI、区域稳定币、新进入者)

**支付处理(商户服务)**:
- Stripe: 25-30%(利用商户基础)
- PayPal: 20-25%(现有用户群)
- Coinbase: 15-20%(加密原生焦点)
- 传统处理器(Visa等): 15-20%
- 其他: 15-25%

**区块链基础设施(支付链)**:
- Ethereum + Layer-2(Base、Arbitrum、Optimism): 40-50%
- Tron: 20-25%(新兴市场主导)
- Solana: 10-15%
- Tempo: 5-10%(如果成功)
- Arc: 3-5%(企业利基)
- Stable/Plasma: 5-10%(新兴市场)

---

## <a name="emerging-challengers"></a>新兴挑战者

### 尚未占主导但值得关注的竞争对手

**1. 构建稳定币能力的传统银行**:

**JPMorgan JPM Coin**:
- 用于机构客户的许可稳定币
- 聚焦B2B跨境支付
- 利用银行关系的潜力

**策略**: 在受信任的银行框架内提供稳定币优势(速度、效率)。针对对加密原生解决方案不舒服的企业。

**2. 进入支付的科技巨头**:

**Amazon/Walmart**:
- 传闻稳定币探索[^36]
- 大规模商户/客户基础
- 如果部署可能迅速实现规模

**策略**: 利用生态系统创建专有支付轨道,减少对Visa/Mastercard的依赖。

**3. 区域稳定币发行人**:

**XSGD(新加坡元稳定币)**:
- 区域焦点提供差异化
- 新加坡的监管清晰度
- 其他司法管辖区的潜在模式

**策略**: 服务全球USD稳定币未满足的区域需求。与本地支付处理器和银行合作。

**4. 去中心化稳定币协议**:

**MakerDAO(DAI)**:
- 去中心化、算法超额抵押
- 中心化稳定币的抗审查替代品
- 吸引重视去中心化的加密原生用户

**策略**: 获取担心中心化发行人风险(Circle、Tether)的用户。与DeFi生态系统深度集成。

### 未知数和颠覆者

**1. 央行数字货币(CBDC)**:

多个国家开发CBDC:
- 数字人民币(中国,运营中)
- 数字欧元(欧盟,开发中)
- 数字美元(美国,研究阶段)

**潜在影响**:
- 如果广泛采用,CBDC可能取代私人稳定币
- 政府可能限制私人稳定币以保护CBDC采用
- 或者,CBDC可能与私人稳定币互操作(混合模式)

**2. 意外科技巨头进入**:

Apple、Google、Meta尚未进入稳定币领域:
- **Apple**: 可将稳定币集成到Apple Pay(大规模分发)
- **Google**: 钱包和支付基础设施已存在
- **Meta**: 以前尝试Libra/Diem(失败但可以重试)

**影响**: 鉴于其用户群和技术能力,任何这些参与者的进入将极大重塑竞争格局。

---

## <a name="strategic-outlook"></a>战略展望和预测

### 12个月预测

**市场结构**:
- **多参与者均衡出现**: 跨所有层级无单一主导参与者
- **发行层整合**: 前3大稳定币(USDT、USDC、PYUSD)获取85%+市场份额
- **基础设施层分散**: 多个成功的支付链共存(Ethereum/L2、Tempo、Arc、Tron、Solana)
- **处理层竞争**: Stripe、PayPal、Coinbase、Visa都获得份额;传统卡网络失去份额

**特定参与者**:
- **Stripe**: 成功的商户采用;Tempo启动但最初采用缓慢
- **Circle**: USDC保持#2位置;Arc在企业利基获得吸引力
- **Tether**: 尽管监管压力,USDT主导地位继续;Plasma采用适度
- **Visa**: 稳定币结算扩展但仍是利基;核心卡业务稳定
- **PayPal**: PYUSD适度增长;仍是封闭生态系统限制上行空间
- **Coinbase**: x402被AI平台早期采用;Base巩固为前3 Layer-2

### 24个月预测

**市场演变**:
- **监管清晰度推动采用**: Genius Act(或等效)通过,提供明确框架
- **基础设施成熟**: 跨链支付无缝;Gas抽象普遍
- **AI代理支付显著**: 来自AI/代理交易的月交易量100亿美元+
- **传统支付量转移**: 全球电子商务的5-10%使用稳定币

**竞争格局**:
- **赢家**: Stripe(商户处理)、Tether(稳定币发行)、Coinbase/Base(基础设施)
- **强劲表现者**: Circle(企业)、PayPal(消费者利基)、Visa(机构桥梁)
- **未知数**: CBDC影响不确定;潜在科技巨头进入重新洗牌

### 长期结构性问题

**1. 稳定币发行会整合还是分散?**

**整合场景**: 网络效应和监管成本偏向前2-3发行人(USDT、USDC,可能PYUSD或CBDC)。区域稳定币获取利基市场。

**分散场景**: 每个区域/用例开发专门稳定币。互操作性协议实现无缝交换,减少赢家通吃动态。

**可能结果**: 全球层面整合(USDT、USDC主导);区域层面分散(EURC、XSGD、BRLC等用于本地市场)。

**2. 支付基础设施会围绕主导链整合还是保持多链?**

**整合场景**: 由于网络效应、流动性和开发者生态系统,Ethereum(+ Layer-2)获取大部分支付量。其他链服务利基用例。

**多链场景**: 不同链为不同用例优化: Ethereum(DeFi集成)、Tempo(AI代理)、Arc(企业)、Tron(新兴市场)、Solana(高频)。

**可能结果**: 多链均衡,抽象层使链选择对用户不可见。多个成功链共存,各服务不同细分市场。

**3. 谁获取价值: 发行人、基础设施还是处理器?**

**发行人价值获取**: 发行人从浮动(投资储备)和可能的交易费中获利。Circle、Tether、PayPal从储备投资中赚取数十亿。

**基础设施价值获取**: 区块链Gas费和网络效应。Tempo、Arc、Base、Ethereum Layer-2获取交易费。

**处理器价值获取**: 商户处理费和增值服务。Stripe、PayPal、Coinbase在支付处理、转换、合规上获利。

**可能结果**: 价值分布在所有层级。发行人获取最大绝对价值(规模储备投资)。基础设施和处理器在利润率上竞争,但高量维持多个盈利参与者。

---

## 结论

2025年的稳定币支付格局呈现追求根本不同策略的多样化参与者之间的激烈竞争。Stripe的双轨商户和基础设施方法、Circle与Arc的垂直整合、Tether的闭环USDT生态系统、Visa的传统金融桥梁、PayPal的生态系统集成和Coinbase的开放协议基础设施各自提供不同的价值主张并面临独特挑战。

尚无单一参与者在所有层级建立不可攻破的竞争护城河。相反,市场正在朝着多参与者均衡演变,不同细分市场有不同的领导者: Tether/USDT主导稳定币发行、Stripe领导商户处理、多个成功的支付链共存(Ethereum/L2、Tempo、Arc、Tron),以及专业参与者服务特定利基(企业、新兴市场、AI代理)。

未来12-24个月将至关重要,因为监管框架巩固(Genius Act、MiCA)、基础设施成熟(跨链结算、Gas抽象)和用例扩展(AI代理、可编程支付)。成功执行其策略的参与者——建立分发、实现产品市场契合并应对监管挑战——将在新兴数字美元经济中获取显著价值。

对于企业、开发者和投资者,理解这些战略定位和竞争动态对于就稳定币支付生态系统中的合作伙伴、集成和投资做出明智决策至关重要。

---

## 导航

[← 上一篇: 基础设施缺口与路线图](./infrastructure-gaps-roadmap.md) | [下一篇: 实施路线图 →](./implementation-roadmap.md)

[返回概览](../Overview-ZH.md)

---

## 参考文献

[^1]: [Coinbase Research – New Framework for Stablecoin Growth](https://www.coinbase.com/blog/new-framework-for-stablecoin-growth)
[^2]: [Industry data compiled from multiple sources (2024-2025)](https://www.theblock.co/data/stablecoins)
[^3]: [Stripe Newsroom – Shopify Merchants to Accept USDC via Stripe](https://stripe.com/newsroom/news/shopify-usdc-payments)
[^4]: [Stripe Documentation – Crypto Payment Processing](https://docs.stripe.com/crypto)
[^5]: [Shopify – USDC Merchant Adoption Statistics](https://www.shopify.com/blog/usdc-merchant-adoption)
[^6]: [Paradigm (Matt Huang) – Tempo: The Blockchain Designed for Payments](https://www.paradigm.xyz/2025/02/tempo-blockchain-for-payments)
[^7]: [Stripe – Tempo Blockchain Announcement](https://stripe.com/blog/tempo-blockchain-launch)
[^8]: [Circle – Arc Blockchain Launch Announcement](https://www.circle.com/blog/introducing-arc-blockchain)
[^9]: [Circle – Arc Vertical Integration Strategy](https://www.circle.com/blog/arc-integration-strategy)
[^10]: [Circle Arc – Gas Fee Structure](https://developers.circle.com/arc/docs/fees)
[^11]: [Circle Arc – Built-in FX Engine Technical Details](https://developers.circle.com/arc/docs/fx-engine)
[^12]: [Circle Arc – Privacy Features Overview](https://developers.circle.com/arc/docs/privacy)
[^13]: [USDC depeg event analysis (March 2023, Silicon Valley Bank)](https://www.coindesk.com/markets/2023/03/11/usdc-depegs-silicon-valley-bank-crisis)
[^14]: [ChainCatcher – Next Battle of Stablecoins (Arc, Plasma, Stable, Tempo)](https://www.chaincatcher.com/en/article/2024/stablecoin-blockchain-wars)
[^15]: [Tether – Closed-loop Ecosystem Architecture](https://tether.io/ecosystem-architecture)
[^16]: [Nasdaq/Motley Fool – USDC vs Tether & Global Usage (350M users)](https://www.nasdaq.com/articles/usdc-vs-usdt-comparing-leading-stablecoins)
[^17]: [Tether – Plasma Blockchain Announcement](https://tether.io/news/plasma-blockchain-launch)
[^18]: [Tether Stable – Main settlement chain](https://tether.io/stable)
[^19]: [Tether – USDT Gas Implementation](https://tether.io/developers/gas-implementation)
[^20]: [Tether – USDT Variants Documentation (gasUSDT, USDT0)](https://tether.io/developers/usdt-variants)
[^21]: [Plasma One – Digital Wallet Launch](https://plasma.one/wallet)
[^22]: [PayPal PYUSD incident – Mint/burn correction (2025)](https://newsroom.paypal-corp.com/2025-pyusd-incident-response)
[^23]: [Nasdaq – U.S. Genius Act Stablecoin Regulation](https://www.nasdaq.com/articles/genius-act-stablecoin-regulation-explained)
[^24]: [EU MiCA Regulation – Asset-referenced token requirements](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32023R1114)
[^25]: [Visa News – Stablecoin Settlement Expansion](https://usa.visa.com/visa-everywhere/blog/expanding-stablecoin-settlement-capabilities.html)
[^26]: [Visa – On-chain Settlement Platform Expansion](https://usa.visa.com/visa-everywhere/blog/on-chain-settlement-expansion.html)
[^27]: [Visa – Multi-coin and multi-chain support announcement](https://usa.visa.com/visa-everywhere/blog/multi-coin-chain-support.html)
[^28]: [PayPal Newsroom – PayPal Launches U.S. Dollar Stablecoin (PYUSD)](https://newsroom.paypal-corp.com/2023-08-07-PayPal-Launches-U-S-Dollar-Stablecoin)
[^29]: [PayPal – PYUSD Ecosystem Integration](https://newsroom.paypal-corp.com/pyusd-ecosystem-integration)
[^30]: [PayPal-Coinbase partnership announcement](https://newsroom.paypal-corp.com/paypal-coinbase-partnership)
[^31]: [PayPal PYUSD mint/burn incident analysis](https://www.coindesk.com/tech/paypal-pyusd-mint-burn-incident)
[^32]: [Cognitive Revolution Podcast – Coinbase's x402 Micropayments Protocol](https://www.cognitiverevolution.ai/coinbase-x402-protocol)
[^33]: [Coinbase – x402 Standard Adoption](https://blog.coinbase.com/x402-standard-adoption)
[^34]: [Coinbase – x402 Protocol Documentation](https://docs.cloud.coinbase.com/x402)
[^35]: [x402 Foundation – Use Cases for AI Agent Payments](https://x402.org/use-cases)
[^36]: [Reports: Amazon and Walmart stablecoin exploration](https://www.reuters.com/technology/amazon-walmart-explore-stablecoin-payments)

---

*Chainsights关于稳定币、支付和C2B商务的通讯系列。*
