# Major Stablecoin Initiatives (2023-2025)

> Part of the [Stablecoins and C2B Payments Overview](../Overview-EN.md) series

## Introduction

Between 2023 and 2025, the stablecoin payment landscape transformed dramatically as major fintech and crypto players launched ambitious initiatives to mainstream stablecoin usage. This period marked a shift from stablecoins as primarily trading instruments to dedicated payment infrastructure with purpose-built blockchains, merchant integrations, and institutional adoption.

This article examines the six most significant platform initiatives that are reshaping how consumers and businesses transact with stablecoins.

![Stablecoin Ecosystem Landscape](../imgs/major-initiatives-ecosystem.jpg)
*The evolving stablecoin ecosystem with major players driving innovation in digital payments*

---

## 1. PayPal USD (PYUSD): Mainstream Integration

### Launch and Structure

In **August 2023**, PayPal made headlines by introducing its own U.S. dollar stablecoin, **PYUSD**, issued by Paxos Trust.[^1][^2]

**Key Characteristics:**
- Fully backed 1:1 by dollar deposits and U.S. Treasury bills
- Issued as an ERC-20 token (Ethereum blockchain)
- Redeemable 1:1 for USD through Paxos
- Regular third-party attestations of reserves
- Integrated into PayPal and Venmo platforms

### Platform Integration

PayPal integrated PYUSD deeply into its existing payment ecosystem:

**Consumer Features:**
- Buy, sell, and hold PYUSD within the PayPal app
- Send peer-to-peer (P2P) transfers to other PayPal/Venmo users
- Fund purchases at millions of online merchants via PayPal checkout
- Seamless conversion between PYUSD and other cryptocurrencies
- Available on Venmo, extending reach to younger demographics[^3]

**Merchant Benefits:**
- Accept PYUSD through existing PayPal integration
- Instant settlement in PYUSD or auto-convert to USD
- No additional integration required for existing PayPal merchants
- Reduced fees compared to traditional payment methods
- Access to crypto-native customer base

### Strategic Significance

PayPal's entry validated stablecoins for mainstream commerce. With 400+ million active users and millions of merchant relationships, PayPal provided instant distribution that crypto-native projects could never achieve.

**PayPal's Vision:**
> "We think stablecoins are a natural evolution for digital commerce, providing a stable instrument that is both digitally native and easily connected to fiat."[^4]

### Recent Developments (2025)

- Partnership with Coinbase for fee reductions and liquidity
- Expansion to additional blockchains beyond Ethereum
- Integration with DeFi protocols for yield generation
- Notable incident: Accidental minting and correction highlighted centralized control mechanisms[^5]

---

## 2. Stripe's Dual Strategy: Integration + Tempo Blockchain

Stripe has pursued the most comprehensive stablecoin strategy, operating on two parallel tracks: merchant integration and infrastructure development.

### Track 1: Merchant Integration (2024-2025)

**Shopify Partnership:**

In mid-2025, Stripe partnered with Shopify to enable millions of merchants in **34 countries** to accept USDC payments from customers.[^6]

**How It Works:**
1. Shoppers pay with USDC using crypto wallets (initially Coinbase's Base network)
2. Stripe handles all crypto-to-fiat conversion automatically
3. Merchants receive funds in their local fiat currency to their bank account
4. Alternatively, merchants can opt to keep the USDC

**Key Innovation:**
Merchants don't need to change their existing checkout flow or hold cryptocurrency – Stripe abstracts all complexity.[^7][^8]

**Additional Features:**
- **Recurring stablecoin payments**: Subscriptions and SaaS can bill in USDC just like credit cards[^9]
- **Global reach**: Tap markets with limited card access or unstable currencies
- **Lower fees**: Bypass traditional card network charges
- **Instant settlement**: T+0 instead of T+2 or longer

### Track 2: Tempo Blockchain (2025)

Stripe, in collaboration with crypto VC firm Paradigm, unveiled **Tempo** – a new Layer-1 blockchain purpose-built for high-volume stablecoin payments.[^10][^11]

**Why a New Blockchain?**

Stripe's CEO noted that existing blockchains were "not optimized" for the scale of real-world payments as stablecoin usage grows.[^12]

**Tempo Design Principles:**

**1. High-Throughput, Low-Cost Architecture**
- Sub-second finality
- Thousands of transactions per second
- Minimal fees (fractions of a cent)
- Optimized for payment patterns, not general computation

**2. Multi-Stablecoin Native Gas**
- Accept USDC, USDT, and other stablecoins for transaction fees
- No separate volatile token required
- Users pay fees in the same currency they're transacting
- Technically challenging but dramatically improves UX[^13][^14]

**3. Payment-Specific Primitives**
- Built-in conditional payments
- Scheduled/recurring payment support
- Multi-party transaction primitives
- Developer-friendly payment APIs at protocol level[^15]

**4. Enterprise-Grade Partners**
Tempo has attracted an impressive alliance:
- **AI Companies**: OpenAI, Anthropic
- **E-commerce**: Shopify, Coupang
- **Finance**: Visa, Standard Chartered
- **Purpose**: Guide design for real-world payment needs[^16]

### Stripe's Open Issuance Platform

Beyond accepting stablecoins, Stripe launched "**Open Issuance**" – enabling businesses to create their own stablecoins to:
- Capture interest on customer deposits
- Build branded loyalty programs
- Create closed-loop payment ecosystems
- Distribute treasury yields to customers[^17][^18]

This represents Stripe's vision of "agentic" AI-driven commerce where autonomous systems transact seamlessly.

---

![Blockchain Payment Infrastructure](../imgs/major-initiatives-blockchain-infrastructure.jpg)
*Purpose-built blockchain infrastructure optimized for stablecoin payments*

## 3. Coinbase x402 Protocol: HTTP-Native Payments

While others focused on merchant checkout, Coinbase pioneered a more fundamental innovation: integrating payments into the fabric of the internet itself.

### The x402 Standard

Coinbase co-created **x402**, reviving the internet's long-reserved **HTTP 402 "Payment Required"** status code as a tool for seamless micropayments with stablecoins.[^19][^20]

**How It Works:**

Traditional flow:
```
Client → Server: GET /premium-article
Server → Client: 403 Forbidden (paywall)
[User must manually navigate to payment page, enter card, etc.]
```

x402 flow:
```
Client → Server: GET /premium-article
Server → Client: 402 Payment Required
  Price: 0.05 USDC
  Payment Address: 0x...
Client → Blockchain: [Automatic payment]
Client → Server: GET /premium-article (with payment proof)
Server → Client: 200 OK [Article content]
```

### Use Cases

**1. API Micropayments**
- Pay per API call instead of monthly subscription
- Automatic rate limiting based on payment
- No upfront commitment or account setup

**2. Content Paywalls**
- Pay $0.10 to read an article
- No subscription required
- Instant access after micro-payment

**3. AI Agent Transactions**
The protocol particularly anticipates **AI agents paying for services autonomously**:[^21]

- AI agent needs data from an API
- Encounters 402 Payment Required
- Automatically pays requested amount in USDC
- Receives and processes data
- All without human intervention

### x402 Foundation (2025)

Coinbase and partners (including Cloudflare) formed the **x402 Foundation** to promote this as a universal standard for internet microtransactions via crypto.[^22]

By using stablecoins (primarily USDC) for these payments, x402 ensures:
- Pricing is stable and familiar
- Global compatibility without currency conversion
- Machine-readable payment requests
- Instant settlement without intermediaries

### Strategic Vision

x402 positions stablecoins as the "native money of the internet" – enabling the long-promised but never-realized vision of HTTP 402 micropayments. As AI agents become more prevalent, having a standardized way for machines to transact becomes critical infrastructure.

---

## 4. Circle's Arc Blockchain: Vertical Integration

Circle, the issuer of USDC (the second-largest stablecoin), took a bold step in 2025 by launching its own Layer-1 blockchain explicitly designed for stablecoin finance.

### Why Arc Exists

After seeing partners struggle with general-purpose chains not designed for payments, Circle identified specific pain points:[^23][^24]

**Problems with Existing Chains:**
- Unpredictable transaction fees
- Gas paid in volatile ETH/other tokens
- Privacy limitations for enterprise
- Slower finality than card networks
- Complex multi-chain deployment

**Arc's Solution:**
Build a blockchain purpose-built for stablecoin transactions with enterprise requirements in mind.

### Arc Technical Features

**1. USDC as Native Gas Currency**
All fees are paid in USDC for predictable, fiat-denominated costs.[^25]
- No need to hold ETH, SOL, or other volatile tokens
- Businesses can budget fees in familiar dollar terms
- Simplifies accounting and reconciliation

**2. Built-In FX Engine**
24/7 on-chain currency exchange between stablecoins.[^26]
- Convert USDC ↔ EURC ↔ other fiat stablecoins
- Instant, on-chain foreign exchange
- Competitive rates without off-chain intermediaries

**3. Instant Finality**
Sub-second settlement with deterministic finality.[^27]
- Matches or exceeds card network speeds
- Irreversible confirmation in <1 second
- Enterprise-grade reliability

**4. Opt-In Privacy**
Transaction details can be kept confidential.[^28][^29]
- Public verification without exposing amounts
- Enterprise privacy for business transactions
- Compliance-compatible design

**5. Full Circle Integration**
Native integration with Circle's existing services:[^30]
- Circle Account API
- Circle Payments
- Multi-currency stablecoins
- Compliance and identity services

### Strategic Positioning

Circle is executing a **vertical integration strategy**:

1. **Issue USDC** (stablecoin)
2. **Build Arc** (blockchain optimized for USDC)
3. **Operate infrastructure** (nodes, validators)
4. **Provide services** (APIs, wallets, compliance)
5. **Capture value** (fees, interest, services)

By controlling the full stack, Circle ensures:[^31]
- Every Arc transaction uses USDC (driving demand)
- Circle provides add-on services (generating revenue)
- Faster innovation without third-party dependencies
- Enterprise-grade support and SLAs

Arc aims to be the **high-performance backbone for corporations adopting stablecoins**, complementing public networks like Ethereum while mitigating their shortcomings for payments.[^32][^33]

---

## 5. Tether's Plasma and Stable Chains: Ecosystem Control

Tether, issuer of USDT (the largest stablecoin with $83+ billion supply), took an even more ambitious approach in 2025 by launching **two related blockchains**: Plasma and Stable.[^34]

### Strategic Motivation

Tether recognized a massive missed opportunity:

**The Problem:**
- Tether's USDT facilitates over **$1 trillion in transactions per month**
- USDT rode on others' networks (Ethereum, Tron, Solana, etc.)
- Network operators captured all transaction fees
- Tron alone earned billions in gas fees from USDT transfers[^35][^36]
- Tether pocketed **zero transaction fees** despite massive volume[^37][^38]

**The Solution:**
Build proprietary blockchains to capture the value flow of USDT transactions.

### Plasma: Zero-Fee Retail Payments

**Plasma Blockchain** (developed with sister company Bitfinex) focuses on efficiency and accessibility:[^39][^40]

**Key Features:**
- **Zero-fee USDT transfers** targeting retail payment volume
- High-throughput architecture for millions of small transactions
- Competes directly with Tron (currently dominant for retail USDT)
- $373 million raised in token sale (demonstrating market interest)[^41]

**Target Market:**
Merchants currently "ceding 2–3% of their revenue" to card processors – offering them a zero-fee alternative.

### Stable: Main Settlement Layer

**Stable** is envisioned as the "exclusive home for USDT" with a dual-chain architecture:[^42]
- **Stable**: Main settlement chain for security and finality
- **Plasma**: High-speed parallel chain for microtransactions

**Technical Architecture:**

**1. USDT-Based Gas System**
USDT itself is used for paying fees, so users need no separate token.[^43]
- Lowers adoption friction
- Familiar denomination
- No volatile token exposure

**2. Specialized USDT Variants**
- **gasUSDT**: For paying transaction fees
- **USDT0**: For cross-chain bridges
- **All variants**: Pegged 1:1 and swappable with standard USDT at no cost[^44]

**3. StableBFT Consensus**
Custom high-throughput variant of Tendermint for payment reliability.[^45]

### Closed-Loop Ecosystem

Tether is building a complete USDT universe:

**Consumer Layer:**
- **Plasma One**: Digital bank/wallet app
  - >10% APY on stablecoin deposits[^46][^47]
  - 4% cashback on payments
  - Integrated debit card

**Merchant Layer:**
- Zero-fee acceptance
- Instant settlement
- Global reach

**Infrastructure Layer:**
- Plasma (high-speed payments)
- Stable (settlement)
- Bridges (cross-chain)

**Result:** Every aspect of using USDT (transacting, bridging, fees) happens within the USDT ecosystem, capturing value internally.

### Major Validation: PayPal Partnership

In late 2025, **PayPal invested in the Stable network** and arranged for PYUSD to be supported gas-free on Stable as well.[^48]

This shows how serious incumbent fintechs are about leveraging these new stablecoin-dedicated chains for payments.

---

## 6. Legacy Payment Giants: Visa & Mastercard

Traditional payment networks haven't stood idle – they're integrating stablecoins into existing infrastructure.

### Visa's Stablecoin Settlement

Visa expanded its **stablecoin settlement pilot** in 2023-2024:[^49][^50]

**How It Works:**
1. Merchants accept traditional card payments
2. Visa settles daily balances with merchant acquirers
3. Settlement occurs in USDC on Ethereum or Solana
4. **Result**: Near-instant cross-border settlement instead of days

**Partners:**
- Worldpay (merchant acquirer)
- Nuvei (payment processor)
- Multiple international markets

**Benefits:**
- Dramatically speeds cross-border settlements
- Reduces currency conversion complexity
- Maintains familiar card payment UX for consumers
- Positions Visa as "on-chain fiat settlement network"

### Mastercard's Initiatives

Mastercard launched programs to help banks and fintechs integrate stablecoins:[^51]
- Multi-chain support infrastructure
- Cross-border flow optimization
- Stablecoin-based B2B payments
- Central bank digital currency (CBDC) experimentation

### Merchant Interest: Amazon & Walmart

Reports emerged that **Amazon and Walmart** were studying stablecoins as payment options specifically to cut card fees:[^52]

For context:
- Walmart processes ~$600 billion annually
- At 2% card fees, that's $12 billion in fees
- Even 0.5% savings = $3 billion annually

This level of merchant interest from retail giants validates the business case for stablecoin payments.

---

## Cross-Initiative Themes

Across all these initiatives, several common patterns emerge:

### 1. Purpose-Built Infrastructure
Moving beyond general-purpose blockchains to payment-optimized networks (Tempo, Arc, Stable/Plasma).

### 2. Gas Abstraction
Eliminating separate gas tokens in favor of stablecoins as native fees (Arc, Tempo, Stable).

### 3. Institutional Integration
Major enterprises (Visa, PayPal, Shopify) building bridges between crypto and traditional finance.

### 4. Vertical Integration
Stablecoin issuers building their own blockchains to capture more value (Circle, Tether).

### 5. Developer Platforms
Not just payments, but platforms for building payment applications (Stripe, Coinbase).

### 6. Multi-Currency Support
Beyond USD: Euro (EURC), Pound, Yen stablecoins emerging for global commerce.

---

## Conclusion: The "Stablecoin Wars"

Industry analysts have dubbed this competitive landscape the **"stablecoin wars"**[^53][^54] – a race to define next-generation payment rails.

Each major initiative brings distinct advantages:
- **PayPal**: Mainstream distribution
- **Stripe/Tempo**: Developer platform
- **Coinbase/x402**: Internet-native standard
- **Circle/Arc**: Enterprise infrastructure
- **Tether/Stable**: Retail reach + ecosystem control
- **Visa**: Legacy network integration

Rather than a winner-take-all outcome, we're likely to see:
- **Specialized networks** for different use cases
- **Abstraction layers** routing between chains
- **Interoperability protocols** connecting ecosystems
- **Merchant flexibility** accepting multiple stablecoins

The speed and scale of these initiatives (2023-2025) demonstrate that stablecoin payments have moved from experimental to infrastructure-grade, with billions in investment and partnerships with the world's largest companies.

---

## Continue Reading

- [← Previous: Why Stablecoins for C2B Payments](./why-stablecoins-for-c2b-payments.md)
- [Next: Stablecoin Payment Architecture →](./stablecoin-payment-architecture.md)
- [Back to Overview](../Overview-EN.md)

## Related Articles

- [The Stablecoin Abstraction Layer](./stablecoin-abstraction-layer.md)
- [Major Players' Strategic Positioning](./major-players-strategies.md)
- [Implementation Roadmap](./implementation-roadmap.md)

---

## References

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

*Part of the Chainsights newsletter series on stablecoins, payments, and C2B commerce.*
