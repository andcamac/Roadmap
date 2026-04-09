# 🌿 WOLI CBD S.A. — Phygital NFT & Blockchain Strategy

> **Version 1.0 · 2026 · Costa Rica**
> Legally registered company · Real products · Total transparency

---

## 📋 Executive Summary

Woli CBD S.A. is a legally registered Costa Rican cannabis and hemp company with **4+ years of operating history**, a proven physical product line, and a passionate founding team. This strategy solves one central problem: **how to fund manufacturing, marketing, and growth without relying on venture capital or traditional banking.**

Every NFT we mint represents a **real, physical product** in a warehouse in Costa Rica. This is not speculation. This is the pre-sale of the future of a cannabis company that has already proved it can manufacture and sell.

> 🎯 **Mission**: Build the first blockchain-integrated, seed-to-shelf transparent cannabis brand in Latin America.

---

## 📊 Key Data

| Field | Detail |
|-------|--------|
| **Company** | Woli CBD S.A. — Legally registered in Costa Rica |
| **Products** | CBD Ointment (live) · 2 Tinctures (2026 launch) |
| **Current status** | 200/300 ointment cans sold organically · zero paid advertising |
| **Plan A target** | 4–5 ETH (~$10,000 USD) |
| **Plan B target** | 15–30 ETH (~$40,000–75,000 USD) |
| **NFT standard** | ERC-1155 on Base or Abstract |
| **Deployment tool** | Manifold.xyz (no-code contract) |
| **Legal foundation** | Woli CBD S.A. + Fucannamed CR (non-profit foundation) |
| **Website** | wolicbd.com |
| **Foundation** | fucannamedcr.org |
| **Social** | @wolicbd |

---

## 🗺️ The Three Plans at a Glance

| | Plan A | Plan B | Plan C |
|--|--------|--------|--------|
| **Type** | Phygital NFT Drop | Community Token + DAO | RWA Tokenization |
| **Target** | 4–5 ETH | 15–30 ETH | $50K–$150K |
| **Timeline** | Weeks 1–10 | Weeks 1–16 (after A) | Months 6–12 |
| **Risk** | 🟢 Low | 🟡 Medium | 🔴 High |
| **When** | Start now | After Plan A ≥40% sold | After Plans A+B proven |

---

---

# 🎨 NFT Collection Description

## Collection Name: WOLI GENESIS — Batch 001

---

### 📝 Short Description *(for marketplaces — copy exactly, 160 chars)*

> 300 phygital NFTs. Each one backed by a real CBD ointment can made in Costa Rica. Mint it. Hold it. Redeem it. Earn from it. Forever.

---

### 📄 Long Description *(for collection page — copy exactly)*

WOLI GENESIS is not another JPEG.

This is Batch 001 — a collection of 300 NFTs, each one a digital twin of a real, hand-manufactured CBD ointment can made right here in Costa Rica by Woli CBD S.A.

For four years, three founders built this company from nothing. No VC money. No influencers. No shortcuts. Just a belief that cannabis deserves better — better transparency, better quality, and better access.

**Now we're inviting you to be part of what comes next.**

Each WOLI GENESIS NFT gives you:

- 🔥 **Physical redemption rights** — burn your NFT, receive your can.
- 💰 **Perpetual sales rewards** — as Woli sells product, holders earn. Forever.
- 🗳️ **DAO governance** — vote on new products, partnerships, and company direction.
- 🏷️ **Tiered discounts** — the more you hold, the more you save on everything we make.
- ⭐ **Founding member status** — you will always be remembered as a Genesis holder.

This is Woli's promise: every sale we make funds the next batch. Every batch minted adds to your rewards. This is not a one-time drop. This is the beginning of a cannabis company built on-chain, for the long haul.

**Mint. Hold. Earn. Welcome to the future of cannabis.**

---

### 🏆 NFT Tier Breakdown

| Tier | Supply | Price | Physical Benefit | Additional Perks |
|------|--------|-------|-----------------|------------------|
| 🌱 **Cultivator** | 200 NFTs | 0.01 ETH | 1 ointment can + 5% lifetime discount | Sales milestone rewards · community access |
| 🌿 **Grower** | 75 NFTs | 0.025 ETH | 2 cans + 10% lifetime discount | All above + DAO vote on new products |
| 🏅 **Founder** | 25 NFTs | 0.06 ETH | 5 cans + 15% lifetime discount | All above + name in credits · direct team access · priority on all future drops |

---

### 💎 NFT Metadata Attributes *(JSON template)*

```json
{
  "name": "WOLI GENESIS #001",
  "description": "Batch 001 — CBD Ointment. Manufactured in Costa Rica by Woli CBD S.A.",
  "image": "ipfs://[HASH]/001.png",
  "attributes": [
    { "trait_type": "Batch", "value": "Genesis-001" },
    { "trait_type": "Tier", "value": "Cultivator" },
    { "trait_type": "Product", "value": "CBD Ointment" },
    { "trait_type": "Origin", "value": "Costa Rica" },
    { "trait_type": "Redeemed", "value": "false" },
    { "trait_type": "Discount", "value": "5%" }
  ]
}
```

---

---

# 🚀 Plan A — Phygital NFT Drop: Step-by-Step Guide

> **Timeline:** 8–10 weeks · **Target:** 4–5 ETH · **Risk:** 🟢 Low
> Execute FIRST. This is your starting point and proof of concept.

---

## Phase 1: Legal & Structural Foundation *(Weeks 1–2)*

### ✅ Step 1 — Legal Disclaimer

**Action:** Hire a Costa Rican lawyer (~$200 USD) to draft a one-page disclaimer.

The disclaimer must clearly state:

- [ ] NFTs are **utility tokens**, not investment securities
- [ ] They represent pre-purchase access to physical goods manufactured in Costa Rica
- [ ] Holders cannot import products where prohibited by law
- [ ] Rewards are conditional on achieving **sales milestones**
- [ ] Woli CBD S.A. is not responsible for international shipping or import

> ⚠️ **Publish on:** Mint page · Discord · Pinned Twitter post · Website

---

### ✅ Step 2 — Upload Proof Documents to IPFS

- [ ] Woli CBD S.A. corporate registration certificate (renew now if needed)
- [ ] Fucannamed CR non-profit registration
- [ ] Product batch certificates / lab tests for the ointment
- [ ] Professional product photography (minimum 10 quality shots)
- [ ] Short manufacturing process video (minimum 60 seconds)

**Tool:** [Pinata.cloud](https://pinata.cloud) — free tier is sufficient

> 💡 These documents are your **proof of work**. Every serious investor will look for them.

---

## Phase 2: Technical Setup *(Weeks 2–4)*

### ✅ Step 3 — Create Multi-Signature Wallet (Gnosis Safe)

1. Go to [safe.global](https://safe.global)
2. Create a **2-of-3 wallet** (all 3 founders as signers)
3. **Publish this address publicly BEFORE opening the mint**
4. No single founder can move funds alone — this is your trust layer

```
Recommended setup:
Signer 1: Founder A
Signer 2: Founder B
Signer 3: Founder C
Threshold: 2 of 3
```

---

### ✅ Step 4 — Deploy Contract on Manifold

| Parameter | Value |
|-----------|-------|
| **Chain** | Base (recommended) or Abstract |
| **Standard** | ERC-1155 (supports all 3 tiers in 1 contract) |
| **Royalties** | 5% (secondary market earnings) |
| **Contract name** | `WOLI-GENESIS-001` |
| **Deploy cost** | ~0.05 ETH |

**Steps:**
1. Go to [manifold.xyz](https://manifold.xyz)
2. Connect the Safe multisig wallet
3. Create new ERC-1155 contract
4. Configure the 3 tiers as separate tokens within the same contract
5. Set up mint page with photos, video and document links

---

### ✅ Step 5 — Create NFT Artwork & Metadata

**Tool:** Canva Pro ($13/month) is sufficient

| Tier | Visual Treatment |
|------|-----------------|
| 🌱 Cultivator | Product photo · green frame · can number visible |
| 🌿 Grower | Double can · blue frame · "Pro" badge |
| 🏅 Founder | Gold frame · premium treatment · "Genesis Founder" badge |

**Upload flow:**
```
Create image → Upload to Pinata (IPFS) → Copy hash → Create JSON metadata → Upload JSON to Pinata
```

---

## Phase 3: Community Building *(Weeks 3–5)*

> 🎯 **Goal: 200 warm wallets BEFORE opening public mint**
> This is the most critical phase. Most failed drops fail here.

### ✅ Step 6 — Twitter/X Strategy

- [ ] Post a "building in public" thread about Woli's 4-year journey — be emotional and real
- [ ] Tag: `#cannabis #RWA #phygital #DeSci #web3 #NFT #CostaRica`
- [ ] Post product photos with caption: *"200 cans sold. Zero paid ads. Now we're going on-chain."*
- [ ] Personal DMs to the **top 20 cannabis-crypto accounts** — not templates, real messages
- [ ] Engage with other phygital/RWA projects with genuine comments

**Minimum frequency:** 1 post per day during weeks 3–5

---

### ✅ Step 7 — Discord Strategy

**Servers to join:**
1. A cannabis community
2. An RWA-focused server
3. A Latin American Web3 server
4. A DeSci server
5. A general NFT community

> ⏳ **Be genuinely helpful for 2 weeks BEFORE mentioning Woli**

**Channels for the Woli Discord:**
- `#announcements`
- `#product-info`
- `#redemption-faq`
- `#dao-preview`
- `#whitelist`

---

### ✅ Step 8 — Activate Fucannamed CR

- [ ] Post on all Fucannamed CR channels about the upcoming drop
- [ ] Create educational post: cannabis transparency → blockchain traceability
- [ ] Invite existing followers to join the Woli Discord

---

## Phase 4: Mint Execution *(Weeks 6–8)*

### ✅ Step 9 — Whitelist Window (72 hours)

**Whitelist form:** Simple Google Form with:
- ETH wallet address
- Twitter/X handle (optional)
- How did you find Woli?

**Whitelist pricing (10% discount):**

| Tier | Public Price | Whitelist Price |
|------|-------------|-----------------|
| Cultivator | 0.01 ETH | 0.009 ETH |
| Grower | 0.025 ETH | 0.0225 ETH |
| Founder | 0.06 ETH | 0.054 ETH |

---

### ✅ Step 10 — Public Mint (7 days)

**During the mint window:**
- [ ] Post daily sell-through % update on X
- [ ] Respond to EVERY Discord question within 2 hours
- [ ] If 50% sells in 48h → post a celebratory FOMO thread
- [ ] **DO NOT extend beyond 7 days** — scarcity is real

---

## Phase 5: Fund Distribution *(Weeks 8–10)*

### ✅ Step 11 — Fund Allocation

Based on a **4.5 ETH** raise:

| Category | % | ETH | Use |
|----------|---|-----|-----|
| 🔒 Reward Pool | 30% | ~1.35 ETH | LOCKED until sales milestones achieved |
| 🏭 Manufacturing | 42% | ~1.89 ETH | Convert to USD via Binance · 2 tincture runs |
| 📣 Marketing | 14% | ~0.63 ETH | Paid social · influencer outreach · PR |
| 👥 Team Expenses | 7% | ~0.315 ETH | Operational costs for 3 founders |
| 💻 Technology | 7% | ~0.315 ETH | Manifold · IPFS · website updates |

> ⚠️ The reward pool is NOT touched until 50% of physical inventory is sold

---

### ✅ Step 12 — Deliver Product & Distribute Rewards

1. **Physical delivery:** Holders submit data via Google Form → Woli ships product → Post package photos (blurred addresses)
2. **Reward activation:** Upon selling 50% of inventory → distribute proportionally to holders via Safe batch transfer or Merkle drop
3. **Post everything publicly:** Every sales receipt, every shipment, every milestone — on-chain and on social

> 💡 This radical transparency is the most powerful marketing for the next drop

---

## 📈 Success Metrics Plan A

| Metric | Target |
|--------|--------|
| Warm wallets before mint | ≥ 200 |
| Whitelist sell-through (72h) | ≥ 30% |
| Total sell-through (7 days) | ≥ 50% |
| Community → mint conversion | ≥ 15% |
| Discord response time | ≤ 2 hours |

---

## 🛠️ Tech Stack Plan A

```
Wallet:        Safe (safe.global) — 2-of-3 multisig
Contract:      Manifold.xyz — ERC-1155
Chain:         Base or Abstract
Art/design:    Canva Pro
IPFS:          Pinata.cloud
Marketplace:   Magic Eden / OpenSea
Conversion:    Binance (ETH → USD)
```

---

---

# 💎 Plan B — Community Token + DAO: Step-by-Step Guide

> **Timeline:** 10–16 weeks AFTER Plan A · **Target:** 15–30 ETH · **Risk:** 🟡 Medium
> Execute ONLY after Plan A achieves ≥40% sell-through.

---

## Why Plan B Comes After

Plan A is your **proof of concept**. Plan B is your **scale engine**.

Without Plan A first: no sales data, no holder community to vote in the DAO, no credibility for a token.

With successful Plan A: real buyers = market validation · committed holders = first stakers · on-chain transparency = trust for new investors.

---

## Phase 1: Token Design *(Weeks 1–2)*

### ✅ Step 1 — $WOLI Tokenomics

**Total supply:** `10,000,000 $WOLI`

**Three core functions:**

| Function | Description |
|----------|-------------|
| 🗳️ **Governance** | Stake $WOLI to vote on DAO product decisions |
| 💰 **Rewards** | Earn $WOLI from sales milestones proportionally |
| 🏷️ **Discounts** | Holding $WOLI = tiered discount on all Woli products |

**Supply distribution:**

| Category | % | Tokens | Notes |
|----------|---|--------|-------|
| 🌍 Public Sale | 40% | 4,000,000 | Token generation event |
| 🔒 Reward Pool | 30% | 3,000,000 | Locked · distributed at milestones |
| 👥 Team | 20% | 2,000,000 | 2-year linear vest · 6-month cliff |
| 📣 Marketing/Partners | 10% | 1,000,000 | Influencers · partnerships · listings |

---

### ✅ Step 2 — Publish Public Tokenomics Document

> ⚠️ **Required BEFORE deploying any contract**

Document must include:
- [ ] Total supply and distribution
- [ ] Team vesting schedule
- [ ] Reward activation mechanisms
- [ ] How the DAO works
- [ ] What the token does NOT guarantee

**Publish on:** Website · Discord (pinned) · Twitter/X

> 💡 Tokenomics opacity kills projects. Be embarrassingly transparent.

---

## Phase 2: DAO Setup *(Weeks 3–5)*

### ✅ Step 3 — Deploy ERC-20 Token Contract

**Tool:** [OpenZeppelin Contracts Wizard](https://wizard.openzeppelin.com)

```
Type:     ERC-20 with ERC20Votes (Snapshot-compatible)
Chain:    Base
Owner:    Safe multisig (same as Plan A)
Cost:     ~0.02 ETH
```

**Extensions to include:**
- ✅ `ERC20Votes` — voting compatible with Snapshot
- ✅ `Ownable` — minting control
- ✅ Time-locked minting (vesting schedule)

---

### ✅ Step 4 — Set Up Snapshot.org

1. Go to [snapshot.org](https://snapshot.org)
2. Create space `wolicbd.eth`
3. Configure: `100 $WOLI = 1 vote`
4. Link to deployed ERC-20 contract

**First governance vote (strategic — make it easy and exciting):**

> 🗳️ *"Which tincture flavor should we make first — citrus or mint?"*

This proves the DAO works and creates immediate emotional investment from holders.

---

### ✅ Step 5 — Create Initial Liquidity Pool

1. Take 20% of Plan A ETH (reward pool) + token sale proceeds
2. Create `$WOLI/ETH` pool on [Uniswap v3](https://app.uniswap.org) on Base
3. Communicate clearly: *"Initial liquidity is thin. This is a long-term build."*

> ⚠️ Managing expectations here prevents panic and community resentment

---

## Phase 3: Token Sale *(Weeks 6–10)*

### ✅ Step 6 — Token Generation Event

**Tool:** [Juicebox.money](https://juicebox.money) or Manifold claim page

**Initial price:** `$0.01 USD per $WOLI`

**Raise potential:**
```
4,000,000 tokens × $0.01 = $40,000 USD (full sell-through)
Minimum viable target: 50% → $20,000 USD
```

---

## Phase 4: B2B Activation *(Month 4+)*

### ✅ Step 7 — White-Label via DAO

The DAO votes on which brands to approach for white-label manufacturing.

**Process:**
1. Team proposes 3 brand candidates
2. Community votes (Snapshot)
3. Winning brand receives formal proposal from Woli
4. Holders have financial incentive to bring in customers = your sales team

**Available white-label services:**
- Product manufacturing under client's brand
- Export/import in the Latin American region
- Educational webinars with doctors (Spanish/English)
- Web development (frontend, design)

---

## Sales Milestones & Rewards

| Milestone | Sales | Action |
|-----------|-------|--------|
| 🥉 Milestone 1 | 150 units | Distribute 10% of reward pool proportionally to $WOLI stakers |
| 🥈 Milestone 2 | 300 units | Distribute additional 15% + unlock tincture pre-sale |
| 🥇 Milestone 3 | 1,000 units | Distribute additional 20% + DAO votes on cultivation roadmap |

> 📢 **Post EVERY receipt and milestone publicly. On-chain evidence IS your marketing.**

---

## 📈 Success Metrics Plan B

| Metric | Target |
|--------|--------|
| Token sell-through (first week) | ≥ 25% |
| Participation in first DAO vote | ≥ 50 voters |
| $WOLI/ETH pool liquidity | ≥ $5,000 USD |
| White-label deals activated by community | ≥ 1 in first 3 months |

---

## 🛠️ Additional Stack for Plan B

```
ERC-20 Token:   OpenZeppelin Wizard
Governance:     Snapshot.org
Liquidity:      Uniswap v3 (Base)
Token sale:     Juicebox.money
Analytics:      Dune Analytics (public dashboard)
```

---

---

# 🏛️ Plan C — RWA Tokenization: Future State

> **Timeline:** 16–24 weeks · **Target:** $50K–$150K · **Risk:** 🔴 High
> **Prerequisite:** Proven success of Plans A and B

---

## What is RWA Tokenization?

RWA (Real World Asset) tokenization is the institutional-grade version of what Plan A started.

Instead of selling NFTs to crypto enthusiasts, you sell **fractionalized ownership of real business assets** to DeFi investors who want yield backed by tangible collateral.

```
Plan A:  Crypto community → buys NFTs → receives products
Plan C:  DeFi investors → buys RWA tokens → receives yield from sales
```

---

## When to Start Plan C *(Checklist)*

- [ ] 12+ months of documented on-chain sales history
- [ ] Plan A has completed ≥ 2 successful drops
- [ ] $WOLI token with sustained liquidity for 3+ months
- [ ] Clean financial audit of Woli CBD S.A.
- [ ] Costa Rican legal team identified and retained

> ❌ Do not start Plan C without meeting ALL criteria above

---

## Legal Structure: The SPV

```
                ┌─────────────┐
                │  WOLI CBD   │
                │    S.A.     │
                └──────┬──────┘
                       │ manufactures
                       ▼
                ┌─────────────┐
                │     SPV     │ ← separate legal entity
                │ (inventory  │
                │ as collateral)
                └──────┬──────┘
                       │ tokens
                       ▼
                ┌─────────────┐
                │  RWA        │
                │  Investors  │
                └─────────────┘
```

Token holders own shares of the SPV — **not of Woli CBD S.A.** This legal separation is critical.

---

## Key Steps

### Step 1 — SPV with Costa Rican Lawyer
Create separate legal entity holding inventory as collateral. Define participation structure and liquidation mechanisms.

### Step 2 — Choose RWA Platform

| Platform | Specialty | Fit for Woli |
|----------|-----------|-------------|
| [Centrifuge](https://centrifuge.io) | Inventory & invoices | ⭐ Best fit |
| [Goldfinch](https://goldfinch.finance) | Emerging market loans | Good alternative |
| [Maple Finance](https://maple.finance) | Institutional credit | More demanding |

### Step 3 — The Investor Pitch

> 🎯 **12–18% APY backed by Costa Rican cannabis product inventory**
> Yield from real sales revenue · SPV holds physical collateral · Fully doxed team

### Step 4 — Target Audience

| Investor Type | Access Channel |
|--------------|----------------|
| DeFi funds with RWA mandates | Centrifuge community · DeFi Twitter |
| Family offices with crypto exposure | Crypto conferences · LinkedIn |
| Impact investors (LatAm cannabis) | Cannabis industry events |
| Crypto-native HNWIs | Telegram groups · DeFi Discord |

---

## 🗓️ Complete Roadmap 2026–2028

| Year | Quarter | Milestone |
|------|---------|-----------|
| 2026 | Q1–Q2 | Plan A: WOLI GENESIS Batch 001 drop |
| 2026 | Q2–Q3 | Plan B: $WOLI token + DAO launch |
| 2026 | Q3–Q4 | Manufacturing and launch of 2 tinctures |
| 2026 | Q4 | Plan A Drop 2: WOLI GENESIS Batch 002 (tinctures) |
| 2027 | Q1 | Plan C: SPV structuring and due diligence |
| 2027 | Q2 | Plan C: First RWA round |
| 2027 | Q3–Q4 | Physical storefront opening in Costa Rica |
| 2028 | Q1+ | Seed-to-shelf blockchain traceability system live |

---

---

# 📣 Marketing & Social Media Blueprint

---

## Your Competitive Advantage

> You have something most crypto projects will never have: a **real product**, a **real company**, and **Costa Rica** behind you.

Costa Rica has an internationally recognized brand: biodiversity, sustainability, innovation. You are not just a cannabis NFT. You are a **Costa Rican cannabis NFT**. That specificity is your moat.

---

## Content Pillars *(post ≥5 times per week)*

| Pillar | Content Type | Frequency |
|--------|-------------|-----------|
| 🎬 **Behind the Scenes** | Photos/videos of manufacturing · ingredients · packaging | 2x/week |
| 🧪 **Education** | Cannabis science content via Fucannamed CR doctors | 1x/week |
| ⛓️ **Blockchain Transparency** | "Today's batch is now on IPFS: [link]" style posts | 1x/week |
| 👥 **Community** | Repost holder content · public Q&A · celebrate milestones | 1x/week |
| 🗺️ **Roadmap Updates** | Weekly progress reports — be relentlessly transparent | 1x/week |

---

## Launch Thread for X/Twitter *(copy and customize)*

```
1/ We just went on-chain.

After 4 years of building a cannabis company in Costa Rica 
from scratch — no VC, no influencers, no marketing budget — 
we're finally ready to show the world what we've built.

🧵 Thread:

2/ Introducing WOLI GENESIS — 300 NFTs, each one backed by 
a real CBD ointment can made right here in Costa Rica by 
our team of three.

3/ This isn't a JPEG. This is a phygital.

Mint it. Hold it. Redeem it for the physical product.
Earn from our sales. Forever.

4/ We've already sold 200 cans organically.
Zero paid ads.
Just product that works and people who believe in it.

5/ Now we're inviting the crypto community to be part of 
what comes next:

→ 2 tinctures in 2026
→ A DAO
→ Seed-to-shelf traceability
→ The first blockchain-native cannabis brand in Latin America

6/ We are Woli CBD S.A. — legally registered.
Fully doxed. Ready to build in public.

Mint opens [DATE]. Whitelist form: [LINK]

Cannabis is going on-chain. You in?

#cannabis #NFT #phygital #RWA #CostaRica #DeSci #web3
```

---

## Regular Post Templates

### Transparency Post *(weekly)*
```
📊 Woli Update — Week [N]

✅ Batches produced: [X]
✅ Units sold: [X]
✅ NFTs minted: [X]/300
✅ Funds in Safe: [X] ETH
✅ Next milestone: [description]

All verifiable on-chain. Always.

[Safe multisig link]
```

### Product Post *(behind-the-scenes)*
```
This is how the ointment behind every WOLI GENESIS NFT is made.

[photo/video]

Ingredient by ingredient. Can by can. In Costa Rica.

That's what phygital means: not JPEGs — real product.

wolicbd.com
```

### Sales Milestone Post
```
🎉 MILESTONE REACHED: [X] units sold

This means:
→ [X]% of reward pool distributes to holders
→ We start production of the next batch
→ [Y] new NFTs from Batch 002 coming soon

Thank you to every holder who believed first.
```

---

## Discord Community Strategy

### Target Servers

| Type | Why | Approach |
|------|-----|---------|
| Cannabis + crypto | Direct audience | Education + product |
| RWA/DeFi | Serious investors | Tokenomics + yields |
| Web3 LatAm | Regional community | Costa Rican identity |
| DeSci | Scientific cannabis | Fucannamed CR content |
| General NFTs | Wider reach | Phygital + utility |

### Engagement Rules
1. **Week 1–2:** Contribute without mentioning Woli
2. **Week 3:** Mention naturally when relevant
3. **Week 4+:** Invite genuinely interested people to Woli Discord

> ❌ Never spam. Never templates. Always value first.

---

## Marketing KPIs

| Metric | Pre-mint | Launch | Post-mint |
|--------|----------|--------|-----------|
| Twitter/X followers | — | ≥500 | ≥1,000 |
| Discord members | — | ≥200 | ≥400 |
| Whitelist wallets | ≥200 | — | — |
| Impressions per post | ≥500 | ≥2,000 | ≥1,000 |
| Engagement rate | ≥3% | ≥5% | ≥4% |

---

## Marketing Budget (from 14% of mint)

With ~0.63 ETH (~$1,575 USD):

| Channel | Allocation | Goal |
|---------|-----------|------|
| X/Twitter advertising | 40% (~$630) | Reach cannabis+crypto audiences |
| Content creators | 30% (~$475) | 2–3 cannabis/web3 micro-influencers |
| PR and articles | 20% (~$315) | 1–2 crypto/cannabis publications |
| Tools and design | 10% (~$157) | Canva Pro, scheduling tools |

---

---

# ⚖️ Legal Disclaimer & Compliance

---

## Official Disclaimer Text *(use verbatim on mint page)*

---

**LEGAL NOTICE — WOLI GENESIS NFT COLLECTION**

WOLI GENESIS tokens are **utility tokens**. They do not constitute investment securities, financial instruments, equity participation, or any type of asset regulated by securities laws in any jurisdiction.

**What the tokens DO provide:**
- Right to redeem physical products manufactured by Woli CBD S.A. in Costa Rica
- Access to discounts on company products
- Participation in DAO votes when voting periods are open
- Eligibility for rewards based on defined sales milestones

**What the tokens DO NOT guarantee:**
- Any guaranteed financial return
- Profit-sharing or dividends from Woli CBD S.A.
- Ownership of assets, patents, or intellectual property of the company
- Availability of rewards before reaching defined sales milestones

**Holder Responsibilities:**
- Holders are **solely responsible** for compliance with applicable local laws on cannabis, hemp, and cryptocurrency in their jurisdiction
- Woli CBD S.A. **does not provide** international shipping or import assistance
- Physical product redemption is the holder's exclusive responsibility
- Cannabis/hemp products **cannot be imported** where prohibited by law

**About the Company:**
Woli CBD S.A. is a legally registered corporation in the Republic of Costa Rica. The founding team is fully doxed. Corporate registration documents are publicly available on IPFS at [link].

*By participating in the WOLI GENESIS token mint, the holder declares having read, understood, and accepted all of the above terms.*

---

## Compliance Checklist

### Before the Mint
- [ ] Disclaimer reviewed and approved by Costa Rican lawyer
- [ ] Published on mint page (visible without scrolling)
- [ ] Published in Discord (#rules or #legal)
- [ ] Linked in pinned tweet
- [ ] Corporate documents uploaded to IPFS

### During and After the Mint
- [ ] Never promise "guaranteed returns" on any channel
- [ ] Always call tokens "utility" not "investment"
- [ ] Document all sales milestones publicly
- [ ] Keep Safe multisig movements justified and public at all times

---

## Notes for the Lawyer

When hiring a Costa Rican lawyer, specifically request:

1. Disclaimer review for compliance with Costa Rican law
2. Opinion on token classification under local regulation
3. Recommendations on crypto fund handling for a Costa Rican company
4. Recommended structure for reward distributions

**Estimated budget:** $150–$300 USD for basic legal review

---

---

# 🔗 Resources & Links

| Resource | URL |
|----------|-----|
| Company website | [wolicbd.com](https://wolicbd.com) |
| Non-profit foundation | [fucannamedcr.org](https://fucannamedcr.org) |
| Instagram | [@wolicbd](https://instagram.com/wolicbd) |
| Facebook | [Woli CBD](https://facebook.com/profile.php?id=61573027394056) |
| Example NFT project | [Magic Eden Abstract](https://magiceden.io/collections/abstract/0x61652fd267d2ac7d2253a5154f89670d718619c0) |
| Contract deployment | [manifold.xyz](https://manifold.xyz) |
| Multi-sig wallet | [safe.global](https://safe.global) |
| IPFS hosting | [pinata.cloud](https://pinata.cloud) |
| DAO governance | [snapshot.org](https://snapshot.org) |
| Token builder | [wizard.openzeppelin.com](https://wizard.openzeppelin.com) |
| Liquidity | [app.uniswap.org](https://app.uniswap.org) |
| Token sale | [juicebox.money](https://juicebox.money) |
| RWA platform | [centrifuge.io](https://centrifuge.io) |

---

*Woli CBD S.A. · Costa Rica · 2026 · wolicbd.com*
