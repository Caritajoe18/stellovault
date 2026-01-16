# StelloVault

**A secure trade finance decentralized application (dApp) built on Stellar & Soroban**  
Tokenizing collateral (invoices, commodities, etc.) to unlock instant liquidity for African exporters and importers, bridging the massive trade finance gap.

[![Stellar](https://img.shields.io/badge/Built%20on-Stellar-blue?logo=stellar)](https://stellar.org)
[![Soroban](https://img.shields.io/badge/Smart%20Contracts-Soroban-orange)](https://soroban.stellar.org)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?logo=next.js)](https://nextjs.org)
[![Rust](https://img.shields.io/badge/Backend-Rust-orange?logo=rust)](https://www.rust-lang.org)

## 🚀 Overview

StelloVault is a trade finance dApp that enables African SMEs to tokenize real-world assets (e.g., invoices, commodities) as Stellar assets with embedded metadata, use them as collateral in multi-signature escrows managed by **Soroban smart contracts**, and unlock instant cross-border liquidity.

Key innovations:
- **Collateral Tokenization** — Real assets become fractional, traceable Stellar tokens.
- **Automated Escrows** — Multi-sig + conditional release triggered by shipment verification oracles (e.g., IoT/Maersk integration).
- **Dynamic Financing** — Algorithmic loans based on on-chain history and utilization.
- **Risk Scoring** — Backend uses transaction history for creditworthiness.
- **Governance** — Quadratic voting for stakeholders to decide accepted collateral types.

### Why It Matters

Africa faces a **trade finance gap of over $100–120 billion annually** (sources: Afreximbank, African Development Bank, World Bank estimates), disproportionately affecting SMEs — which represent >90% of businesses but are underserved by traditional finance. This stifles **$100B+ in potential exports** and intra-African trade under the **AfCFTA**.

StelloVault leverages:
- Stellar's low-cost, fast settlements and native asset issuance
- Soroban's Rust-based smart contracts for secure, programmable logic
- To reduce intermediary costs by up to **50%**, enable fractional ownership, and foster inclusive trade.

Target: Scalable to **1,000+ deals/month** with real-time oracle verification.

## ✨ Key Features

- **Collateral Tokenization** — Mint Stellar assets from invoices/commodities with provenance metadata.
- **Multi-Sig Escrows & Automated Release** — Soroban enforces release upon oracle confirmation (shipment delivered, quality verified).
- **Oracle Integration** — Real-time data feeds (planned: Maersk APIs, IoT devices, Chainlink-style oracles).
- **Risk Scoring Engine** — Rust backend analyzes on-chain history for dynamic loan terms.
- **Frontend Dashboard** — Next.js interface for deal origination, collateral upload, escrow monitoring, and repayments.
- **Governance Module** — On-chain voting (quadratic mechanisms) for protocol parameters and collateral acceptance.
- **Flash Settlements** — Instant cross-border payments using Stellar's built-in DEX/path payments.

## 📂 Repository Structure (Monorepo)
