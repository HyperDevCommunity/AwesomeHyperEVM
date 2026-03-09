# 🧬 Awesome HyperEVM: Developer & Ecosystem Resources

A curated list of developer tools, SDKs, dApps, infra, bridges, oracles, and resources for building on **HyperEVM** – Hyperliquid's Ethereum-compatible virtual machine built on HyperBFT.

> HyperEVM is optimized for ultra-low latency, gas efficiency, and full Ethereum compatibility – designed for high-frequency DeFi.

---

## 📋 Contents

- [Documentation & Onboarding Guides](#-documentation--onboarding-guides)
- [Developer Tooling](#-developer-tooling)
- [Wallets & Key Management](#-wallets--key-management)
- [RPC Endpoints](#-rpc-endpoints)
- [Oracles, Precompiles & Data](#-oracles-precompiles--data)
- [Cross-Chain & Bridges](#-cross-chain--bridges)
- [Ecosystem Projects & dApps](#-ecosystem-projects--dapps)
  - [DeFi](#-defi)
  - [Analytics & Trading Tools](#-analytics--trading-tools)
  - [Infra & Tooling](#-infra--tooling)
  - [Meme Coins & Fun](#-meme-coins--fun)
- [Integrations](#-integrations)
- [Community](#-community)
- [Contributing](#-contributing)

---

## 📚 Documentation & Onboarding Guides

* 🔗 [HyperEVM Developer Docs](https://hyperliquid.gitbook.io/hyperliquid-docs/for-developers/hyperevm)
* 🔗 [Getting Started with HyperEVM](https://hyperliquid.gitbook.io/hyperliquid-docs/onboarding/how-to-use-the-hyperevm)
* 🔗 [Hyperliquid Python SDK](https://github.com/hyperliquid-dex/hyperliquid-python-sdk)
* 🔗 [Chainlink-style Oracle Integration (HyperLend)](https://github.com/hyperliquid-labs/hyperevm-oracle)

---

## 🧪 Developer Tooling

* [**Hyperliquid Python SDK**](https://github.com/hyperliquid-dex/hyperliquid-python-sdk) – SDK for Hyperliquid API trading with Python
* [**Hyperliquid Rust SDK**](https://github.com/hyperliquid-dex/hyperliquid-rust-sdk) – SDK for Hyperliquid API trading with Rust
* [**Hyperliquid TypeScript SDK (nomeida)**](https://github.com/nomeida/hyperliquid) – Community-built TypeScript SDK for Hyperliquid API trading
* [**Hyperliquid TypeScript SDK (nktkas)**](https://github.com/nktkas/hyperliquid) – Community-built TypeScript SDK for Hyperliquid API trading
* [**HyperEVM Oracle**](https://github.com/hyperliquid-labs/hyperevm-oracle) – Chainlink-compatible oracle infrastructure
* [**Okto SDK**](https://okto.tech/) – Wallet SDK for embedded EVM abstraction (multi-chain, gasless)
* [**HypurrScan**](https://hypurrscan.io/) – Blockchain explorer for HyperEVM

---

## 🔑 Wallets & Key Management

* [**Okto Wallet**](https://okto.tech/) – Chain-abstracted embedded wallet for seamless onboarding & key mgmt
* [**Wallet Utils (Python)**](https://github.com/hyperliquid-labs/hyperevm-oracle/tree/main/scripts) – CLI utilities for private key & deploy flows

---

## 🪐 RPC Endpoints

* **Mainnet RPC**: `https://rpc.hyperliquid.xyz/evm`
* **Testnet RPC**: `https://rpc.hyperliquid-testnet.xyz/evm`
* **Explorer**: [HypurrScan](https://hypurrscan.io/)
* **Community Infra**: Stakely, [HypeRPC](https://rpc.hyperliquid.xyz), [Imperator.co](https://imperator.co/)

---

## 🔮 Oracles, Precompiles & Data

* [**Chainlink-Compatible Oracle**](https://github.com/hyperliquid-labs/hyperevm-oracle) (used by HyperLend)
* **Precompiles** – For reading HyperCore data from EVM
* External oracles: [Pyth](https://pyth.network/), [RedStone](https://www.redstone.finance/), [Stork](https://stork.network/)

---

## 🌉 Cross-Chain & Bridges

* [**deBridge**](https://debridge.finance/) – Custodial token porting via **dePort**
* [**LayerZero**](https://layerzero.network/) – Cross-chain messaging (upcoming)
* [**Allium**](https://allium.so/) – Bridge infra and explorer
* **Native HyperCore<->HyperEVM Bridge**

---

## 🌍 Ecosystem Projects & dApps

###  DeFi

| Project                                           | Description                                        | Docs/Links                                                              |
| :------------------------------------------------ | :------------------------------------------------- | :---------------------------------------------------------------------- |
| [Hyperliquid](https://hyperfoundation.org/)       | Core L1 DEX                                        | [Docs](https://hyperliquid.gitbook.io/hyperliquid-docs/for-developers/hyperevm) |
| [Buffer Finance](https://www.buffer.finance/)     | On-chain options                                   | [Docs](https://docs.buffer.finance/)     |
| [Pear Protocol](https://www.pearprotocol.xyz/)    | Perps & predictions                                | [Docs](https://docs.pearprotocol.io/)   |
| [HyperLend](https://hyperlend.xyz/)               | Lending protocol on HyperEVM                       | [GitHub](https://github.com/hyperliquid-labs/hyperevm-oracle)           |
| [Timeswap](https://timeswap.io/)                  | Interest rate derivatives                          | [Docs](https://timeswap.gitbook.io/docs)     |
| [Rage Trade](https://www.rage.trade/)             | Cross-margin perps                                 | [Docs](https://docs.rage.trade/)   |
| [Felix Protocol](https://felix.exchange/)         | Options infra                                      | X                                                                       |
| [Thunderhead](https://www.thunderhead.xyz/)       | Derivatives infra                                  | X                                                                       |
| [Okto Wallet](https://okto.tech/)                 | Gasless DeFi UX and intent-based trading infra     | [Docs](https://docs.okto.tech/docs)    |

### 📊 Analytics & Trading Tools

| Project                                             | Description             | Docs/Links                      |
| :-------------------------------------------------- | :---------------------- | :------------------------------ |
| [Insilico Terminal](https://insilico.xyz/)          | Terminal + onchain intel | [Docs](https://docs.insilicoterminal.com/documentation)                            |
| [TradeStream](https://tradestream.xyz/)             | Orderflow analytics     | X                               |
| [HyperScanner](https://hyperscanner.xyz/)           | Contract explorer       | X                               |
| [Vegas](https://vegas.fi/)                          | Prediction markets      | [Docs](https://docs.vegas.fi/) |
| [GUESS](https://guess.so/)                          | Community market data   | X                               |
| [ChartScout](https://chartscout.io/)                | analytics + market data | X                               |

### 🛠️ Infra & Tooling

| Project                                        | Description          | Docs/Links |
| :--------------------------------------------- | :------------------- | :--------- |
| [Okto SDK](https://okto.tech/)                 | Wallet SDK           | [Docs](https://docs.okto.tech/docs)       |
| [Omni Network](https://omni.network/)          | Modular chain infra  | [Docs](https://docs.omni.network/)       |
| [Spectral](https://spectral.finance/)          | On-chain reputation  | [Docs](https://docs.spectrallabs.xyz/)       |
| [HyBridge](https://hybridge.xyz/)              | Liquidity layer      | X          |

### 🐶 Meme Coins & Fun

| Token/Project                   | Description                             |
| :------------------------------ | :-------------------------------------- |
| JEFF, RUGMAN, SYLVY, CATBAL, YETI | Community coins native to HyperEVM      |
| HyperGold, POINTS, MUNCH, POPOTOK | Airdrop-eligible or high-volume memecoins |
| FANDA, KOBE, ATERNUM, LIQIUNA   | Emerging memecoins from early traders   |

---

## 🧩 Integrations

* [**Nansen**](https://www.nansen.ai/) – Wallet and flow tracking
* [**CoinGecko**](https://www.coingecko.com/) – Market listings
* [**CoinMarketCap**](https://coinmarketcap.com/) – Token metrics
* [**OneSafe**](https://www.onesafe.io/) – Secure multi-sig support
* [**Notifi**](https://www.notifi.network/) – Alerts & comms infra
* [**fan.fun**](https://fan.fun/) – Fan-token platform

---

## 🤝 Community

* [**Hyperliquid Discord**](https://discord.com/invite/hyperliquid)
* [**@HyperFND on Twitter**](https://twitter.com/hyperfnd)
* [**GitHub**](https://github.com/hyperliquid-labs)
* Ecosystem community: `#builders`, `#hyperevm`, `#ecosystem`

---

## 👥 Contributing

We welcome contributions from the community! Whether you're adding a new tool, updating information, or fixing errors, your help makes this resource better for everyone.

Please see our [Contributing Guidelines](CONTRIBUTING.md) for more information.
