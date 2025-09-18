# Slush Wallet Setup and Funding Guide

This guide explains how to set up a **Slush** wallet on the [slush.app](https://slush.app) platform, store your recovery phrase securely, fund your wallet with SUI and highlights key DeFi protocols on the Sui blockchain. Slush provides a user‑friendly interface for managing Sui tokens and exploring DeFi on Sui.

## 1. Create a Slush Wallet

1. **Open the Slush web app** – Visit [slush.app](https://slush.app) and click **Launch App** to open the web wallet.
2. **Choose a sign‑in method** – Slush supports multiple ways to create an account. You can:
   - **Use an existing Google, Apple, Facebook or Twitch account**. Click the corresponding logo and Slush will create an account linked to your chosen credentials【607209908617494†L56-L58】.  
   - **Create a passphrase account**. Select the **Passphrase Account** option. Slush will generate a recovery phrase (a series of words) and prompt you to set a password【607209908617494†L63-L66】.
   - **Import an existing Sui wallet**. If you already have a wallet, choose the **Import** option to retain access to your existing Sui address and assets【607209908617494†L63-L67】.
3. **Record your recovery phrase** – When creating a passphrase account, Slush displays a recovery phrase. **Write down this phrase offline** (see security best practices below) and confirm it in the wallet interface. Do *not* share your recovery phrase or password with anyone【607209908617494†L63-L66】.
4. **Set a strong password** – Create a long, unique password. Slush will require this password whenever you unlock the wallet.
5. **Secure your account** – After creating your wallet, explore settings to enable auto‑lock timers and two‑factor authentication if available.

## 2. Best Practices for Storing Your Recovery Phrase

- **Write it down with pen and paper** – Use a dedicated notebook (not digital) to write the recovery phrase in the exact order. Avoid storing it in cloud services, e‑mail drafts, or taking screenshots.
- **Store copies in separate safe locations** – Keep the notebook in a secure place such as a fireproof safe. Consider making a second copy and storing it at a trusted relative’s home or a safety deposit box.
- **Do not share your recovery phrase or private key** – Anyone with access to the phrase can control your funds. Slush never asks for your phrase after setup; treat requests for it as scams.
- **Consider a hardware wallet** – For large holdings, use a hardware wallet (e.g., Ledger with Sui support) and connect it via Slush. This keeps the private key offline.

## 3. Funding Your Slush Wallet with SUI

### 3.1 Buy SUI Through Slush’s Integrated On‑Ramp

1. Open the Slush wallet and click **Buy/Sell** on the home screen【53090803332612†L54-L56】.  
2. A panel appears listing tokens; click **Buy** next to **SUI** and enter the amount you want to purchase【53090803332612†L60-L62】.
3. Slush will show a list of approved payment providers (e.g., credit‑card on‑ramps). It displays which provider offers the best rate【53090803332612†L66-L69】.
4. Select a provider (such as MoonPay or Ramp Network). The provider’s site opens, where you can purchase SUI using a debit/credit card or bank transfer. You may be asked to complete KYC with an email address and government ID【53090803332612†L66-L69】.
5. After completing the purchase, SUI will appear in your Slush wallet once the transaction settles on the Sui network.

### 3.2 Transfer SUI from a Centralised Exchange (CEX)

1. **Acquire SUI** – Purchase SUI on an exchange that lists it (e.g., **Coinbase**, **Binance**, **KuCoin**). Complete any required KYC.
2. **Withdraw to your Slush wallet address** – In your exchange account, choose **Withdraw** or **Send** and select **SUI** as the asset.  
   - Enter your Slush wallet’s Sui address (found in the wallet under “Receive”).  
   - Make sure to choose the **Sui network** (not an incompatible network) when withdrawing.  
   - For security, send a small test transaction first.
3. **Confirm the transaction** – After the withdrawal is processed on the exchange, the SUI should appear in your Slush wallet. Withdrawal times vary by exchange.

### 3.3 Use a Third‑Party On‑Ramp

Services like **Ramp Network**, **Transak** or **MoonPay** allow you to purchase Sui tokens directly with fiat without going through an exchange. To use them:
1. Visit the provider’s website (e.g., [Ramp.network](https://ramp.network)) and choose **SUI** as the token.  
2. Enter your Slush wallet address and amount.  
3. Complete the payment using a supported method (credit/debit card, bank transfer or Apple Pay).  
4. Wait for the payment to clear; the provider will send SUI to your wallet address.

## 4. Leading DeFi Protocols on Sui (By TVL)

The Sui ecosystem hosts a variety of DeFi protocols. The following table lists some of the largest protocols by total value locked (TVL) as reported in the Sui Q2 2025 DeFi roundup【631223880373537†L55-L81】【631223880373537†L76-L81】. Figures are approximate end‑of‑quarter TVLs and rounded for clarity.

| Protocol | Category | Approx. TVL (Q2 2025) |
|---|---|---|
| **Suilend** | Lending | ≈ $701 m TVL, with ~$166 m borrowed【631223880373537†L76-L79】 |
| **NAVI** | Lending | ≈ $673 m TVL and ~$175 m borrowed【631223880373537†L76-L79】 |
| **Scallop** | Lending | ≈ $146 m TVL【631223880373537†L76-L80】 |
| **AlphaLend** | Lending | ≈ $137 m TVL【631223880373537†L76-L81】 |
| **Momentum** | DEX/AMM | ≈ $112 m TVL【631223880373537†L55-L60】 |
| **Bluefin AMM** | DEX | ≈ $91 m TVL【631223880373537†L60-L63】 |
| **Cetus** | DEX & Aggregator | ≈ $81 m TVL【631223880373537†L60-L63】 |
| **Aftermath** | DEX & Aggregator | ≈ $45 m TVL【631223880373537†L61-L64】 |
| **Scallop Lend** | Lending | ≈ $92 m TVL (subset of Scallop)【631223880373537†L76-L79】 |
| **AlphaFi** | Yield Aggregator | ≈ $42 m TVL【631223880373537†L88-L90】 |
| **SpringSui** | Liquid Staking | ≈ $189 m TVL【631223880373537†L92-L96】 |
| **Haedal** | Liquid Staking | ≈ $150 m TVL【631223880373537†L92-L96】 |
| **Volo** | Liquid Staking | ≈ $71 m TVL【631223880373537†L92-L96】 |

These protocols are among the most active on Sui and offer services such as lending/borrowing, swaps, yield aggregation and liquid staking. Always research each platform’s smart‑contract risks and tokenomics before depositing funds.

---

*This guide provides general information and does not constitute financial advice. Always use caution when interacting with DeFi applications.*
