# Bangladesh Golden Poysha Currency (BGPC)

> A BEP-20 utility token on BNB Smart Chain, built for the Bangladeshi diaspora community.

<p align="center">
  <img src="https://goldenpoysha.com/BGPC_Platimum.png" alt="BGPC Coin" width="180"/>
</p>

<p align="center">
  <a href="https://goldenpoysha.com">Website</a> ·
  <a href="https://goldenpoysha.com/airdrop.php">Airdrop</a> ·
  <a href="https://goldenpoysha.com/security.php">Security Audit</a> ·
  <a href="https://bscscan.com/token/0x42B49e5A5F594587042f499a55EAace09246e7B7">BscScan</a>
</p>

---

## What is BGPC?

Bangladesh Golden Poysha Currency (BGPC) is a BEP-20 utility token deployed on BNB Smart Chain, designed to serve the Bangladeshi diaspora community as a digital identity and exchange medium. The project focuses on community participation, accessible distribution through an airdrop program, and long-term utility for diaspora users.

## Contract Details

| Field | Value |
|---|---|
| **Contract Address** | `0x42B49e5A5F594587042f499a55EAace09246e7B7` |
| **Token Name** | Bangladesh Golden Poysha Currency |
| **Symbol** | BGPC |
| **Standard** | BEP-20 |
| **Chain** | BNB Smart Chain (Chain ID: 56) |
| **Decimals** | 18 |
| **Total Supply** | 500,000,000 BGPC |
| **Buy Tax** | 0% |
| **Sell Tax** | 0% |
| **Transfer Tax** | 0% |
| **LP Lock** | 12 months via PinkLock |
| **Verification** | [Source verified on BscScan](https://bscscan.com/token/0x42B49e5A5F594587042f499a55EAace09246e7B7) |

## Security & Transparency

The smart contract was deployed using [Bitbond Token Tool](https://tokentool.bitbond.com), a no-code token deployment platform by Bitbond GmbH (Berlin, Germany). The underlying contract template (`BitbondTokenToolAdvancedToken`) is CertiK-audited.

Multiple independent security scanners have analyzed the BGPC contract:

| Scanner | Result | Verify |
|---|---|---|
| **SolidityScan** | 61/100 (standard OpenZeppelin patterns) | [Report on website](https://goldenpoysha.com/security.php) |
| **GoPlus Security** | 13 of 16 checks fully green | [Verify](https://gopluslabs.io/token-security/56/0x42B49e5A5F594587042f499a55EAace09246e7B7) |
| **HashDit (BNB Chain)** | 28/100 — Low Risk | [Verify](https://hashdit.io/check) |
| **TokenSniffer** | "Not a honeypot, token is sellable" | [Verify](https://tokensniffer.com/token/bsc/0x42B49e5A5F594587042f499a55EAace09246e7B7) |

All scanners independently confirm: contract source is verified, no honeypot mechanisms, 0% transaction taxes, no self-destruct ability, owner cannot arbitrarily modify user balances, no hidden owner functions.

**Full security disclosure including public commitments on tax/mint/whitelist:**
👉 [goldenpoysha.com/security.php](https://goldenpoysha.com/security.php)

## Tokenomics

- **Total Supply:** 500,000,000 BGPC (capped)
- **Distribution:** Primarily via community airdrop program
- **Liquidity:** Locked for 12 months via PinkLock
- **Taxes:** 0% across all transactions (publicly committed permanently)

## Community Airdrop

The BGPC community airdrop is live. Submit your wallet to receive 500 BGPC tokens:

👉 [goldenpoysha.com/airdrop.php](https://goldenpoysha.com/airdrop.php)

Subject to eligibility: airdrop is not available to residents of OFAC-sanctioned jurisdictions and several other restricted regions per our compliance policy.

## Links

### Official channels
- 🌐 Website: [goldenpoysha.com](https://goldenpoysha.com)
- 💬 Telegram: [t.me/goldenpoyshaBGPC](https://t.me/goldenpoyshaBGPC)
- 𝕏 (Twitter): [x.com/gpoysha](https://x.com/gpoysha)
- 📘 Facebook: [facebook.com/Gpoysha](https://www.facebook.com/Gpoysha/)

### On-chain
- 🔍 BscScan: [Contract page](https://bscscan.com/token/0x42B49e5A5F594587042f499a55EAace09246e7B7)
- 🥞 PancakeSwap: [Trade BGPC](https://pancakeswap.finance/swap?outputCurrency=0x42B49e5A5F594587042f499a55EAace09246e7B7)

### Documentation
- 🛡️ Security & Audit Page: [goldenpoysha.com/security.php](https://goldenpoysha.com/security.php)
- 📝 Airdrop Terms: [goldenpoysha.com/airdrop.php](https://goldenpoysha.com/airdrop.php)

## Public Commitments

Golden Poysha makes the following permanent public commitments regarding contract administration:

1. **0% Transaction Tax — Permanent.** Despite the contract having technical capability to modify taxes, current rate of 0% on buys, sells, and transfers will be maintained permanently.
2. **Mint Function — Restricted Use.** The `mint()` function exists in the contract (standard Bitbond template feature) but will only be used for documented community program purposes, never for arbitrary token creation.
3. **No Active Whitelist.** Although the template includes whitelist capability, no addresses are currently whitelisted for special treatment.
4. **Multi-Sig Governance — Planned.** Single-signer EOA ownership is current state; migration to multi-signature governance is on the project roadmap.

## Repository Contents

This repository will contain:

- 📄 `README.md` — this file
- ⚖️ `LICENSE` — MIT license for project documentation, branding, and supporting code (excludes contract code)
- 📁 `audits/` — Copies of independent security scanner reports *(planned)*
- 📁 `docs/` — Whitepaper, tokenomics docs *(planned)*
- 📁 `assets/` — Brand assets, logos *(planned)*

Note: The smart contract source code is **not** in this repository. The contract code is the intellectual property of Bitbond GmbH (the template publisher), not Golden Poysha. The source is publicly visible and verified on BscScan at the contract address above.

## License

The smart contract source code is **not licensed by Golden Poysha** — it is the IP of Bitbond GmbH. Source is publicly visible via BscScan verification.

Project documentation, branding, and supporting code in this repository (excluding any contract code) are licensed under the **MIT License** — see [LICENSE](./LICENSE) file.

## Disclaimer

This repository and its contents are provided for informational purposes only and do not constitute financial advice. Cryptocurrency investments carry significant risk including total loss of capital. Always do your own research (DYOR) and consult qualified financial advisors before making investment decisions. Past performance does not guarantee future results.

The information in this repository reflects the project's state at the time of writing and may change. For the most current information, refer to the official website at [goldenpoysha.com](https://goldenpoysha.com).

## Contact

- 📧 Email: info@goldenpoysha.com
- 🌐 Website: [goldenpoysha.com](https://goldenpoysha.com)

---

*Last updated: May 2026 · BGPC Foundation · goldenpoysha.com*
